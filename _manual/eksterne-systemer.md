---
title: "Eksterne systemer"
category: "Konfiguration"
topic: 
- "Webstatistik"
- "FBS"
- "Publizon"
- "Adgangsplatformen"
---
Folkebibliotekernes CMS har brug for at kommunikere med flere eksterne systemer. Forbindelsen til dem skal være sat korrekt op. 
## FBS ##
Opsæt forbindelse til bibliotekssystemet.

**Klik sti:** Indstillinger > Web-services > FBS indstillinger
\
**URL:** `admin/config/services/fbs`
{: .notice--primary}

|Feltnavn|Værdi|
|FBS Service URL|`https://fbs-openplatform.dbc.dk`|

## Adgangsplatformen (OpenID connect) ##
Adgangsplatformen sikrer et ensartet login-flow for brugerne på tværs af bibliotekstjenester. Brugeren sendes til en en selvstændig loginside. Efter login sendes brugeren retur igen.

Single Sign-On gør, at brugerne kan skifte mellem bibliotekstjenester uden at skulle logge ind flere gange. Er du f. eks. logget ind i Folkebibliotekernes CMS kan du bruge Filmstriben eller Ereolen uden at logge ind på ny.

**Klik sti:** Indstillinger > Web-services > OpenID Connect
\
**URL:** `admin/config/services/openid-connect`
{: .notice--primary}

|Feltnavn|Værdi|
|Enabled OpenID Connect clients|`Adgangsplatformen` (kun det)|
|Klient ID|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Client secret|Oplyses ved henvendelse til DBC via https://kundeservice.dbc.dk/|
|Token endpoint|`https://login.bib.dk/oauth/token/`|
|UserInfo endpoint|`https://login.bib.dk/userinfo/`|
|Logout endpoint|`https://login.bib.dk/logout`|
|Agency ID|Jeres biblioteksnummer (6 cifre - ingen DK foran)|


## Publizon ##
## RSS Feed til Biblioteket App'en ##
## Mapp Intelligence ##
Gennem Det Digitale Folkebibliotek har bibliotekerne adgang til web- og appstatistikløsningen MAPP, som giver indblik i brugen af bibliotekernes hjemmesider og appen Biblioteket. [Læs mere om MAPP og find link til MAPP-login](https://detdigitalefolkebibliotek.dk/section/i-brug-paa-biblioteket/bibliotekernes-web-og-appstatistik)

For at data fra hjemmesiden sendes til Mapp skal to felter være rigtig udfyldt. Sitet fødes med de korrekte værdier, men det er en god ide at kontrollere om opsætningen er korrekt alligevel.


**Klik sti:** Indstillinger > System > Mapp Intelligence indstillinger 
\
**URL:** `admin/config/system/dpl-mapp`
{: .notice--primary}

|Feltnavn|Værdi|
|Domæne|`responder.wt-safetag.com`|
|ID|`476651662471322`|

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/51e0fc7c-edf7-4356-916d-ed2678ca50c9" alt="MAPP indstillinger" caption="MAPP indstillinger" %} 

Det er hensigtsmæssigt at konfigurere MAPP-indstillingerne før hjemmesiden sættes i drift, så det er muligt at se brugerstatistik fra første dag hjemmesiden tages i brug.
