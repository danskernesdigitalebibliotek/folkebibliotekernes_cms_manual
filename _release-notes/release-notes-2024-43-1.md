---
title:  "Release Notes 2024.43.1"
category: "Release Notes"
weight: 367
---

# Flere forbedringer og fejlrettelser

Releasedato: 24-10-2024

Opgraderingen rulles ud til: Redaktørbiblioteker: Produktionssites opgraderes. Webmasterbiblioteker: Kun testsite opgraderes.

## Fejlrettelser og forbedringer

- ”Reserveringer på pause” og mobilvisning: Fejl rettet hvor man på mobil har svært ved at anvende datovælger og handlingsknapper i forbindelse med valg af pauseperiode for reserveringer.

- Reservering: Periodisk fejl rettet hvor der udføres flere reservationer af samme værk for den samme bruger  

- Autosuggest og filtrering: Fejl rettet hvor valgt filtrering i forbindelse med autosuggest (f.eks. kan autosuggest tilbyde en filtrering på materialetype for en forfatter) ikke afspejles i det endelige søgeresultat. 

- Naxos Music Library: Nu fejler værkvisningssiden og søgeresultatet ikke, når der genereres availability-labels for værker fra kilden “Naxos Music Library” 

- FBS API: Nu henter Folkebibliotekernes CMS FBS-data fra ny version af FBS-API. 

- Åbningstider: Nu er det muligt at slette åbningstidskategori. 

- Arrangement: Bedre angivelse af afholdelsestidspunkt og ensretning på tværs af gentagelsesmønster. 

- Artikler fra Infomedia: Fejl rettet hvor det kun er muligt at print side 1. 

- Side: Fejl rettet hvor paragraph-element, der henviser til slettet indhold blokerer for, at man kan ændre på siden. 

- Brugeroprettelse med MitID: Fejl rettet hvor 18-årige, der forsøger at oprette sig som brugere efter autentifikation med MitID præsenteres for fejlmeddelelse ”Ugyldig SSN - Denne SSN er ugyldig”. 

- Søgekampagner bliver nu også vist for redaktionelle brugere, der er logget på Folkebibliotekernes CMS. 

- Åbningstider: Fejl rettet hvor åbningstidsmodal (vises når man vælger ur-ikonet i hovedmenuen) kaster fejl, hvis oprettet filial er slettet, men stadig har tilknyttet åbningstider. 

- Værkvisning: Tallet i ”Biblioteket har XX eksemplarer” under handleknappen ”Find på hylden” på værkvisningssiden blev tidligere styret af lokal konfiguration (admin/config/dpl-library-agency/general-settings) for ”Afhentningsfilialer”. Det styres nu af konfiguration under ”Tilgængelighed”.
