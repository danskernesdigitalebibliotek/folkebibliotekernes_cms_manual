---
title: "Side"
category: "Indholdstyper"
weight: 1
---
Indholdstypen Side bruges til at oprette forsider og lignende samlende indgange til tilknyttet indhold på dit site.

FB CMS benytter betegnelserne sektionsside og navigationsside, men det henviser blot til deres funktioner – der er ikke forskel på, hvordan man som udgangspunkt opretter dem. 

Her kan du få idéer til hvordan du kan opbygge indhold som f. eks. personaleside og andet.[Klik her]({{ site.baseurl }}{% link _startopsaetning/struktur-indhold-intro.md %}).

Hvis du vil opbygge dine sider i en struktur, der også laver en brødkrummesti og url'er, så kan du læse 
[Guiden: Brødkrummesti]({{ site.baseurl }}{% link _indhold/broedkrummesti.md %}).
{: .notice--primary}

## Sådan opretter du en side
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Tilføj indhold** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/3acbbb9d-734d-4423-8621-fad6d257d997" alt="Klik på Tilføj indhold" caption="Klik på Tilføj indhold" %} 

Klik på **Side**
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/1deb5772-166e-46fd-a58f-8aaae6f059d0" alt="Klik på Page" caption="Klik på Page" %} 

Artiklens indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl. a. Branch (bibliotek), Titel og Paragraphs.
- Sidebar-panelet indeholder bl.a. Planlægning, Indstillinger for forfremmelse samt mulighed for at gøre siden til en skabelon (’Entity Clone Template’).

{% include figure image_path="https://github.com/user-attachments/assets/23ec4f8a-9ecf-429d-bba1-4e034f2f3ea6" alt="Hovedindholdsfelt til venstre, sidebar til højre" caption="Hovedindholdsfelt til venstre, sidebar til højre" %}

## Opbygning af sider

### Branch
I dropdown’en under Branch kan du tilknytte siden til en af dine bibliotekssider, fx Hovedbiblioteket eller Østerby Lokalbibliotek.

### Publiser og send til Delingstjenesten
Læs om [Send til Delingstjenesten](https://www.folkebibliotekernescms.dk/main/delingstjenesten/eksport-af-indhold/), for at vurdere om denne indstilling er relevant for din side.

### Breadcrumb parent
Læs mere om [brødkrummestier](https://www.folkebibliotekernescms.dk/main/indhold/broedkrummesti/), for at forstå hvordan feltet skal udfyldes.

### Titel
Titel-feltet skal udfyldes. Det er din sides navn i back-enden, men vises som udgangspunkt ikke for slutbrugeren.

Hvis du gerne vil have, at der vises en overskrift og eventuelt en under-overskrift på siden, kan du slå det til ved at aktivere toggle-knappen, så den bliver grøn.

Det giver mulighed for at udfylde felterne **Hero title** og **Subtitle**. Hero title er en overskrift - subtitle er en under-overskrift.

Hvis toggle-knappen er aktiveret, men du ikke skriver noget i Hero title-feltet, vil sidens titel vises for slutbrugeren som overskrift.

### Display titles

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

### Gem som skabelon

Her kan du vælge at gøre siden til en skabelon ved at aktivere knappen (grøn). 

Skabeloner kan benyttes som udgangspunkt for hurtig oprettelse af andre, lignende sider, som du efterfølgende kan arbejde videre med og ændre.

Se hvordan du opretter skabeloner i guiden [Opret indhold: Skabelon]({{ site.baseurl }}{% link _indhold/skabeloner.md %}).

### Planlægning

Udgivelse af siden kan planlægges via sidebar-panelet. Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

### Forfatter

Forfatternavn kan ændres. 

Tidspunkt for sidens oprettelse kan også ændres her.

### Indstillinger for forfremmelse

Her kan du vælge at aktivere knapperne **Promoted to front page** og/eller **Klæbrig**. 

## Udgivet/Gem

Tryk **Gem** for at gemme/publicere siden.

Det er også muligt via **Gennemse** at vurdere sidens slutbruger-visning inden publicering.

Du kan gemme siden uden at publicere ved slukke for den grønne knap ved **Udgivet**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/aa1d35c3-168f-4648-b371-d1120e0c2f39" alt="Gem findes i øverste højre hjørne" caption="Gem findes i øverste højre hjørne" %} 
