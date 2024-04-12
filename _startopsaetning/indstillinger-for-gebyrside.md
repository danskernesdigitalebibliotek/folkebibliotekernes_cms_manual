---
title: "Opgave 3: Indstillinger for gebyrside"
category: "Startopsætning"
weight: 3
emneord:
  - Betaling
---

## For biblioteker der bruger Mit Betalingsoverblik
Du skal kopiere indstillinger fra DDB CMS over i Folkebibliotekernes CMS.

### Find oplysninger i DDB CMS
1. Log ind i DDB CMS med en bruger der har "Lokal administrator" rollen.
2.  I topmenuen klik på Indstillinger > Ding > Adgangsplatformen

Eller åbn via direkte link (udskift mit-domænenavn.dk):
https://mit-domænenavn.dk/admin/config/ding/adgangsplatformen

Kopier Client ID og Client Secret. Vær omhyggelig så det hele kommer med!



Indsæt oplysninger i Folkebibliotekernes CMS
1. Log ind som lokaladmin på jeres nye hjemmeside
2. Åbn siden med **Indstillinger for gebyrside**. Den ligger her: Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside
- Gennemgå og udfyld alle felter. 


Først skal du hente linket til Mit Betalingsoverblik fra DDB CMS. Dette gøres ved at følge stien Indstillinger - Betaling - Ding Payment. Under overskriften Payment Button finder du linket, der skal bruges i Next

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/7135c8f1-92b1-4332-9b24-2ebc7c41192c" alt="Siden Ding Payment i DDB CMS" caption="Siden Ding Payment i DDB CMS" %}


I Next tilgår du nu siden Indstillinger for begyrside, som angivet ovenfor.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/e230e220-e845-4899-9940-b11c6821a915" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}


Linket skal indsættes i to felter på siden: Indstillinger for knap til betaling, og Blokeret bruger.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/2e16d2f6-9d3f-4a7e-af7a-eaee1e0aa13a" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}

Du kan finde hjælp til alle felter på [manualsiden om Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/konfiguration/gebyrindstillinger/).
