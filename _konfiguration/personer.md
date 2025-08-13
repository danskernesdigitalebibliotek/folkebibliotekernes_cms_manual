---
title: "Redaktionelle brugere"
click-path: "Redaktionelle brugere"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/people`

Via menupunktet **Reaktionelle brugere** kan du:
- [Oprette logins til dine kolleger, så de kan arbejde med hjemmesidens indhold](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#opret-ny-redaktionel-bruger)
- [Glemt password funktion](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#glemt-password-funktion)
- [Skifte dit eget password](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#skift-dit-eget-password)
- [Skifte password for en kollega](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#skift-password-for-redaktionel-bruger)
- [Oprette adgang til eksterne systemer som f. eks. Place2book](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#opret-bruger-til-ekstern-adgang-api-bruger)

## Opret ny redaktionel bruger
Kolleger, der skal hjælpe dig med at opdatere hjemmesiden, skal du oprettes som redaktionelle brugere.

Log på med en bruger der har rollen **administrator** eller **lokal administrator**. Ellers har du ikke nok rettigheder, til at kunne oprette brugere.

Klik på knappen **Tilføj bruger** i øverste højre hjørne.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/e287f512-9efb-4687-972b-cca5db8dc94e" alt="Klik på knappen Tilføj bruger" caption="Klik på knappen Tilføj bruger" %}

Udfyld følgende:

+ **Forfatternavn** - Brugerens synlige navn. Det vises i forbindelse med indhold, som brugeren har skrevet
+ **E-mail-adresse** -  Brugerens email.
+ **Brugernavn** - Brugerens interne brugernavn. Mange vælger deres initialer. (er kun synligt i kontrolpanelet).
+ **Adgangskode** - Brugerens adgangskode.

#### Status:
Er automatisk sat til **Aktiv**. Hvis brugeren skal blokeres vælges Blokeret.

#### Roller:
Vælg brugerens rolle. For de fleste almindelige redaktører vil rollen **Redaktør** være tilstrækkelig. Redaktør kan oprette indhold, men har ikke adgang til at ændre indstillinger på siden.
{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/e3b2a3d5-0cd0-46ee-a096-83d1bc7b8df0" alt="Brugerroller" caption="Brugerroller" %}

Man skal kun have én rolle. 
- Får man tildelt **Lokal Administrator**, har man også rettighederne som **Redaktør** og **Formidler**.
- Er man **Redaktør** har man også rettighederne der hører til **Formidler**.

[Læs mere om de tilgængelige brugerroller](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#roller-1)

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

Man kan også oprette brugere af typen **eksternt system**. Den type brugere oprettes på vegne af eksterne partnere, der skal hente artikler eller arrangementer fra jeres CMS via APIet. Det kan f. eks. være Place2book eller et storskærmssystem. 

**Patron** er lånerne. Patron-brugerprofilen oprettes automatisk, når en låner første gang logger ind på websitet via Adgangsplatformen. Patron-brugerne skal være der, og der bliver automatisk ryddet op i dem. 

## Spærret brugere
Der er to måder at redaktionelle brugere bliver spærret:
- IP spærring - 50 fejlforsøg på 1 time af én eller flere brugere på samme IP adresse. Alle brugere på samme IP bliver spærret. Efter 1 time, kan man igen lave login forsøg fra samme IP.
- Bruger spærring - én bruger laver 5 fejlforsøg på 6 timer. Efter 6 timer, kan man igen lave login forsøg med samme brugernavn.

Vi anbefaler at man ændrer sin adgangskode ved 'glemt password funktionen' (se hvordan du gør længere nede på denne side), hvis man er ved at nå en spærring med antal fejlforsøg.

Grunden til overstående er at man vil undgå spam bots og DDoS angreb.  

### Det kan I gøre når der er en spærring
Det bedste man kan gøre er at vente på at spærringen ophæves. Brugere som er 'Administrator eller' 'Lokal administrator' kan hjælpe kollegaer ved at dobbelttjekke om det er et korrekt brugernavn/email som bliver brugt til at logge ind med. Se afsnittene der omhandler adgangskoder herunder. 

Man kan ikke som kollega-admin “lukke op” for en spærret bruger. Der kan ikke lukkes op for spærret brugere ved at kontakte Det Digitale Folkebibliotek. Eneste måde at hæve spærringen fra centralt side, er at tømme det DB table som holder styr på logging af fejlslagne loginforsøg. Det er besværligt, omstændigt og resursekrævende. Så det kommer kun til at ske i ekstraordinære tilfælde, og vi anbefaler at vente til spærringen er hævet.

## Glemt password funktion
Er du redaktionel bruger og har glemt dit password er der en **Glemt adgangskode** funktion, der nulstiller dit password.
1. Gå til `https://mit-domænenavn.dk/user/login`\
(udskift mit-domænenavn.dk)
2. Klik på **Glemt din adgangskode?** og følg guiden.
   
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f5bcc166-db83-44b5-9a0c-6d59e3c8be6a" alt="Nulstil din adgangskode" caption="Nulstil din adgangskode" %}

## Skift dit eget password
Kender du dit password og vil du gerne skifte det kan det ordnes via din brugerprofil.
1. Gå til `https://mit-domænenavn.dk/user/login` (udskift mit-domænenavn.dk) og log ind
2. Klik på **dit brugernavn** i øverste højre hjørne og vælg **Rediger profil**
   {% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/8238fe8f-9f52-45a1-a9a1-4838779ccf45" alt="Skift din egen adgangskode" caption="Skift din egen adgangskode" %}
3. I din brugerprofil kan du angive en ny adgangskode.


## Skift password for redaktionel bruger
Skal en kollega have nyt password, kan du skifte det for vedkommende.
1. Log på med en bruger der har rollen **administrator** eller **lokal administrator**. Ellers har du ikke nok rettigheder, til at kunne ændre en anden brugers password.
2. Fremsøg din kollega på **navn** eller **email**.
3. Tryk **Rediger** til højre for deres navn
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/364d0455-8802-4ae7-9a28-dc8f6daf5345" alt="Fremsøg redaktionel bruger på navn" caption="Fremsøg redaktionel bruger på navn" %}
4. Udfyld ny adgangskode for din kollega.
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/a70ce1c9-13ff-4ba6-aec6-e8186c382296" alt="Angiv ny adgangskode for redaktionel bruger" caption="Angiv ny adgangskode for redaktionel bruger" %}
5. Tryk **Gem** nederst på siden.

## Opret bruger til ekstern adgang (API bruger)
Eksterne samarbejdspartnere har mulighed for at lave integrationer til Folkebibliotekernes CMS via et API.
API-kald til jeres CMS skal ske via en særlig bruger, som I skal oprette og udlevere til jeres eksterne samarbejdspartner.
Denne type bruger skal have rollen **Eksternt system**.

Vi anbefaler at I opretter en bruger pr. integration. Har I f. eks. integration til både Place2book og et storskærmssystem, så skal I oprette en bruger til hver. Derved holdes trafikken adskilt.

Læs mere om Place2book integration.



