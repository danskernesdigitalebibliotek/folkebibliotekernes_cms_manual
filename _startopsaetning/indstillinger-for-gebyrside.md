---
title: "Opgave 3: Indstillinger for gebyrside"
category: "Startopsætning"
weight: 3
emneord:
  - Betaling
---

Kopier **betalingslink** og **betalingsknaptekst** fra DDB CMS over i Folkebibliotekernes CMS.

[For biblioteker der ikke har Mit betalingsoverblik](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/startopsaetning/indstillinger-for-gebyrside/#for-biblioteker-der-ikke-har-mit-betalingsoverblik)

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
Biblioteker der pt. bruger Nets EASY betalingsmodulet, skal finde en ny løsning. Folkebibliotekernes CMS har ikke integration til Nets EASY og får det heller ikke. Årsagen ligger i det kommende FBS udbud, hvor al betalingsfunktionalitet udgår.

De fleste kommuner er i dag overgået til [ØiR](https://digitaliseringskataloget.dk/l%C3%B8sninger/oekonomi-i-rammearkitekturen){:target="_blank"}. Mange kommuner bruger desuden KMD Opus økonomisystemet, hvor borgernes udeståender samles i "Mit betalingsoverblik". 

I kommuner, der bruger andre økonomisystemer, er det anderledes. Ikke alle har en betalingsside, der kan linkes til. Her sendes opkrævninger via Digital Post og betaling sker via bankoverførsel.

Har I ikke "Mit betalingsoverblik", skal du udfylde gebyrindstillingerne anderledes.

Her er en guide:
1. Feltet **Indledende tekst** må ikke stå tomt. Hvis det står tomt, kommer der automatisk en tekst frem på gebyrsiden, der henviser til "Mit betalingsoverblik". Lav en kort beskrivelse af, hvordan betaling skal ske i jeres kommune.
2. Opret selv en [side](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/side/) med uddybende forklaring om vilkår for betaling. Indsæt link til denne side i felterne **Link til betalingsside** og **Link til blokeret bruger, som vises i modal**.
3. På gebyrsiden vises en knap til jeres side om betalingsvilkår. I bestemmer hvad der skal stå på knappen. udfyld **Tekst på knap til betalingsside** med ønsket knaptekst.


Du kan finde hjælp til alle felter på [manualsiden om Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/konfiguration/gebyrindstillinger/).






