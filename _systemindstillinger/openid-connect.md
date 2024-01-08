---
title: "OpenID connect (Adgangsplatformen)"
category: "Web-services"
emneord: 
- "Adgangsplatformen"
---

Adgangsplatformen sikrer et ensartet login-flow for brugerne på tværs af bibliotekstjenester. Brugeren sendes til en en selvstændig loginside. Efter login sendes brugeren retur igen.

Single Sign-On gør, at brugerne kan skifte mellem bibliotekstjenester uden at skulle logge ind flere gange. Er du f. eks. logget ind i Folkebibliotekernes CMS kan du bruge Filmstriben eller Ereolen uden at logge ind på ny.

## Her finder du indstillinger for Open ID Connect 
I topmenuen klik på Indstillinger. \
Vælg dernæst Web-services > OpenID Connect

Eller åbn via direkte link (udskift mit-domænenavn.dk):

https://mit-domænenavn`/admin/config/services/openid-connect`
{: .notice--primary}

## Standardindstillinger for OpenID Connect

|Feltnavn|Værdi|
|---|---|
|Enabled OpenID Connect clients|`Adgangsplatformen` (kun det)|
|Klient ID|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Client secret|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Token endpoint|`https://login.bib.dk/oauth/token/`|
|UserInfo endpoint|`https://login.bib.dk/userinfo/`|
|Logout endpoint|`https://login.bib.dk/logout`|
|Agency ID|Jeres biblioteksnummer (6 cifre - ingen DK foran)|

{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2c2ae8ab-a365-49ca-afde-167ed05a612a" alt="Aktiver Adgangsplatformen - ikke andet" caption="Aktiver Adgangsplatformen - ikke andet" %} 
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/552b7a3c-5ced-437c-9dbd-3f35e4ba3aca" alt="Client ID og secret udleveres ved henvendelse til DBC" caption="Client ID og secret udleveres ved henvendelse til DBC" %} 