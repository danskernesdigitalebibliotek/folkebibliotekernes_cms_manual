---
title: "Indstillinger for strakslån"
click-path: "Indstillinger > Biblioteksindstillinger > Indstillinger for strakslån"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/instant-loan`

## Hvad er strakslån?
Mens man opretter en reservation kan man få en strakslåns-notifikation.

{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/92878194-ce04-4b91-bf10-a602dc50b427" alt="Strakslåns-notifikation" caption="Strakslåns-notifikation" %}

Du møder strakslåns-notifikationen, når der er reserveringskø på den materialetype, du er ved at reservere OG hvis biblioteket har et eller flere ikke-reserverbare eksemplarer hjemme. Mange biblioteker har ikke-reserverbare eksemplarer i form af "kviklån" eller "kortlån".

I det tilfælde bliver du gjort opmærksom på, at du kan springe reservationskøen over, hvis du tager hen på biblioteket med det samme.

## Opsætning af strakslåns-notifiation
I kan opsætte strakslånsnotifikation for jeres bibliotek, hvis I benytter jer af **materialegrupper**, der ikke er reserverbare. 
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/62bd67d0-d043-452e-a124-d0bff09d83fe" alt="Opsætning af strakslåns-notifikation" caption="Opsætning af strakslåns-notifikation" %}

Som standard er stakslåns-notifikationen deaktiveret. 

Når I aktiverer funktionen, skal også feltet **Non-res materialegrupper** udfyldes med **Navn** på materialegruppen eller -grupperne. Er der flere materialegrupper, skrives de på hver sin linje.

En oversigt over **materialegrupper** findes på Ciceros F6 Fane. Det er det, der står i kolonnen **Navn** der skal indsættes.
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/3ad077ae-a563-47c6-8480-0e5a8e8182d7" alt="Materialegrupper i Cicero" caption="Materialegrupper i Cicero" %}

I skal også vælge hvor mange ikke-reserverbare eksemplarer der skal stå på en filial, før strakslåns-notifikationen vises.

|Feltnavn|Standardværdi|
|---|---|
|Tilvælg|Deaktiveret|
|Non-res materialegrupper|Tom|
|Varsel|1|





