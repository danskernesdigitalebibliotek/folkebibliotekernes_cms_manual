---
title: "Brugeroprettelse"
click-path: "Indstillinger > Biblioteksindstillinger > Brugeroprettelse"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/people/registration`

{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/a0344283-1367-4d2b-8984-5ed9f93e7b44" alt="Indstillinger for brugeroprettelse" caption="Indstillinger for brugeroprettelse" %}

## Minimumsalder for selvoprettelse som låner
Standardværdi er 18 år. 

|Feltnavn|Standardværdi|
|---|---|
|Minimumsalder for selvoprettelse som låner|18|

## URL til brugeroprettelsesside
Standardværdi er `/opret-bruger`. Det bør man ikke ændre på, da det skal matche URL på den [faste side](https://www.folkebibliotekernescms.dk/main/indhold/faste-sider/) "Opret bruger". Ændrer man værdien i dette felt, ændrer man URL bag "Opret bruger" linket på Login-panelet.

|Feltnavn|Standardværdi|
|---|---|
|URL til brugeroprettelsesside|Standardværdi er `/opret-bruger`|

{% include figure class="thirty" image_path="https://github.com/user-attachments/assets/c09164f6-74d3-4d65-a38f-7b8003945464" alt="Her styrer du hvilken URL som 'Opret bruger' linket skal pege på" caption="Her styrer du hvilken URL som 'Opret bruger' linket skal pege på" %}

## Side som låner omdirigeres til ved oprettelse
Standardværdi er `/velkommen`. Det bør man ikke ændre på, da det skal matche URL på den [faste side](https://www.folkebibliotekernescms.dk/main/indhold/faste-sider/) "Velkommen".
Denne side vises til brugere, der netop har oprettet sig med MitID på bibliotekets hjemmeside.
|Feltnavn|Standardværdi|
|---|---|
|Side som låner omdirigeres til ved oprettelse|Standardværdi er `/velkommen`|

