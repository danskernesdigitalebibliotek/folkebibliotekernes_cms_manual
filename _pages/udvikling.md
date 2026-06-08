---
permalink: /overblik/udvikling/
title:  "Udvikling på FB CMS"
sidebar: true
nav: "overblik"
---

Der kommer til at ske rigtig mange ting i 2026, og herunder kan du se en oversigt over og en status på alt hvad vi skal lave. Der er også mindre opgaver vi laver som ikke vil blive beskrevet her, men som kommunikeres via enten nyhedsbreve eller release notes.

Vi opdaterer siden løbende.

Forklaring på farverne: <span title="Færdig">🟢</span> betyder at opgaven er helt færdig, <span title="I gang">🟡</span> betyder at udvikling på opgaven er i gang, <span title="Ikke i gang">🔴</span> betyder at vi ikke er begyndt på udviklingen (kan dog være startet på analyse eller planlægning af opgaven), og <span title="Udskudt">⚫</span> betyder at det er udskudt til senere. Farverne har tooltip, hvis du ikke kan se farverne. 
{: .notice}

## Udviklingsønsker
Vi går snarligt i gang med at udvikle på arrangementer, og så skal vi se hvad vi gør med resten af udviklingsønsker. Vi skal se om vi skal udvikle på emneområderne Søgning og værkvisning og Formidlingsparagrafer, og hvorvidt vi skal involvere bibliotekerne.

Læs mere om [udviklingsønskerne for 2026](https://www.folkebibliotekernescms.dk/main/overblik/udviklingsoensker/efteraar-2025) eller [generelt om udviklingsønsker](https://www.folkebibliotekernescms.dk/main/overblik/udviklingsoensker/). 

### <span title="I gang">🟡</span> Arrangementer
Vi forventer at lave arrangementsdelen færdig inden sommerferien. Vi kan ikke lave alle ønskerne indenfor dette emneområde, så vi udvikler efter en prioritering.

Ønskerne:
* <span title="I gang">🟡</span> [CMS-578: Sortering af arrangementer på kategori eller bibliotek](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-578)
* <span title="I gang">🟡</span> [CMS-943: Opret målgruppe i taksonomi](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-943)
* <span title="I gang">🟡</span> [CMS-945: Søgning på arrangementer efter dato](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-945)
* [CMS-1828: Status på arrangementer #2](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1828)
  * <span title="I gang">🟡</span> Implementering på selve arrangements-siden
  * Mulighed for at selv at definere egen status
  * Mulighed for at filtrere på arrangements-status i lister
  * Implementere på div. arrangements-paragraphs
* [CMS-1000: Arrangementer - Mulighed for at klone](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1000)
* [CMS-1032: Arrangementsoversigt - Væk med "Vis flere"](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1032)
* [CMS-1033: Arrangementsoversigt - Adskillelse af måneder](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1033)
* [CMS-1357: Opdeling af arrangementer og udstillinger/længerevarende forløb](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1357)
* [CMS-1583: Større fleksibilitet i gentagelsesmønster ved arrangementer](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1583)
* [CMS-1832: Flere kategorier på samme arrangement](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1832)

### <span title="Ikke i gang">🔴</span> Resten
Vi skal have en plan for hvad vi skal udvikle for den sidste del af budgettet. Vi forventer at dette bliver udviklet færdigt i Q4.  
Søgning og værkvisning og Formidlingsparagrafer er de to efterfølgende højest prioriteret emneområder. Det kan blive en blanding af de vigtigste opgaver inden for de to områder eller noget tredje.

## Puljeprojekt: Sammenhæng i brugerrejsen på tværs af biblioteket 
Der er tre spor i dette projekt: GO, Merengagement og Statistik.

### <span title="I gang">🟡</span> GO
Vi har flere forbedringer til GO.

- <span title="Færdig">🟢</span> Loginlogik
- <span title="Færdig">🟢</span> Tilpasning af formidling (højformatvideo)
- <span title="Færdig">🟢</span> Tilpasning af VIP-profil og værkvisning
- <span title="I gang">🟡</span> Reservering af fysiske materialer
- <span title="Ikke i gang">🔴</span> Personaliserede anbefalinger

### <span title="I gang">🟡</span> Merengagement
Vi vil udvikle flere elementer, der skal præsentere bibliotekets tilbud til borgerne på det rette tidspunkt i brugerrejsen. Bedre kampagner blev udviklet i første halvdel af året og de resterende opgaver udvikles i slutningen af året.

- <span title="Færdig">🟢</span> Bedre kampagner
- <span title="Ikke i gang">🔴</span> Landingsside til serier i værkvisningen
- <span title="Ikke i gang">🔴</span> Præsentér andre relevante materialer efter endt reservering
- <span title="Ikke i gang">🔴</span> Anbefalinger på dashboardet

### <span title="Ikke i gang">🔴</span> Statistik
Vi udvider mængden af målepunkter, og introducerer et dashboard på FB CMS til data. 

## Drift og integrationer
Der er en del opgaver, som skal laves til forbedre den daglige drift, og der er også nogle 3. parts integrationer, som vi skal have udviklet mod.

### <span title="Færdig">🟢</span> Migrering til ny platform til hjemmesiderne
Vi er færdige med at migrere alle siderne til en ny platform.

### <span title="Færdig">🟢</span> Fire repositories til en samlet kodebase
Vi har samlet de fire repositories til én samlet kodebase. Dette øger effektiviten hos vores leverendør og sparer en stor mængde tid.

### <span title="I gang">🟡</span> Nye apps
Der kommer tre nye apps til bibliotekerne. Der kan være nogen elementer, som kan overlappe eller skal udvikles i CMS'et.

### <span title="Ikke i gang">🔴</span> Ny platform og reader/player funktion til ebøger/lydbøger 
Der kommer en ny platform og en ny reader/player funktion til ebøger/lydbøger. Vi er i gang med at analysere hvordan CMS'et påvirkes, og hvor stor en opgave der venter.

### <span title="Ikke i gang">🔴</span> Design review
Vi laver et større design review, der skal sikre bedre principper og guidelines. Derudover vil der kigges på at få rettet irritationspunkter i designet på hjemmesiderne.

### <span title="Udskudt">⚫</span> FBS 2.0
Er flyttet til næste år. Der kommer et nyt FBS 2.0. Dette påvirker mange af de udviklingsopgaver vi har. Vi er i gang med at analysere hvordan CMS'et påvirkes, og hvor stor en opgave der venter.

## Vores fokusområder
Dette er de områder, som vi i Det Digitale Folkebibliotek kan se skal løftes på baggrund af vores arbejde eller jeres input. Det vil som oftes være større opgaver eller mange små indenfor samme område, som vi samler til et fokusområde. 

OBS Alle områderne er ikke nødvendigvis noget som skal laves i 2026. Vi kan ikke nå alt, der er beskrevet herunder.

### <span title="Færdig">🟢</span> Ny forbedret Simple search
Vi har implementeret funktionerne fra avanceret søgning ind på simple search.

### <span title="I gang">🟡</span> eReolen efterslæb
Vi skal have kigget på de mest kritiske problemer efter at eReolen blev integreret på hjemmesiderne. Vi har lavet flere forbedringer bl.a. i søgemulighederne på hjemmesiden.

### <span title="Ikke i gang">🔴</span> Huskeliste
Vi samarbejder med DBC om at lave en global huskeliste, så det ikke er hver tjeneste, der har adskilte huskeliste. 

### <span title="Ikke i gang">🔴</span> Materialernes tilgængelighed og adgang
Der er flere problem med tydeligheden af om et materiale er tilgængeligt og hvordan man får adgang til det. Det meste af dette område bliver sandsynligvis først kigget på i 2027 efter FBS 2.0 opgaverne.

### <span title="Ikke i gang">🔴</span> Periodika
Periodika på hjemmesiderne har flere uhensigtmæssigheder, som bl.a. gør det svært at finde og vælge de korrekte udgaver. Bliver sandsynligvis først kigget på i 2027 efter FBS 2.0 opgaverne.

### <span title="Ikke i gang">🔴</span> Ny forbedret CQL søgning
Efter vi har forbedret avanceret søgning og simple search, så skal vi have implementeret funktionerne ind i CQL søgningen også. Bliver sandsynligvis først kigget på i 2027 efter FBS 2.0 opgaverne.

## I samarbejde med andre
Der sker også udvikling, der fx finansieres af andre eller hvor rettelserne skal ske i en anden tjeneste. Ingen af nedenstående er fastsat til 2026 medmindre der står andet under punktet. Dette er mest som et overblik, så bibliotekerne kan se hvad vi ellers har i gang.

### <span title="Ikke i gang">🔴</span> Servicebanner
Vi er i dialog med København, der overvejer at få finansiere en ny funktion, hvor man kan tydeliggøre servicebeskeder på hjemmesiden. Der er ikke planlagt en tidsplan.

### Webmasterudvikling
Flere webmasterbiblioteker har udviklet nogle funktioner, som vi mener kan være meget givtige at få, som fast funktionalitet i FB CMS for alle bibliotekerne. 

- <span title="Ikke i gang">🔴</span> Digitale tilbud - Dansk Centralbibliotek for Sydslesvig har udviklet en meget brugbar løsning til Digitale tilbud. Der er ikke aftalt hvordan dette skal finansieres eller udvikles.
- <span title="Ikke i gang">🔴</span> Ny visuel navigationskomponent - Herning Bibliotekerne har lavet en pæn og overskuelig paragraph, som kan bruges som supplement til de andre navigationsparagrapher. Den er bedre til at lave et pænt visuelt overblik. Der er ikke aftalt hvordan dette skal finansieres eller udvikles.
