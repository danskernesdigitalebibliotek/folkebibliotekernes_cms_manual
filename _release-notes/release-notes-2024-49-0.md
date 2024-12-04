---
title:  "Release Notes 2024.49.0"
category: "Release Notes"
weight: 355
---  

# IMS-placeringsoplysninger, data om samarbejdspartner og rettelser til arrangementsfeed til appen ”Biblioteket”.  

Releasedato: 05-12-2024

Opgraderingen rulles ud til: 
Redaktørbiblioteker: Produktionssites opgraderes til 2024.49.0. 
Webmasterbiblioteker: Testsite opgraderes til 2024.49.0. 

## Nye features 
- IMS-placeringsoplysninger: Biblioteker som har Intelligent Materialestyring (IMS) vil nu på materialeposter (under bl.a. ”Find på hylden”) få vist placeringsoplysninger baseret på data fra IMS. 

- API for arrangementer: Indeholder nu mulighed for at udstille data (field_event_partners) om evt. samarbejdspartnere på et arrangement.

- Logging: Logging af redaktørevents tilføjet. Sitet logger nu, når der ændres på en bruger - f.eks. redigering af e-mail. Eksempel: Bruger ændrer sin e-mail fra nino@email.com til ninoooo@email.com. 

- Arrangementsfeed til app: Indeholder nu oplysninger om pris på arrangement. 

- Arrangementsfeed til app: Indeholder nu oplysninger om link til ekstern billetleverandør, hvor billetter kan købes. 

## Fejlrettelser
- Arrangementsfeed til app:  Specialtegn i feedet er nu encodet. F.eks. er ”&” encodet som ”&amp;” for ikke at skabe fejl i forbindelse med importen af arrangementer til appen.

- API for arrangementer: Hvis man som redaktør opdaterer en eventserie vil de enkelte instanser nu også figurere som opdaterede i API for arrangementer (se  værdien ”updated_at” i API). Det betyder at eksterne billetleverandører i de berørte tilfælde kan se hvornår et arrangement er opdateret og holde egne oplysninger om arrangementet ajour, så snart der sker ændringer.  
