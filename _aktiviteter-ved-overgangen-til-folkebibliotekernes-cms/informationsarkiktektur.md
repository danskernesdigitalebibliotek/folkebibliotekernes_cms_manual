---
title: "Opgave 6: Informationsarkitektur og navigation"
category: "Overgangsaktiviter"
---
## Beskrivelse ##
Ligesom når man flytter ind i et nyt hus, så skal der også indrettes på en ny hjemmeside. Hvad vil I have hvor, og hvordan skal man kunne komme rundt mellem siderne?  

I denne opgave vil vi give jer nogle ideer til hvordan I kan gribe opgave an. 

## Overblik over komponenter og sidetyper ##
I Folkebibliotekernes CMS er der to faste navigationskomponenter, der går igen på alle sider. 
- **Header**: Headeren (hovedmenuen) er det primære faste navigationskomponent og har samme layout på tværs af alle sider på bibliotekets website. Punkter i hovedmenuen kan ikke have undermenupunkter. Hovedmenuen er kun i ét niveau.
- **Footer**: Footeren er det sekundære, faste navigationselement og går på tværs af alle sider på bibliotekets website.

For at opnå dybde og bredde i navigationen kan der fra header og footer linkes til sektionssider/navigationssider.
- **Sektionsside/navigationsside**: I bund og grund er de to typer det samme. En sektionsside er tænkt som en samling om et bestemt emne, hvor navigationssidens primære formål er at lede brugeren videre til det indhold, de søger, og fungerer derfor primært som en transportside. Begge typer af sider kan der linkes til fra headeren.  

I Folkebibliotekernes CMS er der også:
- **Indholdstyper** Det der før hed Nyheder er omdøbt til Artikler. Arrangementer og Sider findes stadig. Det samme gør Filialsider og Medarbejderoverigten.
- **Listesider**: Som I nok kender det i dag, vil I kunne bruge listesider som fx nyhedslister og arrangementslister. 
- **Komponenter**: På hjemmesiden kan I gøre brug af en lang række komponenter som slider, hero, banner, nyheds-komponent, materialekomponent. Komponenter er de byggeklodser som forside, sektionssider og navigationssider opbygges af.
  
[Her kan I se eksempler på hvordan de enkelte designelementer kan bruges](https://detdigitalefolkebibliotek.dk/sites/default/files/designsystem_formidling.pdf). Lad jer inspirere til en ny måde at strukturere og vise indhold.


{% capture designsystem %}
**Designbureauet Dept** har lavet grunddesign til Folkebibliotekernes CMS. Dept har arbejdet med et særligt navigationsprincip, som det er værd at sætte sig ind i. Jeres nye hjemmeside bliver bedst hvis I benytter design systemet, som det er tiltænkt.

Med **navigation hub konceptet** navigerer man i dybden i stedet for bredden. Man har få menupunkter i hovedmenuen. Det giver en overskuelig header med få simple valg for brugeren. Fra forsiden linkes til fokuserede sektionssider/navigationssider. Ved brug af navigationselementer på disse sider guides brugerne "step-by-step" gennem flere niveauer, indtil de finder det indhold de leder efter. Navigation hub princippet er velegnet til informationstunge hjemesider.

Vi anbefaler jer at se designbureauets præsentation om informationsarkitektur. Målet er at ramme en struktur, der hverken er for bred (mange menupunkter) eller for dyb (mange niveauer =mange klik). [Navigationskoncept - DDF Præsentation](https://www.figma.com/proto/XLA0k1DTwIekLMLHOJ54ek/DDF-Pr%C3%A6sentation?page-id=7127%3A13870&node-id=7127-14034&viewport=1347%2C-1112%2C0.08&scaling=scale-down&starting-point-node-id=7127%3A17822&hide-ui=1) 
{% endcapture %}
<div class="notice--info">{{ designsystem | markdownify }}</div>

## Metode og fremgangsmåde ##
På baggrund det indhold I valgte ud i den foregående opgave, så find ud af hvordan jeres indhold skal vises: 

- Hvad skal ligge i headeren? 
- Hvad skal vises i footeren? 
- Hvad skal jeres forsiden indeholde? 
- Hvilke overordnede sektionssider/navigationssider vil I oprette og hvilket indhold skal der vises indgang til herfra? Tegn evt. de sektionssider, som I skal have lavet, så I har nogle skitser af, hvad siderne skal indeholde af informationer. 

Det kan være en god idé at lave et flowchart over navigationen inden I går i gang med at implementere alle siderne på hjemmesiden, så har I et overblik over hvad der skal oprettes. I kan finde en masse gratis flowchart skabeloner på nettet.  


## Resultat ##
I har et overblik over hvilke sider, der skal oprettes og at alt jeres indhold får en plads på sitet. 

## Involverede parter ##
Webredaktionen