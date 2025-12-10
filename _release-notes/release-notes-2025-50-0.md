---
title:  "Release Notes 2025.50.0"
category: "Release Notes"
weight: 316
---  

Releasedato: 11-12-2025

**Redaktør**: Produktionssites: 2025.50.0

**Webmaster**: Produktionssites: 2025.48.2, Moduletestsites: 2025.50.0 

## Ny udvikling

•	Ny Avanceret søgning
Avanceret søgning har fået et designløft, hvor der bl.a. er kommet automatiske forslag i søgefelter og afgræsningsmuligheder. Der er lavet filtre efter endt søgning og indgangen til avanceret søgning er blevet gjort tydeligere. Læs mere på [manual-sitet](https://www.folkebibliotekernescms.dk/main/overblik/udviklingsoensker/foraar-2025#avanceret-s%C3%B8gning) 
Vær opmærksom på, at den nye avanceret søgning findes på url’en **/advancedsearch**. Den gamle avanceret søgning er på **/advanced-search**. Det har vi gjort for at linket i jeres indhold til CQL-søgninger ikke går i stykker, da CQL-søgningen også bygger på den gamle avanceret søgning-løsning.

Men hvis I har linket direkte til **advanced-search** på sitet fx i hjælpebåndet i simple search – så bør I sørge for at få rettet linket til det nye, for ellers vil bru-gerne i mellemtiden støde på den gamle avanceret søgning.

I 2026 kigger vi på at revidere og forbedre CQL-søgningen, så der skal vi un-dersøge nærmere, om revideringen kommer til at påvirke jeres indhold fx links til gemte søgninger. Det melder vi mere ud om i 2026.

[CMS-1011]( https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1011) 

[CMS-952](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-952)

[CMS-1144](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1144)
 
[CMS-1475](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1475)

[CMS-1483](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1483)

•	Webmasterbiblioteker: Mulighed for at tilføje CSS-klasser på noder og para-graffer
CMS’et har fået et nyt felt på indhold særligt for webmasterbibliotekerne, “Cus-tom CSS classes”, og tilfører nu automatisk klasse på noder og paragraffer baseret på type og unikt id, hvilket gør det lettere for webmastere at målrette asset injec-tions. [CMS-1734](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1734) 


  
## Forbedringer og fejlrettelser

•	Autosuggest i Simple Search er forbedret
Autosuggest-funktionen i Simple Search er forbedret, så der nu søges på søge-termen med det valgte indeks (titel, emne, forfatter) og ikke kun fritekst. Dette sikrer mere præcise søgeresultater, når brugeren vælger et forslag fra autosuggest.

•	Frasesøgning i Simple Search er gjort muligt
Søgning med anførselstegn i simple search fører nu til en frasesøgning i simple se-arch i stedet for complex search. Det betyder, at det nu er muligt at søge eksakt i simple search. [CMS-1744](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1744) 

•	Visning af antal materialer og reserveringer
Der vises nu tydeligt, hvor mange materialer der er tilgængelige sammen med antal reserveringer i kø på oversigten over ens reserveringer, så brugeren nemmere kan vurdere, hvornår et materiale vil være klar til lån. [CMS-1223](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1223) 

•	Link fra lånerstatus (reserveringer) til værkvisningssiden
Link fra reserveringer i Dit overblik og ved klik på en reservering under Alle reserve-ringer linker til værkvisningen. Bemærk det er ikke implementeret under lån i Dit overblik og under lån under Alle lån – dét kommer i en senere release. [CMS-971](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-971) 

•	Material grid – begrænsning af antal materialer
Material grid manual kan nu vise op til 100 materialer i stedet for 32, og feltet er ændret, så man manuelt indtaster det antal materialer, man vil vise. Det er ikke muligt at taste mere end 100.





