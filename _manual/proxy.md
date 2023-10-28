---
title: "Fjernadgang med proxy"
category: "Konfiguration"
---
## Baggrund og virkemåde ##
Formålet med fjernadgang er at give biblioteksbrugerne adgang hjemmefra til elektroniske ressourcer - databaser, e-tidsskrifter osv. - som bibliotekerne har købt adgang til.

Udbyderne af elektroniske ressourcer tilbyder som oftest kun adgang fra bestemte IP-adresser, f.eks. dem fra biblioternes fysiske adresser, men udbyderne kender ikke bibliotekets lånere, og det er her, fjernadgangsproxyen kommer ind i billedet. Den kan optræde som "mellemmand" mellem bibliotekslånere og udbyder, så udbyderne ser trafikken komme fra en bestemt IP-adresse, nemlig proxyens, mens proxyen sikrer at det kun bibliotekets brugere, typisk kommunens borgere, som har adgang. For at det kan fungere er det nødvendigt at omskrive links til de elektroniske ressourcer, så brugerne kommunikerer med proxyen i stedet for direkte med udbyderne.

Et link, der uden fjernadgang ser således ud:
```
https://www.pressreader.com
```
kan i stedet komme til at se således ud

```
https://bib123.bibbaser.dk/login?url=https://www.pressreader.com
```
Den del som er blevet tilføjet i starten af linket - `https://bib123.bibbaser.dk/login?` - er et proxy prefix. Det sikrer at man i stedet for at ramme PressReader direkte i stedet bliver sendt til proxyløsningen. Det trecifrede tal i proxy prefix'et er kommunenummeret - svarende til ciffer 2-4 i biblioteksnummeret - altså i dette tilfælde 123 fra det hypotetiske biblioteksnummer 712300

Idet man kontakter proxyen bliver det checket om man kommer fra en af bibliotekets egne IP-adresser. Gør man det, kommer man direkte til ressourcen, men sidder man f.eks. hjemme, skal man være logget ind (via adgangsplatformen). Er man ikke allerede logget ind bliver man bedt om det. Derefter bliver man ledt videre til e-ressourcen, men via proxyen, således at brugerens browser kommunikerer med proxyen, som så kommunikerer videre med udbyderen.

Proxyen omskriver automatisk alle links på websiderne fra udbyderen, så de peger tilbage på proxy'en i stedet for direkte på e-ressourcen. Det giver nogle lidt spøjse links som `https://www-pressreader-com.bib123.bibbaser.dk/catalog`. Lad endelig være med at bruge disse links direkte på jeres egen hjemmeside - brug altid proxy-prefix klistret foran den "oprindelige" url.

Den nationale proxyløsning er bygget på ezproxy. Den drives af DBC for DDF.


## Vejledning ##
Når proxyen er opsat korrekt vil links til eressourcer i søgeresultater automatisk blive omskrevet, så de peger på bibliotekets fjernadgangsproxy.

Bemærk! Links på e-materiale siderne omskrives ikke automatisk. I skal huske at bruge URL'er med "proxy prefix", når I linker til eressourcer rundt omkring på sitet - ikke mindst e-materiale-siderne.

Denne vejledning handler primært om opsætningen af "Proxy Settings" under "Indstillinger" i DDB CMS (Sti: /admin/config/ting/proxy). 
"Proxy Settings" benyttes i DDB CMS til at tilpasse url'er i brøndkilder, så biblioteksspecifikke oplysninger bliver indsat, og links kommer til at pege på bibliotekets fjernadgangsproxy.

