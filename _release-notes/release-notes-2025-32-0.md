---
title:  "Release Notes 2025.32.0"
category: "Release Notes"
weight: 330
---  

#  Forbedringer til avanceret søgning, mere brugervenligt design af autofuldførelse og fejlrettelser

Releasedato: 07-08-2025

**Redaktør**: Produktionssites: 2025.32.0

**Webmaster**: Produktionssites: 2025.27.2, Moduletestsites: 2025.32.0


## Nye features

- Support ID til Publizon på FB CMS: Brugerprofilen (/user/me) indeholder nu information om Support ID, som bruges ved supporthenvendelser til Publizon. 

- Avanceret søgning: Det er nu muligt at filtrere på "Department" og "Branch" under "CQL søgning".

- Emnetal (DK5) vises nu også på værksvisningssiden for udenlandsk skønlitteratur.

- Find på hylden: Det er nu muligt at konfigurere (admin/config/dpl-library-agency/general-settings), om beholdninger på alle filialer i “Find på hylden” modalen er udfoldet, når brugeren kommer derind.


## Fejlrettelser og opgraderinger

- Lektørudtalelse vises nu også under "Anmeldelser" på værkvisningssiden.

- Avanceret søgning: Mindre rettelser bl.a. justering af placeholdertekst til “e.g. term.title=snemand*” og tilføjelse af link (https://danbib.dk/soegekoder-complex-search) til søgekoder.

- Dropdown med autogenererede forslag ved søgefelt: Lille designændring som skaber kontrast mellem dropdown med autogenererede forslag og baggrund. Brugertest har vist, at mange brugere overser dropdown, fordi den har samme farve som baggrunden, og den samtidig befinder sig i brugerens perifære syn, når fokus er på søgefeltet. 

- Udløbstidspunkt for reserverede digitale materialer er nu korrekt. Tidligere har udløbstidspunktet været en time forskudt i FBCMS i forhold til diverse notifikationer på sms og mail. 

- Blå titler fra e-reolen: Brugere som ikke er logget ind på sitet får nu også vist om en titel fra e-reolen er en såkaldt blå titel - dvs. en titel som ikke tæller med i brugerens kvote over hvor meget der kan lånes.  

- Rettigheder for lokalt installerede moduler: Fejl rettet hvor rettighedsindstillinger forsvinder ved hver opgradering af FBCMS. Kun relevant for webmasterbiblioteker. 

- Ændring af pinkode på mobil: Fejl rettet hvor sitet kaster en fejlmeddelelse når man forsøger at ændre pinkode til brugerprofil via mobil. 

- GO: Fejl rettet hvor link til det almindelige CMS fejler på GO, når der anvendes relative links. 

- Forbedret læsevisning af Infomedia-artikler.

