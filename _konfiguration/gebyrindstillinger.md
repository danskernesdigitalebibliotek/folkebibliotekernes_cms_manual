---
title: "Indstillinger for gebyrside"
click-path: "Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside"
category: "Konfiguration"
emneord: 
- "Betaling"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/fees`

## Benyttelse af Mit Betalingsoverblik
Først skal du hente linket til Mit Betalingsoverblik fra DDB CMS. Dette gøres ved at følge stien Indstillinger - Betaling - Ding Payment. Under overskriften Payment Button finder du linket, der skal bruges i Next

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/7135c8f1-92b1-4332-9b24-2ebc7c41192c" alt="Siden Ding Payment i DDB CMS" caption="Siden Ding Payment i DDB CMS" %}


I Next tilgår du nu siden Indstillinger for begyrside, som angivet ovenfor.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/e230e220-e845-4899-9940-b11c6821a915" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}


Linket skal indsættes i to felter på siden: Indstillinger for knap til betaling, og Blokeret bruger.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/2e16d2f6-9d3f-4a7e-af7a-eaee1e0aa13a" alt="Indstillinger for begyrside" caption="Indstillinger for begyrside" %}



På brugersiden vil det nu se således ud:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/772addb4-9c5d-48dc-886a-7905f2e66270" alt="Gebyr på brugerprofilen" caption="Gebyr på brugerprofilen" %}



Hvis man har overskredet gebyrgrænsen vil det således ud:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/95400b0e-5f52-4d01-9edc-0047ade881bf" alt="Pop up vindue med besked om at begybrgrænsen er overskredet" caption="Pop up vindue med besked om at begybrgrænsen er overskredet" %}




## Blokeret bruger - Link til blokeret bruger som vises i modal
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/cc02b26e-f7d1-4791-ae12-a8615972ef7a)


## Blokeret bruger -  Link i modal til blokeret bruger (til fx Mit betalingsoverblik)
Hvis en bruger er blokeret pga. af overskredet gebyrgrænse vises en pop-up til brugeren ved login. I den pop-up har I mulighed for at tilføje link til jeres betalingsløsning - f. eks. Mit betalingsoverblik. Det er ikke påkrævet at udfylde feltet. Hvis det ikke er udfyldt, vises der bare ingen link i pop-op vinduet. Har I ikke har Mit betalingsoverblik kan det give god mening at linke til siden /takster i stedet.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2585e42e-af01-44cc-a543-4df5494c22a7" alt="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." caption="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." %} 

|Feltnavn|Anbefalet værdi|
|---|---|
|Link i modal til blokeret bruger|Link til betalingsside / alternativ side om betalingsmuligheder. Hvis feltet ikke udfyldes, skjules linket.|
