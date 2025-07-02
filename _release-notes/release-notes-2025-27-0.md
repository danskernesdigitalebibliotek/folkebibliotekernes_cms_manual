---
title:  "Release Notes 2025.27.0"
category: "Release Notes"
weight: 331
---  

###  Firstaccessiondate-søgekode bliver til firstaccessiondateitem-filter

Releasedato: 03-07-2025

**Redaktør**: Produktionssites: 2025.27.0

**Webmaster**: Produktionssites: 2025.26.1 / 2025.27.0, Moduletestsites: 2025.27.0

Følgende webmasterbiblioteker overgår ekstraordinært efter aftale til 2025.27.0 også på produktionssites:
- Tårnby
- Herning
- Sønderborg
- Ballerup
- Albertslund
- Roskilde
- Odense
- Aalborg
- Faxe

Følgende webmasterbiblioteker har ønsket at blive på deres normale udrulningsplan, dvs. deres produktionsites får 2025.26.1:
- Aarhus
- København
- Silkeborg
- Sydslesvig

## Nye features
- Filtering på firstaccesiondateitem: CQL-søgning under Avanceret søgning understøtter nu filtrering af et søgeresultat på baggrund af "firstaccesiondateitem", som er mere nøjagtig ift. udstilling af nyindkøbte materialer end søgekoden "firstaccessiondate", som DBC derfor også nedlægger. **Bemærk dog, at DBC på henvendelse fra Det Digitale Folkebibliotek har udskudt nedlæggelsen af søgekoden "firstaccessiondate" fra d. 1. august til 1. oktober**. Derfor skal rettelser af links og material grids, som bruger "firstaccessiondate"-søgekoden fremfor det nyere "firstaccesiondateitem"-filter, nu i stedet være rettet senest 1. oktober på ens CMS-side. 
- Tabel over brug af firstaccessiondate: Til brug ved udskiftning af firstaccessiondate-søgekoder til firstaccessiondateitem-filteringer er der udviklet en interaktiv tabelvisning, der samler alle sider og paragrahs på de pågældende sider, som benytter sig af "firstaccessiondate"-søgekoden, sådan at man kan springe direkte fra tabellen og over til redigering af siden, hvor man har benyttet "firstaccessiondate". Når tabellen er tom, betyder det helt enkelt, at man ikke har nogen material grids på sin side, der benytter "firstaccessiondate". Tabellen tilgås via: wwww.BIBLIOTEKSDOMÆNE.dk/admin/content/firstaccessiondate, og kan bl.a. sorteres på titel på sidene og seneste opdateringstidspunkt.

## Fejlrettelser og opgraderinger
- Duplikerede medier: En tidligere fejl gjorde, at medier fra importeret indhold fra Delingstjenesten blev duplikeret igen og igen i mediegalleriet. Det blev også løst ved en tidligere release, men med denne release er de duplikerede medier så også fjernet.
- Delingstjenesten: Login-knappen i hovedmenuen, som ikke skal bruges på delingstjenesten.dk og blot er arvet fra den alm. CMS, er nu fjernet på delingstjenesten.dk.
- GO: Relative links fra GO til bibliotekets alm. CMS-side linker nu korrekt videre fra GO til den alm. biblioteksside.
- Tilgængelighed ift. søgning: Fokus ift. oplæsning holdes nu altid på valgt titel blandt søgeforslagene, fremfor fejlagtigt at læse øvrige elementer op på siden mellem oplæsning af søgeforslagene.
