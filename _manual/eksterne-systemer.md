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
## Adgangsplatformen (OpenID connect) ##
## Publizon ##
## RSS Feed til Biblioteket App'en ##
## Mapp Intelligence ##
Gennem Det Digitale Folkebibliotek har bibliotekerne adgang til web- og appstatistikløsningen MAPP, som giver indblik i brugen af bibliotekernes hjemmesider og appen Biblioteket. [Læs mere om MAPP og find link til MAPP-login](https://detdigitalefolkebibliotek.dk/section/i-brug-paa-biblioteket/bibliotekernes-web-og-appstatistik)

For at data fra hjemmesiden sendes til Mapp skal to felter være rigtig udfyldt. Sitet fødes med de korrekte værdier, men det er en god ide at kontrollere om opsætningen er korrekt alligevel.

**Sti/URL**
\
Klik-sti: Indstillinger > System > Mapp Intelligence indstillinger 
\
URL: `admin/config/system/dpl-mapp`
\
\
**Anbefalede feltværdier**
\
Domæne: `responder.wt-safetag.com`
\
ID: `476651662471322`
{: .notice--primary}

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/51e0fc7c-edf7-4356-916d-ed2678ca50c9" alt="MAPP indstillinger" caption="MAPP indstillinger" %} 

Det er hensigtsmæssigt at konfigurere MAPP-indstillingerne før hjemmesiden sættes i drift, så det er muligt at se brugerstatistik fra første dag hjemmesiden tages i brug.
