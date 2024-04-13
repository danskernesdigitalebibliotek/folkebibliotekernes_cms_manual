---
title: "Opgave 3: Indstillinger for gebyrside"
category: "Startopsætning"
weight: 3
emneord:
  - Betaling
---

Kopier **betalingslink** og **betalingsknaptekst** fra DDB CMS over i Folkebibliotekernes CMS.

[For biblioteker der ikke har Mit betalingsoverblik]()

## Kopier oplysninger fra DDB CMS
1. Log ind i DDB CMS med en bruger, der har "Lokal administrator" rollen.
2. I topmenuen klik på **Indstillinger > Betaling > Ding Payment**\
   Eller åbn via URL (udskift mit-ddbcms-domænenavn.dk):\
  `https://mit-ddbcms-domænenavn.dk/admin/config/payment/ding`
3. Under overskriften **Payment Button** ligger de oplysninger, der skal kopieres. Du skal bruge linket under **Payment Button URL** og knapteksten under **Payment Button Text**. Vær omhyggelig, når du kopierer, så det hele kommer med!
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c99ae7a4-7027-4544-bda1-ebe471158cb5" alt="Siden Ding Payment i DDB CMS" caption="Siden Ding Payment i DDB CMS" %}

## Indsæt oplysninger i Folkebibliotekernes CMS
1. Log ind på jeres nye hjemmeside med en bruger, der har rollen "Lokal administrator".
2. Via topmenuen åbn **Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside**
    {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/e230e220-e845-4899-9940-b11c6821a915" alt="Indstillinger for gebyrside" caption="Indstillinger for gebyrside" %}

3. Indsæt **Payment Button URL** i to felter på siden: **Link til betalingsside** og **Link til blokeret bruger, som vises i modal**.
4. Indsæt **Payment Button Text** i feltet **Tekst på knap til betalingsside**.

   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/ed9403ca-fe18-4fc1-ab4a-361c7b0b587c" alt="Indstillinger for gebyrside" caption="Indstillinger for gebyrside" %}

## For biblioteker, der ikke har Mit betalingsoverblik
Biblioteker, der hidtil har modtaget betalinger via Nets EASY betalingsmodulet på den gamle hjemmeside, skal finde en ny løsning. Folkebibliotekernes CMS har ikke integration til Nets EASY og får det heller ikke. Årsagen ligger i det kommende FBS udbud, hvor al betalingsfunktionalitet udgår.

De fleste kommuner er i dag overgået til [ØiR](https://digitaliseringskataloget.dk/l%C3%B8sninger/oekonomi-i-rammearkitekturen). I kommuner med KMD Opus økonomisystemet samles borgernes udeståender i "Mit betalingsoverblik". I kommuner, der bruger andre økonomisystemer, er det anderledes. Ikke alle har en betalingsside, der kan linkes til. Her sendes opkrævninger via Digital Post og betaling skal ske via bankoverførsel.

Virker det sådan i din kommune, skal du  udfylde felterne anderledes.

Først 



Du kan finde hjælp til alle felter på [manualsiden om Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/konfiguration/gebyrindstillinger/).






