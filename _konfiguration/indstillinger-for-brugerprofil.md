---
title: "Indstillinger for brugerprofil"
click-path: "Indstillinger > Biblioteksindstillinger > Indstillinger for brugerprofil"
category: "Konfiguration"
emneord: 
- "FBS"
- "Publizon"
- "Faste sider"

---

I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/patron-page-settings`

## Url til side om hvordan man bliver slettet som bruger af biblioteket
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d5250e9e-20c7-495f-9946-6056a9950067" alt="Vises som et link nederst i brugerprofilen (/user/me)" caption="Vises som et link nederst i brugerprofilen (/user/me)" %} 

Her kan du indsætte et link til en hjælpeside om, hvordan man bliver slettet som bruger på biblioteket. Som standard linkes til 
[**Privatlivspolitik**](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/privatlivspolitik/), der er navnet på en [fast side](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/faste-sider/) som Folkebibliotekernes CMS leveres med.
Ønsker I at linke til en anden side end privatlivspolitik, indsætter I bare en anden URL i feltet.

|Feltnavn|Standardværdi|
|---|---|
|Url til side om hvordan man bliver slettet som bruger af biblioteket|Standardværdien er `/privatlivspolitik`. Kan udskiftes med en anden URL efter ønske.|

## eReolens titler som altid er tilgængelige
Her skal indsættes et link til eReolens titler, som altid er tilgængelige. Det vises på brugerprofilen under Digitale lån.

{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/7a124bee-2617-4070-ad91-6c56d96d91cb" alt="Vises som et link på brugerprofilen" caption="Vises som et link på brugerprofilen" %}

Som standard er feltet tomt. Vi anbefaler, at I indsætte linket: `https://ereolen.dk/content/boeger-du-altid-kan-laane`

|Feltnavn|Anbefalet værdi|
|---|---|
|eReolens titler som altid er tilgængelige|`https://ereolen.dk/content/boeger-du-altid-kan-laane`|


## Pinkodelængde (minimumslængde)
I Cicero har I indstillet, hvor lange brugernes pinkoder skal være. Det mest almindelige er 4 cifre, men nogle kommuner bruger 5 cifre. Nogle kommuner bruger et miks af de to. Det er vigtigt, at I her oplyser den rigtige pin kode længde.
 
|Feltnavn|Standardværdi|
|---|---|
|Pinkodelængde (minimumslængde)|4|

## Pinkodelængde (maksimumslængde)
I Cicero har I indstillet, hvor lange brugernes pinkoder skal være. Det mest almindelige er 4 cifre, men nogle kommuner bruger 5 cifre. Nogle kommuner bruger et miks af de to. Det er vigtigt, at I her oplyser den rigtige pinkode længde.

|Feltnavn|Standardværdi|
|---|---|
|Pinkodelængde (maksimumslængde)|4|


