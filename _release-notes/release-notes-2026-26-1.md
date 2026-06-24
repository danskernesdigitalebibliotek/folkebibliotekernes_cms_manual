---
title:  "Release Notes 2026.26.1"
category: "Release Notes"
weight: 303
---  

Releasedato: 25-06-2026

**Redaktør**: Produktionssites: 2026.26.1  
**Webmaster**: Produktionssites: 2026.24.1, Moduletestsites: 2026.26.1


## Ny udvikling

- Arrangementer: ”Målgruppe” er tilføjet som ny taksonomi på arrangementer. Brugere kan nu filtrere arrangementer efter målgruppe (fx børn, unge, voksne). Målgruppe kan vælges ved oprettelse af arrangementer, vises på arrangementssiden og er tilgængelig som filter i arrangementsoversigten.[CMS-943](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-943) 
I kan læse mere i CMS-Manualen, om hvordan I opretter målgrupper og føjer dem til arrangementer: [Målgrupper i Manualen](https://www.folkebibliotekernescms.dk/main/indhold/indholdstaksonomier/#m%C3%A5lgrupper)   

- Ændringer til arrangements API’et: Vi har tilføjet audiences, som udstiller de målgrupper I tildeler arrangementerne.

- Arrangementer: Redaktøroplevelsen for valg af lokation ved oprettelse af arrangementer er forbedret. "Fysisk eller Online" vises nu øverst, og bibliotek og "anden lokation" er samlet i én boks, så det er tydeligt, at de hænger sammen. Overskriften er ændret til "Arrangements lokation", og "Anden lokation" er som standard slået fra, indtil redaktøren aktivt tilvælger den. Filial er blevet obligatorisk. Det betyder at hvis I redigerer et arrangement uden filial eller I opretter nye arrangementer så skal I sætte en filial på. 

<br>

## Forbedring og fejlrettelser

- Fejl rettet, hvor lånere ikke kunne ændre perioden for deres reserveringspause ved login med MitID. Fejlen skyldtes, at FBI-adapteren krævede en PIN-kode, som ikke er tilgængelig ved MitID-login. Rettelsen dækker alle profilopdateringer (email, telefon, afhentningsfilial, interesseperiode, pinkode og reserveringspause) for begge logintyper.

- Fejl rettet, hvor "Sted" ikke blev vist på arrangementsinstanser i en serie, selvom serien havde et sted angivet. Fejlen skyldtes forkert nedarvningslogik, der fejlagtigt satte et tomt felt på instanser, som ikke var markeret som online. De eksisterende berørte instanser bliver rettet automatisk. [CMS-2047](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2047) 

- Fejl rettet, hvor materialer fra blacklistede filialer blev vist i simpel søgning og avanceret søgning. Blacklist fungerede korrekt i CQL-søgning, men ikke i de øvrige søgetyper. Materialer fra blacklistede filialer filtreres nu korrekt fra i alle søgetyper. [CMS-2058](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2058) 

- Mulighed for kloning af arrangementer er blevet tilrettet, så det gerne skulle virke nu. [CMS-1000](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1000)

•	Værkvisningssiden: "Skøn-/faglitteratur"-linjen vises ikke længere på værkvisningssiden, hvis FBI-API svarer “Vides ikke” for det pågældende værk.




