---
title: "Opgave 10: Opret søge- og visningsprofil i VIP"
category: "Overgangsaktiviter"
weight: 10
emneord:
  - Søgning
  - VIP og søgeprofiler
---
Hjemmesiden henter data fra [databrønden](https://www.dbc.dk/fbi/databronden){:target="_blank"} i mange forskellige sammenhænge, og disse
sammenhænge kan overordnet inddeles i søgning og visning.

**Folkebibliotekernes CMS kræver to brøndprofiler i [VIP-basen](http://vip.dbc.dk){:target="_blank"} - en søgeprofil
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
Tilføj kilden ”Overbygningsmaterialer” hvis I ønsker, at brugerne skal kunne fremsøge centralbibliotekernes materialer og oprette fjernlån direkte fra Folkebibliotekernes CMS. Læs mere om [overbygningsmaterialer]({{ site.baseurl }}{% link _nye-features/overbygningsmaterialer.md %}).

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/22dfeac7-4a4f-4a7f-8710-95b7efb70f9e" alt="Visningsprofilen skal IKKE have flueben i Tilføj alle visningskilder" caption="Søgeprofilen skal IKKE have flueben i Tilføj alle visningskilder" %} 


## Visningsprofilen
Visningsprofilen bruges i de sammenhænge, hvor brugerne skal se detaljer om et værk. Det gælder værkvisnings-siden, lånerstatus og huskelisten. Der er en række scenarier, hvor brugerne har brug for at se en værkvisningsside for et materiale, der ikke er i lokal beholdning. F. eks. hvis de klikker på titlen på et fjernlånt materiale i deres lånerstatus, men også hvis der er tilføjet et værk til huskelisten via et andet bibliotek, eller hvis de klikker på et link til et kasseret materiale i en gammel artikel.

Det er ikke nødvendigt at tilføje nogle kilder til profilen, men der skal til gengæld sættes flueben i ”Tilføj alle visningskilder”

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/720a7cb1-063c-4b9c-b04d-6a33c2fb8fe1" alt="Visningsprofilen skal have flueben i Tilføj alle visningskilder" caption="Visningsprofilen skal have flueben i Tilføj alle visningskilder" %} 




