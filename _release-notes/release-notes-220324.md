---
title:  "Release Notes 220324"
category: "Release Notes"
weight: 1000
---

## Nye features

- Artikelliste: Under /articles lister oprettede artikler. Der er mulighed for at filtrere på artikelkategorier.
- Redigeringslås på alle indholdstyper: Forhindrer at flere redaktører redigerer i det samme indhold samtidig. Alle redaktører har mulighed at lukke en lås op, i tilfælde at låsen er aktiv uden grund.
- Automatisk materialeparagraph: Tilføj en liste med materialer til din artikel eller anden indholdstype. Listen genereres på baggrund af CQL-søgestreng.
- Manuel materialeparagraph: Tilføj en liste med materialer til din artikel eller anden indholdstype. Listen genereres pba manuelt indsatte ID'er på den enkelte værker f.eks. work-of:870970-basis:136336282
- Anbefalingsparagraph (recommendation): Tidligere har det kun været muligt at linke til et værk og ikke til de specifikke materialetyper værket eksisterer som. Det er det nu. F.eks. kan man henvise direkte til en e-bog.
- Uret i headeren kan nu konfigureres: Bestem hvad uret skal linke til under /admin/config/dpl-library-agency/general-settings og feltet "Opening hours link".
- Filialliste: /branches lister oprettede filialer.
- Arrangement kan tilknyttes filial i forbindelse med oprettelse via feltet "Branch". Der er oprettet separat opgave på at adresse fra filialen skal bruges i relation til arrangementet.
- Filialnavn vises nu i relation til arrangementer i diverse lister.
- Arrangementer kan nu afpubliseres automatisk: Under /admin/config/dpl-event/settings kan redaktører nu konfigurere hvornår arrangementer som udgangspunkt skal afpubliceres.
- Knap til billetsystem viser nu retvisende tekst for gratisarrangementer. Default tekst er nu "Get tickets"/"Hent billet" ved gratis arrangementer, som kræver billet/tilmelding.
- Hero-paragraph: Det store billede i hero-paragraphen linker nu også til det indhold, der formidles og fonttypen er korrekt.


## Fejlrettelser:

- Arrangementer: Tekststørrelse på arrangementer er gjort større på mobilvisning
- Tilgængelighed: Arrangementer i arrangementslideren forsvinder ikke længere ud af viewport ved keyboardfokus.
- Tvungen alt-tekst på billeder er fjernet.
- Pargraphen "Linkboks" kan nu også linke til eksterne lokationer.
- Roller og rettigheder: Administrator har nu også rettigheder til at redigere i footeren.
- Roller og rettigheder: Roller udover admin kan nu også anvende skabeloner.
- Ensretning af placering af felter på tværs af indholdstyper, serie og enkeltinstanser.
- Arrangement: Beslægtede felter til indsættelse af billetkategori og link er nu placeret ved siden af hinanden.
- Filialer kan nu oprettes uden der i første omgang kastes fejlmeddelelse.
- Arrangementsliste: Layoutet skrider ikke længere i toppen af arrangementslisten.
- Paragraph: "Card grid automatic" og "Card grid manual" viser nu udelukkende indholdstypen artikler.
  - Bemærk at dette hele tiden har været meningen, men en fejl gjorde at man kunne indsætte andre typer. Dette har været meldt ud da fasen startede og står i ”Status til piloter”. Der kommer senere en særskilt komponent til at fremhæve arrangementer
- Artikler: Nu vises dato kun én gang på artikler.

## Kendte fejl:
Generelt set løser denne release de fejl der var registrerede op til pilotfasen gik i gang. Derfor kan I forvente at størstedelen af de fejl I har indmeldt IKKE er rettet endnu, men forventes med i næste release. Der er dog en del af jeres indmeldte fejl, som også blev fundet af vores testere i ugen inden pilotfasen, og derfor er nået at blive rettet til denne release.
- Accordion formattering: Styling. Formatering i editor vises ikke korrekt i slutbrugervisningen. Det gælder f.eks. afsnitsformatering, styling af overskrifter og brødtekst der ikke renderes efter bogen.- Nogle gange mangler mellemrum mellem paragraphs, ex mellem link og accordion- Paragraph media: Tekst til byline lægger sig over redigeringsikoner. Preview af tekst til byline lægger sig over ikoner der giver adgang til at redigere billede.- Artikelliste: Enkelte kategorier vises selvom der tilsyneladende ikke er indhold under kategorien. - Paragraph: Overskrifter på accordions er default h3. Skal være h2.- Arrangementer: Redigeringsmulighed mangler på billederne i sidebaren til højre
- iOS generelt:
  - Arrangement: Mobil (iOS): Skalerer ikke i forhold til mobilvisning.
  - Mobilvisning (iOS): Scrollbar i flere dimensioner.
  - Paragraph: Material grid: Mobil (iOS): felter forskellig størrelse
- Branch: Unødvendige prikker i liste-visningen
- Paragraph: "Card grid - automatic" kan pt. ikke trække indhold ind fra mere end et tag ad gangen.
- Footer: Det kræver to klik at gemme ændringer
- Beskrivelsestekst til Sider mangler. Når jeg går ind under /admin/content/add savner jeg den lille beskrivelsestekst til hvad en Side er, ligesom der er under de andre indholdstyper
- Arrangementer: Brødtekst skal flyttes op under descriptionfeltet på arrangementer. Som ønsket i DDFFORM-187: skal brødtekstfeltet ligge umiddelbart under descriptionfeltet på arrangementer. Ellers sker det at redaktørerne lægger alt tekst ind i descriptionfeltet og det kan designet ikke håndtere.
- Arrangement: Weekly events: Ingen slutdato for serie af gentagne arrangementer. Når man opretter Weekly event vises på frontend at arrangement afholdes hver tirsdag 10:00-12:00 men indtil hvilken dato? Det burde vises at arrangement afholde hver tirsdag mellem 10 og 12:00 indtil 25. marts 2024 
- Arrangementer: Styling: Afstand mellem tags og brødtekst følger ikke design


