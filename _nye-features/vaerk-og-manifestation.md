---
title: "Værk og manifestation"
category: "Søgning"
---
Søgeresultater i  Folkebibliotekernes CMS leveres fra [brønden](https://www.dbc.dk/fbi/databronden). Søgninger sendes afsted og resultater modtages via en ny-udviklet snitflade der hedder [FBI-API](https://fbi-api.dbc.dk/). Den virker helt anderledes end den snitflade der bruges i DDB CMS.

FBI-API skelner mellem **værker** og **manifestationer**. Det er begreber, der er hentet fra [Dublin Core](https://www.dublincore.org/), som er en samling af internationale standarder for katalogisering.

Her er en skematisk oversigt over hvordan der skelnes mellem værk og manifestation i FBI-API. Læg f. eks. mærke til at en oversættelse af et værk betragtes som et selvstændigt værk, mens en nyoversættelse i samme sprog blot er en ny manifestation.

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f8e8f3a8-78fb-4916-a797-736a725490fe)
*Værk- og manifestationsbegreberne i FBI-API*

Indførelsen af det nye værk-begreb betyder et større fokus på indhold, og et mindre på form, eftersom det nu er hele værket, der formidles - f. eks. ”Kongens Fald”, ikke ”Lydbogs-udgaven på MP3-cd af Kongens Fald”.

Der er flere **fordele ved værk-begrebet**. En af de vigtigste er, at alle manifestationer af samme værk nu samles på én [værkvisningsside](vaerkvisningssiden.md), hvor det før var sådan, at når der kom en ny udgave af en bog, så kom der også en ny materialeside, hvilket ofte førte til, at en ny udgave af en populær titel kunne trække reserveringskøer, mens ældre udgaver stod urørte hen.

Desuden bringer øget fokus på værket os et skridt nærmere RDA, den nye katalogiseringsstandard, som DBC arbejder hen imod en indførelse af.

