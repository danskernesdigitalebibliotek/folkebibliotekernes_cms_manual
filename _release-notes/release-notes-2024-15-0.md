---
title:  "Release Notes 2024.11.0"
category: "Release Notes"
---

**Denne release gør det let for brugerne at finde rundt på dit site med brødkrumme og slutbrugervenlige URL'er. Nu mulighed for at redigere servicemenu.**

2024.15.0 Release Note 

Nye features 

Filialer: Vælg at filial skal vises i toppen af /branches. Hvis flere filialer er tildelt topplacering listes disse alfabetisk. 

Slutbrugervenlige URL'er: Alt indhold vises nu med slutbrugervenlige URL'er. Man har som redaktør pt. ikke mulighed for at ændre navngivningen af disse. Det bliver muligt i kommende release. 

Paragraph "Card grid automatic": Kan nu liste indhold med udgangspunkt i kategori og branch. 

Servicemenu: Servicemenuen (den der ligger under footeren) er nu redigerbar under /admin/structure/footer.

Åbningstider (Bemærk brug ikke til endeligt indhold): Taksonomi oprettet for åbningstider under admin/structure/taxonomy. Den hedder (Opening hour categories). 

Åbningstider (Bemærk brug ikke til endeligt indhold): Mulighed for at oprette åbningstider. Oprettelse sker via fane på indholdstypen filial/branch. Åbningstider kan trækkes fra andre applikationer via API. 

Brødkrumme: Sider kan manuelt tildeles brødkrumme under /admin/structure/taxonomy/manage/breadcrumb_structure/overview (se efter bagværk i menulinjen). Opret på følgende måde: 1) Lav først de strukturerende sider dvs. sider som ender med at fungere som lister over andre sider. Det kan f.eks. være en oversigt som liste licenser eller licenskategorier eller hjælpesideoversigt a la https://bibliotek.kk.dk/hjaelp/gebyr-og-erstatning. 2) Opret brødkrumme der linker til de strukturerende sider 3) Opret de enkelte indholdssider (det kunne f.eks. for et afsnit af sitet, som skal indeholde hjælpesider være https://bibliotek.kk.dk/hjaelp/gebyr-og-erstatning/betalingsfrister). Under oprettelsen kan de tildeles placering i brødkrummestrukturen (breadcrumb children til sider i brødkrummestrukturen). 
Bemærk at der er en række kendte fejl og forbedringer, som allerede er oprettet i relation til løsningen. Se under "Kendte fejl i releasen". Der genereres automatisk brødkrumme i relation til artikler (baseret på indholdstype, kategori og artikel). 

Dokumentation af API (Bemærk ikke klar til brug): API (til udveksling af arrangementer med billetsystem) opdateret efter dialog med billetleverandør. Dokumentation på https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/event-integration/ og https://github.com/danskernesdigitalebibliotek/dpl-cms/blob/develop/openapi.json


Artikler og arrangementer: Hvis man har oprettet indlejrede kategorier - f.eks. børn -> 0-2år - vil hierarkiet også fremgå af filtreringer under /articles og /events. 


Fejlrettelser og forbedringer

Arrangement: Teasertekst (farvet boks) vises nu igen i listevisninger. 

Paragraph medie: Tekst fra byline kan ikke længere skjule redigeringsikoner.  

Paragraph "Card Grid": Kan nu liste indhold med udgangspunkt i mere end ét tag. 

Footer: Kun nødvendigt at vælge "Indsend" én gang for at gemme indhold i footeren.  

Billedbeskæring: Muligt at previewe alle beskæringer. 

Artikler: Muligt at redigere teaserbillede efter upload.  

Roller og rettigheder: Alle roller, som har mulighed for at uploade billeder, kan slette billeder fra admin/content/files

Arrangement: Nu vises der også byline på billeder ved instansvisning. 


Kendte fejl og mangler i release 

Brødkrumme: Muligt at oprette brødkrumme uden den linker til indhold. Linker du ikke din brødkrumme til indhold i forbindelse med oprettelse kaster sitet en fejl, når man tilknytter brødkrummen til sider. 

Brødkrumme: Statisk overskrift "Breadcrump children", som ikke kan ændres af redaktørerne. 

Brødkrumme: Ikke muligt at vise manchet på listede breadcrumb children. 

Brødkrumme: Mangler på filialer og arrangementer. 

Brødkrumme: Overskrift på breadcrumb children er <h2> children er <h1>.

Brødkrumme: Oprettes side på paragraph med breadcrumb children placers den altid i toppen.

Filialer og arrangementer: Ingen slutbrugervenlige URL'er endnu.  

Kun superadmin kan lave URL-omdirigeringer.
