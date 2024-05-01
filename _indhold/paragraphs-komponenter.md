---
title: "Paragraphs Komponenterne"  
category: "Generelt"
---

De komponenter, som du opbygger dit indhold i artikler, begivenheder og sider af, kaldes **Paragraphs**.

Klik på **+ Add** for at tilføje de paragraphs, som du ønsker, at din side skal bestå af.

{% include figure class="eightty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/e4d6ebdd-2d4a-44f4-9992-7d70ef05a726" alt="Klik på + Add" caption="Klik på + Add" %}

Paragraphs kan tilføjes både over og under allerede indsatte paragraphs.

## Formidlingskomponenter
Her er de visuelle navigationskomponenter, som kan henvise og fremvise til andet indhold på siden fx content slider.

### Filtered event list

### Manual event list

### Card grid – automatic
Den automatiske variant af Card grid-komponenten kan automatisk trække spots for indhold ind på din begivenhed, side, artikel etc.

Den eneste indholdstype, som Card grid-komponenten trækker ind, er artikler. Der kan sorteres på tags, kategori og tilknyttet bibliotek.

Card grid - automatic trækker seks spots ind.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/d03d9ff4-17f6-4cf5-aba6-5d1c5083452d" alt="Eksempel på et card grid" caption="Eksempel på et card grid" %}

### Card grid – manual
Den manuelle variant af Card grid-komponenten giver dig mulighed for individuelt at udvælge specifikke artikler, som vises som spots på din begivenhed, side, artikel etc.

Card grid - manual kan trække op til seks artikler ind, men du kan også vælge at tilknytte færre.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/d03d9ff4-17f6-4cf5-aba6-5d1c5083452d" alt="Eksempel på et card grid" caption="Eksempel på et card grid" %}

### Content slider
Giver mulighed for redaktionelt at udvælge et vilkårligt antal af arrangementer og artikler i en redaktørudvalgt rækkefølge. 

Afhængigt af om du har valgt billede for indhold vises i slidere et billede eller en alternativ teasertekst på baggrund af bibliotekets signaturfarve.

På sigt kan der sættes automatikker op, så den henter en bestemt type indhold ind - fx arrangementer inden for en bestemt kategori. XX

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/74bc26c6-990d-4a24-89be-e79d4b4c3485" alt="Eksempel på en content slider" caption="Eksempel på en content slider" %}

### Hero
Linkende indgangsbillede og tekst i toppen af side.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/4c3894d2-1d63-44f2-8e4e-409e785edace" alt="Eksempel på en hero" caption="Eksempel på en hero" %}

## Indholdskomponenter
Her er de komponenter, som man kan bruge til at indsætte indhold såsom tekst, billeder og video.

### Accordion
En type indhold med en liste af overskrifter stablet oven på hinanden. Når der klikkes på en overskrift, vil den enten åbne eller lukke en tilknyttet indholdsrude.

### Files
Tilknytning af filer til artiklen, fx pdf, mp3, mp4, mov etc.

### Video
Video fra YouTube eller Vimeo kan trækkes ind via url.

### Media(s)
Tilknytning af billeder. Tilladte filtyper: png gif jpg jpeg.

### Text body
Artiklens brødtekst.

## Navigationskomponenter
Her er de tekst- og linksbaseret navigationskomponenter, som kan henvise til andet indhold på siden fx navigation grid.

### Navigation grid – manual
Mulighed for at tilføje spots for redaktørudvalgt indhold. 

Lægger sig som et grid (felter). 

Trækker ikke teaserfotos ud, kun teasertekst (hvis tilvalgt)

### Navigation spots – manual
Mulighed for at fremhæve redaktørudvalgt indhold. 

Trækker teaserfotos med.

### Links
Tilknytning af links til artiklen, fx interne/eksterne links og links til søgeresultater.

## Materialekomponenter
Her er de komponenter, som man kan bruge til at fremhæve bibliotekets materialer.

### Recommendation
Anvendes til anbefaling af bøger og andre materialer.

Materialet trækkes ind via Work ID. **Eksempel:** work-of:870970-basis:136336282

I øjeblikket hentes Work ID ved at udføre en søgning efter et materiale manuelt i søgefeltet på hjemmesiden og kopiere værdien fra søgeresultatet i URL’en.

Det er muligt at ændre værkets titel og beskrivelse manuelt.

### Material grid automatic

Med Material grid-komponenten kan du udstille bøger og andre materialer.

Automatic-varianten trækker materialer ind via en CQL-søgestreng.

CQL-søgestrengen kan du finde ved at lave en avanceret søgning i websitets søgefunktion og kopiere søgestrengen derfra.

[Sådan opretter du CQL-søgestrenge](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/cql-soegestrenge/)

Du kan indstille komponenten til at vise et bestemt antal materialer. Antallet skal være deleligt med fire. Antallet bestemmer du i feltet **Amount of materials**.

Komponenten viser minimum 4 materialer og kan maksimalt sættes til 32 materialer.

### Material grid manual

I Material grid manual-varianten vælger du selv manuelt de materialer, du vil udstille.

Materialer trækkes ind via Work ID. **Eksempel:** work-of:870970-basis:135822388

I øjeblikket hentes Work ID ved at udføre en søgning efter et materiale manuelt i søgefeltet på hjemmesiden og kopiere værdien fra søgeresultatet i URL’en.

Antallet af materialer skal være deleligt med fire. Du kan altså indsætte 4 materialer eller 8 eller 12 osv. 

Indsætter du fx 7 materialer, vil der kun blive vist 4. Du må så tilføje et mere, så der er 8 i alt for at få vist dem alle.

Du kan dog godt indsætte blot et, to eller tre materialer.

Maksimalt kan der indsættes 32 materialer.
