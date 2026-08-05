---
title:  "Release Notes 2026.32.0"
category: "Release Notes"
weight: 302
---  

Releasedato: 06-08-2026

**Redaktør**: Produktionssites: 2026.32.0  
**Webmaster**: Produktionssites: 2026.26.2, Moduletestsites: 2026.32.0

## Ny udvikling

- Forbedret filtrering på fysiske beholdninger i avanceret søgning, CQL-søgning og paragraphs. Filtreringer på "På hylden", "Bibliotek", "Afdeling", "Opstilling" og "Delopstilling" viser nu kun fysiske materialer i egen beholdning og inkluderer ikke længere overbygningsmaterialer eller onlineudgaver. Dette er opnået ved at tilføje filtrering på useOnlineHoldings:false samt sitets agencyId.
Bemærk: Forbedringen gælder kun avanceret søgning, CQL-søgning, facetter og paragraphs – ikke simpel søgning, da simple search hos DBC ikke understøtter de samme filtre. Der kan desuden pga. synkroniseringstid mellem FBS og FBI forekomme værker, hvor alle eksemplarer er udlånte, hvis det senest tilgængelige eksemplar er udlånt for nyligt (typisk indenfor et døgn).
[CMS-1978](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1978)
[CMS-1885](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1885)
[CMS-1725](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1725)

- Arrangementsoversigt: Fleksibel visning og slut med "Vis flere"
Vi har opdateret arrangementsoversigten, så det nu er muligt at konfigurere (under Arrangementsoversigt på siden /admin/config/dpl-event/settings), hvor mange elementer der skal vises ad gangen (25, 50 eller 100). Som noget nyt kan man også vælge "infinity scroll", hvilket fjerner behovet for manuelt at klikke på "Vis flere"-knappen. Dette sikrer en mere glidende brugeroplevelse og løser problemet med, at oversigten "glemmer" sin position, når man navigerer tilbage fra et specifikt arrangement. [CMS-1032](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1032)


## Forbedring og fejlrettelser

- Afhentningsfilial vises nu med navn i stedet for biblioteksnummer i lånerstatus. Blacklistede filialer, som alligevel kan bruges via work-around viste DK-biblioteksnummer i stedet for filialens navn. [CMS-344](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-344)

- "Original titel: Unknown title" skjules nu på værkvisningssiden. Feltet "Original titel" vises ikke længere, hvis den returnerede værdi er "Unknown title". [CMS-1365](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1365)

- Felter for SMS-notifikation under "Opret bruger" respekterer nu indstillingen i back-end. Tidligere blev feltet "Mobilnummer" (som obligatorisk) og checkboksen "Modtag sms om dine lån, reserveringer osv." vist under brugeroprettelsen, selv når SMS-notifikationer var deaktiveret i CMS-indstillingerne. Nu skjules check-boksen, og mobilnummer er ikke længere obligatorisk, når indstillingen er slået fra. [CMS-2085](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2085)

- Lup-ikon igangsætter nu søgning. Klik på forstørrelsesglasset i det globale søgefelt udløser nu søgning på samme måde som Enter. [CMS-1988](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1988)

- Digital Artikelservice: Modal åbner nu korrekt efter login. Bestilling af digital kopi efter login åbner nu modalen korrekt, og scrollfunktionalitet bevares. [CMS-1992](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1992)

- Taxonomifejl rettet: Events vs. Arrangementer. URL-aliaser for arrangementer skifter ikke længere vilkårligt mellem /events og /arrangementer. [CMS-2025](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2025)

- Alle linjer i abstractet vises nu på værkvisningssiden. Når et værk har flere indholdsbeskrivende noter (felt 504), vises nu alle noter i stedet for kun den første. [CMS-1987](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1987)

- Backend: Sortering på startdato i arrangementsadministration fejler ikke længere. Sortering på startdato i /admin/content/eventseries fungerer nu korrekt, også efter en søgning. [CMS-2032](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2032)

- Værkvisningssiden: Korrekt sortering af udgaver med samme udgivelsesår. Udgaver sorteres nu med højeste udgavenummer først, og "Seneste udgave" vælger den faktisk seneste udgave. [CMS-2030](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2030)

- Lån af e-bøger: "Henter"-fejl rettet. Websiden linkede fejlagtigt til fravalgte PDF-versioner af e-bøger i stedet for tilgængelige EPUB-versioner. CMS'et vælger nu den korrekte udgave (PUBLIZON-identifikator). [CMS-2043](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2043)

- Oversættelser slår nu igennem. Fejl i oversættelsesudrulningssystemet er rettet, så oversættelser (bl.a. "Audience") vises korrekt på bibliotekernes sites. Bemærk: Vi mangler dog en sidste rettelse på dette, så ”Målgruppe” også vises oversat på selve arrangementssiden. Det kommer i en kommende release. 
