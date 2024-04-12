---
title: "Opgave 3: Indstillinger for gebyrside"
category: "Startopsætning"
weight: 3
emneord:
  - Betaling
---

Kopier **betalingslink** og **betalingsknaptekst** fra DDB CMS over i Folkebibliotekernes CMS.

## Kopier oplysninger fra DDB CMS
1. Log ind i DDB CMS med en bruger der har "Lokal administrator" rollen.
2. I topmenuen klik på **Indstillinger > Betaling > Ding Payment**\
   Eller åbn via URL (udskift mit-ddbcms-domænenavn.dk):\
  `https://mit-ddbcms-domænenavn.dk/admin/config/payment/ding`
3. Under overskriften **Payment Button** ligger de oplysninger der skal kopieres. Du skal bruge linket under **Payment Button URL** og knapteksten under **Payment Button Text**.
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c99ae7a4-7027-4544-bda1-ebe471158cb5" alt="Siden Ding Payment i DDB CMS" caption="Siden Ding Payment i DDB CMS" %}


## Indsæt oplysninger i Folkebibliotekernes CMS
1. Log ind på jeres nye hjemmeside med en bruger, der har rollen "Lokal administrator".
2. Via topmenuen åbn **Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside**
3. 
- Gennemgå og udfyld alle felter. 


Først skal du hente linket til Mit Betalingsoverblik fra DDB CMS. Dette gøres ved at følge stien Indstillinger - Betaling - Ding Payment. Under overskriften Payment Button finder du linket, der skal bruges i Next




I Next tilgår du nu siden Indstillinger for begyrside, som angivet ovenfor.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/e230e220-e845-4899-9940-b11c6821a915" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}


Linket skal indsættes i to felter på siden: Indstillinger for knap til betaling, og Blokeret bruger.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/2e16d2f6-9d3f-4a7e-af7a-eaee1e0aa13a" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}

## For biblioteker der skifter fra Nets EASY

Du kan finde hjælp til alle felter på [manualsiden om Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/konfiguration/gebyrindstillinger/).
