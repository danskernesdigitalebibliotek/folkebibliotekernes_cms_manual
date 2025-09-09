---
permalink: /overblik/status
title:  "Status på udvikling og fejlrettelser"
sidebar: true
nav: "overblik"
---

## 9/9 -25 Problemer med afspilning af digitale lån på hjemmesiderne
Vi oplever pt. problemer med afspilning og visning af e-bøger og nogle lydbøger via hjemmesiderne og via GO.

Vi arbejder på at løse problematikken som er relateret til Publizon Adapteren, og melder ud her når der er nyt i sagen. 
## 5/9 -25 Fortsat fejl på UNI-login på nogle skoler
Vi oplever fortsat fejl på UNI-login på nogle skoler. Vi arbejder på sagen sammen med STIL og Reload og melder ud, når der er styr på situationen igen. På alle GO-sites er der nu lagt information ud til slutbrugerne. 

På mandag den 8/9 kører vi et hotfix ud til alle de biblioteker, som lige nu er på release 2025.36.0, så de kommer på release 2025.36.1. Vi håber, hotfixet kan bringe os nærmere på nogle løsninger på Unilogin ustabiliteten.
## Uni-login på GO-sitet fejler for nogle elever
Vi har desværre fået meldinger ind på at Uni-loginet via GO-sitet fejler på nogle skoler. Vi er i fuld gang med at fejlsøge og lokalisere fejlen.
Derfor har vi brug for jeres hjælp. Hvis I får henvendelser fra kommunens skoler, vil vi bede jer om at få følgende oplysninger fra skolerne:

- Skolens institutionsnummer?

- Er det web, app eller begge steder, de ikke kan logge ind med Unilogin?

- Er det alle elever, der oplever, at de ikke kan logge ind eller kun nogle?

- Hvilken fejlmeddelelse modtager de, når de prøver at logge ind? Send meget gerne screenshots, hvis muligt.
## Servicevinduer fredag den 22. august og mandag den 25. august. Begge dage er efter kl. 22.
I forbindelse med nedlukningen af det nuværende ereolengo.dk har vores leverandør brug for at tildele ekstra ressourcer til databasen. Det kræver at databasen bliver flyttet til en større maskine, hvilket vil betyde nedetid på tværs af sites'ne under flytningen.
Vi laver flytningen fredag aften, men har planlagt begge servicevinduer så vi har mulighed for at reagere mandag aften, hvis der er brug for ekstraordinære ændringer.
## 12/8 Microsoft har flyttet Azure servicevinduet kl. 17-08
Var oprrindeligt sat til den 11/8.
Baseret på erfaringer fra tidligere servicevinduer vil det for os medføre en genstart af databasen, hvilket kan medføre ~30 minutters nedetid.
## 6/8 kl. 13.07 Alle sites er oppe igen
Vi genstartede databasen og alle hjemmesider er nu oppe.
## 6/8 kl.12 Flere hjemmesider er nede
Flere hjemmesider er nede. Vi arbejder på sagen og melder tilbage her, når det er løst.
Vi afventer at Azure selv stabiliserer databasen.
Hvis ikke det sker inden 12:20 så genstarter vi databasen manuelt. Hvis det bliver nødvendigt så vil det medføre yderligere 30 minutters nedetid for de sites som er påvirket.
## Servicevindue mandag den 11. august kl. 21
Mandag den 11. august kl. 21 vil vi afholde et servicevindue til at opdatere konfigurationen af databasen. Opdateringen kan medføre nedetid på tværs af alle sites i 20-30 minutter.
## 30/7 Adgangsplatformen virker igen
## 30/7 Adgangsplatformen på hjemmesiden fejler
Man kan lige nu ikke logge ind på hjemmesiden. Vi har meldt fejlen vedrørende Adgangsplatformen til DBC. 
## 4/7 Problem med manglende indhold på GO LØST
Nogle biblioteker har oplevet problemer med synkronisering af formidlingsindhold på GO.
Med release 2025.27.2, som blev rullet ud til alle biblioteker i går (med undtagelse af få biblioteker, der har fået separat besked) er følgende udfordringer blevet løst:
- Et GO! site kunne stå med en tom forside og andre undersider (”Ups! Noget gik galt”)
- Et GO! site blev ikke opdateret, når indhold blev opdateret i FB CMS - enten af lokale redaktører eller igennem Delingstjenesten
- Et FB CMS site modtog ikke opdateringer fra Delingstjenesten igennem deres abonnement på GO!

Meld endelig ind i Servicedesk hvis I opdager andre fejl.
## 30/6 GO-sites: Forsiden melder "Ups, Noget gik galt"
Vi er blevet opmærksomme på, at forsiden på nogle bibliotekers GO-sites melder "Ups, Noget gik galt". Reload er i gang med lave en fejlrettelse, som vi forventer kommer ud enten i dag d. 30/6 eller i morgen d. 1/7. Vi vil melde ud her på statussitet, når alle GO-siderne igen kører som normalt.
## 19/6 Webforms: Formularerne virker med forbehold
Webformularerne virker igen. Vi har ikke fået det endeligt bekræftet endnu fra vores udviklere. Reload er i dialog med Microsoft om at få hævet kvoten på mailudsendelserne, men Microsoft har ikke hævet det endnu. Så det kan være at vi bliver ramt af endnu en høj stigning af mails, som får formularerne til at fejle. Så med andre ord: Vi arbejder fortsat på dette.
## 18/6 Webforms: Vi arbejder fortsat på en løsning
Vores udvikler Reload arbejder fortsat på at finde ud af hvorfor der sendes så meget ud fra formularerne og dermed få formularerne til at virke igen. 
## 17/6 Webforms: Mailudsendelse (primært ifm. kontaktformularer) virker pt. ikke
Det er pt. ikke muligt at sende via webforms, da der er konstateret en klar stigning i antal requests, som har fået webformularerne til at gå ned.
Vi arbejder på at rette dette, og melder ud på statussitet, når de igen virker.
## 17/6 Søgning er igen stabil på hjemmesiderne
Efter fejl på internettet hos DBC har der været ustabil drift på søgningen. Det er nu løst.
## 17/6 kl. 9.30 Ustabil drift på søgning på hjemmesiderne
Vi arbejder på en løsning.
## Servicevindue onsdag den 18. juni kl. 22
Onsdag den 18. juni kl. 22 vil vi afholde et servicevindue til at opdatere konfigurationen af databasen. Opdateringen vil medføre nedetid på tværs af alle sites i 20-30 minutter.
## 14/5 kl. 17.50 Alle sites oppe igen
Vi har haft et udfald på databasen, men alle sites er oppe igen.
## 14/5 kl. 17.30 Ustabile sider
Vi oplever lige nu at dele af hjemmesiderne fejler. Vi er på sagen.
## 7/5 Alle sites skulle være stabile igen
Vi har valgt at flytte de 6 biblioteker, som er blevet overflyttet til ny database, tilbage til den gamle database, da vi i dag har oplevet ustabil drift på de sites. Nu er alle sites på den gamle database og stabile.
Vi melder snart en ny plan ud for migreringen af siderne.
## 7/5 Fejl på sites efter databaseflytningen
Vi oplever fejl og nedetid på følgende sites:

- Albertslund
- Sønderborg
- Allerød
- Nordfynsbib
- Assens
- Ballerup

Vi arbejder på at få siderne stabiliteret.
## 5/5 Ny release i morgen den 6/5 som retter fejl
Fejlen med at kontaktoplysninger slettes ved ændring i fraværsperiode bliver rettet i en ny release som kommer ud i morgen 6/5:

Redaktør:
- Produktionssites: 2025.18.1

Webmaster:
- Produktionssites: 2025.17.2
- Moduletestsites: 2025.18.1 (disse bliver ikke nulstillet)
## 5/5 Kontaktoplysninger slettes ved ændring i fraværsperiode
Når man logger ind på hjemmesiden og indsætter eller ændrer fraværsperiode under reserveringer, så slettes profilens kontaktoplysninger (e-mail og mobilnummer) i Cicero. Vi er på sagen og får forhåbentlig rettelsen klar til ugens release. I kan følge med i denne sag: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1512 
## 5/5 Webmasterbibliotekerne mangler adgang til Delingstjenesten via backenden
Selvom der burde være adgang til Delingstjenesten fra release 2025.17.0, så har webmasterbibliotekerne ikke fået adgangen endnu. Det er på vej. Følg med i sagen her: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1509
## 30/4 kl. 16 LØST- Problemer med at logge på hjemmesiderne med MitID 
DBC har lavet en opdatering ud til FBS Adapteren og nu kan brugerne igen logge ind med MitID.
## 30/4 kl. 15.20 Problemer med at logge på hjemmesiderne med MitID
DBC er på sagen er i gang med at opdatere FBSadapteren. De håber problemet er løst inden for 30 min.
## 30/4 kl. 13.40 Problemer med at logge på hjemmesiderne med MitID
Problemet er nu fundet og sendt videre til DBC. Vi skriver igen her, når der er nyt i sagen.
## 30/4 kl. 11.45 Problemer med at logge på hjemmesiderne med MitID
Vi oplever lige nu at man ikke kan logge på hjemmesiderne med MitID. Vi er i gang med at undersøge sagen og vender tilbage.
Brugerne kan godt logge på med CPR + pinkode.
## 29/4 Opdatering af hjemmesider grundet ændringer i FBS-integrationer
I dag releaser vi en ekstraordinær opdatering til hjemmesiderne, da vi er nødt til at tilpasse vores integrationer til FBS (Fælles Bibliotek System). 
Baggrunden er, at Systematic udruller en ny version, hvor flere API’er udgår. Disse API’er er essentielle for, at brugerne kan se og redigere deres brugeroplysninger. 
Det har ikke været muligt at gennemføre de nødvendige ændringer i de i forvejen planlagte releases og vi udsender derfor denne ekstra-release. Det får dog ingen betydning for jer på bibliotekerne.

Planen for opdateringen er følgende:

•	Redaktørhjemmesider opdateres til version 2025.17.1.

•	Webmasterhjemmesider opdateres til:

o	Produktionssites: 2025.15.2

o	Moduletestsites: 2025.17.1

Modultestsites bliver ikke nulstillet ifm. denne release.

### OBS! Brugere som ikke har typen person – altså virksomhed, bibliotek og gruppe – kan ikke opdatere stamdata. Det vil sige at de ikke kan ændre telefonnummer, e-mail, afhentningsfilial, pinkode og reserveringspause. Det vil blive rettet snarligt. Vi melder ud i en releasenote, når problemet er løst.

## 11/4 - Digitale artikler fra Gale og ComicPlus virker igen
DBC har fixet problemet med proxy-url'erne, så nu virker det igen.
## 10/4 - Digitale artikler fra Gale + ComicPlus fejler på værkvisningssiden
Det er en fejl som er introduceret ifm at vi begyndte at benytte DBCs linktjekker, idet den ikke fungerer på nogle proxy-links, hvilket gør at visse links fra materialer fra licensbelagte kilder fejler, hvilket igen gør, at der er scenarier, hvor alle links fejler link-tjek i FBI API - og når det sker, fejler værkvisningssiden.
Sag: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1478

Sagen er højt prioriteret og vil forhåbentlig kunne rettes med releasen efter påske.
## 9/4 - “Lån e-bog” og “Lån lydbog (Online)” knapperne under Udgaver virker ikke, og “låser” brugerne på siden
“Lån e-bog” og “Lån lydbog (Online)” knapperne under Udgaver virker ikke, og “låser” brugerne på siden. Klikker man på knapperne, ændrer url’en sig godt nok, men der kommer ingen modal frem, og sidens scroll-funktion disables således at brugeren er “låst” og ikke kan komme videre.
Anvender brugerne i stedet låne-knapperne øverst på værk-siden så fungerer tingene heldigvis.
I kan finde sagen her: (https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1473)
Vi har sendt sagen til udviklerne og prioriteret den højest. Den vil forhåbentlig kunne rettes med releasen efter påske.
## 31/3 - Release 2025.13.1 kommer ud i dag
Efter udrulning af release 2025.13.0 oplever nogle biblioteker at deres login, søgning mv. ikke virker. De fem biblioteker hvor fejlen har vist sig, har heldigvis været hurtige til at sende det ind til os i Servicedesk, så det kunne løses.
I dag mandag den 31. marts vil vi sende en rettelse ud til alle redaktørbibliotekerne, så de kommer på release 2025.13.1. Webmasterbibliotekerne får 2025.13.1 på torsdag i stedet for 2025.13.0. 
Fejlen er relateret til introduktionen af yderligere webstatistik, hvilket har identificeret en bug i kodebasen som går helt tilbage til at integrationen med Mapp er blevet introduceret.
Af ukendte grunde træder den først i effekt nu - og ikke konsistent på tværs af sites. Heldigvis har Reload været hurtige til at lokalisere fejlen og lave en fejlrettelse.
## 26/3 kl. 15.12 - Alle sites er oppe igen
## 26/3 kl. 15 - vi arbejder fortsat på at genstarte databasen
Vi regner med at siderne er oppe inden for 30 min.
## 26/3 kl. 14.15 - Siderne er ustabile
Der arbejdes på sagen. Vi oplever lige nu et nedbrud på hjemmesiderne. Azure databasen er gået ned og Azure ved ikke hvorfor endnu. 
Vi har desværre ingen tidshorisont.
Varnishe cachen vil holde dele af bibliotekernes sites i live en tid endnu, men f.eks. arrangementssiderne og login  vil ikke virke. 
## Fejlen på material grid manual og recommendation paragraphs vil blive rettet i release 2025.11.0 som kommer ud på torsdag den 13/3.
Bemærk at der ikke kommer nogen release ud i uge 12, hvor der er nedsat kapacitet hos Reload.
## Efter release 2025.10.0 er der fejl på material grid manual og recommendation paragraphs
Det betyder, at man ikke kan redigere eller tilføje nye materialer til eksisterende eller nye material grid manual og recommendation paragraphs.
Vi beklager fejlen, som vil blive rettet hurtigst muligt.
## Servicevindue 18/2 efter kl. 22
Tirsdag den 18/2 kl. 22 vil vi afholde et servicevindue til at opdatere konfigurationen af databasen. Opdateringen vil medføre nedetid på tværs af alle sites i 20-30 minutter.
## 12/2 kl. 15.19 oppe igen
Alle sites er oppe igen. 
## 12/2 kl. 14.53 Alle sites er nede
Vi oplever problemer med alle sites. Vi er i gang med at undersøge.
Problemet er sandsynligvis vedr. databasen.
Vi forventer at sites er oppe igen om ~30 minutter.
## Problemer med statusser og billetknap ift. Place2book
Vi arbejder på flere sager angående integration med Place2book. Derudover arbejder Place2book også på nogle ting i deres ende. 

Hvis man oplever problemer med billetknappen, så er der her en lille guide til hvad man selv kan tjekke:
1. Arrangement er sat til "Overfør til billet udbyder" i FB CMS
2. At arrangementet har priser.
3. At check at FB CMS integrations siden i Place2Book ikke viser nogen fejl i Historikken over imports.
4. Og så køre en "Hent opdateringer fra CMS" i Place2Book.

Kendte fejl er bl.a.: 
- Billetknappen skifter ikke status i det øjeblik arrangement åbner for salg.
- Billetknap skifter ikke status eller dukker ikke op i FB CMS. Skyldes "The website encountered an unexp" fejl.
- Ændring i arrangementstidspunkt opretter nyt arrangement i Place2book.
## Fejl i release 2025.5.1: Ikke muligt at redigere footeren
Desværre er der opstået en fejl i release 2025.5.1, som gør at man ikke kan redigere footeren på hjemmesiderne. Fejlen vil blive rettet hurtigst muligt i en kommende release. 
## DBC opgraderer databaseservere onsdag den 29. januar 2025
DBC opgraderer databaseservere onsdag den 29. januar 2025 klokken 6 til 8, hvor der kan opleves ustabil drift på DBC DIGITALs tjenester og services.
Alle deres services og tjenester kan i dette tidsrum have kortere eller længere nedetid. Herunder også de API’er, vi benytter os af. Det gælder også Adgangsplatformen (Bibliotekslogin), så brugere vil ikke kunne logge ind på de tjenester, der kræver login.
## 24/1 Fejl på sidebaren med åbningstider
Vi har opdaget en fejl i Release 2025.4.0, der gør, at biblioteker med mange filialer ikke kan se den øverste del eller scrolle op/ned til de første/sidste åbningstider i åbningstider-sidebaren, som åbner, når man trykker på uret i højre side. En midlertidig workaround vil være at gå til /admin/config/dpl-library-agency/general-settings og udfylde “Åbningstider link (fjern link for at aktivere sidebar)” med et link til listen over filialer ”/branches”. Så fjerner man midlertidiget sidebaren med åbningstiderne.
## 21/1 Hvor er publicer/afpublicer knappen blevet af?
Efter release 2025.3.2 har muligheden for at publicere eller afpublicere gemt sig. På sider og artikler ligger muligheden ude til højre ved Gem, mens du under arrangementsinstanser skal helt ned under Partners når du vil publicere eller afpublicere. Se denne sag: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1259
Vi har selvfølgelig oprettet en sag på det hos vores udvikler Reload.
## 17/1 kl. 15.10: Alle sites er oppe igen
Vi skal nok opdatere jer nærmere om hændelsesforløbet på mandag, når vi får mere information fra Reload.
## 17/1 kl. 13.10 Status: 
Vi forventer nu nedbrud hver time indtil sagen med Microsofts database er løst. Vi arbejder så hurtigt vi kan på at løse situationen.
## 17/1 kl. 12.28 For tredje og forhåbentlig sidste gang: Alle sites er nede
Microsoft kører et script som gør at siderne fejler. Vi er i kontakt med dem.
## 17/1 kl. 11.30 Siderne er oppe igen
Meld ind hvis I fortsat oplever fejl. Vi får en redegørelse senere fra Reload, så vi kan sige lidt mere om grunden for nedbruddet.
Endnu en gang beklager vi nedetiden.
## 17/1 kl. 10.10 Alle sites er nede
Vi var for hurtige til at melde at fejlen var løst. Alle sites er meldt nede igen nu. Vi beklager nedetiden.
## 17/1 kl. 9.30 Alle sites kommer op igen nu
Vi beklager nedetiden.
## 17/1 kl. 9.20 Alle sites er nede 
Der blev registreret et health event på databasen hos Microsoft for 13 minutter siden. Vores forventning er at databasen kommer op igen om ~10 minutter.
## 15/1 kl. 10 Alle sites er oppe igen
## 15/1 kl. 9.30 Alle sites er nede 
Vi er i gang med at løse det.
## 13/1 Kort nedetid på tværs af hjemmesiderne efter kl. 22 i dag
På grund af en fejl på databasen, som har medført driftproblemer på Solrød Biblioteks hjemmeside, er vi nødt til at genstarte databasen hos Microsoft. Derfor vil der kunne forekomme nedetide efter kl. 22 i aften.
## 17/12 Servicevindue tirsdag den 7. januar kl. 19
Tirsdag den 7. januar kl. 19 vil der være et servicevindue i forbindelse med vedligeholdelse af platformen, da vi skal opgradere et af de centrale systemer, som Folkebibliotekernes CMS gør brug af. Der kan forekomme lidt ustabil drift i 10-15 minutter.

## 17/12 Fejlen i API'et til åbningstiderne i APP'en vil blive rettet i januar 2025

## 13/12 Der er fejl i åbningstids-API'et
Det betyder at app'en ikke viser kategori på åbningstiderne fx selvbetjent. Redia er i gang med at rette op på det og forhåbentlig har vi en rettelse i næste uge til jer. Redia anbefaler, at I venter med at skifte til automatisk hentning af åbningstider, indtil problemet er løst.

## 13/12 Fejlen med manglende DK5 numre er nu rettet i release 2024.50.0

## 6/12 Efter release 2024.49.0 er der ikke DK5-numre under "Find på hylden".
Vi er på sagen, som højest sandsynligt vil kræve en release-rettelse i næste uge. Vi følger op på mandag.

## 29/11 kl. 10.40 Opdateret status på release 2024.48.0
Som skrevet er alle produktionssites opdateret dvs.
- Redaktørbiblioteker er på 2024.48.0
- Webmasterbiblioteker er på 2024.47.2
- Webmasterbiblioteker der har tilvalgt seneste release er på 2024.48.0

Vi har problemer med modultestsitesene. og derfor har vi ikke kunnet gennemføre release processen her.

#### Vores plan er som følger:
- Vi pakker en release 2024.48.1 og ruller den ud på staging
- På mandag ruller vi 2024.48.1 ud på webmasternes modultestsites
- Efter udrulning af 2024.48.1 fortsætter vi udrulningsprocessen og synkroniserer webmasternes modultestsites med produktion
#### Vent med at teste opdatering af egne moduler endnu. Vi skal nok sige til, når I kan teste det.

## 29/11 kl. 9.50 Status på release 2024.48.0
Releasen er færdig på alle produktionssites, men vi arbejder stadig med moduletestsitesene. Vi melder mere ud, så snart vi har den videre plan/tidshorisont fra udviklerne.
## 21/11 Alle redaktørsites + moduletestsites er nu opdateret til 2024.47.2
Husk I kan se releasenotes her: (https://www.folkebibliotekernescms.dk/main/overblik/release-notes/)
## 14/11 Alle redaktørsites + moduletestsites er nu opdateret til 2024.46.0
Husk I kan se releasenotes her: (https://www.folkebibliotekernescms.dk/main/overblik/release-notes/)
## 11/11 Driftsstatus: Alle sider burde være oppe igen
Microsofts database var nede.
## 11/11 Driftsstatus: Vi oplever ustabil drift på siderne
Det gælder både front- og backend. Vi arbejder på sagen.
## 4/11 Alle redaktørsites + moduletestsites er nu opdateret til 2024.44.1
Fejlen med webforms der fejlede skulle nu være rettet.
## 4/11 Driftsstatus kl. 13.48: Alle hjemmesider er oppe igen
Det var heldigvis et kort nedbrud på databasen.
## 4/11 Driftsstatus kl. 13.42: Alle hjemmesider er nede
Vi arbejder på sagen. Næste opdatering kl. 15.30
## 1/11 Driftsstatus: Alle webforms på release 2024.44.0 melder fejl ved afsendelse.
Fejlen er fundet. Vi vil ikke rulle rettelsen ud her lige inden weekenden, men gør det som det første på mandag, hvor alle redaktørbibliotekernes sitets rettes med release 2024.44.1
## 1/11 Alle sites er nu opdateret til 2024.44.0 (webmaster produktionssite på 2024.43.1)
Husk I kan se releasenotes her: (https://www.folkebibliotekernescms.dk/main/overblik/release-notes/)
## 24/10 Alle sites (bortset fra webmasterbibliotekers produktionssites) er nu opdateret til 2024.43.1
Husk I kan se releasenotes her: (https://www.folkebibliotekernescms.dk/main/overblik/release-notes/)
## Servicevindue 15/10 kl. 21
Tirsdag den 15/10 fra kl. 21 vil der være et servicevindue i forbindelse med vedligeholdelse af platformen, da vi skal opgradere et af de centrale systemer, som Folkebibliotekernes CMS gør brug af. Der kan forekomme lidt ustabil drift i 10-15 minutter.
## 10/10 Alle sites (bortset fra webmasterbibliotekers produktionssites) er nu opdateret til 2024.41.1
Husk I kan se releasenotes her: (https://www.folkebibliotekernescms.dk/main/overblik/release-notes/)
### Uge 42 er der ingen ny release.

## 3/10 Alle sites (bortset fra webmasterbibliotekers produktionssites) er nu opdateret til 2024.40.0
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-40-0/
## 26/9 Alle sites er nu opdateret til 2024.39.1
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-39-0/
## 23/9 ”Find på hylden” på værker uden ophav giver fejlmeddelelse
Efter opgradering til 2024.38.1 udløser klik på ”Find på hylden” fejlmeddelelse på tidsskrifter og titler uden forfatter. Fejlen bliver løst i denne uge i release 2024.38.2.
## 20/9 Alle sites (bortset fra webmasterbiblioteker) er nu opdateret til 2024.38.1
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-38-1/
## 18/9 Ekstraordinær opdatering 23-25/9
Vi udruller en ekstraordinær opdatering, der skal forbedre vores ressourceforbrug på driftsplatformen. Den rulles ud til hjemmesiderne over flere dage fra mandag den 23/9 til onsdag den 25/9. Opdateringen påvirker ikke det, som webmasterbibliotekerne selv har installeret på produktionssiderne.
De to releases kommer til at hedde:
- 2024.38.2 til redaktørbiblioteker og modultest sites for webmasterbiblioteker
- 2024.35.2 til produktionssites for webmasterbiblioteker.

## 12/9 Alle sites (bortset fra webmasterbiblioteker) er nu opdateret til 2024.37.0
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-37-0/
## 6/9 kl. 13.40 Alle sites er nu opdateret
### Lige nu er webmasterbiblioteker på prod 35.1 og modultest 36.0.
Vi har dog stadig Tårnby hvor opgraderingen af moduletestsitet driller. Vi er ved at arbejde på et fix.
## 6/9 kl. 8.30
### Release 2024.36.0 er kommer ud til alle redaktørbiblioteker (pånær Næstved)
## 5/9 kl. 13
### Release 2024.36.0 kommer ud til jer i dag (gælder ikke for webmasterbiblioteker)
Det er en lille release men med nogle gode ting som fx Digital artikelservice rettelse.
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-36-0/
## 4/9 kl. 10
### Hjemmesider havde en kort nedetid
Dette skyldes et serverproblem. Alle sider skulle være oppe igen.
## 30/8 kl. 15.40
### Release 2024.35.1 er nu ude på alle produktionssites (moduletestsiderne er på vej)
Det var en større release og derfor tog det ekstra lang tid denne gang og gav desværre også en del udfordringer - også ude på jeres sites. Det beklager vi. 
Husk I kan se releasenotes her: https://www.folkebibliotekernescms.dk/main/overblik/release-notes/release-notes-2024-35-0/
## 28/8
### Release 2024.35.1 kommer ud i morgen
På grund af gårsdagens fejl har vi valgt at skubbe releasen til i morgen den 29/8.
## 28/8 kl. 08.45
### I må nu igen lægge filer (billeder mv.) op på hjemmesiden (ikke webmasterbiblioteker)
I må nu igen lægge filer op på hjemmesiderne. Vi har nu gennemført CSI udskiftningen til ende. Vi havde noget kort nedetid efter det endelig skift, men det er gået over nu. Måske det har skyldtes backup'en som har kørt sideløbende med.
Der er nogle få biblioteker som muligvis har tabt dele af gårsdagens uploadede filer og moduler.
Webmasterbiblioteker: Webmasterbibliotekernes moduletest sider er ikke blevet udskiftet endnu og derfor kan I stadigvæk opleve manglende billeder. Derfor skal I vente med at lægge noget op. I løbet af dagen bliver I udskiftet. Vi giver besked her.
## 27/8 kl. 15.20
### Billeder/videoer fejler igen
Vores driftsleverandør kæmper med at rette fejlen. Indtil da har de bedt os skrive til jer, at I ikke skal oprette nyt indhold (arrangementer, sider mv.) med billeder før vi siger til. Der sker egentlig ikke noget ved det, andet end at I mister billederne. 
De billederne, som I pt. mangler på jeres sites, kommer igen lige så snart fejlen er blevet rettet.
I må gerne rette i tekster på siderne.
Vi melder tilbage her, når I igen må oprette billeder og indhold.
## 27/8 kl. 8.30
### Billeder/videoer fejler igen
Vores udvikler troede de havde et permanent fix til billede-problemet med manglende billeder på hjemmesiderne. De testede det i går på to biblioteker og det virkede. Derfor sendte de det ud til alle sider i dag. Desværre gav det en del fejl på siderne og de måtte rulle tilbage. De er ikke helt i mål og derefter skal det før omtalte script køres ud til bibliotekssiderne, så I kan få jeres billeder tilbage. Vi opdaterer statussitet her, når vi har noget nyt.
## 23/8 kl. 13.45
### Alle biblioteker er oppe igen
Vi beklager nedetiden.
## 23/8 kl. 13.15
### Ustabil drift på siderne
Flere bibliotekers hjemmesider har været nede pga. en serverfejl. Vi har stadig problemer med Odder og Hvidovre bibliotek.
## 19/8
### Hvorfor mangler vores billeder/videoer?
Som de fleste af jer har bemærket, har billedvisningen på hjemmesiden til tider været ustabil og ofte helt manglet her på det sidste. Det har vist sig at være en periodisk fejl, som er opstået ved en særlig kombination af mange brugere på én gang, hvor filsystemet bliver overbelastet. 
Fejlen er nu lokaliseret og analyseret, og en løsning, så fejlen ikke opstår igen, er under udarbejdelse. Vi forventer, at denne løsning efter udvikling og test vil være klar til udrulning i løbet af max 14 dage. 
Indtil da har vi iværksat en mere kortsigtet håndtering af problemet, der består i, at vi 3 gange dagligt (morgen, middag og før fyraften) på alle hverdage vil køre et script, som retter fejlen på de sites, der er ramt af problemet. Dvs. I behøver ikke melde den fejl ind via Serviceplatformen med mindre, den viser sig at være permanent.
Når den langsigtede løsning er klar til implementering, vil I få besked om, at der er et tidsrum, hvor I ikke vil kunne arbejde på sitet, mens udrulningen foregår. Det kommer sandsynligvis til at foregå om aftenen og således være til gene for så få som muligt. Vi giver jer selvfølgelig besked i så god tid som muligt.
## 16/8
### Ingen release i uge 34
Grundet temadage hos både DDF og udviklere kommer der ingen release i uge 34.
## 15/8
### Alle biblioteker bortset fra webmasterbiblioteker er opdateret til 2024.33.0
Nogle biblioteker oplevede nedetid på dele af deres site under opdateringen.
## 14/8 kl. 15
### Fejlen med filsystemet er desværre ikke løst helt for alle biblioteker
Meld ind i servicedesk: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-763 når I oplever det.
## 14/8 kl. 10.50
### Filsystemet fejler igen
Vi oplever desværre at det igen driller med upload og visning af billeder på hjemmesiderne. Fejlen var ikke fikset helt i går. Vi er på sagen.
## 13/8
### Filsystemet på sites virker nu igen
Fejlen er rettet så de biblioteker, som ikke kunne se billeder eller lægge indhold ind i går, igen kan formidle indhold. Udviklerne er ved at analysere hvorfor fejlen opstod. 
## 12/8
### Filsystemet på site fejler
Flere biblioteker oplever lige nu problemer med at lægge indhold ind på deres sites og at se deres billeder på hjemmesiden. Vi er i fuld gang med at fejlrette og det det lader til at være et problem med filsystemet på platformen. Vi melder ud her samt de relaterede sager: https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-753 og https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-754 når vi ved mere.
## 8/8 kl. 18
### Alle sites skulle nu være opdateret til 2024.32.1
Tjek at I er på den nye release. Hvis I er på den nye cms version, kan I nu igen lægge indhold på jeres sites. Lav en sag i servicedesk, hvis I mod forvent ikke er på version 2024.32.1.
## 8/8 kl. 15
### Vi kører nu release 2024.32.1 ud til jer
Det tager 2-3 timer. Vi skriver her, når alle er på og I kan oprette nyt indhold igen.
## 8/8 kl. 10.30
### Vigtig besked: Release 2024.32.1 har fejlet og er ikke rullet ud alligevel
Gårsdagens release 2024.32.1 er desværre fejlet. Vi har lige nu fokus på at fikse situationen.
Vigtigt - Vi skal bede jer om IKKE at lave indhold lige nu, da vi kommer til at rulle ud igen i dag!
Vi regner desværre med at der kommer til gå 5-6 timer før alle er på den nye release. Hold øje med jeres releasenummer og tjek denne side for nyt.
Vi beklager de gener det medfører.
## 7/8
### Ny release 2024.32.1 ude men fejlede på enkelte biblioteker
Vi kørte i går den nye release 2024.32.1 ud, men releasen fejlede på følgende biblioteker, som derfor endnu ikke er opgraderet:
- København
- Herning
- Allerød
- Esbjerg
- Lejre
- Lolland
- Næstved
- Nordfyn
- Ringkøbing-Skjern
- Silkeborg

Vi arbejder på at få den nye release ud til disse biblioteker hurtigst muligt.
## 6/8
### Kontaktformularer og webformularer kan nu afsende mails
Webformularerne og kontaktformularen på hjemmesiden har drillet med afsendelse. Dette er løst med et fix i nat, så der igen kan sendes fra formularerne.
Men grunden til at de stoppede med at virke i første om gang, handler om at bots har spammet webformsene på de forskellige sites og det har lukket ned for udsendingen. Det er jo i princippet godt at de lukker ned ved spam, men vi har opsat ekstra antibots-løsninger, som forhåbentlig sikre at der ikke kommer spam igennem formularerne. Hvis I modtager spam fra jeres formularer, må I meget gerne sende det ind via Servicedesk, så vores udviklere kan lukke det ned.
## 5/8
### Kontaktformularer og webformularer fejler ved afsendelse
Vi oplever at kontaktformularer og webformularer fejler, når de bliver afsendt. Vores udvikler er på sagen og har lokaliseret problemet. Vi skal nok skrive, når der er nyt i sagen.
## 2/8
### Kontaktformularer sender ikke indhold
En del biblioteker oplever at deres kontaktformularer ikke sender indhold, så modtageren kun modtager emnefelter uden det, som der er blevet indtastet. Vi arbejder på at få det løst hurtigst muligt og melder tilbage her, når det er løst.
## 16/7
### Release med fejlrettelser
Vi udgiver iløbet af idag en release der retter de problemer der har været med formularer og relateret indhold.
### Lav bemanding de kommende uger
Frem til uge 32 kører vi med meget lav bemanding. I er selvfølgeligt velkomne til at oprette tickets i vores servicedesk, men forvent længere behandlingstid. Vi holder løbende øje med den, så sker der noget kritisk, vil vi naturligvis agere på det.
### Brug servicedesk fremfor email 
I perioden 21/7 til 29/7 tjekker vi kun servidedesken, så sørg for at bruge denne, fremfor cms-info@fddf.dk.
### Webmaster biblioteker
Der burde være adgang for alle webmaster biblioteker til at teste i jeres modultest-miljøer. Er der problemer med det, så meld ind via servicedesken.
## 15/7
Releasen fra i torsdags har skabt problemer med kontaktformular og visning af relateret indhold i artikler og arrangementer. Vi knokler på at løst disse, og forventer at rulle en release med fejlrettelser ud imorgen, tirsdag.
## 11/7
### Release idag
Vi releaser idag den forventeligt sidste opdatering inden august. Da vi stadig kæmper med Microsofts Mariadb databaser, går vi med livrem og seler, og kører få biblioteker ad gangen. Det forventer vi resulterer i en problemløs release. Vær dog klar over at mellem 13 og 17 idag kører releasen ud, og hvis I oplever problemer, så opret en ticket i servicedesken. Vi arbejder stadig på at stablisere databaserne.
### Problemer med log in på tværs af biblioteker
Vi oplever fejl der opstår når en bruger er logget ind på et bibliotekssite, og så forsøger at oprette sig på et andet bibliotek. Brugeren oplever at blive halvvejs logget ind, og må logge ud, for at kunne oprette sig et nyt sted. Det er desværre ikke noget vi kan nå at få rettet inden tidligst uge 32.
### Udfordringer med webmasterbiblioteker
Vi har afdækket en fejl mellem vores oversættelsesmodul og rettighedsmodul, som har gjort det umuligt for webmasterbiblioteker at aktivere nye moduler. Vi har ikke et fiks klart, men følgende hack bør få det til at virke for jer:
1. Log ind som bruger med administrator-rollen
2. Gå til redigering af brugerprofilen
3. Skift administrationssproget for brugeren til engelsk 
4. Tildel tilladelserne for det nye modul til de resterende roller
5. Skift administrationssproget for brugeren tilbage til dansk

## 10/7 Kommunikation og releases i sommerferien
I ugerne 29, 30 og 31 planlægger vi grundet sommerferie ikke med at lave nye releases. Opstår behovet vil vi dog release. Samtidigt er det i denne periode ekstra vigtigt at problemer og henvendelser sker via cms-info@fddf.dk eller via vores servicedesk.
## 4/7 status på aktiviteter
### Arrangement API
Vi har analyseret og haft dialog med Place2Book omkring de udfordringer der er oplevet. Herunder kan I se hvad status er og vi har aftalt med Place2Book:
1.	Efter integration er billetkapacitet sat til 0/ubegrænset: Place2Book har rettet og dette bør ikke være et problem.
2.	Passive arrangementer tildeles billetknap: Place2Book har rettet og dette bør ikke være et problem længere.
3.	Der mangler felt til at angive billetkapacitet i Folkebibliotekernes CMS: Denne retter vi hurtigst muligt (forhåbentligt til 10/7).
4.	Udfordringer når man anvender anden billetleverandør end P2B: Vi indsætter et afkrydsningsfelt (forhåbentligt til 10/7) hvor man kan angive om et arrangement skal til ens normale billetleverandør. Fjerner man afkrydsning, vil Place2Book ikke hente arrangementet.
5.	Forvirring/fejl omkring sletning i begge systemer: Place2Book har rettet og dette bør ikke være et problem.

## Status på nedbrud i Microsoft databaser
Vi oplevede igen igår nedetid, dog 25 min. Vi afventer stadig at Microsoft svarer på vores oplevede problemer med Maria databaserne der understøtter vores løsning. Det er højst usædvanligt med så meget nedetid og højst utilfredsstillende service vi oplever. Vores aftale siger at de garanterer 99,9% oppetid, hvilket svarer til mindre end en time om året. Pt har vi haft 4 nedbrud fra 10 min til 13,5 timer. Vi forsøger at afbøde problemet med at allokere mere hukommelse til serverne, men kan ikke garantere at det vil løse problemet. Pt er vi desværre overladt til hvornår Microsoft hjælper.

## Institutionslogin
Mange har henvendt sig omkring institutionslogin (alle brugere der ikke er personer) der godt nok giver adgang til at logge ind, men ikke se sine lån m.v. Vi har været vidt omkring i forsøget på at skabe adgang for disse brugere, og har sammen med DBC indsnærpet problemet, så vi forhåbentligt snart har en løsning.

## 2/7 status på aktiviteter
Efter weekendens nedbrud fortsætter vi på fejlfinding og beredskabsplan. Vi melder ud snarest. 
### Arrangement API
Vi modtager mange henvendelser omkring integration til Place2Book lige nu. Vi fokuserer på at få dem samlet og skabe en god løsning i samarbejde med Place2Book. I bedste fald kan vi lancere rettelser næste onsdag 10/7.
### Webmaster
Vi har haft alt for lidt tid til at håndtere de af jer der ønsker at være på webmaster løsningen, eftersom lanering af alle sites i juni var hovedfokus. Vi begynder at samle op på området og melder ud om dette snarest, også til jer der har meldt ting ind i vores servicedesk
## 29/6 Status på nedbrud
Microsoft ser ud til at have løst problemet, men vi mangler stadig dokumentation fra dem. Jeres sider burde virke nu. Vi beklager meget, og garanterer at vi vil lære af dette forløb, og tage tiltag for at gøre os mere uafhængige af disse databaser.
## 21/6 Status
### Arrangementer til Place2Book
Vi har opdaget en fejl i vores snitflade, som gør at Place2Book ikke får arrangementer korrekt overført. Fejlrettelsen kommer ud mandag, og så vil det igen være muligt at hente arrangementer.
### Udfordringer for Hjørring, Tårnby, Aabenraa, Helsingør og Vejle
Efter gårsdagens nedbrud i vores databaser er fem biblioteker ramt af en fejl. Ovenstående fem biblioteker vil opleve at nogle sider ikke kan vises, men generelt bør siderne dog kunne redigeres som normalt. Vi releaser mandag en rettelse til dette problem. Det bør ikke holde nogen fra at gå live i næste uge.
### Problemer med materialekomponenter
Flere af jer har meldt problemer ind omkring materialekomponenter efter release 2024.25.01. Efter analyse har vi afdækket at det gælder allerede oprettede komponenter, som IKKE er blevet redigeret siden sidste release. Dertil at problemet KUN optræder på preview, mens det vil se rigtigt ud for slutbrugeren. Det er vigtigt at nævne at selvom det derfor kan se ud til at noget mangler eller er gået tabt, så er det der stadig. Det er kun i preview funktionen at problemet ses.
### Release fejlede for svendborg, Sydslesvig, Syddjurs, Tårnby, Thisted, Vallensbæk, Varde, Vejle, Vesthimmerland, Viborg og Vordingborg      
Det betød at de nye funktioner i release 2024.25.01 IKKE var tilgængelig for jer. Dette er rettet og I skulle ikke opleve problem med dette.        

## 20/6 Nedetid for enkelte biblioteker
Efter et kortere databasenedbrud er alle sites i luften igen. Vi beklager den lidt længere respons for Herlev, Middelfart, Aabenraa, Furesø og Rudersdal, hvor der var udfordringer med seneste release. Men alt burde køre nu.

## 20/6 Status på udvikling
### Visningsprofil i VIP
Der er fortsat en fejl med visningsprofiler. Visningsprofilen bruges til at generere lånerstatus, huskeliste, samt værkvisningssiden for værker i fysiske materialetyper, som ikke er i lokal beholdning. Vi og DBC arbejder på højtryk for at få den løst.
Fejlen betyder, at hvis man følger den fremgangsmåde for oprettelse af visningsprofil, som er beskrevet i manualen, så vil indloggede lånere ikke kunne se nogen materialer under deres lånerstatus.
Der er et work-around, som går ud på at tilføje kilden ”Folkebiblioteker og Nationalbibliografi (alle 870970-poster, til FBS)” til jeres visningsprofil, hvilket får de fleste, skønt ikke alle, poster til at blive vist.
Det tager op til fire timer før rettelser i VIP-basen slår igennem.

### Søgeprofil i VIP
Får i resultater i jeres søgning på materialer, som I slet ikke har, eller ser I materialer I har, men som materialetyper, I ikke har, så bør I tjekke jeres søgeprofil igennem for at se, at der kun er slået kilder til, som I rent faktisk har. Søgeprofilen må IKKE have kilden “Folkebiblioteker og Nationalbibliografi (alle 870970-poster, til FBS)” aktiveret, og heller ikke ”Forskningsbiblioteker til danbib”.

### Fjernlån fra Det Kongelige Bibliotek vises ikke i lånerstatus
Flere har meldt ind, at fjernlån fra KB ikke vises i lånerstatus.
Der er også en kendt fejl, der gør at reserveringer, der er oprettet samtidig af personale via Cicero, opfattes som en parallelreservering, så kun én af disse reserveringer vises.
Begge fejl har den højeste prioritet.

### Fejl på institutionslån og særlige lånerprofiler (fx andre biblioteker)
En anden dum fejl, som vi oplever, er, at biblioteker ikke kan logge ind hos hinanden og forny lån. Det samme gælder institutionskort som læsekredse med “særlige” lånernumre (som ikke bruger cpr) ikke kan logge rigtigt ind på og få vist udlån.

### Søgeresultatsiden crasher
Der er også en del eksempler på, at søgeresultatsiden crasher, når man scroller ned, eller i sjældnere tilfælde blot ved søgning. Vi har en arbejdshypotese om årsagen, og løsning af denne fejl har også højeste prioritet.

### Visning af lydbogsudgaven som standard + manglende forsider
Det er ikke hensigtsmæssigt at det er lydbogsudgaven som bliver vist som standardmaterialetype, når man går ind på et materiale. Vi har en sag på at få det rettet, så værkvisningssiden altid vises med materialetypen ”Bog” valgt, såfremt denne findes, og medmindre der i søgeresultatet er klikket på en anden materialetype.

### Manglende forsider
Der kommer også en del sager ind på manglende forsider. Vi ved godt, at der mangler forsider i rigtig mange visninger, og det påvirker jeres formidling på sitet. Problemet vil blive prioriteret i et senere projekt, men for nu har vi valgt at fokusere på forretningskritisk funktionalitet.

### VIGTIG tilføjelse til startopsætningen i manualen
I Netpunkt findes en Er hjemme - slå op funktion. Den linker til beholdningsvisning for en titel i bibliotekets eget CMS. Netpunkt skal kende url-strukturen I jeres nye CMS, for at funktionen virker. Den skal I angive i VIP. Læs hvordan her: https://www.folkebibliotekernescms.dk/main/integrationer/12netpunkt-slaa-op/

## 10/6: Status på udvikling
### Søgning og VIP profil
Vi oplever en flaskehals på de fejl der er meldt ind, relateret til søgning og VIP profil. Vi gør hvad vi kan, men I er nødt til at forvente længere svartider på dette område. 
### Webforms
Muligheden for at rette afsender-email skulle aldrig have været der, da vi kun understøtter udsendelse fra vores centrale email-adresse. Men selvfølgeligt har mange af jer gjort det helt oplagte og skrevet jeres egne bibliotekers emails ind der. Det beklager vi! Det er rettet således at I ikke længere kan indsætte mail, og dermed skulle løsningen gerne virke for alle.
### Snitflader til arrangementer
Vi arbejder på at tilbyde flere oplysninger via vores API, således at eksempelvis Kultunaut for alle oplysninger de har brug for. Bemærk at vi pt ikke understøtter at indsætte de kategorier Kultunaut anvender. Det er efter aftale med Kultunaut, da de alligevel gennemgår arrangementerne manuelt. Bemærk også at arrangementer enten kan overføres direkte fra CMS (hvor Kultunaut henter arrangementer på samme måde som Place2Book), eller at arrangementerne flyder fra CMS over Place2Book til Kultunaut. Vi anbefaler den første løsning, så snart denne er klar, da Place2Book ikke behøves være mellemmand i det dataflow (og som sådan jo ikke har interesse i arrangementer uden billetter).
### Arrangementer
Når man har oprettet en arrangementsserie, og efterfølgende manuelt tilføjer instanser af serien, så arver den nye instans ikke beskrivelse (og andre felter) og instansen fremstår tom. Det er vi igang med at rette. I mellemtiden kan man manuelt kopiere felterne fra serien til instansen. Eller vente til vi lige om lidt har et fix.

## 29/5: Status på udvikling
### Snitflade til arrangementer: 
Vi har udviklet en snitflade hvorfra billetsystemer kan hente arrangementer fra de nye hjemmesider, og opdatere disse arrangementer med URL´er og status. Place2Book har været involveret, da så mange af jer brugere deres løsning, og er klar til at integrere. Place2Book oplyser at den fulde integration er oppe at køre i næste uge. De sender nyhedsbrev ud når løsningen er klar. Se mere her: https://support.place2book.com/support/solutions/folders/80000719510. I kan desuden tilmelde jer deres mailingliste her: https://mailchi.mp/ca700eb1edce/place2book-signup  (check evt i "uønsket mail" for verifikationsmail )

### Åbningstider til app
Vi arbejder lige nu på at kunne sende åbningstider til Biblioteket appen. Dette vil involvere at I giver Redia en liste over jeres filialer, hvilket vi vil informere mere om når vi er lidt længere i processen.
### Sikkerhedsopdateringer til Drupal
Da I indtil idag har haft lidt flere rettigheder end nødvendigt, har I kunnet se at Drupal skulle opdateres. Denne opdatering er noget vores driftleverandør tager sig af og skal derfor ikke være synlig for jer. Der er mange af jer der har skrevet til os, om det var noget I selv skulle håndtere. 
### Gentagende arrangementer
Kræver en smule designmæssig kærlighed, men det virker dog. Vi håber at lave en visuel opgradering i efteråret.
### Problemer relateret til visningsprofiler (VIP) og søgning
Vi oplever en række fejl som vi arbejder på at kunne fikse samlet. Noget relaterer sig til jeres VIP profiler, men det er ikke hele svaret. Vi arbejder videre og forventer at have mere herom i næste uge
### Påhængsposter
Problemet med påhængsposter skulle gerne være løst med dagens release
### Åbningstider
Er udviklet færdig, undtagen lidt arbejde på visninger af dem. Vi kigger derudover på et par indmeldte fejl. Desuden kan det lige nu påvirke performance at loade siden med åbningstider, hvilket vi er lige ved at have fixet.
### Søgning i redaktionelt indhold
Denne opgave er specificeret og vi forventer at gå igang med den meget snart.
### Tag samlesider
Kan laves ganske simpelt når vi har lavet Søgning i redaktionelt indhold.
### Webmaster hostingplan
Vi forventer i næste uge at lancere Webmaster hostingplanen til de biblioteker der specifik har bedt om det. De får så mulighed for at teste det med de moduler de gerne vil aktivere. Lidt senere rækker vi ud til alle jer der i januar meldte jer som webmasterbiblioteker, for at høre om I stadig ønsker at gå over, eller blive på redaktørplanen.
### Admin menu
Vi har lavet et første udkast til en lidt mere overskuelig struktur i backenden af CMS. Denne lancerer vi ganske snart, med hvad det indebærer af at opdatere manual m.v.
### Bannere
Lige om lidt kan I bruge bannere på jeres side
### Anbefalingskomponentens backend
Vi arbejder lige nu på at forbedre jeres muligheder for at lave anbefalingskomponenter.
### Artikler
Har fået tilknyttet en slider i bunden med "relateret indhold."
### Arrangementer
Har også fået tilknyttet en slider i bunden med "relateret indhold."
### SEO: Søgemaskineoptimering
Vi har indbygget en del i løsningen der gør siderne bedre ift SEO end den gamle løsning. Når vi har fået lidt erfaringer med hjemmesiderne vil vi genbesøge SEO og se om der skal optimering til.
### Afsender email-adresse
Vi har ved en fejl giver jer mulighed for at indtaste jeres foretrukne email, hvilket systemet dog slet ikke understøtter. Vi kan lige nu kun udsende mails fra vores centrale emailadresse. Da det var meget logisk at indtaste sin egen email, er der mange af jer der har fået problemer med at mails fra formularer eller nyoprettede brugere ikke nåede frem. I næste uge får vi et fix ind, der sætter email tilbage til vores, og fjerner jeres mulighed for at indtaste egen email. Ønsker I at kunne bruge en lokal email, så send det gerne ind som udviklingsønske efter 1/9.


## 24/5: Sikkerhedsfejl fra Aalborg rettet
Det sikkerhedsproblem vi blev gjort opmærksomme på fra Aalborg, er nu identificeret, genskabt og rettet. Den nye release rammer de tre biblioteker der er gået live (Aalborg, Herlev og Billund) mandag kl 10. Onsdag kl 13 kører vi den normale ugentlige release, hvor alle får fejlrettelsen og alle de andre ting vi har udviklet de seneste to uger. Der er særskilt sendt mail til alle kontaktpersoner og bibliotekschefer om denne problematik flere gange de seneste dage.

## 24/5: Microsofts databaser kører stabilt igen
Vi har oplevet problemer med Microsofts databaser, over det sidste døgn. Dette har medført lav performance på jeres sites, og der har været nedetid sporadisk siden igår eftermiddags. Det skulle nu være iorden.

