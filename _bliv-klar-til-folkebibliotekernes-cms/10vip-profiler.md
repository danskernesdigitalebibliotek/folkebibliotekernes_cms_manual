---
title: "Opgave 10: Konfiguration af søge- og visningsprofiler"
category: "Overgangsaktiviter"
weight: 10
emneord:
  - Søgning
---
Hjemmesiden henter data fra [databrønden](https://www.dbc.dk/fbi/databronden) i mange forskellige sammenhænge, og disse
sammenhænge kan overordnet inddeles i søgning og visning.

**Folkebibliotekernes CMS kræver to brøndprofiler i [VIP-basen](http://vip.dbc.dk) - en søgeprofil
og en visningsprofil.**

I kan allerede nu bygge de to brøndprofiler. I må selv bestemme hvad de skal hedde. Kald dem f. eks. `fbcms-soeg` og `fbcms-vis`.

## Søgeprofilen
Søgeprofilen anvendes når brugerne foretager søgninger på bibliotekets hjemmeside både ved ’almindelig’ og avanceret søgning. Den bruges også, når der skal hentes filtre og facetter, og når autosuggesten skal hente forslag baseret på brugerens indtastninger mv.

Søgeprofilen skal indeholde:

**1. Online kilder**\
De kilder, som I ønsker, at brugerne kan søge i på jeres hjemmeside. Det er selvfølgelig eReolen og Filmstriben – men det er også fx artikelbasen, de tekstlicenser i abonnerer på samt gratis online kilder som videnskab.dk mv.

**2. Poster, der er i lokal beholdning**\
Tilføj kilden "Bibliotekets poster med aktive beholdninger - for FBS biblioteker". 

**3. Overbygningsmaterialer**\
Tilføj kilden ”Overbygningsmaterialer” hvis I ønsker, at brugerne skal kunne fremsøge centralbibliotekernes materialer og oprette fjernlån direkte fra Folkebibliotekernes CMS. Læs mere om [Overbygningsmaterialer](/nye-features/overbygningsmaterialer). 

## Visningsprofilen
Visningsprofilen bruges i de sammenhænge, hvor brugerne skal se detaljer om et værk. Det gælder værkvisnings-siden og lånerstatus.
Der er en række scenarier, hvor brugerne har brug for at se en værkvisningsside for et materiale,
der ikke er i lokal beholdning - typisk hvis de klikker på titlen på et fjernlånt materiale i deres lånerstatus, men også hvis der er tilføjet et værk til huskelisten via et andet bibliotek, eller hvis de klikker på et link til et kasseret materiale i en gammel artikel.

Derfor skal visningsprofilen ikke være afgrænset til den lokale beholdning.

**Vi anbefaler at I opretter visningsprofilen, så den er helt identisk med søgeprofilen. Med den ene forskel at visnings-profilen har flueben i ”Tilføj alle visningskilder”, mens søgeprofilen ikke har.**

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3076e60c-802e-4acc-8f8d-be779352e1f7" alt="Visningsprofilen skal have flueben i Tilføj alle visningskilder" caption="Visningsprofilen skal have flueben i Tilføj alle visningskilder" %} 


