---
title:  "Release Notes 2025.25.0"
category: "Release Notes"
weight: 333
---  

### Fejlrettelser og opgradering til Drupal 10.4.  

Releasedato: 19-06-2025

**Redaktør**: Produktionssites: 2025.25.0

**Silkeborg, Albertslund og København (Go-piloter)**: Produktionssites: 2025.25.0 Moduletestsites: 2025.25.0

**Webmaster**: Produktionssites: 2025.24.1 Moduletestsites: 2025.25.0

## Nye features
- Avanceret søgning: Sortering af søgeresultatet er nu gjort mulig ved feltsøgning og CQL-søgning efter seneste/ældste udgivelsesdato, efter alfabetisk rækkefølge og efter forfatternavn. Bemærk, at sortering på udgivelsesdato sorterer efter seneste/ældste udgave, ikke seneste/ældste oprindelige udgivelsesår/workyear, som er dét, der vises i søgeresultatet.
  
    Vi har dog fundet en potentiel fejl i DBCs FBI-API som gør, at der mht. udgivelsesdato ikke sorteres efter rækkefølgen af de udgaver, der findes i den lokale beholdning, men efter hvad der findes i nationalbibliografien (som på Bibliotek.dk). Det betyder, at rækkefølgen af nogle     værkposter i søgeresultatet vil give indtryk af, at der ikke sorteres korrekt, men det skyldes altså blot, at det enkelte bibliotek ikke har den seneste (eller ældste) af værkets udgaver i beholdning. Vi er i dialog med DBC omkring en løsning på dette, men har besluttet at rulle     sortering af søgeresultatet ud med det samme, da det er en meget efterspurgt søgeforbedring.


## Fejlrettelser og opgraderinger
- E-bøger og lydbøger: Knapperne ”Lån e-bog” og ”Lån lydbog (Online)” under ”Udgaver” fungerer nu igen.
  
- Afspiller (Læs og lyt): Nu er det også muligt at betjene afspilleren hvis man udelukkende anvender tastatur. Afspilleren lever derfor op til de krav der stilles i lov om webtilgængelighed for offentlige websites.

- Drupal opgraderet til 10.4 og tilpasning så webmasterne stadig kan uploade, installere og opgradere moduler via administrativ backend efter opgraderingen. 

