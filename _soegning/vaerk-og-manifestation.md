---
title: "Værk og manifestation"
category: "Visning og reservering"
---
Søgeresultater i  Folkebibliotekernes CMS leveres fra [brønden](https://www.dbc.dk/fbi/databronden){:target="_blank" rel="noopener"}. Søgninger sendes afsted og resultater modtages via en ny-udviklet snitflade der hedder [FBI-API](https://fbi-api.dbc.dk/){:target="_blank" rel="noopener"}. Den virker helt anderledes end den snitflade der bruges i DDB CMS.

FBI-API skelner mellem **værker** og **manifestationer**. Det er begreber, der er hentet fra [Dublin Core](https://www.dublincore.org/){:target="_blank" rel="noopener"}, som er en samling af internationale standarder for katalogisering.

Her er en skematisk oversigt over hvordan der skelnes mellem værk og manifestation i FBI-API. Læg f. eks. mærke til at en oversættelse af et værk betragtes som et selvstændigt værk, mens en nyoversættelse i samme sprog blot er en ny manifestation.

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f8e8f3a8-78fb-4916-a797-736a725490fe" alt="Værk- og manifestationsbegreberne i FBI-API" caption="Værk- og manifestationsbegreberne i FBI-API" %} 

Indførelsen af det nye værk-begreb betyder et større fokus på indhold, og et mindre på form, eftersom det nu er hele værket, der formidles - f. eks. ”Kongens Fald”, ikke ”Lydbogs-udgaven på MP3-cd af Kongens Fald”.

Der er flere **fordele ved værk-begrebet**. En af de vigtigste er, at alle manifestationer af samme værk nu er samlet på en [værkvisningsside]({{ site.baseurl }}{% link _soegning/vaerkvisningssiden.md %}). Førhen når der kom en ny udgave, så kom der også en ny materialeside, hvilket ofte førte til, at den nye udgave af en populær titel trak reserveringskøen, mens de ældre udgaver stod uberørte hen. Nu vil reserveringen fordele sig på alle udgaver af værket.

Desuden bringer øget fokus på værket os et skridt nærmere RDA, den nye katalogiseringsstandard, som DBC arbejder hen imod en indførelse af.
