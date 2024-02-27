---
title: "Artikel"
category: "Indholdstyper"
weight: 1
---
Artikel svarer til den indholdstype, der i det gamle CMS hed ”Nyhed”.

## Sådan opretter du en artikel
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-
domænenavn.dk)

Klik på **Tilføj indhold** i øverste højre hjørne:
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bb91fe76-7eea-4b71-be46-b7da64513851)

Klik på Article:
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/cb12a6a3-01d0-4398-9717-f5b899b47adc)

Artiklens indhold opbygges via et hovedindholdsfelt (findes der er bedre ord??) til venstre og et
sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Title, Subtitle og Paragraphs.
- Sidebar-panelet indeholder Teaser text, Teaser image, Planlægning mv.
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/08aff2c9-f12c-4e92-8783-48fc5fb58ffa)


## Opbygning af artikel-indhold

### Title
**Title** må ikke være tom. Det er din artikels overskrift.

### Subtitle
Subtitle er din artikels manchet/indledningstekst. Dette felt er valgfrit.
Bemærk at subtitle ikke er det samme som Teaser text. Teaser text er den tekst, der trækkes ud som appetizer for artiklen andre steder på sitet. Teaser text tilføjes i sidebar-panelet. 

### Override author
Hvis du ønsker, at artiklen skal have en anden forfatter-byline end dit navn – fx Redaktionen - kan du aktivere denne knap og indtaste en valgfri byline her.

### Categories
Kategori, fx ’Vi anbefaler’, kan vælges i dropdown-menu.
XXXDu opretter selv dine kategorier andetsteds i backend’en (hvor?)

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til din artikel

### Paragraphs
Paragraphs er dine indholdskomponenter, bl.a. brødtekst (text body), billeder, filer samt spots for andre relevante artikler/events/sider. 
Klik på **+ Add** for at tilføje de paragraphs, du ønsker, at din artikel skal indeholde.

Paragraphs-mulighederne er:
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
(beskrivelse mangler pt.)

### Card grid – manual
(beskrivelse mangler pt.)

### Content slider
Giver mulighed for redaktionelt at udvælge et vilkårligt antal af arrangementer og artikler i en redaktørudvalgt rækkefølge. 
Afhængigt af om redaktøren har valgt billede for indhold vises i slidere et billede eller en alternativ teasertekst på baggrund af bibliotekets signaturfarve

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

Materialet trækkes ind via Work ID. Eksempel: work-of:870970-basis:136336282. I øjeblikket hentes dette ved at udføre en søgning efter et materiale manuelt i bibliotekets hjemmeside og kopiere værdien fra søgeresultatet i URL'en.

Det er muligt at ændre værkets titel og beskrivelse manuelt.

### Video
Video fra YouTube eller Vimeo kan trækkes ind via url.

### Text body
Artiklens brødtekst.

### Links
Tilknytning af links til artiklen, fx interne/eksterne links og links til søgeresultater.

### Media(s)
Tilknytning af billeder. Tilladte filtyper: png gif jpg jpeg.

**Bemærk**
Paragraphs kan tilføjes både over og under allerede indsatte paragraphs.
{: .notice}

## Sidebar-panel

### Teasertekst og teaserbillede
Teaser-felterne bruges til visningskortene (udtræk, der fungerer som appetizers for artiklen andre steder på sitet). 
Hvis der ikke er valgt et teaserbillede, vises teaserteksten på farvet baggrund i kort-udtrækkene.

### Planlægning
Udgivelse af artiklen kan planlægges via sidebar-panelet.
Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

### Meta tags
Meta tags-feltet giver mulighed for at indsætte en canonical url, hvis der er behov for dette.
En canonical URL bør indsættes, hvis indholdet er blevet duplikeret fra andre websteder. Dette hjælper med at signalere til søgemaskiner, at den foretrukne kilde til dette indhold er den angivne canonical URL, hvilket forhindrer potentielle problemer med duplikatindhold og sikrer korrekt tilskrivning til den originale kilde.
Skal være en ekstern URL som f.eks. http://example.com.

## Gennemse/Gem
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/0d43f364-aa54-4f09-8075-a2c77e54fe96)

Det er muligt via **Gennemse** at vurdere artiklens slutbruger-visning inden publicering.
Tryk på **Gem** for at gemme/publicere artiklen.



