---
title: "Drupal-modulet Config Ignore Auto"
category: "Webmaster-funktionalitet"
weight: 5
---
Drupal-modulet **Config Ignore Auto** er som standard aktiveret i Folkebibliotekernes CMS og kan ikke deaktiveres. Det er et nødvendigt modul, som alle webmastere bør kende til. Hvis **Config Ignore Auto** ikke var installeret, ville webmasterbibliotekerne miste deres lokale konfigurationer hver uge, når deres sites opdateres.

## Hvad er det?

**Config Ignore Auto** er et Drupal-modul, der opdager, registrerer og bevarer alle ændringer, som du foretager gennem administrationsgrænsefladen i backend. Det kan være en oversættelse du ændrer, eller et flueben, som du sætter på en indstillingsside.  

## Sådan virker det

- **Automatisk sporing**  
  Når modulet er aktiveret, overvåger det ændringer foretaget gennem administrationsgrænsefladen og tilføjer dem til listen over ignorerede konfigurationer.


- **Lokale ændringer bevares**\
  De indstillinger, som Config Ignore Auto tilføjer til sin liste, overskrives ikke når core opdateres. Dvs. de bevarer den værdi, som du har sat. Også selvom standardværdien ændrer sig.


## Hvad skal jeg være opmærksom på
Det er let og hurtigt at ændre en indstilling via administrationsgrænsefladen, men man skal ikke tage let på det, for det kan have vidtrækkende konsekvenser.

- Før logbog over alle ændringer, som du foretager i indstillinger via administrationsgrænsefladen, så du hele tiden har et komplet overblik.
- Overvej nøje om du ændrer en essentiel værdi, som andre dele af sitet afhænger af. Man kan ikke altid vide det, men prøv alligevel.

## Hvilke ricici er der?
- **Ny funktionalitet mangler**: Du risikerer at ny funktionalitet i core ikke bliver synlig på jeres site, fordi en indstilling, som du har sat, forhindrer det. Der kommer ikke nødvendigvis en fejl ud af det, så du opdager det måske slet ikke.
  
- **Jeres site kan ikke opdateres**: Hvis jeres site pga. lokal konfiguration er anderledes end forventet af koden i core, kan der opstå en fejl, så jeres site slet ikke kan opdateres. 





