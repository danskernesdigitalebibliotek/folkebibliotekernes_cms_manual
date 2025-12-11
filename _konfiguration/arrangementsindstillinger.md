---
title: "Arrangementsindstillinger"
click-path: "Indstillinger > Biblioteksindstillinger > Arrangementsindstillinger"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-event/settings`

## Price currency
Her vælger I, hvilken valuta priser bliver angivet i. Det gælder både priser på arrangementer og gebyrer.

{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/b53efcb9-2d89-43bd-bdaf-207878e8fed1" alt="Vælg valuta for hjemmesiden" caption="Vælg valuta for hjemmesiden" %}

Valg af valuta træder også igennem i event API'et og sendes dermed videre til f. eks. Place2book.

|Feltnavn|Standardværdi|
|---|---|
|Price currency|Danske kroner|

## Automatisk afpublicering
For at undgå at afholdte arrangementer vises på hjemmsiden i automatic paragraphs og lister, kan I vælge at de bliver automatisk afpubliceret et tidsrum efter sluttidspunktet. Hvis I ønsker et andet tidsinterval eller helt at slukke for automatisk afpublisering, kan det gøres her.

I kan vælge mellem om det er instanser og/eller serien der bliver afpubliceret. Vi anbefaler at både serier og instanser afpubliseres. Hvis I har mange arrangementer kan det være en fordel at have kortere afpubliseringsperiode og omvendt - en længere periode, hvis I har få arrangementer. 

Vær opmærksom på, at hvis du vælger IKKE at afpublisere udløbede arrangementsinstanser, er det muligt, at de vises i automatiske og manuelle lister rundt om på siden.

Når I afpublicerer serier så vil links til de afpublicerede instanser redirecte hen til serien. Det betyder at hvis man har linket til et arrangement i en manual paragraph eller linket i et nyhedsbrev, så mødes brugeren ikke med en fejlside når instanser bliver afpubliceret. Dog opleves der flere problemer med ikke at afpublisere både serier og instanser.

{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/fcee14a1-4a54-4192-808e-47f4ee4e4501" alt="Indstil at arrangementer afpubliceres automatisk fra hjemmesiden" caption="Indstil at arrangementer afpubliceres automatisk fra hjemmesiden" %}

|Feltnavn|Standardværdi|
|---|---|
|Automatisk afpublicering|6 timer|

