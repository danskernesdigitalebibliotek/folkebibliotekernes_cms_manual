---
title:  "Release Notes 2026.8.0"
category: "Release Notes"
weight: 311
---  
Releasedato: Bemærk denne release indeholder også 2026.8.0, som af tekniske årsager ikke kom ud som planlagt. 

**Redaktør**: Produktionssites: 2026.10.0
**Webmaster**: Produktionssites: 2026.6.0, Moduletestsites: 2026.10.0 (den 12/3 vil webmasterbibliotekerne få både 2026.8 og 2026.10 på deres produktionssite)

## Ny udvikling

•	**Muliggørelse af visning af lokale emneord samt færøske og grønlandske emne-ord: [CMS-1496](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1496)** <br>
Bibliotekerne kan nu få vist egne lokale emneord samt emneord på færøsk og grønlandsk på værkvisningssiden, så materialer kan beskrives og findes mere præ-cist lokalt. Klik på disse særlige emneord resulterer i en afgrænset søgning i avan-ceret søgning, da disse ikke på samme måde som DBCs kontrollerede emneord kan gøres søgbare ved hjælp af facettering i simpel søgning. Bemærk: Dette skal konfigureres under Biblioteksindstillinger > Generelle indstillinger.



•	Find på hylden: Fjerne nameSort og erstatte med alle opstillingsdata med shelf-mark.shelfmark og shelfmark.postfix: [CMS-1056](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1056)

“Find på hylden”-funktionen bruger nu de fulde opstillingsdata fra bibliotekssy-stemet. Det giver mere præcise henvisnigner til opstillinger og gør det nemmere for både personale og borgere at finde materialer fysisk. Ændringen er gjort mulig på baggrund af en ændringsanmodning til KOMBIT og DBC om at udvide shelf-mark-data i FBI API’et.


•	Ny VIP-profil implementeret på GO:
Jeres GO-site har fået implementeret en ny VIP-profil (fbcms-go), der sikrer, at kun de rette materialer dukker op i søgningen. VIP-profilen tager stadig udgangs-punkt i jeres lokale beholdning samt digitale bøger og podcasts fra eReolen. De vi-ste materialetyper er fysiske bøger, e-bøger, lydbøger (online) og podcasts. I et af de kommende sprint vil værkvisningen blive tilrettet, så også tegneserier og gra-phic novels (fysiske såvel som digitale) kan vises. I skal ikke foretage jer noget for at det virker, og lav endelig ikke ændringer i VIP-profilen. 


•	Find nærmeste filial på: /biblioteker
Brugerne kan nu lettere finde deres nærmeste bibliotek eller filial via /biblioteker-siden. Det gør det nemmere for brugerne at blive opmærksom på deres lokale fili-al, hvad enten de er nye brugere eller f.eks. flytter adresse indenfor kommunen. Bemærk: “Brug min placering” kræver, at brugeren giver tilladelse til lokation i browseren. Adressesøgningen kan også aktiveres/deaktiveres under Biblioteksind-stillinger > Generelle indstillinger, og filiallisten fungerer fortsat uden adressesøg-ning, hvis man ønsker det.


## Forbedringer og fejlrettelser

•	Visse poster kan ikke fremsøges i simpel søgning
[CMS-1915](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1915)
En fejl, hvor bibliotekets fysiske materialer ikke dukkede op i simpel søgning på udvalgte sites, er rettet. Materialerne vises nu igen ved alle typer søgninger.

•	Episodenr. og serienr. vises forkert i låne- og reserveringsoversigt:
[CMS-1219](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1219)
Nu vises sæson-, episode- og serienummer korrekt for titler i brugerens låneover-sigt, så det er nemmere at se præcis hvilken del af en serie, der er lånt eller reser-veret eller findes et mellemværende på.

•	Lektørudtalelse ("reviewbylibrarian") under "Anmeldelser" på værkvisningssi-den viser "null" i stedet for udgivelsesdato:
Fejlen hvor der stod “null” i stedet for udgivelsesdato ved lektørudtalelser er ret-tet.

•	Disc nr. på tv-serier vises i titlen på værkvisningssiden efter sæson nr.
Titler på tv-serier viser nu også disc-nummer efter sæsonnummeret på værkvis-ningssiden. Det hjælper både personale og brugere med at adskille poster med de forskellige discs i en tv-serie.

•	GO-forside synkroniser ikke på flere bibliotekers GO-sites
En fejl, hvor forsiden i GO! ikke blev opdateret korrekt på nogle biblioteks-sites, er nu løst. Ændringer på forsiden slår nu mere stabilt igennem.

•	Webmasterbiblioteker: Ignorer oversættelser i config import/export
[CMS-1829](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1829) og [CMS-1942](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1942)
Når konfiguration importeres/eksporteres mellem sites, bliver sproglige oversæt-telser nu ikke overstyret. Det mindsker risikoen for, at lokale oversættelser bliver overskrevet ved tekniske opdateringer.

