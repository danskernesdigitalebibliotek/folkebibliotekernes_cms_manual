---
title: "Opret side"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---
Indholdstypen Side bruges til at oprette forsider eller andre samlende indgange til tilknyttet indhold på dit site.

FB CMS benytter betegnelserne sektionsside og navigationsside, men det henviser blot til deres funktioner – der er er ikke forskel på, hvordan man som udgangspunkt opretter dem. 

Du kan se eksempler på, hvordan sektions- og navigationssider kan se ud i [Design-manualen](https://www.figma.com/file/Zx9GrkFA3l4ISvyZD2q0Qi/Designsystem?type=design&node-id=7477-38814&mode=design)


## Sådan opretter du en side
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Add Content** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/26601a79-3284-494f-a817-1a5a5ca4c4b1" alt="Tilføj indhold" caption="Add Content" %} 

Klik på Page
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/1deb5772-166e-46fd-a58f-8aaae6f059d0" alt="Klik på Page" caption="Klik på Page" %} 

Artiklens indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder Branch (bibliotek), Titel og Paragraphs.
- Sidebar-panelet indeholder bl.a. Planlægning, Indstillinger for forfremmelse samt mulighed for at gøre siden til en skabelon (’Entity Clone Template’).

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/692f2a62-3ca4-4877-ac18-b31595fd2413" alt="Hovedindholdsfeltet på en side" caption="Hovedindholdsfeltet på en side" %} 

## Opbygning af sider

### Branch
I dropdown’en under Branch kan du tilknytte siden til en af dine bibliotekssider, fx Hovedbiblioteket eller Østerby Lokalbibliotek.

### Titel
Titel-feltet skal udfyldes. Det er din sides navn i back-enden, men vises ikke for slutbrugeren.

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

## Beskrivelse af Paragraphs-elementernes indhold/funktioner

### Accordion
En type indhold med en liste af overskrifter stablet oven på hinanden. Når der klikkes på en overskrift, vil den enten åbne eller lukke en tilknyttet indholdsrude.

### Card grid – automatic
Kan opsættes, så den automatisk trækker spots for indhold ind på din artikel, side, begivenhed etc. 

Hvilken indholdstype, der skal trækkes ind, vælger du ved afkrydsning i komponenten.
Content types-valgmuligheder i Card grid - automatic er pt: Page, Article, Branch, Campaign og User Registration. Du kan godt vælge mere end en.

Card grid - automatic trækker seks indholdselementer ind.

### Card grid – manual
Giver dig mulighed for manuelt at udvælge specifikt indhold, fx artikler eller begivenheder, som vises som spots på din artikel, side, begivenhed etc. 

Card grid - manual kan trække op til seks indholdselementer ind, men man kan også vælge at benytte færre.

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
Materialet trækkes ind via Work ID. Eksempel: work-of:870970-basis:136336282. I øjeblikket hentes dette ved at udføre en søgning efter et materiale manuelt i søgefeltet på hjemmesiden og kopiere værdien fra søgeresultatet i URL'en.

Det er muligt at ændre værkets titel og beskrivelse manuelt.

### Video
Video fra YouTube eller Vimeo kan trækkes ind via url.

### Text body
Artiklens brødtekst.

### Links
Tilknytning af links til artiklen, fx interne/eksterne links og links til søgeresultater.

### Media(s)
Tilknytning af billeder. Tilladte filtyper: png gif jpg jpeg.

*Bemærk: Paragraphs kan tilføjes både over og under allerede indsatte paragraphs.*

## Sidebar-panel

### Entity Clone Template

Her kan du vælge at gøre siden til en skabelon ved at aktivere knappen (grøn). Skabeloner kan benyttes som udgangspunkt for hurtig oprettelse af andre, lignende sider.

### Planlægning

Udgivelse af siden kan planlægges via sidebar-panelet. Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

### Forfatter

Forfatternavn kan ændres. 

Tidspunkt for sidens oprettelse kan også ændres her.

### Indstillinger for forfremmelse

Her kan du vælge at aktivere knapperne **Promoted to front** page og/eller **Klæbrig**. 
