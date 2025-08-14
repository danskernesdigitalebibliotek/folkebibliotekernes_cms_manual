---
title: "3. Betaling"
category: "Opgaver - Basiskonfiguration"
weight: 3

---
De fleste kommuner er i dag overgået til [ØiR](https://digitaliseringskataloget.dk/l%C3%B8sninger/oekonomi-i-rammearkitekturen){:target="_blank"}. Mange kommuner bruger desuden KMD Opus økonomisystemet, hvor borgernes udeståender samles i "Mit betalingsoverblik". 

"Mit betalingsoverblik" giver en samlet oversigt over de økonomiske mellemværender med kommunen. Det er alt fra betaling af børnehaveplads, ejendomsskat og biblioteksgebyrer.

[Har I ikke "Mit betalingsoverblik", så læs mere her](https://www.folkebibliotekernescms.dk/main/startopsaetning/betaling/#for-biblioteker-der-ikke-har-mit-betalingsoverblik).

Skal biblioteket i gang med ØiR og "Mit betalingsoverblik" skal du kontakte den person, der er ansvarlig for systemet i jeres kommune og sørge for at biblioteket bliver tilknyttet. 
Du skal også have udleveret et link til den side, som borgerne skal logge ind på, for at betale deres mellemværende.

URLen til "Mit betalingsoverblik" er den samme for alle enheder i jeres kommune. Biblioteket skal ikke have et særligt link. 

Mangler du linket, kan du ofte finde det på kommunens hjemmeside. Find et sted hvor der linkes til "Mit betalingsoverblik" og kopier linket. 

## Udfyld Indstillinger for gebyrside
**Her indstiller du link til Mit betalingsoverblik, labels på betalingsknap og andre indstillinger der handler om gebyrer og betaling**

- Log ind som lokaladmin på jeres nye hjemmeside
- Åbn siden med **Indstillinger for gebyrside**. Den ligger her: Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside
- Gennemgå og udfyld alle felter. Du kan finde hjælp til alle felter på [manualsiden om de Indstillinger for gebyrside](https://www.folkebibliotekernescms.dk/main/konfiguration/gebyrindstillinger/).

## Sådan ser det ud for brugerne

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/772addb4-9c5d-48dc-886a-7905f2e66270" alt="Gebyr på brugerprofilen" caption="Gebyr på brugerprofilen" %}

Når man trykker på knappen "Se mere" under overskriften "Dit overblik" får man en detaljeret oversigt over hvilket materialer der er pålagt gebyr og med knap til betaling på Mit betalingsoverblik.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/f15f8d81-801d-47da-9e67-f29312cbb02e" alt="Oversigt over begyrer" caption="Oversigt over begyrer" %}


Hvis man har overskredet gebyrgrænsen vil det således ud:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/95400b0e-5f52-4d01-9edc-0047ade881bf" alt="Pop up vindue med besked om at begybrgrænsen er overskredet" caption="Pop up vindue med besked om at begybrgrænsen er overskredet" %}

## Tilret gebyrlabels i Cicero
Folkebibliotekernes CMS viser via labels om et mellemværende er et gebyrer eller en erstatning. Labeltekster hentes fra Cicero.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c74189b1-d44f-47e9-9364-eb80a9bc0797" alt="Labeltekster hentes fra Cicero." caption="Labeltekster hentes fra Cicero." %}

I kan tilrette de viste labels i Cicero.
1. Log ind som administrator i Cicero og gå til **F7 - SYSADMIN**
2. Søg på **systemoprettede**
3. Tilret værdierne for de tre viste parametre. Hvis de er for lange, bliver de ikke vist korrekt i Folkebibliotekernes CMS. Vi anbefaler at I giver dem værdierne **Erstatning**, **Gebyr** og **Gebyr (for sent)**

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/900c11a2-6893-4ac0-92ab-f9516c2c955e" alt="Tilret labeltekster i Cicero." caption="Tilret labeltekster i Cicero." %}


## For biblioteker, der ikke har Mit betalingsoverblik

De fleste kommuner er i dag overgået til [ØiR](https://digitaliseringskataloget.dk/l%C3%B8sninger/oekonomi-i-rammearkitekturen){:target="_blank"}. Mange kommuner bruger desuden KMD Opus økonomisystemet, hvor borgernes udeståender samles i "Mit betalingsoverblik". 

Kommuner, der ikke bruger KMD Opus økonomisystemet, har ikke "mit betalingsoverblik". Men de har måske en anden betalingsside, der kan linkes til. 
I kommuner hvor der ikke er adgang til en betalingsside kan biblioteket sende opkrævninger via Digital Post og betaling ske via bankoverførsel.

Har I ikke "Mit betalingsoverblik", skal du udfylde gebyrindstillingerne anderledes.

Her er en guide:
1. Feltet **Indledende tekst** må ikke stå tomt. Hvis det står tomt, kommer der automatisk en tekst frem på gebyrsiden, der henviser til "Mit betalingsoverblik". Lav en kort beskrivelse af, hvordan betaling skal ske i jeres kommune.
2. Opret selv en [side](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/side/) med uddybende forklaring om vilkår for betaling. Indsæt link til denne side i felterne **Link til betalingsside** og **Link til blokeret bruger, som vises i modal**.
3. På gebyrsiden vises en knap til jeres side om betalingsvilkår. I bestemmer hvad der skal stå på knappen. udfyld **Tekst på knap til betalingsside** med ønsket knaptekst.


Du kan finde hjælp til alle felter på [manualsiden om Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/konfiguration/gebyrindstillinger/).






