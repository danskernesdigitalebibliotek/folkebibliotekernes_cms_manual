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

Klik på Personer i topmenuen.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/e397e043-3d62-4cf4-8632-3bdeb76cba76" alt="Klik på knappen Personer" caption="Klik på knappen Personer" %}

Klik på knappen Add user i øverste højre hjørne.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c461ffc6-a518-4612-b8e9-6242c774c6fd" alt="Klik på knappen Add user" caption="Klik på knappen Add user" %}

Du skal nu udfylde en formular med oplysninger om den nye systembruger. Se et eksempel på formularen nedenfor.

Indtast oplysningerne i formularen:

+ email adress - systembrugerens email
+ Username - systembrugerens interne brugernavn
+ Password - systembrugerens adgangskode

**Status:**
Er automatisk sat til Active. Hvis brugeren skal blokeres vælges Blocked.

**Roles:**
Vælg systembrugerens rolle. For de fleste almindelige redaktører vil rollen Editor være tilstrækkelig.

+ Administrator har adgang til....
+ Local administrator har adgang til....
+ Mediator kan...
+ Patron er rollen som almindelig bibliotekslåner. (??)

**Notify:**
Knappen Notify kan markeres, hvis alle øvrige systembrugere skal informeres om oprettelse af den nye systembruger (??)

**Language settings:**
Vælg mellem dansk og engelsk sprog for den nye systembrugers kontrolpanel.

**Create new account:**
Afslut opretningen ved at klikke på Create new account

**Eksempel på systembruger formular:**

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/122aaf9b-c55a-45c5-bac3-fe38d2a5e28f" alt="En tom systembruger formular" caption="En tom systembruger formular" %}
