---
title: "Opgave 12: Arrangements API"
category: "Overgangsaktiviter"
weight: 12
---

## Arrangements API til brug for eksterne systemer
Folkebibliotekernes CMS tilbyder alle typer eksterne systemer at hente de arrangementer, der hører til det enkelte bibliotek. Disse systemer kan eksempelvis være:
-	Billetsystemer (Place2Book, Biletto, YourTicket m.fl.)
-	Kultunaut
-	Storskærms-systemer
  
Vores system tilbyder følgende:
- **Hent arrangementer:** Åben snitflade som alle kan bruge. Det eksterne system henter alle arrangementer, som det enkelte bibliotek tilbyder. Det eksterne system kan udfra denne liste selv deducere, hvilke arrangementer, der er nyoprettede, og hvilke der nu mangler (aflyste arrangementer)
- **Opdater arrangement:** Billetsystemer skal kunne melde få data tilbage til Folkebibliotekernes CMS, herunder URL til arrangementet i billetsystemet og status (udsolgt m.v.). Det eksterne system skal etablere en system-til-system integration til Folkebibliotekernes CMS for at kunne benytte denne funktionalitet. Kontakt os for aftale herom.

Dokumentation: https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/event-integration/

API specifikation: https://github.com/danskernesdigitalebibliotek/dpl-cms/blob/develop/openapi.json
