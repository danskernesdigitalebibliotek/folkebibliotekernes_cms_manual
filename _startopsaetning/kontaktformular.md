---
title: "Opgave 11: Ændr kontaktformularens konfiguration"
category: "Startopsætning"
weight: 11
---
Jeres kontaktformular `/kontakt` skal ændres, så det information der sendes til brugerne er korrekt og de rigtigte personer modtager henvendelserne fra brugerne.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/9ef4152e-6912-4bc9-8e07-7f8c9e33c24b" alt="Kontaktformularen" caption="Kontaktformularen" %}

## 1. Opret de korrekte email kategorier
I kontaktformularen kan brugerne vælge en kategori, som henvendelsen omhandler, og I kan tilknytte en email til de kategorier, så de sendes til de rette personer på biblioteket.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/226400d7-9974-4d0d-b7cc-d5b6917cce9a" alt="Email kategorier" caption="Email kategorier" %}

I topmenuen klik på **Struktur** eller åbn `https://mit-domænenavn.dk/admin/structure (udskift mit-domænenavn.dk)`

Tryk på **Taksonomi**

Tryk på **Vis ord** ud for Webform email kategories

Her kan I redigere, tilføje og slette kategorier. 

**Det er vigtigt at I retter emails på alle eksisterende kategorier, som I vil beholde** ellers modtager I ikke mails når brugerne vælger de kategorier.

For at gøre det, så trykker I på **Rediger** ud for den kategori, som skal have tilknyttet en email og retter emailen i feltet **Email** og tryk på **Gem**.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/7dab3d81-8cff-4abb-bdd9-32e5d9f7ffa8" alt="Ret email" caption="Ret email" %}

## 2. Ret de teksten i bekræftelsesbeskederne

### 2.1 Bekræftelsesbesked på hjemmesiden
Først skal I rette den besked, som brugerne modtager på hjemmesiden efter at have udfyldt en henvendelse i kontaktformularen.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/05ee1542-3091-49de-a3c9-f928401fb482" alt="Bekræftelsesbesked på hjemmesiden" caption="Bekræftelsesbesked på hjemmesiden" %}

I topmenuen klik på **Struktur** eller åbn `https://mit-domænenavn.dk/admin/structure (udskift mit-domænenavn.dk)`

Tryk på **Webformularer**

Tryk på **Byg** ud for "Kontaktformular"

Tryk på **Indstillinger** øverst

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/8af25966-532e-4b55-8dce-16134249ba0a" alt="Tryk på Indstillinger" caption="Tryk på Indstillinger" %}

Tryk på **Bekræftelse** 

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/9f9add0a-a7fe-4671-8809-dfa34111b7bb" alt="Tryk på Bekræftelse" caption="Tryk på Bekræftelse" %}

Ret teksten i feltet **Bekræftelse**ryk på **Gem**

Dette kunne være "Tak for din besked. Vi besvarer din mail indenfor X dage."
{: .notice--primary}

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/8ac9f35d-0d0a-42d8-a2e9-f4e823ea81cc" alt="Ret teksten" caption="Ret teksten" %}

Tryk på **Gem**

### 2.2 Bekræftelsesbesked i emails
Herefter skal I rette teksten til bekræftelses-emailen, som borgeren modtager.

Hvis I ikke har fulgt opgave **2.1 Bekræftelsesbesked på hjemmesiden** i denne, så skal I følge den opgave til og med "Tryk på **Indstillinger**" og så komme tilbage til denne opgave.

Tryk på **Emails / Handlers**

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/cdf40089-dd1d-4f29-8940-a2ca97798d0c" alt="Bekræftelses-email" caption="Bekræftelses-email" %}

Tryk på **Rediger** ud for den Email bekræftelse, som har ID'et email_confirmation 

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/15d50e3e-ec41-4c3f-8194-63968b509ce9" alt="Rediger email" caption="Rediger email" %}

Scroll ned til **Besked** og ret teksten

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/1479b81a-85a7-4ca5-99f6-809908528830" alt="Ret teksten" caption="Ret teksten" %}

I teksten er der variabler, som indsætter information baseret på det, som borgeren har indtastet i formularen. Fx indsætter [webform_submission:values:name] det navn, som brugeren indtaster i feltet Navn i kontaktformularen.

Variabler I kan bruge er fx
[webform_submission:values:name] er det som blev indtastet i Navn i formularen
[webform_submission:created] er tidspunktet som henvendelsen i kontaktformularen blev indsendt
[webform_submission:values:subject] er det som blev indtastet i Emne i formularen
[webform_submission:values:message] er det som blev indtastet i Besked i formularen
[webform_submission:values:email] er det som blev indtastet i Email i formularen
{: .notice--primary}

En email besked kunne fx være:\ \
Kære [webform_submission:values:name]\
Vi har modtaget din besked. Vi besvarer henvendelser indenfor X dage.\
Besked blev modtaget: [webform_submission:created]\
Din besked\
[webform_submission:values:subject\
[webform_submission:values:message]\
Med venlig hilsen\
Eksempel Bibliotekerne
{: .notice--primary}

Tryk på **Gem**
