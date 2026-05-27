---
title:  "Release Notes 2026.22.0"
category: "Release Notes"
weight: 306
---  

Releasedato: 28-05-2026

**Redaktør**: Produktionssites: 2026.22.0  
**Webmaster**: Produktionssites: 2026.18.4, Moduletestsites: 2026.22.0

<br>

## Ny udvikling

* Forbedrede kampagner: Vi har forbedret kampagner med nye funktioner og et pænere layout. Nu er det muligt at vægte kampagner, så man kan være sikker på at de vigtigste kampagner aktiveres. Derudover kan man nu få aktiveret sine kampagner ved at matche brugernes søgeord fx hvis de søger på gebyr, så kan man få aktiveret en kampagne om gebyrer. Læs mere i manualen: [Kampagner](https://www.folkebibliotekernescms.dk/main/indhold/kampagner/)

*	Addressefelt forbedret til ikke-danske adresser. Nu kan man vælge at bruge et opslag i GSearch eller fritekst felter.

*	Tillad af upload af 50MB filer: [CMS-1963](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1963)

<br>

## Forbedringer og fejlrettelser - Tilgængelighed (GO)

*	Login-knapperne i login-modalen har nu unikke aria-labels, så skærmlæserbrugere tydeligt kan skelne mellem dem. 

*	Tekstfarve på brugerprofil er rettet, så den har tilstrækkelig kontrast til baggrund.  

*	Oplysninger om udløbstid kan nu oplæses for skærmlæserbrugere.

*	Oplysninger om tilstand på filterknapper kan nu oplæses for skærmlæserbrugere. 

*	Søgesiden giver nu feedback til skærmlæserbrugere om at siden opdaterer ved f.eks. valg af filtre.

*	Knap "Flere" ved filtre viser nu flere filtre for tastaturbrugere.

<br>

## Øvrige forbedringer og fejlrettelser

*	Kvoter for digitale lån vises nu korrekte, så blå titler ikke tæller med i udlånskvoten:  [CMS-1677](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1677)

*	"År"-feltet ved valg af periodika skal ikke bruge samme label som "År" ved "Reserveringsfejl" på værkvisningssiden. Fejlrettelsen betyder også, at brugerne får en mere forklarende fejlmelding, hvis de f.eks. forsøger at reservere et materiale, som de ikke har rettigheder til at låne: [CMS-1941](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1941)

*	GO: Videoerne fejler sommetider i at hente thumbnail ned - Thumbnailen hentes nu direkte fra Drupal i stedet for at afvente svar fra videotool. Det betyder, at forhåndsvisningsbilledet altid vises med det samme. 

*	Fejl på automatisk publicering af arrangementer er rettet i forbindelse med rettelsen af nedenstående sag om import fra Delingstjenesten. 

*	Import af abonnementsartikler fra Delingstjenesten: Et baggrundsjob ophobede synkroniseringsforsøg, så nye abonnementsartikler fra Delingstjenesten ikke blev importeret til bibliotekernes hjemmesider. Fejlen er nu rettet, og artikler hentes igen korrekt. [CMS-2009]( https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2009)

*	Tryk på tilbage-knap efter log ud fører nu til loginsiden på lånerstatussider: Når en låner logger ud og derefter navigerer tilbage til tidligere besøgte sider via browserens tilbage-knap, bliver man nu sendt til loginsiden, hvis siden er en lånerstatusside (sider der starter med /user). Tidligere kunne man ende på tomme lånerstatussider: [CMS-620]( https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-620)

*	Infomedia er ændret til Retriever i modalvisningen af artiklerne, så det er Retrievers logo, der vises: [CMS-1995](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1995)

