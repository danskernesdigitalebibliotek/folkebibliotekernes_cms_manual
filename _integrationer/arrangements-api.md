---
title: "Arrangements API til brug for eksterne systemer"  
category: "Integrationer"
---
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
