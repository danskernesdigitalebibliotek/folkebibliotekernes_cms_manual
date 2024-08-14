---
title:  "Release Notes 2024.33.0"
category: "Release Notes"
weight: 985
---

# Krav til passwordlængde, bedre orddeling og flere forbedringer til webforms m.m. 

Releasedato: 14-08-2024

## Nye features

- Passwordlængde for medarbejderbrugere: Ved oprettelse af nye medarbejderbrugere er det nu et krav, at adgangskode følger en række standardkrav: Rollerne “Editor”, “Mediator”, og “External system” skal i fremtiden vælge passwords, der er mindst 8 tegn lange, og en blanding af bogstaver og tal. Rollerne “Administrator” og “Local Administrator” skal i fremtiden vælge passwords, der er mindst 12 tegn lange og en blanding af bogstaver og tal. Disse to roller skal desuden vælge et nyt password hver 90. dag.

- Links: Mulighed for at vælge om links åbner i nyt eller samme vindue (tab). 

- Bedre automatisk orddeling i overskrifter. 


## Fejlrettelser og forbedringer

- Brødkrumme: Tidligere var indholdstypen side født med brødkrumme med sidens titel. Den er fjernet, så der kun vises brødkrumme, hvis siden faktisk indgår i en brødkrummestruktur.

- Webformularer: Ord i selectbokse ved formularer skriver ikke længere automatisk med stort begyndelsesbogstav. 

- Webformularer: Unødvendig fejlmeddelelse (Advarsel: Du redigerer i det originale Engelsk sprog for denne webform) vises ikke længere.

- Webformularer: Nu muligt at anvende store bogstaver i form keys. Tidligere var det kun muligt at lave form keys bestående af små bogstaver. Webforms nægtede simpelthen at gemme en nøgle med store bogstaver. Nøgler med store bogstaver er ofte en forudsætning for at sende webformdata til tredjepartsservice f.eks. nyhedsbrevsservice som Ubivox. 
