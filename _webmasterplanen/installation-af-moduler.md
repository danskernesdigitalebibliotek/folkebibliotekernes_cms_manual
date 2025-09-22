---
title: "Installation og opdatering af moduler"
category: "Webmaster-funktionalitet"
weight: 5
---

Som **webmasterbibliotek** har I mulighed for at installere moduler lokalt, som ikke er en del af standardudgaven af Folkebibliotekernes CMS (*core*). Det kan være:

- **Contrib-moduler**: Gratis moduler hentet fra [drupal.org](https://new.drupal.org/home){:target="_blank"}, udviklet og vedligeholdt af Drupal-fællesskabet.
- **Egenudviklede moduler**: Moduler udviklet internt til jeres egne behov.

---

## Installation af moduler

For at installere moduler skal du være logget ind med en bruger, der har rollen **Administrator**.

> **Bemærk:** Har du ikke de nødvendige rettigheder, skal du oprette en sag via [Servicedesk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portals){:target="_blank"}.

### Sådan gør du:

1. Log ind med en **Administrator**-bruger.
2. Gå til **Udvid** (`/admin/modules`) og klik på **+ Add new module**.
3. Klik på **Vælg fil**, find modulfilen (f.eks. `.tar` eller `.zip`), og upload den.
4. Søg modulet frem på `/admin/modules`, markér afkrydsningsfeltet, og klik på **Installér** nederst på siden.
5. Nogle moduler tilføjer nye tilladelser. Disse skal manuelt tildeles under **Permissions** for de relevante brugerroller.

---

## Opgradering af moduler

Et modul opgraderes ved blot at installere den nye version oven i den eksisterende.

- Du behøver ikke afinstallere den gamle version først.
- Følg samme fremgangsmåde som ved installation.

### Vigtigt ved opgradering af egenudviklede moduler:

- **Undlad at ændre mappenavnet**. Ellers overskrives det gamle modul ikke, og det kan skabe konflikter. 
- Mappen ikke omdøbes til `mymodule2`, `mymodule-main` eller lignende.


```bash
mymodule/
  mymodule.info.yml
  mymodule.module
  src/
  config/
  README.md
  ...
```
*Mappenavnet skal være det samme mellem versioner*

### Husk at:

- Opdatere `mymodule.info.yml` med det korrekte **modulnavn** og **versionsnummer**.
- Skift altid versionsnummer ved hver ny version – det vises på `/admin/modules`, så du kan bekræfte, at den rigtige version er i brug.
