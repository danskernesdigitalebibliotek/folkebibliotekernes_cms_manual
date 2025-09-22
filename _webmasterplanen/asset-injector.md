---
title: "Injectors"
category: "Webmaster-funktionalitet"
weight: 5
---

Man kan bruge [Asset Injector](https://www.drupal.org/project/asset_injector){:target="_blank"} og [Add to Head](https://www.drupal.org/project/add_to_head){:target="_blank"} modulerne til at indsætte Javascript, CSS mm. på sitet.

*Asset Injector* giver mulighed for at tilføje brugerdefineret CSS eller JavaScript til dit Drupal-site uden at skulle ændre i f.eks. tema eller bruge lokale moduler. Det er praktisk, hvis man hurtigt vil tilpasse udseendet eller funktionaliteten på specifikke sider eller site-wide.

*Add to Head* modulet bruges til at tilføje scripts, styles eller meta-tags direkte til \<head\>-sektionen på sitet.

## Installation

- Hent modulerne i Zip-format fra `https://www.drupal.org/project/MODULENAVN/releases/RELEASENUMMER`
- Upload dem på `/admin/modules/install-or-update`
- Installer dem på `/admin/modules`.

## Udvikling

Den nemmeste måde at komme igang med Asset Injector, er ved at oprette koden direkte i modultestsitets backend på siden `/admin/config/development/asset-injector`. På modultestsitet tester man koden, og så overfører man til produktionssitet. 

Det er dog lidt bøvlet at arbejde med, da man hele tiden skal gemme formularen inden man kan se ændringerne, kan løbe ind i cache issues og ikke kan versionsstyre sin kode.

TIPS:
- På modultetssitet slå Drupal cache fra imens du udvikler: `/admin/config/development/settings`
- Login som admin for, at udgå Varnish cache.
- Det kan være nødvendigt at genoprette Asset Injector indførslerne for, at anonyme bruger kan se ændringerne pga. Varnish cache.

## Skriv Asset injector kode i custom dev-modul
Koden kan med fordel udvikles i et custom modul i et [lokalt udviklingsmiljø](https://www.folkebibliotekernescms.dk/main/webmasterplanen/udviklingsmiljoe/), og så kan det senere lægges op som i asset injectoren. Fordelene ved dette er, at man kan komme uden om de mange caching lag der er i Dpl Cms, at man kan arbejde i en desktop editor og at man kan versionsstyre sin kode.

Dette modul, som kan bruges som udgangspunkt. Det loader js og css på alle ikke admin sider.
[https://github.com/odensebibliotekerne/webmaster_asset_injector_dev](https://github.com/odensebibliotekerne/webmaster_asset_injector_dev)

Det kan være nødvendig, at rydde cache på det lokale udviklingssite, for at se ændringer

```sh
task dev:cli -- drush cr
```

### Anbefalinger

Det kan anbefales, at man skrives sin kode i vanilla Javascript, da det ikke er 100 % sikkert at JQuery er loadet på alle sider.

Man skal være opmærksom på "race conditions" altså hvilken kode indlæses første - specielt, hvis man ønsker at indskyde noget, som ændre i de React genererede sider f.eks. søgesider.

## Eksempler

Asset Injector kan bruges på mange måder, nedenfor en en række eksempler.

For yderligere inspiration kan man på andre webmaster biblioteker f.eks. på herningsbib.dk åbne Dev Tools i browseren. Her kan man enten i head se links eller man kan kigge i netværks tab'en og se js/css, som bliver loaded.

### Eksempel 1
Ændre indstillinger i formularer. Det kan gøres via ændrede indstillinger i backend, men vil så resultere i [configuration overwrites](https://www.folkebibliotekernescms.dk/main/webmasterplanen/konfigurationsaendringer-via-gui/), og det ønsker man ikke. Asset injector er en bedre løsning. Et eksempel er at ændre "Opret billet i billetsystem" knappen så den er slået fra som default, når man opretter et arrangement.

```js
document.addEventListener("DOMContentLoaded", function () {
  console.log(window.location.pathname);

  if (window.location.pathname === "/events/add/default") {
    const checkbox = document.querySelector(
      "#edit-field-relevant-ticket-manager-value"
    );
    if (checkbox) {
      checkbox.checked = false;
    }
  }
});
```

### Eksempel 2
Indsætte elementer i frontend, hvor man ellers ikke har adgang f.eks. i footer. Her er et eksempel på logoer i footer.

```js
document.addEventListener("DOMContentLoaded", () => {
  const anchor = document.querySelector("ul.footer-columns li:last-child");
  if (!anchor) return;

  const container = document.createElement("div");
  container.style.display = "flex";

  const linkEu = document.createElement("a");
  linkEu.href = "/eu";

  const imgEu = document.createElement("img");
  imgEu.src = "/sites/default/files/2025-02/Europe%20Direct%20Odense.png";
  imgEu.id = "eu_direct";
  Object.assign(imgEu.style, {
    display: "block",
    maxWidth: "165px",
    maxHeight: "163px",
    width: "auto",
    height: "auto",
  });

  linkEu.appendChild(imgEu);
  container.appendChild(linkEu);
  anchor.appendChild(container);
});
```

### Eksempel 3
Tematiserere hjemmesiden f.eks. med et stille julesnevejr, skabt med en smule javascript
   https://github.com/odensebibliotekerne/odense_assetinjector_snow

### Eksempel 4
Lave styleændringer via CSS

Style elementer f.eks. begrænset til alle sider med mønsteret /digital/\*

```css
#main-content {
  background-color: #a97c7c;
}
```

Fjerne elementer

```css
/* Fjerner sidste (det aktuelle) element i breadcrumb */
nav.breadcrumb:not(.breadcrumb_material) a:last-child {
  display: none !important;
}
@media screen and (max-width: 767px) {
  /* Minimerer antallet af breadcrumbs i mobilvisning */
  nav.breadcrumb a {
    display: none;
  }
  nav.breadcrumb a:first-child,
  nav.breadcrumb:not(.breadcrumb_material) a:nth-last-child(2) {
    display: initial;
  }
}
```

## Udviklingsmuligheder og afklaring

Hvordan er den optimale brug af Asset Injector i forhold til cache.



