---
title: "Opsæt proxy URL'er"
click-path: "Indstillinger > Biblioteksindstillinger > Proxyindstillinger"
category: "Konfiguration"
---

I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn/admin/config/services/dpl-url-proxy`

## Hvorfor proxy URL'er?
Søgefeltet på hjemmesiden kan vise resultater fra elektroniske ressourcer som biblioteket abonnerer på. Hvilke kilder der skal være søgbare, beslutter I selv via VIP søgeprofilen.

Har I valgt at inkludere kilder som Gale eller Ebook Central er det vigtigt at registere proxy indstillinger for kilden. Gør I ikke det, vil links fra søgeresultatet til kilden ikke fungere. I hvert fald ikke for borgere der sidder på deres egen internetforbindelse og ikke er på biblioteket.

Hvis I indsætter link til elektroniske ressourcer på sider eller andre steder på hjemmesiden er det vigtigt at linket peger på proxy-URL'en. Ellers vil borgere der bruger hjemmesiden via deres egen internetforbindelse ikke kunne få adgang.

## Forstå proxy URL'er

Formålet med fjernadgang er at give biblioteksbrugerne adgang hjemmefra til elektroniske ressourcer - databaser, e-tidsskrifter osv. - som bibliotekerne har købt adgang til.

Udbyderne af elektroniske ressourcer tilbyder som regel kun adgang fra bestemte IP-adresser, f.eks. dem på biblioternes fysiske adresser. Men udbyderne kender ikke bibliotekets lånere og deres IP-adresser, og det er her at fjernadgangsproxyen kommer ind i billedet. Proxyen kan optræde som "mellemmand" mellem bibliotekslånere og udbyder. 

Proxyen får det til at se ud som om at al trafikken fra biblioteksbrugerne kommer fra én bestemt IP-adresse, nemlig proxyens. Den sikrer også at det kun er bibliotekets brugere, typisk kommunens borgere, som har adgang. For at det kan fungere er det nødvendigt at omskrive links til de elektroniske ressourcer, så brugerne kommunikerer med proxyen i stedet for direkte med udbyderne.

## URL omskrivning ##

Et link uden fjernadgang ser sådan ud:
```
https://www.pressreader.com
```
Et link omskrevet med fjernadgang ser sådan ud:

```
https://bib123.bibbaser.dk/login?url=https://www.pressreader.com
```
Den del som er blevet tilføjet i starten af linket - `https://bib123.bibbaser.dk/login?url=` - er et **proxy prefix**. Det sikrer at man i stedet for at ramme PressReader direkte bliver sendt til proxyløsningen. Det trecifrede tal i proxy prefix'et er kommunenummeret - svarende til ciffer 2-4 i biblioteksnummeret - altså i dette tilfælde 123 fra det hypotetiske biblioteksnummer 712300

Idet man kontakter proxyen bliver det checket om man kommer fra en af bibliotekets egne IP-adresser. Gør man det, kommer man direkte til ressourcen, men sidder man f.eks. hjemme, skal man være logget ind (via adgangsplatformen). Er man ikke allerede logget ind bliver man bedt om det. Derefter bliver man ledt videre til e-ressourcen, men via proxyen, således at brugerens browser kommunikerer med proxyen, som så kommunikerer videre med udbyderen.

Proxyen omskriver automatisk alle links på udbyderens website, så de peger tilbage på proxy'en i stedet for direkte på e-ressourcen. Det giver nogle lidt spøjse links som `https://www-pressreader-com.bib123.bibbaser.dk/catalog`. Lad endelig være med at bruge disse links direkte på jeres egen hjemmeside - brug altid proxy-prefix klistret foran den "oprindelige" url.

**TIP**:  Links på e-materiale siderne omskrives ikke automatisk. I skal huske at bruge URL'er med "proxy prefix", når I linker til eressourcer rundt omkring på sitet - ikke mindst e-materiale-siderne.
{: .notice--info}

Den nationale proxyløsning er bygget på ezproxy. Den drives af DBC for DDF.

## Proxy indstillinger ##
Når proxyen er opsat korrekt vil links til eressourcer i søgeresultater automatisk blive omskrevet.

### Guide til at oprette proxy indstillinger

|Feltnavn|Værdi|
|---|---|
|Præfiks til proxy-serverens URL|Udfyldes med `https://bib123.bibbaser.dk/login?url=` BEMÆRK! I skal udskifte `123` med jeres kommunenummer - svarende til ciffer 2-4 i biblioteksnummeret|
|Hostnames / Værtsnavne|Her skrives de hostnavne/værtsnavne, som skal genkendes og omskrives til at pege mod fjernadgangsproxyen. Er du i tvivl om hostname/værtsnavn kan du finde oplysningerne på DBCs oversigt [Kilder i databrønden](https://danbib.dk/kilder-databroenden){:target="_blank"}|
|Replacement|Visse kilder kræver yderligere opsætning, da url'erne skal omskrives med f.eks. en biblioteksspecifik identifier/kode. De kilder der kræver replacement er beskrevet herunder.|

## Elektroniske ressourcer der kræver særlig opsætning ##
### Proquest Ebook Central (Ebrary) ###
Proquest Ebook Central - før Ebrary - kræver særlig opsætning, da der i url'en indgår et biblioteksspecifikt ID.
Biblioteker, som alene skal have adgang til "Ebook Central Plus" kan nøjes med at udfylde "Værtsnavn":

**Værtsnavn:** `ebookcentral.proquest.com`
\
**Regulært udtryk:** `/\[PROVIDERSLIBRARYID\]/`
\
**Replacement:** `myproquestebooksid`

Teksten "myproquestebooksid" i ovenstående eksempel erstattes med bibliotekets ID.

En formentlig ukomplet liste over bibliotekernes ID'er findes nedenfor:

- arhus-ebooks
- fredrikshavn-ebooks
- vordingborg-ebooks
- aabenraa-ebooks
- billundbib-ebooks
- esbjerg-ebooks
- fmbib-ebooks
- faxe-ebooks
- fredensborgbibliotekerne-ebooks
- fredericiabib-ebooks
- frederikssunddk-ebooks
- gladsaxebib-ebooks
- glostrup-ebooks
- halsnaes-ebooks
- horsholm-ebooks
- herlev-ebooks
- herning-ebooks
- horsens-ebooks
- koegebib-ebooks
- kolding-ebooks
- lollandbib-ebooks
- lyngbybib-ebooks
- randers-ebooks
- roskilde-ebooks
- rudersdal-ebooks
- silkeborg-ebooks
- slagelsedk-ebooks
- svendborgbib-ebooks
- taarnby-ebooks
- tbib-ebooks
- viborg-ebooks

### Gale ###
Gale kræver særlig opsætning, da der i url'en indgår en parameter med et biblioteksspecifikt ID - et Gale ID:

**Værtsnavn:** link.galegroup.com
\
**Regulært udtryk:** `/\[PROVIDERSLIBRARYID\]/`
\
**Replacement:** `mygaleid`

**Værtsnavn:** `link.gale.com`
\
**Regulært udtryk:** `/\[PROVIDERSLIBRARYID\]/`
\
**Replacement:** `mygaleid`

(Teksten "mygaleid" i ovenstående eksempel erstattes med bibliotekets Gale ID. Find det i ERMS)

### Mango languages ###
Mango languages skal håndteres på samme måde som Gale. Men bibliotekets identifier kan godt hedde noget andet end for Gale. Se efter den konkrete værdi i ERMS

## Hvordan virker replacement? (For nørderne)
Sektionen "Replacement" er en slags søg- og erstat-funktion. I "Regulært udtryk" beskrives hvad man leder efter. Bemærk at der ikke er tale om en almindelig tekst, men et regulært udtryk - se evt. http://en.wikipedia.org/wiki/Regular_expression . Det betyder blandt andet at man starter og slutter med skråstreg - "/", og at visse tegn skal forsynes med et en foranstillet backslash "\\"."Replacement" er en næsten normal tekststreng, idet man dog kan bruge $1, $2 osv. til at angive delstrenge som er blevet matchet (captured) i det regulære udtryk ovenfor. Lyder det for indviklet, så lev med at låne andres eksempler ;-)


