---
title: "Opgave 4: Informationsarkitektur og navigation"
category: "Overgangsaktiviter"
weight: 4
---
Det er designbureauet **Dept** har lavet grunddesign til Folkebibliotekernes CMS. Det bygger på et navigationsprincip, som hedder **navigation hub konceptet**. 

Navigation Hub handler om at bygge en dyb navigationsstruktur i stedet for en bred. Man har få menupunkter i hovedmenuen. Det giver en overskuelig header med få simple valg for brugeren. Fra forsiden linkes til fokuserede sektionssider/navigationssider. Via navigationselementer på disse sider guides brugerne "step-by-step" gennem flere niveauer, indtil de finder det indhold, de leder efter. Navigation hub princippet er velegnet til informationstunge hjemesider.

## Overblik over komponenter og sidetyper ##
I Folkebibliotekernes CMS er der to faste navigationskomponenter, der går igen på alle sider. 
- **Hovedmenuen**: Hovedmenuen i headeren er det primære faste navigationskomponent og har samme layout på tværs af alle sider på bibliotekets website. Punkter i hovedmenuen kan ikke have undermenupunkter. Hovedmenuen er kun i ét niveau.
- **Footer**: Footeren er det sekundære, faste navigationselement og går på tværs af alle sider på bibliotekets website.

For at opnå dybde og bredde i navigationen kan der fra header og footer linkes til navigationssider.
- **Navigationssider**: Navigationssider skal samle alle links og indgange til om bestemt emne. Navigationssidens primære formål er at lede brugeren videre til det indhold, de søger, og fungerer derfor primært som en transportside.
- **Sektionssider**: En temaside om et bestemt emne. Den leder ikke kun brugeren videre men indeholder også information.

Uanset om man vil bygge en Navigationsside eller en Sektionsside er det **indholdstypen Side** der skal benyttes. Det er sammensætningen af paragraphs der afgør sidens funktion. 

**Paragraphs** er visuelle komponenter, der bruges til at indsætte tekst, billeder, links, materialer osv. De fungere som byggeklodser, der trækkes ind og placeres i den rækkefølge, som  man ønsker det.
Der er over 20 forskellige paragraphs at vælge imellem. [Læs mere om paragraphs](https://www.folkebibliotekernescms.dk/main/indhold/paragraphs-komponenter/).

## Metode og fremgangsmåde ##
Materialet på denne side giver indblik i, hvordan et site bedst opbygges i Folkebibliotekernes CMS. Overvej nu:

- Hvad skal ligge i headeren? 
- Hvad skal vises i footeren? 
- Hvad skal jeres forsiden indeholde? 
- Hvilke overordnede sektionssider/navigationssider vil I oprette og hvilket indhold skal der vises indgang til herfra? Tegn evt. de sektionssider, som I skal have lavet, så I har nogle skitser af, hvad siderne skal indeholde af informationer. 

Det kan være en god idé at lave et flowchart over navigationen inden I går i gang med at implementere alle siderne på hjemmesiden, så har I et overblik over hvad der skal oprettes. I kan finde en masse gratis flowchart skabeloner på nettet.  

## Resultat ##
I har en plan for:
- Menustruktur
- Hvilke sider der skal oprettes
- Hvordan siderne skal bindes sammen vha. navigationskomponenter

## Involverede parter ##
Webredaktionen
