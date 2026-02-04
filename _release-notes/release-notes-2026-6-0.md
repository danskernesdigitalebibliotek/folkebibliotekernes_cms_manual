---
title:  "Release Notes 2026.6.0"
category: "Release Notes"
weight: 313
---  
Releasedato: 05-02-2026

**Redaktør**: Produktionssites: 2026.6.0
**Webmaster**: Produktionssites: 2026.4.1, Moduletestsites: 2026.6.0

### Forbedringer og fejlrettelser

- Alle links til det almindelige CMS omskrives til relative links fra GO og flere linktyper fejler derefter: Alle links fra GO til det almindelige CMS håndteres nu korrekt, så links ikke læn-gere fejlagtigt omskrives til relative GO-links. Det betyder bl.a., at links til CMS-arrangementer, kontaktformularen, redirects og andre CMS-URL’er bevares som gyldige, absolutte links, mens links til GO fortsat virker som forventet. 
[CMS-1657](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1657)

- Forsider loader underligt på GO: Der var en fejl, hvor forsider på GO-sitet nogle gange blev vist meget små eller i forkerte størrelser. Fejlen kunne bl.a. genskabes ved at gå ind på et materiale fra forsiden og derefter bruge browserens “tilbage”-knap, hvorefter forsiden blev vist med små covers. Implementeringen er justeret, så forsiderne nu loader korrekt, og-så når brugeren navigerer tilbage i browseren.

- Max billedstørrelse justeret til 8 MB: Det er nu tydeligt i CMS’et, at der maksimalt kan uploades billeder på 8 MB. Hjælpeteksten er opdateret, så den ikke længere angiver 25 MB, hvilket var misvi-sende i forhold til den underliggende tekniske begrænsning i driftsplatformen. Æn-dringen påvirker kun nye uploadede filer.

- Cookie-indstillings-ikonet dækker for kapiteloversigten i playeren: Der har tidligere været problemer med at tilgå kapiteloversigten, når man læser en e-bog. Dette skyldtes at cookiesamtykke-ikonet dækkede over knappen til e-bogs kapiteloversigten i nederste hjørne ved afspilning på hjemmesiden. Nu er cookie-knappen flyttet en smule, så man nu kan se og tilgå kapitlerne ved afspilning. [CMS-1709](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1709)
