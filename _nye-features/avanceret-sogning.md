---
title: "Avanceret søgning og CQL Søgning"
category: "Søgning"
---

Bemærk: Den komplette liste over alle søgekoder, der kan bruges, findes her: [https://fbi-api.dbc.dk/indexmapper/](https://fbi-api.dbc.dk/indexmapper/)
{: .notice--info}

Når man søger i Folkebibliotekernes CMS, så benyttes som udgangspunkt Simple Search, da det er bygget til at understøtte de hyppigste brugsscenarier.

Men der er også brugs-scenarier, hvor der er behov for traditionel feltsøgning. Studerende og undervisere, der skal finde litteratur til en opgave, og har f. eks. ofte behov for at foretage præcise, verifikative søgninger, som ikke understøttes i simple search. Simple Search understøtter nemlig ikke kommandosøgning og boolsk logik.

Også fagpersonalet på bibliotekerne har brug for avanceret søgning og cql søgning ifm. publikumsekspedition samt ved udformning af indhold til online formidling.

Avanceret søgning tilgås ved at klikke på pilen til højre i søgefeltet: 

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/7fd10fc5-7f9b-4bb4-bb5d-57b390c7a6bb" alt="Billedet viser hvordan man finder avanceret søgning" caption="Billedet viser hvordan man finder avanceret søgning" %}

Så kommer man til denne side:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/70df936c-212e-4ea4-abee-f994fc0c74ce" alt="Billedet viser feltet avanceret søgning" caption="Billedet viser feltet avanceret søgning" %}

Vi har forsøgt at gøre den så selvforklarende som muligt.

I felterne, hvor der står ”Søg på forfatter, titel mv.” kan man skrive sine søgetermer og derpå kan man i dropdown’en til højre vælge, hvilket indeks, der skal søges i:

{% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/1f3a4ba5-cf3f-47d8-b891-40934847e685" alt="Billedet viser udvalget af søgeindekser" caption="Billedet viser udvalget af søgeindekser" %}

Nedenunder kan man vælge ”Materialetype”. Bemærk, at det er generel materialetype (dvs fx ”Lydbog”) – ikke specifik materialetype (dvs ikke ”Lydbog (MP3)”, ”Lydbog (CD)” eller ”Lydbog (online)”):

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/df6c921f-d785-4962-8576-84ceeca7f04b" alt="Billedet viser hvordan man vælger materialetype" caption="Billedet viser hvordan man vælger materialetype" %}

”Skøn/faglitteratur”:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/f78a78ed-e962-49e0-9a54-6499ab69ee6a" alt="Billedet viser hvordan man vælger skøn- eller faglitteratur" caption="Billedet viser hvordan man vælger skøn- eller faglitteratur" %}

…. Eller ”Fysisk/online”:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/f92dbd67-afa1-4316-bc95-36733a48f5c5" alt="Billedet viser hvordan man vælger fysiske eller online materialer" caption="Billedet viser hvordan man vælger fysiske eller online materialer" %}

Bemærk, at mens man taster og tilføjer sine valg, tilretter CQL-søgestrengen i boksen til højre sig:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/0bd70043-de70-476b-bb66-d948192a5a7d" alt="Billedet viser hvordan søgningen tilpasser sig nye valg" caption="Billedet viser hvordan søgningen tilpasser sig nye valg" %}

Ønsker man at benytte ’ren’ kommandosøgning, skal man klikke på ”Rediger CQL”.
Så kommer man til et felt, hvor man kan skrive alle søgekoder:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c68e6232-5e0a-4a7f-93e9-bea12fdca0dd" alt="Billedet viser feltet Avanceret søgning" caption="Billedet viser feltet Avanceret søgning" %}

Den komplette liste over alle søgekoder, der kan bruges, findes her: [https://fbi-api.dbc.dk/indexmapper/](https://fbi-api.dbc.dk/indexmapper/)

Når man har klikket ”Søg”, kommer man til et søgeresultat, der afviger fra det normale på flere måder:
For det første er der ingen filtre – hvis man ønsker at tilrette sin søgning, skal man scrolle op til toppen, hvor ”Avanceret-søgning” brugergrænsefladen befinder sig.

For det andet, gives der en mulighed for ”Link til denne søgning”:

{% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/1a463418-91ab-4e62-94ef-2f89fe3cd47d" alt="Billedet viser knappen Link til denne søgning" caption="Billedet viser knappen Link til denne søgning" %}

Ved klik kopieres linket over til éns udklipsholder:

{% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/557d79b1-57bd-4682-bbb3-b04581879f02" alt="Billedet viser at link til søgning er kopieret til udklipsholder" caption="Billedet viser at link til søgning er kopieret til udklipsholder" %}

Muligheden for at linke direkte til et søgeresultat inkl. filtrering findes ikke i simple search. Ønsker man at dele et link til en søgning, er man derfor nødt til at foretage den vha Avanceret Søgning.

For det tredje, må man være opmærksom på, at en søgning, der er startet i Simple Search ikke kan videreføres i Complex Search, og omvendt. Det er to fundamentalt forskellige søgemaskiner, så det er ikke muligt at tage en søgning, man har udført i Simple Search og trække den over i Avanceret Søgning.
