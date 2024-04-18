---
title: "Opret systembruger og skift password"
click-path: "Personer"
category: "Konfiguration"
emneord: 
- "Brugere og roller"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/people`

## Opret systembruger

Klik på knappen Add user i øverste højre hjørne.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c461ffc6-a518-4612-b8e9-6242c774c6fd" alt="Klik på knappen Add user" caption="Klik på knappen Add user" %}

Du skal nu udfylde en formular med oplysninger om den nye systembruger. Se et eksempel på formularen nedenfor.

Indtast oplysningerne i formularen:

+ Email adress - systembrugerens email.
+ Username - systembrugerens interne brugernavn (er kun synligt i kontrolpanelet).
+ Password - systembrugerens adgangskode.

**Status:**
Er automatisk sat til Active. Hvis brugeren skal blokeres vælges Blocked.

**Roles:**
Vælg systembrugerens rolle. For de fleste almindelige redaktører vil rollen Editor være tilstrækkelig. Editor kan oprette indhold, men har ikke adgang til at ændre indstillinger på siden.

For mere information om brugerroller - se manualens punkt [Startopsætning - opgave 4:  opret systembrugere](https://www.folkebibliotekernescms.dk/main/startopsaetning/systembrugere/)

**Notify:**
Knappen Notify kan markeres, hvis alle øvrige systembrugere skal informeres om oprettelse af den nye systembruger.

**Language settings:**
Vælg mellem dansk og engelsk sprog for den nye systembrugers kontrolpanel.

**Create new account:**
Afslut opretningen ved at klikke på Create new account

**Eksempel på systembruger formular:**

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/122aaf9b-c55a-45c5-bac3-fe38d2a5e28f" alt="En tom systembruger formular" caption="En tom systembruger formular" %}

## Skit password for systembruger

Log ind som systembruger.

Klik på Admin ikonet i øverste højre hjørne og vælg Edit profile.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c20cd123-8f6f-4006-866d-166ccdcd687b" alt="Edit profile" caption="Edit profile" %}

Udfyld felterne med det nuværende password og det nye.
Hvis du ikke kan huske det nuværende password, kan du klikke på linket Reset your password. En vejledning bliver du sendt til din email.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/42efd3ec-175f-4a02-b99e-b0315e86b5da" alt="Skift adgangskode" caption="Skift adgangskode" %}

