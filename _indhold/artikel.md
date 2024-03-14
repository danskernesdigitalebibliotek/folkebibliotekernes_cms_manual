---
title: "Opret artikel"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---
Artikel svarer til den indholdstype, der i det gamle CMS hed ”Nyhed”.

## Sådan opretter du en artikel
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-
domænenavn.dk)

Klik på **Add Content** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/26601a79-3284-494f-a817-1a5a5ca4c4b1" alt="Tilføj indhold" caption="Add Content" %} 

Klik på Article:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/0ba3a563-b887-4aad-b5b7-855bb0d7becb" alt="Klik på Article" caption="Klik på Article" %} 

Artiklens indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Title, Subtitle og Paragraphs.
- Sidebar-panelet indeholder Teaser text, Teaser image, Planlægning mv.
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/08aff2c9-f12c-4e92-8783-48fc5fb58ffa" alt="Opret Article siden" caption="Opret Article siden" %} 


## Opbygning af artikel-indhold

### Title
Title må ikke være tom. Det er din artikels overskrift.

### Subtitle
Subtitle er din artikels manchet/indledningstekst. Dette felt er valgfrit. 

Bemærk at subtitle ikke er det samme som Teaser text. Teaserteksten er den tekst, der trækkes ud som appetizer andre steder på sitet. 
Bemærk også at teaserteksten kun vises som appetizer i de tilfælde, hvor der ikke er valgt et teaserbillede. 
Teaser text tilføjes i sidebar-panelet.

### Override author
Hvis du ønsker, at artiklen skal have en anden forfatter-byline end dit navn – fx Redaktionen - kan du aktivere denne knap og indtaste en valgfri byline her.

### Categories
Kategori, fx ’Vi anbefaler’, kan vælges i dropdown-menu.
XXXDu opretter selv dine kategorier andetsteds i backend’en.

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til din artikel. Vil du tilknytte flere tags, skal de adskilles af et komma.

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

Materialet trækkes ind via Work ID. **Eksempel:** work-of:870970-basis:136336282.

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
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/08aff2c9-f12c-4e92-8783-48fc5fb58ffa" alt="Opret Article siden" caption="Opret Article siden" %} 

Det er muligt via **Gennemse** at vurdere artiklens slutbruger-visning inden publicering.
Tryk på **Gem** for at gemme/publicere artiklen.



