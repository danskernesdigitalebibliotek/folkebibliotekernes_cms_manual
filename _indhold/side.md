---
title: "Opret side"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---
Indholdstypen Side bruges til at oprette forsider og lignende samlende indgange til tilknyttet indhold på dit site.

FB CMS benytter betegnelserne sektionsside og navigationsside, men det henviser blot til deres funktioner – der er er ikke forskel på, hvordan man som udgangspunkt opretter dem. 

Du kan se eksempler på, hvordan sektions- og navigationssider kan se ud i [Design-manualen](https://www.figma.com/file/Zx9GrkFA3l4ISvyZD2q0Qi/Designsystem?type=design&node-id=7477-38814&mode=design)


## Sådan opretter du en side
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Add Content** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/26601a79-3284-494f-a817-1a5a5ca4c4b1" alt="Tilføj indhold" caption="Add Content" %} 

Klik på **Page**
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/1deb5772-166e-46fd-a58f-8aaae6f059d0" alt="Klik på Page" caption="Klik på Page" %} 

Artiklens indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder Branch (bibliotek), Titel og Paragraphs.
- Sidebar-panelet indeholder bl.a. Planlægning, Indstillinger for forfremmelse samt mulighed for at gøre siden til en skabelon (’Entity Clone Template’).

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/cd08eb5c-cbdb-4a6b-8257-891f8eb48ee3" alt="Hovedindholdsfeltet på en side" caption="Hovedindholdsfeltet på en side" %}


## Opbygning af sider

### Branch
I dropdown’en under Branch kan du tilknytte siden til en af dine bibliotekssider, fx Hovedbiblioteket eller Østerby Lokalbibliotek.

### Titel
Titel-feltet skal udfyldes. Det er din sides navn i back-enden, men vises som udgangspunkt ikke for slutbrugeren.

Hvis du gerne vil have, at der vises en overskrift og eventuelt en under-overskrift på siden, kan du slå det til ved at aktivere toggle-knappen, så den bliver grøn.

Det giver mulighed for at udfylde felterne **Hero title** og **Subtitle**. Hero title er en overskrift - subtitle er en under-overskrift.

Hvis toggle-knappen er aktiveret, men du ikke skriver noget i Hero title-feltet, vil sidens titel vises for slutbrugeren som overskrift.

### Paragraphs
Du kan nu opbygge din sides indhold og udseende ved hjælp af Paragraphs-komponenterne.

Klik på **+ Add** for at tilføje de paragraphs, som du ønsker, at din side skal bestå af.

Der er følgende Paragraphs-komponenter at vælge fra:
- Accordion
- Card grid – automatic
- Card grid – manual
- Content slider
- Files
- Hero
- Navigation grid – manual
- Navigation spots – manual
- Recommendation
- Video
- Text body
- Links
- Media(s)
- Material grid automatic
- Material grid manual

## Beskrivelse af Paragraphs-elementernes indhold/funktioner

### Accordion
En type indhold med en liste af overskrifter stablet oven på hinanden. Når der klikkes på en overskrift, vil den enten åbne eller lukke en tilknyttet indholdsrude.

### Card grid – automatic
Den automatiske variant af Card grid-komponenten kan automatisk trække spots for indhold ind på din begivenhed, side, artikel etc.

Den eneste indholdstype, som Card grid-komponenten trækker ind, er artikler. Der kan sorteres på tags, kategori og tilknyttet bibliotek.

Card grid - automatic trækker seks spots ind.

### Card grid – manual
Den manuelle variant af Card grid-komponenten giver dig mulighed for individuelt at udvælge specifikke artikler, som vises som spots på din begivenhed, side, artikel etc.

Card grid - manual kan trække op til seks artikler ind, men du kan også vælge at tilknytte færre.

### Content slider
Giver mulighed for redaktionelt at udvælge et vilkårligt antal af arrangementer og artikler i en redaktørudvalgt rækkefølge. 

Afhængigt af om du har valgt billede for indhold vises i slidere et billede eller en alternativ teasertekst på baggrund af bibliotekets signaturfarve.

På sigt kan der sættes automatikker op, så den henter en bestemt type indhold ind - fx arrangementer inden for en bestemt kategori. XX

### Files
Tilknytning af filer til artiklen, fx pdf, mp3, mp4, mov etc.

### Hero
Linkende indgangsbillede og tekst i toppen af side.

### Navigation grid – manual
Mulighed for at tilføje spots for redaktørudvalgt indhold. 

Lægger sig som et grid (felter). 

Trækker ikke teaserfotos ud, kun teasertekst (hvis tilvalgt)

### Navigation spots – manual
Mulighed for at fremhæve redaktørudvalgt indhold. 

Trækker teaserfotos med.

### Recommendation
Anvendes til anbefaling af bøger og andre materialer.

Materialet trækkes ind via Work ID. **Eksempel:** work-of:870970-basis:136336282

I øjeblikket hentes Work ID ved at udføre en søgning efter et materiale manuelt i søgefeltet på hjemmesiden og kopiere værdien fra søgeresultatet i URL’en.

Det er muligt at ændre værkets titel og beskrivelse manuelt.

### Video
Video fra YouTube eller Vimeo kan trækkes ind via url.

### Text body
Artiklens brødtekst.

### Links
Tilknytning af links til artiklen, fx interne/eksterne links og links til søgeresultater.

### Media(s)
Tilknytning af billeder. Tilladte filtyper: png gif jpg jpeg.

### Material grid automatic

Med Material grid-komponenten kan du udstille bøger og andre materialer.

Automatic-varianten trækker materialer ind via en CQL-søgestreng.\

CQL-søgestrengen kan du finde ved at lave en avanceret søgning i websitets søgefunktion og kopiere søgestrengen derfra.

Klik på **Avanceret søgning**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/4e64d74b-726d-4975-b314-e91b891a2e66" alt="Klik på Avanceret søgning" caption="Klik på Avanceret søgning" %}

Lav din søgning og klik på **Kopier søgestreng**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/39811f60-a69e-4304-88d1-9583cf180d08" alt="Klik på Kopier søgestreng" caption="Klik på Kopier søgestreng" %}

Indsæt søgestrengen i feltet **CQL Search** i Material grid automatic-komponenten.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/ebbf641f-1280-4da0-ad2d-9394c90d59c8" alt="Indsæt søgestrengen i CQL Search-feltet" caption="Indsæt søgestrengen i CQL Search-feltet" %}

[Læs mere om avanceret søgning og CQL søgning](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/nye-features/avanceret-soeging/)\
[Link til FBI-API's Complex Search Documentation](https://fbi-api.dbc.dk/indexmapper/){:target="_blank" rel="noopener"}

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



*Bemærk: Paragraphs kan tilføjes både over og under allerede indsatte paragraphs.*

## Sidebar-panel

### Entity Clone Template

Her kan du vælge at gøre siden til en skabelon ved at aktivere knappen (grøn). 

Skabeloner kan benyttes som udgangspunkt for hurtig oprettelse af andre, lignende sider, som du efterfølgende kan arbejde videre med og ændre.

### Planlægning

Udgivelse af siden kan planlægges via sidebar-panelet. Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

### Forfatter

Forfatternavn kan ændres. 

Tidspunkt for sidens oprettelse kan også ændres her.

### Indstillinger for forfremmelse

Her kan du vælge at aktivere knapperne **Promoted to front page** og/eller **Klæbrig**. 

## Udgivet/Gem

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/aa1d35c3-168f-4648-b371-d1120e0c2f39" alt="Gem og udgiv findes i øverste højre hjørne" caption="Gem og udgiv findes i øverste højre hjørne" %} 

Tryk på **Gem** for at gemme/publicere siden.

Det er muligt at gemme siden uden at publicere ved slukke for **den grønne knap** ved **Udgivet**.
