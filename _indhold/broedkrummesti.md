---
title: "Brødkrummesti"
category: "Navigation"
weight: 1
emneord:
- "Menuer og navigation"
---

***Forklar hvad brødkrummer er.***

## 1. Planlæg strukturen af hjemmesiden

For at oprette strukturen på jeres hjemmesiden, kan I benytte det arbejde, som I lavede i [forberedelsesopgave 4: Informationsarkitektur og navigation]({{ site.baseurl }}{% link _bliv-klar-til-folkebibliotekernes-cms/4informationsarkiktektur.md %}). Hvis I ikke har lavet det endnu, kan det bruges som inspiration til hvordan I vil bygge siden op. 

### Eksempel på en struktur
Vi tager udgangspunkt i en eksempelstruktur for punkterne i hovedmenuen, der ser ud som nedenstående:
- Det sker
- Inspiration
  - Litteratur
    - Læseklubber
      - Tove Ditlevsen klubben
- Netmedier
- For børn

***Forklar børn, forældre og søskende***

## 2. Opret sider til det faste indhold
Start med at oprette de sider, som strukturen skal bestå af. Se hvordan man opretter sider i guiden [Opret indhold: Side]({{ site.baseurl }}{% link _indhold/side.md %})

Som et eksempel tager vi udgangspunkt i ovenstående eksempel på en struktur, og fokuserer på at lave menupunktet 'Inspiration' hele vejen ned til siden 'Tove Ditlevsen klubben'. I dette eksempel ville vi oprette siderne: 1. Inspiration, 2. Litteratur, 3. Læseklubber og 4. Tove Ditlevsen klubben.

## 3. Opret brødkrummer og tilknyt siderne
I topmenuen klik på **Brødkrumme** eller åbn `https://mit-domænenavn.dk/admin/structure/taxonomy/manage/breadcrumb_structure/overview` (udskift mit-domænenavn.dk)

Klik på **Tilføj ord** i øverste højre hjørne:

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/54aa7739-0834-4ea4-a189-7b00bc5a1318" alt="Klik på Tilføj ord" caption="Klik på Tilføj ord" %}

Udfyld **Navn** med det, som skal vises i brødkrummestien. Det behøver ikke at være det samme, som det den tilknyttede side hedder. Brødkrummens navn kan med fordel være kortere og mere præcist end sidenavnet. Fx kan en side i strukturen hedde 'Blåovre læseklubber - genre' hedde Læseklubber i brødkrummen.

Udfyld **Indhold der linkes til** med den side, som skal tilknyttes. Der SKAL tilknytttes en side. 

Vælg om der skal vises sidebørn i **Vis sidebørn**. Det betyder om der skal vises en automatisk liste med indhold, som referer til dette element. Fx en liste med Litteratur, Musik, Film, Spil på siden Inspiration.

Vælg om den skal publiceres i **Publiceret**.

Vælg eventuelt et overordnet ord i **Overordnede ord**. Hvis du ønsker en brødkrummesti som følger: Inspiration > Litteratur > Læseklubber > Tove Ditlevsen klubben. Så skal Inspiration vælges som overordnet ord på brødkrummen Litteratur, og Litteratur skal vælges på Læseklubber, og Læseklubber skal vælges på Tove Ditlevsen klubben.
