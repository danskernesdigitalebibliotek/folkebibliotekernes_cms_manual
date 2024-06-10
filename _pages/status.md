---
permalink: /overblik/status
title:  "Status på udvikling og fejlrettelser"
sidebar: true
nav: "overblik"
---
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

