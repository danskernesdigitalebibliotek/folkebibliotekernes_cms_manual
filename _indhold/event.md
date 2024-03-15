---
title: "Opret event"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---
Event svarer til den indholdstype, der i det gamle CMS hed ”Begivenhed”. Events kaldes også arrangementer.

## Sådan opretter du et arrangement
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Tilføj indhold** i øverste højre hjørne:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/3acbbb9d-734d-4423-8621-fad6d257d997" alt="Tilføj indhold" caption="Tilføj indhold" %} 

Klik på Arrangementsserier:
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/148b9ab9-6ca5-4a79-bd2c-5697afcb8772" alt="Klik på Arrangementsserier" caption="Klik på Arrangementsserier" %} 

## Enkeltstående eller gentagende arrangement?

Folkebibliotekernes CMS tilbyder en række nye muligheder for at oprette arrangementsserier. Arrangementsserier er nyttige, hvis du har tilbagevendende arrangementer, fx læseklubber, legestuer etc.

Når du opretter et arrangement, skal du i **Recur Type**-feltet tage stilling til, om du vil oprette en enkeltstående event eller en serie. Uanset om du vil oprette en enkelt event eller en serie, skal du altså vælge Event Series, når du opretter den.

## Enkeltstående arrangement
Skal du kun oprette et enkelt arrangement (ikke en serie), vælges **Custom/Single Event** i dropdown under
**Recur Type**.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bf7ce6c7-e7c8-4f8b-aaf0-067d6689157c" alt="Vælg Recur Type" caption="Vælg Recur Type" %} 

## Arrangementsserier

Vil du oprette en serie af arrangementer, vælger du gentagelses-typen i dropdown under Recur Type.

Arrangementsserier har følgende valgmuligheder:

- Consecutive Event
- Daily Event
- Weekly Event
- Monthly Event
- Yearly Event

*Consecutive event* kan fx bruges, hvis du har flere arrangementer af samme slags, som finder sted samme dag – eksempelvis en workshop, som afholdes flere gange på en bestemt dato.

## Indhold

Arrangementets indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Title, Recur type, Description og Paragraphs.
- Sidebar-panelet indeholder bl.a. State, Link (billetsalg), Teaser text, Teaser image, Tagging, Planlægning mv.

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/4b59aa35-460a-4fec-a7e1-c23daa1c3bef" alt="Hovedindholdsfeltet i et event" caption="Hovedindholdsfeltet i et event" %} 

## Opbygning af event-indhold

### Title
Title må ikke være tom. Det er navnet på dit arrangement.

### Recur Type
Påkrævet felt. Valg af enkeltstående eller gentagende arrangement. Se beskrivelse ovenfor. 

### Dato/tid
Bemærk at udseendet af dette felt og valgmulighederne i det ændrer sig, afhængigt af hvilken type arrangement, der er valgt i Recur Type.

### Description
Description er dit arrangements manchet/indledningstekst. 

Bemærk at description ikke er det samme som Teaser text. Teaser text er den tekst, der trækkes ud som appetizer for arrangementet andre steder på sitet. Teaser text tilføjes i sidebar-panelet. 

Description-teksten lægger sig ved siden af feltet med praktisk information i slutbruger-visningen.

### Paragraphs
Paragraphs er dine indholdskomponenter, bl.a. brødtekst (text body), billeder, filer samt spots for andre relevante artikler/events/sider. 
Arrangementer er født med en **Text body**-paragraph (brødtekst). 
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
- Material grid automatic
- Material grid manual

[Her er en beskrivelse af Paragraph-komponenternes features](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/event/#beskrivelse-af-paragraphs-elementernes-indholdfunktioner)

### Ticket categories
Her tilknyttes billetnavn (Name) og pris (Price). 
Pris kan også være 0 kr. (gratis).
Arrangementer har pt ved oprettelse ingen Ticket category. Dette er for at tilgodese, at arrangementer ikke nødvendigvis kræver billet.
Hvis dit arrangement kræver billet, skal du altså manuelt tilføje Ticket category.
Det er muligt at tilføje flere Ticket categories, hvis dit arrangement har billetter i forskellige prisklasser.

*Bemærk: Selve linket til billetkøb/billetudbyder skal du tilføje i sidebar-panelet.*

### Address
Adresse, hvor arrangementet afholdes. Obligatorisk felt.
Adresse-oplysninger indtastes pt manuelt.
På sigt vil feltet blive automatisk udfyldt, når der er oprettet biblioteker i CMS.

### Place
Her kan angives specifik lokation, hvor arrangementet afholdes, fx Børnebiblioteket eller Store Sal.

### Partners
Eventuelle samarbejdspartnere kan indtastes her.

## Sidebar-panel

### Image
Her kan du tilføje et billede, som vises øverst på selve dit arrangement.

### State
Obligatorisk felt. Dit arrangements tilstand, fx udsolgt eller aflyst, angiver du via dropdown’en. 
Som udgangspunkt er feltet altid sat til Active.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d77b689a-d4a9-44f2-bef0-0556aba9dee7" alt="State er obligatorisk felt" caption="State er et obligatorisk felt" %} 

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

Teaserbillede vælges via knappen **Tilføj media**. Teaserbillede er dog ikke påkrævet. Hvis man ikke vælger et teaserbillede, vises teaserteksten på farvet baggrund i kort-udtrækkene.

### Categories
Kategori, fx ’Litteratur’ eller ’Digitalt’, kan vælges i dropdown-menu.
Du opretter selv dine kategorier andetsteds i backend’en. XX

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til dit arrangement.
Vil du tilknytte flere tags, skal de adskilles af et komma.

### Planlægning
Udgivelse af arrangementet kan planlægges via sidebar-panelet.
Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

## Udgivet/Gem

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/eb881bd7-8bf9-41b0-86b5-9f557008d720" alt="Gem og udgiv findes i øverste højre hjørne" caption="Gem og udgiv findes i øverste højre hjørne" %} 

Tryk på **Gem** for at gemme/publicere arrangementet.

Det er muligt at gemme arrangementet uden at publicere ved slukke for **den grønne knap** ved **Udgivet**.

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


*Bemærk: Paragraphs kan tilføjes både over og under allerede indsatte paragraphs.*
