---
title: "Opret systembruger og skift password"
click-path: "Redaktionelle brugere"
category: "Konfiguration"
emneord: 
- "Brugere og roller"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/people`

## Opret systembruger

Log på med en bruger der har rollen **administrator** eller **lokal administrator**. Ellers har du ikke nok rettigheder, til at kunne oprette brugere.

Klik på knappen **Add user** i øverste højre hjørne.

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

[Læs mere om de tilgængelige brugerroller](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#roller)

**Notify:**
Knappen Notify kan markeres, hvis alle øvrige systembrugere skal informeres om oprettelse af den nye systembruger.

**Language settings:**
Vælg mellem dansk og engelsk sprog for den nye systembrugers kontrolpanel. Det er vigtigt at sætte sproget til dansk. Hele manualen er skrevet ud fra den danske oversættelse.

**Create new account:**
Afslut opretningen ved at klikke på Create new account

**Eksempel på systembruger formular:**

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/122aaf9b-c55a-45c5-bac3-fe38d2a5e28f" alt="En tom systembruger formular" caption="En tom systembruger formular" %}

## Roller

Når du opretter en ny systembrugere skal han/hun tildeles en rolle. 

Som udgangspunkt skal jeres brugere ikke tildeles flere rettigheder, end dem der er nødvendige, for at de kan løse deres arbejdsopgaver.
{: .notice}

**Redaktørbiblioteker** kan oprette tre typer brugere:

- **Formidler (mediator)** er til brugere som ofte laver det dynamiske formidlingsindhold på hjemmesiden. Har adgang til at oprette og redigere arrangementer, artikler, sider og kampagner. 

- **Redaktør (editor)** er til brugere som udover formidlingsopgaver også skal stå for det faste indhold (fx åbningstider) og opbygning af sidens struktur. De kan have ansvaret for at koordinere og styre formidlernes arbejde. Har adgang til det samme som formidler plus alle indholdstyper i /admin/content samt taksonomi og menuer i admin/structure.

- **Lokal administrator (local administrator)** er til brugere som skal indstille hjemmesiden ift. indstillinger, udseende, integrationer, overordnet oplysninger, biblioteksbrug etc. Har adgang til det samme som redaktør plus sidens konfigurationsmuligheder i /admin/config, oprettelse af brugere i /admin/people og ændring af sidens udseende i /admin/appearance.

**Webmasterbiblioteker** har en ekstra brugertype:
- **Administrator** kan ændre siden udover CMS'ets standardindstillinger fx ved at aktivere og deaktivere moduler. Har adgang til alt i CMS'et.

**Patron** er lånerne. Patron-brugerprofilen oprettes automatisk, når en låner første gang logger ind på websitet via Adgangsplatformen. Patron-brugerne skal være der, og der bliver automatisk ryddet op i dem. 

## Skit password for systembruger

Log ind som systembruger.

Klik på Admin ikonet i øverste højre hjørne og vælg Edit profile.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c20cd123-8f6f-4006-866d-166ccdcd687b" alt="Edit profile" caption="Edit profile" %}

Udfyld felterne med det nuværende password og det nye.
Hvis du ikke kan huske det nuværende password, kan du klikke på linket Reset your password. En vejledning bliver du sendt til din email.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/42efd3ec-175f-4a02-b99e-b0315e86b5da" alt="Skift adgangskode" caption="Skift adgangskode" %}

