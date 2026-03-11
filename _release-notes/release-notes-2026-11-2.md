---
title:  "Release Notes 2026.11.2"
category: "Release Notes"
weight: 310
---  

**Redaktør**: Produktionssites: 2026.11.2
**Webmaster**: Produktionssites: 2026.10.2, Moduletestsites: 2026.11.2 



## Ny udvikling

### Ny simple search:
Filtreringsmulighederne og søgeresultatsiden i simple search er løftet, så de i højere grad svarer til dem, man kender fra avanceret søgning: fx [CMS-186](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-186)<br>
**Bemærk**: Vi har, for en kort periode, fjernet kampagner fra simple search. Det har vi gjort for at kunne forbedre både funktionalitet og design på kampagnerne.
<br><br>

### Event api'et er ændret i forhold til billedstørrelser:
Event api'et er ændret til at vi sender billedet fra arrangementer med i tre forskellige versioner: <br>
- 'image' er arrangementets hovedbillede, hvor bredden altid er 1920px og højden vil variere. Dette er anbefalet til arrangementsvisning på fx billetsystemer eller arrangementskalendere, der ikke skal bruge et meget stort billede.<br>
- 'originalImage' er det originale hovedbillede, der ikke er skaleret. Dette er anbefalet til fx infoskærme, der skal bruge et stort billede.<br>
- 'teaserImage' er det billede, som I har sat ind som teaserbillede på arrangementet. Dette er anbefalet til listevisning på fx billetsystemer eller arrangementskalendere.<br>

Ændringerne er 1) at ‘image’ er gået fra 896x670 til i stedet at være 1920px i bredden og 2) Vi har introduceret ‘originalImage’.

<br>


## Forbedringer og fejlrettelser

### Tilgængelighed: Tomt link i "Anbefaling" og "Andre Materialer":
Der er rettet en tilgængelighedsfejl, hvor der kunne opstå tomme links i modulerne “Anbefaling” og “Andre materialer”.
Det betyder:
- Skærmlæsere ikke længere møder “usynlige” eller meningsløse links.
- Brugere, der navigerer med tastatur eller hjælpemidler, får en mere forudsigelig og tilgængelig oplevelse.

### Tilgængelighed: Synlig tekst er ikke en del af tilgængelig tekst:
En række steder var den tekst, som brugeren kunne se, ikke korrekt koblet til den tekst, som hjælpemidler (fx skærmlæsere) læser op.
Det er nu justeret, så:
- Hjælpemidler får den samme, meningsfulde tekst som synlige brugere.
- Brugere med hjælpemidler lettere kan forstå indhold og funktioner på siderne.

### GO: Problem med load af materialer i søgning:
En fejl betød, at der i GO kunne opstå situationer, hvor flere søgeresultater ikke blev loadet, når man scrollede eller forsøgte at hente flere materialer.
Fejlen er rettet, så:
- Søgeresultater nu fortsætter med at loade som forventet.
- Brugerne kan scrolle sig igennem flere materialer uden at “ramme en mur”.
**Bemærk**: Søgeordet forbliver nu synligt i søgefeltet, også når man klikker sig ind på et værk. Det er et bevidst valg for at sikre stabil indlæsning af resultater.

### GO-forside synkroniser ikke på flere bibliotekers GO-sites:
Der var et problem, hvor forsiden i GO ikke blev korrekt synkroniseret på tværs af enkelte bibliotekers GO sites.
Det er nu rettet, så forsideindhold igen bliver opdateret og synkroniseret som forventet, og lokale redaktørers ændringer på forsiden slår igennem de relevante steder. 
<br> [CMS-1914](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1914)

