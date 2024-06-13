---
title:  "Release Notes 2024.24.0"
category: "Release Notes"
weight: 992
---

# Flere data i indholds-API, mulighed for at angive adresser i andre lande på filialer og fejl rettet hvor boks til info om gebyrer blev vist for alle lånere 

## Nye features

- Filialer: Mulighed for at angive adresser i Tyskland, Færøerne, Grønland og Island i forbindelse med oprettelse af filialer. 

- API: Indhold i første brødtekstfelt på arrangementer udstilles nu også i API. 

- API: Oplysninger om hvor mange billetter der sælges til et arrangement (kapacitet) udstilles nu også i API. 

- API: Oplysninger om filial på arrangement udstilles nu også i API. 

- API: Tags på arrangementer udstilles i API. 


## Fejlrettelser og forbedringer

- Arrangement: /arrangementer viser nu ikke længere forældede seriearrangementer, som er en del af et seriearrangement, med aktive arrangementer. 

- Åbningstider: Fejl hvor åbningstiderne ikke vises for lånere som er logget ind er nu rettet. 

- Paragraph Slider/Content slider: Fejl rettet hvor slider kaster fejlmeddelelse og låser den side som den er en del af, hvis slideren indeholder afholdte arrangementer. 

- Burgermenu: Brugere af iPad og andre enheder med mellemstore skærme kan nu også åbne burgermenuen. 

- Dashboard: Boks til meddelelse om mellemværende vises ikke for lånere uden mellemværende.  

- API: Korrekte tidszoner nu knyttet til tidsangivelser på arrangementer. 

- Tilgængelighed: Fokusrækkefølge for filtre i modal bevarer nu meningen for slutbrugere, som anvender skærmlæsere og tastaturnavigation. 

- Tilgængelighed: Link til avanceret søgningen var tidligere kodet som en knap (<button>) med role=”menuitem”, uden at have den forældre som var forudsætning for rollen. Det er nu rettet så elementet er kodet som et link og forælderen til elementet har korrekt rolle. 

- Tilgængelighed: Inputfelter overholder nu krav til kontrastforhold for grænsefladekomponenter. 

- Tilgængelighed: Filtrene under ”Flere filtre” er nu kodet som elementer i lister. Det betyder at skærmlæserbrugere får annonceret antallet af filtre for de forskellige filterkategorier og flugter også med måden filtre er kodet andre steder på sitet. 


