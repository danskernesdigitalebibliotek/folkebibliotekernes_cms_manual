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

## Blokeret bruger -  Link i modal til blokeret bruger (til fx Mit betalingsoverblik)
Hvis en bruger er blokeret pga. af overskredet gebyrgrænse vises en pop-up til brugeren ved login. I den pop-up har I mulighed for at tilføje link til jeres betalingsløsning - f. eks. Mit betalingsoverblik. Det er ikke påkrævet at udfylde feltet. Hvis det ikke er udfyldt, vises der bare ingen link i pop-op vinduet. Har I ikke har Mit betalingsoverblik kan det give god mening at linke til siden /takster i stedet.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2585e42e-af01-44cc-a543-4df5494c22a7" alt="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." caption="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." %} 

|Feltnavn|Anbefalet værdi|
|---|---|
|Link i modal til blokeret bruger|Link til betalingsside / alternativ side om betalingsmuligheder. Hvis feltet ikke udfyldes, skjules linket.|
