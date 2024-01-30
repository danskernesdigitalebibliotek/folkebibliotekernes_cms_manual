---
title: "Opgave 9: Overblik over integrationer"
category: "Overgangsaktiviter"
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
- Storskærmssystemer ([cmscontent.dbc.dk](https://cmscontent.dbc.dk/))
- App
- IMS
 

### Billetintegration
Vi arbejder på at arrangementerne på Folkebibliotekernes CMS bliver udstillet i et API, som billetleverandørerne kan vælge at hente data fra (dette kræver i det fleste tilfælde at leverandøren udvikler et anvendersystem, som kan hente disse data og udstille dem i deres setup). Det Digitale Folkebibliotek vil kontakte de fleste billetleverandører for at forklare dem, hvordan det kommende API vil kunne bruges, så de har mulighed for at udvikle en ny løsning inden implementeringen.

Kontakt jeres billetleverandør for få en afklaring på, om de har udviklet en løsning der kan hente data fra API’et.

### Børneindmeldelsesflow
Vi arbejder på at det bliver muligt at oprette forskellige brugertyper på Folkebibliotekernes CMS. Det betyder at I i administrationsgrænsefladen kan angive en specifik URL for oprettelse efter brugertype fx til X-Flow eller en kommunal e-blanket til oprettelse af jeres børnelånere. Gem URL I evt. bruger på det nuværende site, så I har den til at sætte ind i administrationen.

### Nyhedsbrevsmodul

Der vil i Folkebibliotekernes CMS ikke være et specifikt nyhedsbrevsmodul. Derfor er det vigtigt at tænke ind om I kan linke til en nyhedsbrevsløsning et andet sted.

### Webforms/kontaktfomularer
På grund af bl.a. GDPR-mæssige årsager vil der højest sandsynligt ikke i første omgang være mulighed for at oprette webforms/kontaktformularer på Folkebibliotekernes CMS. Derfor skal I tænke over, hvor på hjemmesiden I bruger webforms (fx til læsekredse eller tilmeldinger) og overveje hvordan I kan sikre at få oplysninger fra jeres brugere ind alligevel fx vha. en mailadresse henvisning.

### Storskærmsintegrationer
Måske har I i dag en storskærmsløsning som hiver fx arrangementer fra jeres hjemmeside. Det er vigtigt at jeres leverandør af storskærmsløsningen (ligesom med billetleverandøren) kan gøre brug af API’et (som vi arbejder på at kunne tilbyde) til at hente data og udstille dem.

### APP
I det nuværende DDBCMS kan man vinge af at arrangementer, nyheder og åbningstider kan vises på Biblioteket APP’en. Vi arbejder på at denne mulighed også bliver muligt i det nye CMS.

### IMS
I KOMBIT regi arbejdes der på en løsning hvor IMS placeringsstrenge sendes fra IMS over i FBS og derfra videre til Folkebibliotekernes CMS / Biblioteket App via FBS CMS Adapteren. Det eksisterende IMS-modul til DDB CMS kan ikke bruges i Folkebibliotekernes CMS og det vil ikke blive videreudviklet.