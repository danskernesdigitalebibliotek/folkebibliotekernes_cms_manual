---
title:  "Release Notes 2024.20.2"
category: "Release Notes"
weight: 995
---

# Række af gentagne åbningstider kan nu slettes på en gang, API til redaktionelt indhold tilgængelig og bibliotekslogo linker på mobilvisningen også til forsiden. 

## Nye features

- Paragraph Brødtekst: Bedre formatering af elementet lister (<ul> <ol>)  i slutbrugervisningen. 

- Paragraph: Bedre standardoplistning af paragraphs til redaktørerne med mulighed for at filtrere på prædefinerede kategorier for de forskellige typer af paragraphs. 

- Cache: Kun lokal_admin kan rydde cachen. Funktionen er tilføjet beskrivende tekst, der beskriver konsekvenserne ved rydning af cache. 

- API til redaktionelt indhold: Dokumentation på API under admin/config/services/openapi/swagger/rest. Alle arrangementer kan ses under /api/v1/events. 

- Åbningstider: Bedre muligheder for at administrere gentagne åbningstider herunder mulighed for at slette række af gentagne åbningstider på en gang og slette en enkelt åbningstid, som er en del af en række.  

- Paragraph Nyhedskomponent: I stedet for navn på indholdstypen dvs. ”Artikel” vises artiklens kategori. Hvis ingen kategorier er tilknyttet vises ”Artikel” som tekst. 

- Tags: Mulighed for at oprette nye tags direkte fra artikler og arrangementer. 

- På redigeringsgrænsefladen til de enkelte indholdstyper er link til ”Filer” erstattet med link til mediebiblioteket.

- Gebyr og erstatninger: Advarselsbesked om gebyrer ved overskredne lån øverst på siden. Linker til informationsside. 


## Fejlrettelser og forbedringer:

- Arrangement: Efter man har sorteret på filial under /arrangementer vises arrangementer i en serie igen korrekt. Før manglede oplysninger på arrangementer og alle arrangementer i en serie af gentagne arrangementer blev ikke vist.  

- Arrangementer: Teasertekst (tekst på farvet boks som erstatter billede) vises nu også på enkeltstående arrangementer. 

- Paragraph Nyhedskomponent – automatisk: På mobilvisninger lægger tekst sig ikke længere henover titelbillede. 

- Paragraph Materialekomponent: Forsidebilleder til Lydbøger har nu samme størrelse, som andre forsider i Materialekomponenten. 

- Artikler: Formidler har nu mulighed for at publicere artikler oprettet med udgangspunkt i afpubliceret skabelonartikel. 

- Arrangementer: Fejl hvor seriearrangement uden grund opdeles i listevisningen under /arrangementer er nu løst. 

- Bibliotekslogo: Linker nu også til forsiden på mobilvisningen. Logoet er tilføjet tilgængelig tekst (aria-label), så brugere af skærmlæsere oplæses relevant information. 

- Listevisninger: Bedre trunkering af tekst i diverse listevisninger under f.eks. /arrangementer og /artikler.

- Værkvisningssiden fejler for specifikt værk "Dramatis Personae", work-of:150086-netmusik:BIS-2067. Fejlen er nu rettet.
  
- Tilgængelighed: Rolle tildelt div-element, der åbner modal med detaljevisning for titel vist i gruppemodal.

- Tilgængelighed: Ikke længere dublikerede ID'er i modal for lån, der snart skal afleveres.

- Tilgængelighed: Avanceret søgning: Ved brug af keyboardnavigation. Efter sletning af række med inputfelt sættes fokus aktivt. 

- Tilgængelighed: Søgning og filtrering: Tom alt-attribut indsat på close-ikon ved valgt filter.

- Tilgængelighed: Label “MATERIALETYPE|STATUS” får nu kun rollen knap, hvis det er muligt at vælge mellem forskellige materialetyper. Vigtigt for brugere af skærmlæsere, som ellers kan få indtrykket, at der kan interageres med knap, som faktisk kun er label.
  
- Tilgængelighed: Skjult mobilmenu kan ikke længere tildeles fokus på desktopvisning. Har tidligere fungeret som tastaturfælde. 

- Tekstbeskeder ved sletning af materiale: Tekster skifter nu mellem ental og flertalsform alt efter om man vælger ét eller flere materialer til sletning

- Ved søgning på " " eller "null" vises der vejledende tekst







