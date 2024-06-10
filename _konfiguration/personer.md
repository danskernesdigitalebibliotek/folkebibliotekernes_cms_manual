---
title: "Redaktionelle brugere"
click-path: "Redaktionelle brugere"
category: "Konfiguration"
emneord: 
- "Brugere og roller"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/people`

Via menupunktet **Reaktionelle brugere** kan du:
- Oprette logins til dine kolleger, så de kan arbejde med hjemmesidens indhold
- Skifte password for dine kolleger
- Oprette adgang til eksterne systemer som f. eks. Place2book 

## Opret ny redaktionel bruger

Log på med en bruger der har rollen **administrator** eller **lokal administrator**. Ellers har du ikke nok rettigheder, til at kunne oprette brugere.

Klik på knappen **Tilføj bruger** i øverste højre hjørne.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/e287f512-9efb-4687-972b-cca5db8dc94e" alt="Klik på knappen Tilføj bruger" caption="Klik på knappen Tilføj bruger" %}

Udfyld følgende:

+ Forfatternavn - Brugerens synlige navn. Det vises i forbindelse med indhold, som brugeren har skrevet
+ E-mail-adresse -  Brugerens email.
+ Brugernavn - Brugerens interne brugernavn. Mange vælger deres initialer. (er kun synligt i kontrolpanelet).
+ Adgangskode - Brugerens adgangskode.

#### Status:
Er automatisk sat til **Aktiv**. Hvis brugeren skal blokeres vælges Blokeret.

#### Roller:
Vælg brugerens rolle. For de fleste almindelige redaktører vil rollen **Redaktør** være tilstrækkelig. Redaktør kan oprette indhold, men har ikke adgang til at ændre indstillinger på siden.
{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/e3b2a3d5-0cd0-46ee-a096-83d1bc7b8df0" alt="Brugerroller" caption="Brugerroller" %}

[Læs mere om de tilgængelige brugerroller](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#roller)

#### Påmind bruger om ny konto:
Aktiver denne, hvis der skal sendes en mail med login-oplysninger til brugeren. I mailen er et link til hjemmesiden, hvor brugeren bliver bedt om at skifte sin adgangskode. (Linket er svært at få øje på)

#### Sitets sprog:
Vælg mellem dansk og engelsk sprog for den nye systembrugers kontrolpanel. Det er vigtigt at sætte sproget til dansk. Hele manualen er skrevet ud fra den danske oversættelse.

#### Opret konto:
Afslut opretningen ved at klikke på **Opret konto**

## Roller

Når du opretter en ny redaktionel bruger, skal han/hun tildeles en rolle. 

Som udgangspunkt skal jeres brugere ikke tildeles flere rettigheder, end dem der er nødvendige, for at de kan løse deres arbejdsopgaver.
{: .notice}

**Redaktørbiblioteker** kan oprette tre typer brugere:

- **Formidler (mediator)** er til brugere som ofte laver det dynamiske formidlingsindhold på hjemmesiden. Har adgang til at oprette og redigere arrangementer, artikler, sider og kampagner i /admin/content. 

- **Redaktør (editor)** er til brugere som udover formidlingsopgaver også skal stå for det faste indhold (fx åbningstider) og opbygning af sidens struktur. De kan have ansvaret for at koordinere og styre formidlernes arbejde. Har adgang til det samme som formidler plus alle indholdstyper i /admin/content samt taksonomi og menuer i /admin/structure.

- **Lokal administrator (local administrator)** er til brugere som skal indstille hjemmesiden ift. indstillinger, udseende, integrationer, overordnet oplysninger, biblioteksbrug etc. Har adgang til det samme som redaktør plus sidens konfigurationsmuligheder i /admin/config, oprettelse af brugere i /admin/people og ændring af sidens udseende i /admin/appearance.

**Webmasterbiblioteker** har en ekstra brugertype:
- **Administrator** kan ændre siden udover CMS'ets standardindstillinger fx ved at aktivere og deaktivere moduler. Har adgang til alt i CMS'et.

**Patron** er lånerne. Patron-brugerprofilen oprettes automatisk, når en låner første gang logger ind på websitet via Adgangsplatformen. Patron-brugerne skal være der, og der bliver automatisk ryddet op i dem. 

## Glemt password funktion
Er du redaktionel bruger og har glemt dit password er der en **Glemt adgangskode** funktion, der nulstiller dit password.
1. Gå til `https://mit-domænenavn.dk/user/login`\
(udskift mit-domænenavn.dk)
2. Klik på **Glemt din adgangskode?** og følg guiden.
   
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f5bcc166-db83-44b5-9a0c-6d59e3c8be6a" alt="Nulstil din adgangskode" caption="Nulstil din adgangskode" %}

## Skift password for redaktionel bruger

Er der en redaktionel

Klik på Admin ikonet i øverste højre hjørne og vælg Edit profile.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/c20cd123-8f6f-4006-866d-166ccdcd687b" alt="Edit profile" caption="Edit profile" %}

Udfyld felterne med det nuværende password og det nye.
Hvis du ikke kan huske det nuværende password, kan du klikke på linket Reset your password. En vejledning bliver du sendt til din email.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/42efd3ec-175f-4a02-b99e-b0315e86b5da" alt="Skift adgangskode" caption="Skift adgangskode" %}

