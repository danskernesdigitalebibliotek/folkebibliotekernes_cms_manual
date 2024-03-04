---
title: "Event"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---
Event svarer til den indholdstype, der i det gamle CMS hed ”Begivenhed”. 

## Sådan opretter du en event
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Tilføj arrangement** i øverste højre hjørne:

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/ad036889-9305-4286-b13c-271f2ffb7860)


## Enkeltstående eller gentagende event?

Folkebibliotekernes CMS tilbyder en række nye muligheder for at oprette event-serier. Event-serier er nyttige, hvis du har tilbagevendende events, fx læseklubber, legestue etc.

Når du opretter en event, skal du i **Recur Type**-feltet tage stilling til, om du vil oprette en enkeltstående event eller en serie.

## Enkeltstående event
Skal du kun oprette en enkelt event (ikke en serie), vælges **Custom/Single Event** i dropdown under
**Recur Type**.

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bf7ce6c7-e7c8-4f8b-aaf0-067d6689157c)

## Serie-events

Vil du oprette en serie af events, vælger du gentagelses-typen i dropdown under Recur Type.

Serie-events har følgende valgmuligheder:

- Consecutive Event
- Daily Event
- Weekly Event
- Monthly Event
- Yearly Event

*Consecutive event* kan fx bruges, hvis du har flere events af samme slags, som finder sted samme dag – eksempelvis en workshop, som afholdes flere gange på en bestemt dato.

## Indhold

Eventens indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Title, Recur type, Description og Paragraphs.
- Sidebar-panelet indeholder bl.a. State, Link (billetsalg), Teaser text, Teaser image, Tagging, Planlægning mv.

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/4b59aa35-460a-4fec-a7e1-c23daa1c3bef)

## Opbygning af event-indhold

### Title
”Title” må ikke være tom. Det er navnet på din event.

### Recur Type
Påkrævet felt. Valg af enkeltstående eller gentagende event. Se beskrivelse ovenfor. 

### Dato/tid
Bemærk at udseendet af dette felt og valgmulighederne i det ændrer sig, afhængigt af hvilken type Event, der er valgt i Recur Type.

### Description
Description er din events manchet/indledningstekst. 

Bemærk at description ikke er det samme som Teaser text. Teaser text er den tekst, der trækkes ud som appetizer for event’en andre steder på sitet. Teaser text tilføjes i sidebar-panelet. 

Description-teksten lægger sig ved siden af feltet med praktisk information i slutbruger-visningen.

### Paragraphs
Paragraphs er dine indholdskomponenter, bl.a. brødtekst (text body), billeder, filer samt spots for andre relevante artikler/events/sider. 
Event er født med en **Text body**-paragraph (brødtekst). 
Denne Text body-paragraph kan fjernes manuelt ved behov.
Klik på **+ Add** for at tilføje flere paragraphs, som du ønsker, at din event skal indeholde.

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

XXX Se nederst for beskrivelse af Paragraph-komponenternes features.

### Ticket categories
Her tilknyttes billetnavn (Name) og pris (Price). 
Pris kan også være 0 kr. (gratis).
Events har pt ved oprettelse ingen Ticket category. Dette er for at tilgodese, at events ikke nødvendigvis kræver billet.
Hvis dit arrangement kræver billet, skal du altså manuelt tilføje Ticket category.
Det er muligt at tilføje flere Ticket categories, hvis dit arrangement har billetter i forskellige prisklasser.

*Bemærk: Selve linket til billetkøb/billetudbyder skal du tilføje i sidebar-panelet.*

### Address
Adresse, hvor arrangementet afholdes. Obligatorisk felt.
Adresse-oplysninger indtastes pt manuelt.
På sigt vil feltet blive automatisk udfyldt, når der er oprettet biblioteker i CMS XX.

### Place
Her kan angives specifik lokation, hvor arrangementet afholdes, fx Børnebiblioteket eller Store Sal.

### Partners
Eventuelle samarbejdspartnere kan indtastes her.

## Sidebar-panel

### Image
Her kan du tilføje et billede, som vises øverst på selve din begivenhed.

## State
Obligatorisk felt. Din events tilstand, fx udsolgt eller aflyst, angiver du via dropdown’en. 
Som udgangspunkt er feltet altid sat til Active.

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d77b689a-d4a9-44f2-bef0-0556aba9dee7)

Andre State-valgmuligheder er:
- Ticket sale not open
- Sold out
- Canceled
- Occurred

### Link
Link til billetkøb hos billetudbyder indsættes i dette felt.
Er arrangementet uden billet, efterlades feltet tomt.

### Teasertekst og teaserbillede
Teaser-felterne er det indhold, som trækkes ud i visningskort (udtræk, der fungerer som appetizers for artiklen andre steder på sitet). 

*Tip: Måske ønskes samme tekst i Teaser text-feltet som i Description-feltet. Det vil i en del tilfælde være oplagt. Man kan så manuelt kopiere teksten fra det ene felt og indsætte den i det andet.*

Teaserbillede vælges via knappen ’Tilføj media’. Teaserbillede er dog ikke påkrævet.

Hvis man ikke vælger et teaserbillede, vises teaserteksten på farvet baggrund i kort-udtrækkene.

### Categories
Kategori, fx ’Litteratur’ eller ’Digitalt’, kan vælges i dropdown-menu.
Du opretter selv dine kategorier andetsteds i backend’en. XX

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til din event.
Vil du tilknytte flere tags, skal de adskilles af et komma.

### Planlægning
Udgivelse af eventen kan planlægges via sidebar-panelet.
Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

## Udgivet/Gem

![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/eb881bd7-8bf9-41b0-86b5-9f557008d720)


Tryk på **Gem** for at gemme/publicere eventen.

Det er muligt at gemme eventen uden at publicere ved slukke for **den grønne knap** ved **Udgivet**.

## Beskrivelse af Paragraphs-elementernes indhold/funktioner

### Accordion
En type indhold med en liste af overskrifter stablet oven på hinanden. Når der klikkes på en overskrift, vil den enten åbne eller lukke en tilknyttet indholdsrude.

### Card grid – automatic
Beskrivelse følger. XX

### Card grid – manual
Beskrivelse følger. XX

### Content slider
Giver mulighed for redaktionelt at udvælge et vilkårligt antal af arrangementer og artikler i en redaktørudvalgt rækkefølge. 
Afhængigt af om redaktøren har valgt billede for indhold vises i slidere et billede eller en alternativ teasertekst på baggrund af bibliotekets signaturfarve.
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
