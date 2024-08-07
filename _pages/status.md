---
permalink: /overblik/status
title:  "Status på udvikling og fejlrettelser"
sidebar: true
nav: "overblik"
---
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
I perioden 21/7 til 29/7 tjekker vi kun servidedesken, så sørg for at bruge denne, fremfor CMS-info@kk.dk.
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
I ugerne 29, 30 og 31 planlægger vi grundet sommerferie ikke med at lave nye releases. Opstår behovet vil vi dog release. Samtidigt er det i denne periode ekstra vigtigt at problemer og henvendelser sker via CMS-info@detdigitalefolkebibliotek.dk eller via vores servicedesk.
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
I Netpunkt findes en Er hjemme - slå op funktion. Den linker til beholdningsvisning for en titel i bibliotekets eget CMS. Netpunkt skal kende url-strukturen I jeres nye CMS, for at funktionen virker. Den skal I angive i VIP. Læs hvordan her: https://www.folkebibliotekernescms.dk/main/bliv-klar-til-folkebibliotekernes-cms/12netpunkt-slaa-op/

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

