---
title: "OpenID connect (Adgangsplatformen)"
click-path: "Indstillinger > Web-services > OpenID Connect"
category: "Konfiguration"
emneord: 
- "Adgangsplatformen"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn/admin/config/services/openid-connect`

## Om OpenID connect (Adgangsplatformen)
Adgangsplatformen sikrer et ensartet login-flow for brugerne på tværs af bibliotekstjenester. Brugeren sendes til en en selvstændig loginside. Efter login sendes brugeren retur igen.

Single Sign-On gør, at brugerne kan skifte mellem bibliotekstjenester uden at skulle logge ind flere gange. Er du f. eks. logget ind i Folkebibliotekernes CMS kan du bruge Filmstriben eller Ereolen uden at logge ind på ny.

Adgangsplatformen autoriserer også hjemmesiden til at udføre søgninger i FBI-API.

## Anbefalede indstillinger for OpenID Connect

|Feltnavn|Værdi|
|---|---|
|Enabled OpenID Connect clients|`Adgangsplatformen` (kun det)|
|Klient ID|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Client secret|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Token endpoint|`https://login.bib.dk/oauth/token/`|
|UserInfo endpoint|`https://login.bib.dk/userinfo/`|
|Logout endpoint|`https://login.bib.dk/logout`|
|Agency ID|Jeres biblioteksnummer (6 cifre - ingen DK foran)|

{% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2c2ae8ab-a365-49ca-afde-167ed05a612a" alt="Aktiver KUN Adgangsplatformen - ikke andet" caption="Aktiver KUN Adgangsplatformen - ikke andet" %} 
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3cf6e2ff-7993-4b5a-a924-754563244a0f" alt="De fleste felter er udfyldt korrekt. I skal selv udfylde Client ID, Client secret og Agency ID" caption="De fleste felter er udfyldt korrekt. I skal selv udfylde Client ID, Client secret og Agency ID" %} 