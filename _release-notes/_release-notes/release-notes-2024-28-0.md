---
title:  "Release Notes 2024.28.0"
category: "Release Notes"
weight: 988
---

**Denne release indeholder forskellige fejlrettelser.**

Releasedato: 03-07-2024

## Fejlrettelser

- Fjernlån fra Det Kongelige bibliotek og andre fagbiblioteker vises nu i lånerstatus – dog uden materialetype.
  
- Mulighed for at tilføje "holding", "location" og "sublocation" ved avanceret søgning under rediger CQL.

- Kontaktformular: Bekræftelsesmail slår nu igennem.

- Webformularer/kontaktformularer sender nu også indhold fra felter til modtagermail.

- Mange enkel reserveringer foretaget på én gang i Cicero LMS opfattes ikke længere som en parallelreservering.

- Tilgængelighed: Paragraph material grid: Alt-attribut med tilgængelig tekst indsættes for billeder der fungerer som links.

- Periodisk fejl ved valg af billeder til Media Paragraph og teaserbillede. Fejl der gjorde at indsatte billeder i media paragraph og teaserbillede indimellem erstattes af andre billeder fra mediebiblioteket.

- Problem med sidebørn der kom til udtryk, hvis man fra “brødkrumme strukturen” tilføjede et stykke indhold i træet, og så ikke bagefter gik ind og gemte det indhold, så blev indholdet ikke opdateret.

- Fejl der gjorde at brødkrumme dukkede op på enkelte instanser af arrangementsserie

- Styling: Ugevælger i Åbningstider er nu stylet korrekt.

- Fejl ved at slette materialer på material grid manual, hvor det kun var muligt at slette det sidste materiale.

- Fejl på ArrangementsAPI der fejlede hvis der sendes invalid eventstate med.

- Artikler i card grid automatic og content slider automatic sorteres nu efter nyeste udgivet.

- Mulighed for at dele billeder af arrangementer på Facebook

- Recommendation paragraph: Fejl der ændrede materialet hvis man har flere anbefalinger på en side.

- Byline på filtered event list er nu fjernet.

- 8 biblioteker (Fredensborg, Frederiksberg, Halsnæs, Horsens, Næstved, Norddjurs, Tårnby og Thisted) manglede billetkapacitet på deres arrangementer.
  

  ## Udvikling

- Mulighed for at markere et citat i en tekst. 

- Paragraph: Card grid automatic/nyheds- eller artikelkomponenten linker nu til oversigt over nyheder/artikler.

- Bannerparagraph er blevet udviklet (vil blive beskrevet yderligere i manualen).

- Redigér-knap på skabeloner.

- OR mellem tags og mellem kategorier i automatiske komponenter.

- Mulighed for at vælge om subtitles/teasertekst skal vises i en breadcrumb children paragraph.

- Fjerne gamle arrangementer fra API.

- Materialekomponentvælger viser ikke valgte materialer med forkerte typer i backenden. 

- Inspirationsslider viser ikke indhold med samme filial, nyeste artikler og næste arrangementer.

- Opdatering af Drupal til 10.3.

