---
title:  "Release Notes 2024.32.1"
category: "Release Notes"
weight: 986
---

# Login for institutioner fungerer, krav til passwordlængde for redaktionelle brugere og default brødkrumme fjernet fra side 

Releasedato: 07-08-2024

## Nye features

- Arrangementer: Nu muligt at angive pris på arrangement i euro. Konfigureres under /admin/config/dpl-event/settings.

- Passwordlængde for medarbejderbrugere: Ved oprettelse af nye medarbejderbrugere er det nu et krav at adgangskode følger en række standardkrav: Rollerne “Editor”, “Mediator”, og “External system” skal i fremtiden vælge passwords, der er mindst 8 tegn lange, og en blanding af bogstaver og tal. Rollerne “Administrator” og “Local Administrator” skal i fremtiden vælge passwords, der er mindst 12 tegn lange og en blanding af bogstaver og tal. Disse to roller skal desuden vælge et nyt password hver 90. dag.

- Paragraph ”Simple links”: Nyt paragraphelement til listning af links. 

- API til arrangementer: Udstiller nu postnummer for afholdelsessted på diverse arrangementer. 

- Paragraph slider og Indholdsslider: Mulighed for at markere hvilke ord der skal understreges i slideroverskift (grafisk effekt).  


## Fejlrettelser og forbedringer

- Login og visning af udlån for bl.a. institutioner og læsekredse fungerer nu. 

- Tilgængelighed: Unødvendig alt-attribut fjernet fra ikonet for åbningstider. 

- Brødkrumme: Tidligere var indholdstypen side født med brødkrumme med sidens titel. Den er fjernet, så der kun vises brødkrumme, hvis siden faktisk indgår i en brødkrummestruktur. 

- Paragraph Materialekomponent automatisk: Skjules nu i slutbrugervisningen, hvis den er konfigureret med materialesøgning uden resultater. 

- Redaktionel søgning på arrangementer: Redaktører har nu mulighed for at søge efter et arrangement under admin/content/eventseries. Tidligere kastede sitet en fejl ved søgning. 

- Fallback på materialekomponenter:  Hvis man f.eks. viser en bog-udgave af et materiale og den pludselig ikke findes længere vil materialekomponenten falde tilbage på materialetypen for best representation for værket, som viser det som er muligt.

- Fejl rettet hvor brugere med rollen ”Local_administrator” var forsvundet fra oversigten over redaktionelle brugere.

- Visning af materiale: Fejl løst hvor materialer under ”Udgave” har forkert status på availability-label.  

