---
title: "Overblik over integrationer"
permalink: /integrationer/
---
Integrationerne på jeres hjemmeside har stor betydning for de muligheder og tilbud I tilbyder jeres brugere. Derfor er det vigtigt at se på inden overgangen til den nye hjemmeside, så I tager højde for disse funktioner – også på det nye site.

## Mål
Målet med denne opgave er at danne sig et overblik over hvilke integrationer, I har på jeres nuværende hjemmeside og hvilke der skal med over på Folkebibliotekernes CMS.

## Metode og fremgangsmåde
Kig jeres nuværende hjemmeside igennem for integrationer. Det kan være:

- Billetintegration (fx Place2Book)
- Børneindmeldelsesflow (fx fra X-flow eller e-blanketter)
- Nyhedsbrevsmodul
- Webforms/kontaktformularer
- Storskærmssystemer
- App
- IMS
 

### Billetintegration
Folkebibliotekernes CMS tilbyder alle eksterne billetsystemer at hente og opdatere arrangementer via et API. Det Digitale Folkebibliotek har undersøgt hvilke billetsystemer, som flest biblioteker samarbejder med og kontaktet dem med information om det nye API, så de har mulighed for at udvikle en ny løsning inden implementeringen. Er I i tvivl om jeres billetleverandør kender til det nye API, er det en god ide at kontakte dem for få en afklaring. [Læs mere om arrangements API'et her.](https://www.folkebibliotekernescms.dk/main/integrationer/9integrationer/#arrangements-api-til-brug-for-eksterne-systemer)

### Børneindmeldelsesflow
Vi arbejder på at det bliver muligt at oprette forskellige brugertyper på Folkebibliotekernes CMS. Det betyder at I i administrationsgrænsefladen kan angive en specifik URL for oprettelse efter brugertype fx til X-Flow eller en kommunal e-blanket til oprettelse af jeres børnelånere. Gem URL I evt. bruger på det nuværende site, så I har den til at sætte ind i administrationen.

### Nyhedsbrevsmodul
Der vil i Folkebibliotekernes CMS ikke være et specifikt nyhedsbrevsmodul. Derfor er det vigtigt at tænke ind om I kan linke til en nyhedsbrevsløsning et andet sted.

### Webforms/kontaktfomularer
Webforms, som vi kender fra DDB CMS, findes også i Folkebibliotekernes CMS. 

### Storskærmsintegrationer
Måske har I i dag en storskærmsløsning som hiver fx arrangementer fra jeres hjemmeside. Jeres leverandør af storskærmsløsningen kan gøre brug af det nye arrangements API til at hente data og udstille dem. [Læs mere om arrangements API'et her.](https://www.folkebibliotekernescms.dk/main/integrationer/9integrationer/#arrangements-api-til-brug-for-eksterne-systemer)

### APP
Læs om automatisk overførsel af arrangementer og åbningstider til Biblioteket Appen her: https://www.folkebibliotekernescms.dk/main/indhold/redia/

### IMS
I KOMBIT regi arbejdes der på en løsning hvor IMS placeringsstrenge sendes fra IMS over i FBS og derfra videre til Folkebibliotekernes CMS / Biblioteket App via FBS CMS Adapteren. Det eksisterende IMS-modul til DDB CMS kan ikke bruges i Folkebibliotekernes CMS og det vil ikke blive videreudviklet.

## Arrangements API til brug for eksterne systemer
Folkebibliotekernes CMS tilbyder alle typer eksterne systemer at hente arrangementer direkte fra hvert biblioteks hjemmeside. 

Disse systemer kan eksempelvis være:
-	Billetsystemer (Place2Book, Biletto, YourTicket m.fl.)
-	Kultunaut
-	Storskærms-systemer
  
Vores system tilbyder følgende:

**Hent arrangementer:** Åben snitflade som alle kan bruge. Det eksterne system henter alle arrangementer, som det enkelte bibliotek tilbyder. Det eksterne system kan udfra denne liste selv deducere, hvilke arrangementer, der er nyoprettede, og hvilke der nu mangler (aflyste arrangementer)

Arrangementer er tilgængelige i JSON-format for hvert bibliotek via denne URL (udskift mit-domænenavn.dk): \
`https://mit-domænenavn.dk/api/v1/events`

**Opdater arrangement:** Billetsystemer kan melde få data tilbage til Folkebibliotekernes CMS, herunder URL til arrangementet i billetsystemet og status (udsolgt m.v.). Det eksterne system skal etablere en system-til-system integration til Folkebibliotekernes CMS for at kunne benytte denne funktionalitet. Kontakt os for aftale herom.

Yderligere dokumentation kan findes her:

Dokumentation: [https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/event-integration/](https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/event-integration/)

API specifikation: [https://github.com/danskernesdigitalebibliotek/dpl-cms/blob/develop/openapi.json](https://github.com/danskernesdigitalebibliotek/dpl-cms/blob/develop/openapi.json)







