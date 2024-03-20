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

Klik på **Tilføj indhold** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/3acbbb9d-734d-4423-8621-fad6d257d997" alt="Tilføj indhold" caption="Tilføj indhold" %} 

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
Kategori, fx ’Litteratur’ eller ’Digitalt’, kan vælges i dropdown-menu.
Du opretter selv dine kategorier via **Struktur > Taksonomi**

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til din artikel. Vil du tilknytte flere tags, skal de adskilles af et komma.

### Paragraphs
Du kan nu opbygge din sides indhold og udseende ved hjælp af Paragraphs-komponenterne.

[Læs om Paragraphs-komponenterne og deres funktioner](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/paragraphs-komponenter/)

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

Tryk **Gem** for at gemme/publicere artiklen.

Det er også muligt via **Gennemse** at vurdere artiklens slutbruger-visning inden publicering.

Du kan gemme siden uden at publicere ved slukke for den grønne knap ved **Udgivet**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/70d09f84-7cd5-4547-8d6c-9fcb42fa7504" alt="Klik på Gennemse eller Gem" caption="Klik på Gennemse eller Gem" %} 
