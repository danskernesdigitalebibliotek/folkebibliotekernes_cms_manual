---
title:  "Release Notes 2024.35.0"
category: "Release Notes"
weight: 980
---

# Knap til fornyelse af flere lån fungerer igen, oplysninger i API om arrangement er relevant for billetleverandør og fejl rettet med forsvundne billeder m.m. 

Releasedato: 29-08-2024

## Nye features

- Mobilvisning: Åbningstidsikon vises i stedet for huskelisteikon. 

- Brødkrummer og sider: Hvis man ønsker at slette en side tilknyttet en brødkrumme, skal man nu linke brødkrummen til nyt indhold, inden man får lov til at slette siden. Det sikrer, at der ikke ved en forglemmelse, opstår brødkrummer med døde links. 

- Arrangementer og API: Nyt felt på arrangementer, som sender data med i API om at arrangementet er relevant for billetleverandør. Feltet er default markeret. 

- Event API: Unikke ID'er til priser. 

- Arrangementer og P2B: Hvis arrangementet er udsolgt på P2B, opdateres status på FBCMS. 

- Standardbesked til blokerede brugere vises nu kun i forbindelse med login og forsøg på reservering. 

- Menu til avanceret søgninger er nu kodet semantisk. Dvs. elementet er kodet på en måde, så kodningen bedst muligt afspejler elementets funktion for slutbrugerne. Det betyder bl.a. at elementet let kan afkodes som en menu af skærmlæsere. 




## Fejlrettelser og forbedringer

- Proxy-url: Korrekt encoding af proxy-url'er. Nu kan man lægge proxy-URL'er med tegn som "?" i paragraphelementet Hero, uden at tegnet ændres og linket ikke længere fungerer i praksis.  

- Billeder: Fejl rettet hvor billeder er forsvundet på nogle sites. 

- Arrangementsliste: Fejl rettet hvor afholdte arrangementer fremgår af arrangementsliste. 

- Fornyelse af lån: Forny flere knappen på oversigten /user/me/loans fungerer nu igen. 

- Brugerprofil: Fejl rettet hvor der står tekststrengen "null" i overskriften "Vælg afhentningssted". 
