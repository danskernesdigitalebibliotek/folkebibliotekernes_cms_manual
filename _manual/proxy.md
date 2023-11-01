---
title: "Fjernadgang med proxy"
category: "Konfiguration"
comment: "Copied from DDB CMS tutorial last updated 20/12-22"
---
## Baggrund og virkemåde ##
Formålet med fjernadgang er at give biblioteksbrugerne adgang hjemmefra til elektroniske ressourcer - databaser, e-tidsskrifter osv. - som bibliotekerne har købt adgang til.

Udbyderne af elektroniske ressourcer tilbyder som oftest kun adgang fra bestemte IP-adresser, f.eks. dem fra biblioternes fysiske adresser, men udbyderne kender ikke bibliotekets lånere, og det er her, fjernadgangsproxyen kommer ind i billedet. Den kan optræde som "mellemmand" mellem bibliotekslånere og udbyder, så udbyderne ser trafikken komme fra en bestemt IP-adresse, nemlig proxyens, mens proxyen sikrer at det kun bibliotekets brugere, typisk kommunens borgere, som har adgang. For at det kan fungere er det nødvendigt at omskrive links til de elektroniske ressourcer, så brugerne kommunikerer med proxyen i stedet for direkte med udbyderne.

## URL omskrivning ##

Et link, der uden fjernadgang ser således ud:
```
https://www.pressreader.com
```
Et link omskrevet med fjernadgang ser således ud:

```
https://bib123.bibbaser.dk/login?url=https://www.pressreader.com
```
Den del som er blevet tilføjet i starten af linket - `https://bib123.bibbaser.dk/login?` - er et proxy prefix. Det sikrer at man i stedet for at ramme PressReader direkte i stedet bliver sendt til proxyløsningen. Det trecifrede tal i proxy prefix'et er kommunenummeret - svarende til ciffer 2-4 i biblioteksnummeret - altså i dette tilfælde 123 fra det hypotetiske biblioteksnummer 712300

Idet man kontakter proxyen bliver det checket om man kommer fra en af bibliotekets egne IP-adresser. Gør man det, kommer man direkte til ressourcen, men sidder man f.eks. hjemme, skal man være logget ind (via adgangsplatformen). Er man ikke allerede logget ind bliver man bedt om det. Derefter bliver man ledt videre til e-ressourcen, men via proxyen, således at brugerens browser kommunikerer med proxyen, som så kommunikerer videre med udbyderen.

Proxyen omskriver automatisk alle links på websiderne fra udbyderen, så de peger tilbage på proxy'en i stedet for direkte på e-ressourcen. Det giver nogle lidt spøjse links som `https://www-pressreader-com.bib123.bibbaser.dk/catalog`. Lad endelig være med at bruge disse links direkte på jeres egen hjemmeside - brug altid proxy-prefix klistret foran den "oprindelige" url.

Den nationale proxyløsning er bygget på ezproxy. Den drives af DBC for DDF.


## Proxy indstillinger ##
Når proxyen er opsat korrekt vil links til eressourcer i søgeresultater automatisk blive omskrevet, så de peger på bibliotekets fjernadgangsproxy.

**Klik sti:** Indstillinger > Web-services > Opsæt proxy URL'er
\
**URL:** `admin/config/services/dpl-url-proxy`
{: .notice--primary}

|Feltnavn|Værdi|
|---|---|
|Præfiks til proxy-serverens URL|Udfyldes med `https://bib123.bibbaser.dk/login?` BEMÆRK! I skal udskifte `123` med jeres kommunenummer - svarende til ciffer 2-4 i biblioteksnummeret|
|Hostnames / Værtsnavne|Her skrives de hostnavne/værtsnavne, som skal genkendes og omskrives til at pege mod fjernadgangsproxyen. Værtsnavnene kan normalt findes i ERMS. Er der ikke nogen anden dokumentation på hvilket værtsnavn, man skal angive, kan man aflure navnet ved at holde musecursoren over "Online"-linket på en post fra den pågældende brøndkilde|
|Replacement|Visse kilder kræver yderligere opsætning, da url'erne skal omskrives yderligere, f.eks. med en biblioteksspecifik identifier/kode. Sektionen "Replacement" er en slags søg- og erstat-funktion. I "Regulært udtryk" beskrives hvad man leder efter. Bemærk at der ikke er tale om en almindelig tekst, men et regulært udtryk - se evt. http://en.wikipedia.org/wiki/Regular_expression . Det betyder blandt andet at man starter og slutter med skråstreg - "/", og at visse tegn skal forsynes med et en foranstillet backslash "\\"."Replacement" er en næsten normal tekststreng, idet man dog kan bruge $1, $2 osv. til at angive delstrenge som er blevet matchet (captured) i det regulære udtryk ovenfor. Lyder det for indviklet, så lev med at låne andres eksempler ;-)|

**TIP**:  Links på e-materiale siderne omskrives ikke automatisk. I skal huske at bruge URL'er med "proxy prefix", når I linker til eressourcer rundt omkring på sitet - ikke mindst e-materiale-siderne.
{: .notice--info}


