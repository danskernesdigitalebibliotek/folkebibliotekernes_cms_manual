---
title: "Brugeroprettelse"
click-path: "Indstillinger > Biblioteksindstillinger > Brugeroprettelse"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/people/registration`

## Minimumsalder for selvoprettelse som låner
Standardværdi er 18 år. 

## URL til brugeroprettelsesside
Standardværdi er `/opret-bruger`. 
Ændrer man værdien i dette felt, påvirker man, hvor "Opret bruger" linket på Login panelet peger hen.
{% include figure class="fifty" image_path="https://github.com/user-attachments/assets/c09164f6-74d3-4d65-a38f-7b8003945464" alt="Vises som et link på brugerprofilen" caption="Vises som et link på brugerprofilen" %}

## Side som låner omdirigeres til ved oprettelse
Standardværdien er `/velkommen`. Det bør man ikke ændre på, da det skal matche URL på den [faste side](https://www.folkebibliotekernescms.dk/main/indhold/faste-sider/) "Velkommen".
Denne side vises til brugere, der netop har oprettet sig med MitID på bibliotekets hjemmeside.
