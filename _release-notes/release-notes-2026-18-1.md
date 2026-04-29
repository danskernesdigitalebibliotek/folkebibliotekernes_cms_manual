---
title:  "Release Notes 2026.18.1"
category: "Release Notes"
weight: 307
---  

Releasedato: 30-04-2026

**Redaktør**: Produktionssites: 2026.18.1
**Webmaster**: Produktionssites: 2026.16.0, Moduletestsites: 2026.18.1 


## Ny udvikling

- GO: Videobundle i højformat – nyt videobundle til højformat-videoer med tilknyttede materialer. Denne nye paragraph gør det muligt at lave formidling, som ligner det, børnene er vant til at se på YouTube etc. Udviklingen er en del af puljeprojektet “Sammenhæng i brugerrejsen”.

- Redaktører skal kunne slette filer helt (og ikke kun slette de medier, der indeholder dem) – gør det muligt at slette filer permanent direkte fra Filer-menuen), så gamle links/filer kan fjernes korrekt. Sagen er vigtig ift. overholdelse af GDPR (fx fjernelse af personfølsomt materiale).

- Knap direkte til CQL-søgning fra Avanceret søgning – tilføjer en direkte adgang til CQL-søgning allerede på første skærmbillede i Avanceret søgning (uden at skulle køre en søgning først). Bemærk, at knappen ikke importerer data fra de udfyldte felter i feltsøgningen. Vil man importere data fra felterne til en søgning til CQL, skal man først trykke Søg. [CMS-1925](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1925)

- Mediatype skal opdeles i Filer paragrafen – Filer-paragrafen opdeles i relevante fil-typer (billede/lyd/dokument/video), så filer gemmes med korrekt mediatype og filtrering virker som forventet.


## Forbedringer og fejlrettelser:

- Visning af lokale emneord samt færøske og grønlandske emneord vises nu kun én gang og ikke i dubletter – emneord på tværs af flere manifestationer/udgaver kunne vises gentagne gange på værkvisningen, hvis flere udgaver havde det/de samme lokale emneord. Fremover vises identiske lokale emneord kun én gang. [CMS-1496](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1496)

- GO: Bibliotekslogin og Unilogin - redirect til værkvisning efter login – sikrer at brugeren sendes tilbage til værkvisningen og lån af det ønskede digitale materiale efter bibliotekslogin og Unilogin fremfor til lånerstatus som tidligere.

- GO: Fejl i filtre på allesøgning – fjerner/retter tomme materialetype-filtre, som opstod ved allesøgning (fx søgning på *) efter nye materialetyper. 

- GO: Justering i prioritering i materialetyper – justerer rækkefølgen/prioriteringen af materialetyper i filtre.

- URL aliaser med forkert sprog – retter generering af URL-aliaser, så der ikke dannes aliaser med forkert sprogsti (fx /articles/ fremfor /artikler/). [CMS-1971](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1971)
