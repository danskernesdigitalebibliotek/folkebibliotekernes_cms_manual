---
title:  "Release Notes 2025.36.0"
category: "Release Notes"
weight: 327
---  

# Forbedringer, fejlrettelser og landingsside til eReolen/GO

Releasedato: 04-09-2025

**Redaktør**: Produktionssites: 2025.36.0

**Webmaster**: Produktionssites: 2025.34.0, Moduletestsites: 2025.36.0 

## Nye features
- eReolen/GO: Landingsside, der henviser til lokale sider, erstatter de gamle sites.  


## Forbedringer og fejlrettelser

-	Søgning: Forslag i søgefeltet afgrænses nu på agency-niveau og viser derfor kun materialer, der reelt er i beholdning.

-	Reservering: Kun første klik på ”RESERVÉR (Bestilles fra et andet bibliotek)” registreres. Tidligere kunne flere klik udløse gentagne reservationer.

-	Fanø: Borgere på Fanø har fået adgang til Infomedia artikler, da FBI API nu kaldes fra FBCMS med municipalityAgencyId.

-	Oversættelser: Manglende oversættelser i administrationsgrænsefladen er rettet.

-	Tilgængelighed: Tastaturbrugere kan nu lukke modaler ved låneroversigten via luk-knappen.

-	Webforms: E-mailvalidering skærpet for at reducere fejl fra ugyldige adresser.

-	Reservér-knap: Knappen ”Reservér fra et andet bibliotek” vises ikke længere på materialer i beholdning når filialen er blacklistet som afhentningssted.

-	Værkvisning: Værkvisningssider som tilgås uden type giver ikke længere fejl.

-	GO - materialetyper: Materialetyper vises nu korrekt på mindre skærme.

-	GO - login: Redirect ved fejlede loginforsøg i Udbyderportalen er fjernet.

-	GO - statuskoder: Siden returnerer nu korrekte statuskoder: 404 (side ikke fundet) og 500 (systemfejl).
