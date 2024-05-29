---
title:  "Release Notes 2024.22.1"
category: "Release Notes"
weight: 994
---

# Retvisende fejlbesked ved indtastning af forkert pinkode, bedre layout på oprettelsesformularer til nye lånere og en lang række tilgængeligheds- og fejlrettelser. 

## Nye features

- Udvidelse af API: Nu med salgs- og admin-URL’er som del af data.   


## Fejlrettelser og forbedringer

- Tilgængelighed: Overskriftshierarkiet på elementer listet som breadcrumb children er nu korrekt. Overskriften på afsnittet er H2 og de enkelte overskrifter på breadcrumb children er H3.
 
- Tilgængelighed: Paragraph Navigationskomponent og Materialekomponent. Hvis man vælger knappen ”Show all” med tastaturnavigation vil keyboardfokus blive sendt videre til næste element og ikke som tidligere til footeren.

- Tilgængelighed: Søgning og filtrering: Skjulte overskrifter gør det nemmere for skærmlæserbrugere at afkode, hvad formålet og handlemuligheder er for de forskellige filtre på søgesiden.
  
- Tilgængelighed: Skærmlæserbrugere får nu annonceret ændring i overskrift i forbindelse med filtervalg ved søgninger hvor overskriften opdateres for f.eks. at vise status eller resultatet af søgning.
  
- Tilgængelighed: Felter til avanceret søgning har nu skjulte labels.
  
- Tilgængelighed: Felter til angivelse af mobilnummer og e-mail har nu korrekt type (type=”email” og type=”tel”). Det betyder at browserne kan autoudfylde, at skærmlæserbrugere bliver bedre guidet på vej og det er garanteret at korrekt datatype sendes til Cicero.

- Brugeroprettelse: Ikke længere krævet at man udfylder mobilnummer i forbindelse med brugeroprettelse.
  
- Arrangementer: Oversættelse: Ugedag på serie af arrangementer er nu på dansk.
  
- Tilgængelighed: Footeroverskrifter er nu H2.
  
- Åbningstider: Rettelse af fejl hvor enkelte biblioteker ikke har kunnet se oprettede åbningstider.

- Materialer: Listede udgaver indikerer ikke længere, at de er klikbare ved mouseover.
  
- Reservationsliste: Håndtering af fejl i konfiguration af liste.

- Interesseperiode: Valg af 1 måneds interesseperiode giver ikke længere interesseperiode på 365 dage.

- Ændring af pinkode: Fejlbesked ved forkert længde pinkode er nu retvisende.

- Oprettelsesformular til nye brugere: Bedre styling af oprettelsesformular. 
