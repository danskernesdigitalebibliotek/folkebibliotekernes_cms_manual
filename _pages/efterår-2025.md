---
permalink: /overblik/udviklingsoensker/efteraar-2025
title:  "Udviklingsønsker efterår 2025"
sidebar: true
nav: "overblik"
---

Siden webinaret den 20. maj har 76 bibliotekskommuner prioriteret mellem de 20 emneområder, som udviklingsønskerne er inddelt i. Vi vil gerne benytte chancen for at takke jer for at indsende jeres prioriteringer samt at berige de sager, som ligger inden for emneområderne. Det er en kæmpe hjælp for arbejdet med udviklingen af hjemmesiderne. 

Resultatet er ret tydeligt hvor emneområdet Avanceret søgning samt Arrangementer har fået flest stemmer. 

{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/c23e8d2c-f355-4e56-a8f1-52fa56cd18b4" alt="Prioriteret liste" caption="Prioriteret liste" %}

Sammen med Reload har vi nu estimeret de enkelte sager, og vores forventning er, at vi kan nå emneområderne 1. Avanceret søgning, 2. Arrangementer, 3. Søgeresultatsiden og værkvisningssiden og 4. Lånerstatus og brugerprofil i efteråret 2025. 

{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/277b0589-fcec-4eb2-a256-4de4534cdfc5" alt="Tidsplan" caption="Tidsplan" %}

Ønskerne i et emneområde vil komme ud løbende i de releases indenfor deres releaseperiode.  

Perioderne i roadmappet illustrerer, hvordan vi forventer, at udviklingen kommer til at foregå. Men det er vigtigt at pointere at dette roadmap ikke er statisk. 

Da vi ikke har releases i ugerne 28-31, så vil de første uger i august sandsynligvis gå med sager fra supporten i sommerferien. 

Som vi nævnte på webinaret vil det ikke være muligt at nå alle sager inden for et emneområde, men ud fra jeres kommentarer i sagerne og dialog med sagsindmelderne vil vi løbende vurdere de enkelte sager. Der vil være nogle sager, som vi ikke kan gå videre med pga. størrelsen af opgaven fx at det er for teknisk kompleks eller af UX/designmæssige årsager.  

Selvom Avanceret søgning er det højest prioriterede emneområde vil selve udviklingen starte med emneområderne Arrangementer og Søgeresultatsiden og værkvisningssiden, da Avanceret søgning kræver et større analysearbejde.  Vi kan gå i gang med to forskellige emneområder på samme tid, da de to emneområder er lavet i to forskellige teknologier, og derfor kan forskellige udviklere arbejde på de to samtidigt. 

## Avanceret søgning 

### Beskrivelse
Den nuværende implementering af avanceret søgning består af to grænseflader: Feltsøgning og CQL-søgning. Dette emneområde angår udviklingsønsker i begge.

### Fremgangsmåde
Som sagt så vil vi starte med at analysere, hvad den rigtige løsning skal indeholde. Til den proces vil vi gerne inddrage nogle biblioteker. Vi prioriterer inddragelse af de biblioteker, som har indmeldt sager indenfor dette emneområde. Vi leder efter 1. input til hvor avanceret søgning ikke virker og 2. feedback på en potentiel løsning. 

Fordi det er en analyseopgave, får vi højest sandsynligt ikke udviklet alt i denne omgang, da vi ikke kender omfanget før analysen er færdig. 

Flere har udtrykt ønske om at vi læner os meget op ad Bibliotek.dk’s avancerede søgning, men DBC har fundet flere ting, som de gerne vil rette i deres løsning. Derfor kan vi ikke sigte efter en tæt kopi af deres løsning. I stedet vil vi se, hvad der fungerer i Bibliotek.dk og lytte til deres erfaringer.  

Odense Bibliotekerne (webmasterbibliotek) har også implementeret [en avanceret søgning på deres side](https://www.odensebib.dk/advanced-search ){:target="_blank"}, som er et godt eksempel til inspiration. 

### Kom med input
Hvis du har inputs til avanceret søgning, så meld det meget gerne ind i [denne sag om avanceret søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-952){:target="_blank"}. I må gerne beskrive helt præcist, hvad der ikke fungerer som forventet og for hvilke brugere det ikke virker samt hvad der skal til for løsningen lever op til brugernes forventninger. 

### Sager
Opgavernes størrelse er ikke estimeret, da de indgår i et større analysearbejde.

[CMS-952: Forbedring og udbygning af avanceret søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-952){:target="_blank"}  
[CMS-960: Ikon for avanceret søgning skal ændres](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-960){:target="_blank"}  
[CMS-965: Mulighed for sortering bl.a. på nyeste først ifm Avanceret Søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-965){:target="_blank"}  
[CMS-1011: Avanceret søgning – forslag til at forbedre brugervenlighed samt søgeresultater](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1011){:target="_blank"}  
[CMS-1475: Målgruppe i avanceret søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1475){:target="_blank"}  
[CMS-1482: Avanceret søgning som bibliotek.dk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1482){:target="_blank"}  
[CMS-1483: Ønske om flere søgbare felter via avanceret søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1483){:target="_blank"}  
[CMS-1486: Besked om syntaksfejl i Complex Search](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1486){:target="_blank"}  
[CMS-1487: Filtreringsindekser ”Department” og ”Branch” i avanceret søgning](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1487){:target="_blank"}

## Arrangementer
### Beskrivelse
Dette emneområder indeholder både ønsker til arrangementsoversigten og arrange-mentssiden. Bemærk: Området dækker ikke paragrafer som eventlist manual og automatic eller billetintegration.

### Fremgangsmåde
Langt de fleste sager i dette emneområde er koncentreret om arrangementsoversigten, og det vil derfor give mening at se på sagerne i en samlet helhed for at sikre en forbedret visning af listen. 

### Sager
Disse er opdelt i størrelsen af opgaven. Der bruges en t-shirt størrelse. Det kan ikke sammenlignes med t-shirt størrelserne på emneområdet. Det er for at indikere at vi ikke kan lave mange større opgaver indenfor dette emneområde.

#### XL-opgaver
[CMS-1000: Arrangementer - Mulighed for at klone](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1000){:target="_blank"}  
[CMS-945: Søgning på arrangementer efter dato](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-945){:target="_blank"}  
[CMS-1251: Billetknap i arrangementsliste](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1251){:target="_blank"}  
[CMS-1007: Arrangementer - Arrangementsvisning på mobil](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1007){:target="_blank"}  
[CMS-1033: Arrangementsoversigt - Adskillelse af måneder](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1033){:target="_blank"}  

#### L-opgaver
[CMS-938: Status på arrangementer](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-938){:target="_blank"}  

#### M-opgaver
[CMS-1342: Manglende indhold ved rettelse af instanser i seriearrangementer](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1342){:target="_blank"} 
[CMS-1032: Arrangementsoversigt - Væk med "Vis flere"](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1032){:target="_blank"}  
[CMS-1006: Arrangementer - Arrangementsoversigt på mobil](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1006){:target="_blank"}  
[CMS-1044: Arrangementer - når det ikke foregår på bibliotek](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1044){:target="_blank"}

#### S-opgaver
[CMS-1005: Mulighed for at oprette arrangementer uden klokkeslæt](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1005){:target="_blank"}  
[CMS-1026: Arrangementer - Mulighed for at fravælge at det vises i div. automatiske oversigter](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1026){:target="_blank"}  

#### XS-opgaver
[CMS-1086: Afholdelsesbibliotek på instanser i stakvisning af enkeltstående arrangementer med flere datoer](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1086){:target="_blank"}  

#### Andet
[CMS-1357: Opdeling af arrangementer og udstillinger/længerevarende forløb](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1357){:target="_blank"} - skal defineres før den kan estimeres, læs mere i sagen. 

[CMS-1471: Arrangementsvisning layout](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1471){:target="_blank"} - laves sammen med andre opgaver om arrangements layout

## Søgeresultatsiden og værkvisningssiden
### Beskrivelse
Værkvisningssiden er den side som samler alle materialetyper og udgaver for en titel. Søgeresultatsiden er den side med posterne i søgeresultatet, som brugerne ser, når de har foretaget en søgning.

### Fremgangsmåde
Et stort antal af udviklingsønskerne, såvel som tidligere indmeldte fejl, under dette emneområde, indgår i et større problemkompleks, og relaterer sig til hinanden. Vi kan derfor forvente, at løsning af én sag kan medføre at andre kan lukkes, eller skal omskrives.
Derfor skal arbejdet indledes med en analyse, hvorunder udviklingsønsker og fejl der vedrører søgeresultat og værkvisning behandles under ét, prioriteres, og relateres til hinanden.

### Sager
Disse er opdelt i størrelsen af opgaven. Der bruges en t-shirt størrelse. Det kan ikke sammenlignes med t-shirt størrelserne på emneområdet. Det er for at indikere at vi ikke kan lave mange større opgaver indenfor dette emneområde.

#### XXL-opgaver
[CMS-982: Link fra værkvisning til noder hvor værket er formidlet](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-982){:target="_blank"}  
[CMS-1489: "Skift"-knap mangler ved reservering](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1489){:target="_blank"}  

#### L-opgaver
[CMS-1091: Print-knap](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1091){:target="_blank"}  
[CMS-1107: Link til Bibliotek.dk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1107){:target="_blank"}  
[CMS-1235: Link til bibliotek.dk ønskes ved 0-søgninger](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1235){:target="_blank"}  

#### M-opgaver
[CMS-1016: Find på hylden udfoldet](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1016){:target="_blank"}  
[CMS-1106: Forbedret læsevisning af Infomedia-artikler](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1106){:target="_blank"}  
[CMS-1488: ”Kopier link til udgave”-funktion som i bibliotek.dk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1488){:target="_blank"}  

#### S-opgaver
[CMS-1451: Søgning efter skønlitteratur på et andet sprog end dansk bør gøres mulig via klik på emnetal](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1451){:target="_blank"}  

#### XS-opgaver
[CMS-981: Anmeldelser på værkvisning skal ikke vises hvis ikke relevant](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-981){:target="_blank"}  

#### Andet
[CMS-1012: Brødkrummer - På værkvisningen](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1012){:target="_blank"} - skal eventuelt skubbes til automatisk genereret samlesider er lavet.

[CMS-1376: Find på hylden: Mulighed for at fravælge visning af de eksemplarer, som pt. er udlånt](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1376){:target="_blank"} - skal undersøges mere før den kan estimeres.

## Lånerstatus og brugerprofil
### Beskrivelse
Lånerstatus dækker over huskeliste, brugerprofil, låne- og reserveringsoversigt. Sagerne i dette emneområde er forskellige forbedringer og nye funktioner.

### Fremgangsmåde
Sagerne i dette emneområde er meget forskellige og skal behandles som enkeltsa-ger. Det skal være lettere for slutbrugerne at navigere fra lånerstatus til oplysnin-gerne fra værkvisningssiden. Der vil være ting som kræver lidt mere analyse fx skal reserveringer sorteres efter afhentningsnummer eller er det mere anvendeligt at de sorteres efter hvornår de udløber? Når der skal træffes  valg, så tager sagerne ofte længere tid at implementere.

### Sager
Disse opgaver er ikke estimeret endnu.

[CMS-810: Dato i "Afleveringsfrist" står med for lille typografi](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-810){:target="_blank"}  
[CMS-971: Link fra lånt materiale til værkets info](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-971){:target="_blank"}  
[CMS-1040: Huskeliste hopper til side 1 efter redigering](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1040){:target="_blank"}  
[CMS-1109: Visning af reserveringer klar til afhentning ønskes sorteret i nummerækkefølge efter afhentningsnumre](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1109){:target="_blank"}  
[CMS-1135: Låneoversigt: Visning af alle elementer, ikke kun 25 pr. gang](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1135){:target="_blank"}  
[CMS-1223: Antal materialer i reserveringsoversigter](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1223){:target="_blank"}  
[CMS-1296: Bekræftelse af mobiltlf og email på brugerprofilen](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1296){:target="_blank"}
