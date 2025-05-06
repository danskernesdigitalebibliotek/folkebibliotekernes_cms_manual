---
title:  "Release Notes 2025.18.1"
category: "Release Notes"
weight: 339
---
## 2025.18.1 - 06-05-2025
Fejlen (https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1512) med at kontaktoplysninger slettes ved ændring i fraværsperiode rettes.

**Redaktørbiblioteker**: Produktionssites opgraderes til 2025.18.1
**Webmasterbiblioteker**: Produktionssites opgraderes til 2025.17.2. Modultestsites opgraderes til 2025.18.1 (disse bliver ikke nulstillet).

## 2025.18.0 - 01-05-2025
### Publicer og send til Delingstjenesten

**Redaktørbiblioteker**: Produktionssites opgraderes til 2025.18.0
**Webmasterbiblioteker**: Produktionssites opgraderes til 2025.17.1. Modultestsites opgraderes til 2025.18.0.

### Nye features

#### Artikler kan sendes fra CMS til Delingstjenesten
I indholdstypen **Artikel** kan du nu sætte flueben i **Publicer og send til Delingstjenesten**. Artiklen overføres én gang – præcis som i BPI.

På Delingstjenesten kan artikler indsendt fra bibliotekerne fremsøges sådan: 
1. Tryk på **Alt indhold** i hovedmenu
2. I søgefunktion sæt dropdown-filteret **Edited by BNR** til værdien **Uncategorized**.
 
Følgende paragraphs understøttes i indholdstypen Artikel ved send:
-	Brødtekst 
-	Link(s) 
-	Billede(r) 
-	Fil(er) 
-	Video 
-	Accordion 
-	Enkel linkliste 
-	Material grid link - automatisk
-	Materialekomponent – manuel 
-	Recommendation 
-	Hero 
-	Banner 

#### Forfatterfeltet - afsender på artiklen
- Ved hent af artikel, vil forfatterfeltet automatisk bliver udfyldt med teksten “Biblioteket”.
- Ved indsendelse af artikel, vil forfatterfeltet være udfyldt med dit brugernavn i CMS. Ønsker du et andet navn, sæt flueben i "Override the author" og skriv i feltet "Override author". 
- På søgesiden vises biblioteksnavnet altid som afsender.


### Fejlrettelser
**Delingstjenesten**:\
Felterne Navn og Billedtekst på billeder overføres nu korrekt, både når:
-	artikler hentes fra Delingstjenesten til CMS
-	artikler sendes fra CMS til Delingstjenesten
  
Denne rettelse sikrer, at billedtitler og tekster til brug for fotokreditering og info om copyright altid følger med artikler uden manuelle efterrettelser.

**Arrangementsfeed**: Biblioteket App fejler ikke mere, hvis det indeholder et arrangement oprettet af en bruger, der efterfølgende er blevet slettet. 

