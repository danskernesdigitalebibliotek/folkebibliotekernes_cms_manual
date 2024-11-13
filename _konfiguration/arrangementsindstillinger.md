---
title: "Arrangementsindstillinger"
click-path: "Indstillinger > Biblioteksindstillinger > Arrangementsindstillinger"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-event/settings`

## Price currency
Her vælges hvilken valuta priser skal angives i. Både på arrangementer og på gebyrer.

{% include figure class="thirty" image_path="https://github.com/user-attachments/assets/b53efcb9-2d89-43bd-bdaf-207878e8fed1" alt="Vælg valuta for hjemmesiden" caption="Vælg valuta for hjemmesiden" %}

Valg af valuta træder også igennem i event API'et og sendes dermed videre til f. eks. Place2book.

|Feltnavn|Standardværdi|
|---|---|
|Price currency|Danske kroner|

## Automatisk afpublicering
For at undgå at afholdte arrangementer vises på hjemmsiden, bliver de automatisk afpubliceret 6 timer efter sluttidspunktet.
Hvis I ønsker et andet tidsinterval eller helt at slukke for automatisk afpublisering, kan det gøres her.

{% include figure class="thirty" image_path="https://github.com/user-attachments/assets/edd58240-306c-45dd-8cdf-d952afa0249c" alt="Arrangementer afpubliceres automatisk fra hjemmesiden" caption="Arrangementer afpubliceres automatisk fra hjemmesiden" %}

|Feltnavn|Standardværdi|
|---|---|
|Automatisk afpublicering|6 timer|

