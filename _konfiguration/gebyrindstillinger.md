---
title: "Indstillinger for gebyrside"
click-path: "Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/fees`

Skal du i gang med gebyr-konfiguration? [Baggrundsinformation vedr. Indstillinger for gebyrside](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/startopsaetning/indstillinger-for-gebyrside/).
{: .notice--primary}

## URL
URL til informationsside om gebyrtakster, erstatninger og betaling. Der linkes til denne side flere steder, bla. fra Gebyrer & Erstatninger, men også fra materialer, som er ved at udløbe.

Som standard linkes til [**Takster**](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/takster/), der er navnet på en [fast side](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/faste-sider/) som Folkebibliotekernes CMS leveres med.

Ønsker I at linke til en anden side, indsætter I bare en anden URL i feltet.

## Indledende tekst
Indledende tekst, som vises øverst på brugernes oversigt over "Gebyrer & erstatninger". Efterlades feltet tomt, vises teksten "Gebyrer og erstatninger håndteres via Mit betalingsoverblik". Standardteksten erstattes automatisk, af det du skriver.

## Link til betalingsside
Her indsættes link til "Mit betalingsoverblik" eller anden betalingsside. Har I ikke en ekstern betalingsside, som I kan linke til, kan I selv oprette en side med uddybende forklaring om vilkår for betaling og linke til den.

## Tekst på knap til betalingsside
Her bestemmer I, hvad der skal stå på knappen der linker til betalingssiden.

## Blokeret bruger -  Link i modal til blokeret bruger (til fx Mit betalingsoverblik)
Hvis en bruger er blokeret pga. af overskredet gebyrgrænse vises en pop-up til brugeren ved login. I den pop-up har I mulighed for at tilføje link til jeres betalingsløsning - f. eks. Mit betalingsoverblik. Det er ikke påkrævet at udfylde feltet. Hvis det ikke er udfyldt, vises der bare ingen link i pop-op vinduet. Har I ikke Mit betalingsoverblik kan det give god mening at linke til siden /takster i stedet.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2585e42e-af01-44cc-a543-4df5494c22a7" alt="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." caption="Pop-up, der vises til blokerede brugere med overskredet gebyrgrænse. I bestemmer, hvor linket markeret med rødt peger hen, eller om det overhovedet skal vises." %} 


