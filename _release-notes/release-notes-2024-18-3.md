---
title:  "Release Notes 2024.18.3"
category: "Release Notes"
weight: 996
---

# Bedre og mere logisk grænseflade til at oprette og administrere gentagne arrangementer, overblik for slutbrugerne over arrangementer i samme serie og forfatternavn på artikler

## Nye features

- Arrangementer: Hvis et arrangement er en del af en serie, vises henvisninger til kommende arrangementer i serien på arrangementet. Midlertidigt vises de på samme måde som ”stacked events” på /arrangementer. Der arbejdes på ny visning. 

- Arrangementer: Mere logisk og overbliksskabende visning og redaktionelle arbejdsgange ved oprettede arrangementer i administratorgrænsefladen. Bl.a. vises et arrangement kun en gang på oversigten /admin/content/eventserie, selvom det er en arrangementsserie. Et tal i oversigten indikerer hvor mange instanser af arrangementet, der er oprettet. Arrangementer i en serie kan redigeres via fanen ”Edit instances” under arrangementet. 

- Paragraph Material Grid tillader nu en søgestreng længere end 255 tegn. 

- Paragraph Card Grid Manual: Nu er muligt at indsætte indholdstypen ”Side”. Tidligere har det kun været muligt at indsætte indholdstypen ”Artikel”. 

- Forfatternavn på Artikler: I forbindelse med oprettelse af ny administrativ bruger i systemet er det et krav at brugerens navn indsættes i forbindelse med oprettelsen. Navnet bruges default som skribentnavn på oprettede artikler. 

- Proxyindstillinger: I administratormenuen er der nu et link til proxyindstillinger admin/config/services/dpl-url-proxy. Linket findes under ”Indstillinger” > ”Biblioteksindstillinger” > ”Proxyindstillinger”.  

- Brødkrumme: Bedre styling af brødkrumme. 




## Fejlrettelser og forbedringer:

- Editor/Wysiwyg: Nu kun ét standard tekstformat med alle aktive formateringsmuligheder. Tidligere har redaktører været nødt til at skifte fra formatet ”begrænset” til ”standard” i forbindelse med oprettelse. 

- Editorrollen har nu adgang til ”Struktur” i administratormenuen.

- Paragraph Links: Links oprettet med paragraph-elementet fungerer nu igen. 

- Sprogindstillinger for administrative brugere er default dansk. 

- Mobilvisning: Der er nu begrænsning på hvor meget man kan zoome ud på siden. 

- Arrangement: Daglige og årlige tilbagevendende begivenheder er fjernet, da de kan oprettes med andre gentagelsestyper. 

- Menupunkt: Tilføjede menupunktet vises nu med det samme i grænsefladen. Tidligere har det været nødvendigt at tømme cachen. 

- Footer: Vises nu også, når man tilgår sitet på mobil. 


