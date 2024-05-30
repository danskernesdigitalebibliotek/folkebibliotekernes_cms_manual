---
title: "Arrangement"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---

Når du skal oprette et arrangement i FB CMS, skal du vælge **Arrangement(er)**. 

Det gælder uanset om du vil oprette et enkeltstående arrangement eller en serie af arrangementer.

## Sådan opretter du et arrangement
I topmenuen klik på **Indhold** eller åbn `https://mit-domænenavn.dk/admin/content` (udskift mit-domænenavn.dk)

Klik på **Tilføj indhold** i øverste højre hjørne:
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/3acbbb9d-734d-4423-8621-fad6d257d997" alt="Tilføj indhold" caption="Tilføj indhold" %} 

Klik på Arrangement(er):
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/5dd4e1f9-4b8d-488b-b850-82c1c3cd506f" alt="Klik på Arrangement(er)" caption="Klik på Arrangement(er)" %} 

## Enkeltstående eller gentagende arrangement?

Folkebibliotekernes CMS tilbyder en række nye muligheder for at oprette **arrangementsserier**. 

Arrangementsserier er nyttige, hvis du har tilbagevendende arrangementer, fx læseklubber, legestuer etc.

Når du opretter et arrangement, skal du i **Gentagelsesmønster**-feltet tage stilling til, om du vil oprette en enkeltstående event eller en serie. 

En ny funktion i Folkebibliotekernes CMS er **skabeloner**. Brug en skabelon, hvis du har flere arrangementer, der ligner hinanden, men som ikke skal oprettes i en arrangementsserie. En Læseklub-skabelon er et godt eksempel. [Læs mere om skabeloner](https://www.folkebibliotekernescms.dk/main/indhold/skabeloner/)
{: .notice}

## Enkeltstående arrangement
Skal du kun oprette et enkelt arrangement (ikke en serie), vælges **Custom/Single Event** i dropdown under
**Gentagelsesmønster**.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bf7ce6c7-e7c8-4f8b-aaf0-067d6689157c" alt="Vælg gentagelsesmønster" caption="Vælg gentagelsesmønster" %} 

## Arrangementsserier

Vil du oprette en serie af arrangementer, vælger du gentagelsestypen i dropdown under Gentagelsesmønster.

Du kan vælge mellem fortløbende, ugentlig og månedligt.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/cfdd915f-84a8-4d8b-85a0-15b133bb1d95" alt="Vælg gentagelsesmønster for arrangementsserie" caption="Vælg gentagelsesmønster for arrangementsserie" %} 

## Indhold

Arrangementets indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Title, Gentagelsesmønster, Description, Ticket categories og Paragraphs.
- Sidebar-panelet indeholder bl.a. State, Teaser text, Teaser image, Tagging, Planlægning mv.

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/4b59aa35-460a-4fec-a7e1-c23daa1c3bef" alt="Hovedindholdsfelt til venstre, sidebar til højre" caption="Hovedindholdsfelt til venstre, sidebar til højre" %} 

## Opbygning af arrangements-indhold

### Title
Title må ikke være tom. Det er navnet på dit arrangement.

### Description
Description er dit arrangements manchet/indledningstekst. 

Bemærk at description ikke er det samme som Teaser text. Teaser text er den tekst, der trækkes ud som appetizer for arrangementet andre steder på sitet. Teaser text tilføjes i sidebar-panelet. 

Description-teksten lægger sig ved siden af feltet med praktisk information i slutbruger-visningen.

### Gentagelsesmønster
Påkrævet felt. Valg af enkeltstående eller gentagende arrangement. Se beskrivelse ovenfor. 

### Dato/tid
Bemærk at udseendet af dette felt og valgmulighederne i det ændrer sig, afhængigt af hvilken type arrangement, der er valgt i Gentagelsesmønster.

### Address
Adresse, hvor arrangementet afholdes. Obligatorisk felt.
Adresse-oplysninger indtastes pt manuelt.
På sigt vil feltet blive automatisk udfyldt, når der er oprettet biblioteker i CMS.

### Ticket link
Hvis der er billetsalg til dit arrangement, lægges link til billetkøb ind her.

### Ticket categories
Her tilknyttes billetnavn (Name) og pris (Price). Pris kan også være 0 kr. (gratis).

Arrangementer har pt ved oprettelse ingen Ticket category. Dette er for at tilgodese, at arrangementer ikke nødvendigvis kræver billet. Hvis dit arrangement kræver billet, skal du altså manuelt tilføje Ticket category.

Det er muligt at tilføje flere Ticket categories, hvis dit arrangement har billetter i forskellige prisklasser.

### Place
Her kan angives specifik lokation, hvor arrangementet afholdes, fx Børnebiblioteket eller Store Sal.

### Partners
Eventuelle samarbejdspartnere kan indtastes her.

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

### Planlægning
Udgivelse af arrangementet kan planlægges via sidebar-panelet.
Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

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

### Teasertekst og teaserbillede
Teaser-felterne er det indhold, som trækkes ud i visningskort (udtræk, der fungerer som appetizers for artiklen andre steder på sitet). 

*Tip: Måske ønskes samme tekst i Teaser text-feltet som i Description-feltet. Det vil i en del tilfælde være oplagt. Man kan så manuelt kopiere teksten fra det ene felt og indsætte den i det andet.*

Teaserbillede vælges via knappen **Tilføj media**. Teaserbillede er dog ikke påkrævet. Hvis man ikke vælger et teaserbillede, vises teaserteksten på farvet baggrund i kort-udtrækkene.

### Categories
Kategori, fx ’Litteratur’ eller ’Digitalt’, kan vælges i dropdown-menu.
Du opretter selv dine kategorier via **Struktur > Taksonomi**

### Tags
Her kan du tilknytte valgfrie ’tags’, emneord, til dit arrangement.
Vil du tilknytte flere tags, skal de adskilles af et komma.


## Udgivet/Gem

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/eb881bd7-8bf9-41b0-86b5-9f557008d720" alt="Gem findes i øverste højre hjørne" caption="Gem findes i øverste højre hjørne" %} 

Tryk på **Gem** for at gemme/publicere arrangementet.

Det er muligt at gemme arrangementet uden at publicere ved at slukke for **den grønne knap** ved **Udgivet**.



## Vigtig viden om arrangementers struktur i back-end'en

I FB CMS' backend har alle arrangementer både en serie-visning **(master)** og en visning af det enkelte arrangement **(instans)**. 

Det gælder også for arrangementer, som er enkeltstående og ikke indgår i en serie - og det skal man lige vænne sig til.

Selve arrangementets indhold ligger i masteren. 

Klikker du ind på den enkelte instans i back-end’en (altså et af arrangementerne i serien), så fremstår den tom, fordi den trækker indholdet fra masteren. 

Ændrer du indholdet i masteren, slår det igennem i alle instanserne i serien. Det er altså nemt at redigere alle arrangementer i en serie hurtigt ved at rette i masteren (serie-visningen).

Hvis du kun vil ændre indholdet i én eller nogle af instanserne i serien, skal du klikke ind på den eller de instanser, som du vil rette. I første omgang vil de fremstå med tomme indholdsfelter. Her skal du fylde indhold i disse felter.

Ved enkeltstående arrangementer har man på samme måde en serie-visning (master) og en instans-visning. Her kan det virke ulogisk med denne to-delte struktur - altså at der også er en serie-visning - eftersom der kun er tale om ét arrangement, ikke en serie. 

Alligevel vil man ved enkeltstående arrangementer også som udgangspunkt blive bedt af systemet om at lave indholdsændringer i masteren - ikke i instansen.

Systemet viser en dialogboks, der fortæller, når man befinder sig i instans-visning og tilbyder mulighed for at tilgå masteren (serie-visningen) ved at klikke på **Redigér hele serien her**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/627ed5b1-2a31-469a-860e-e0a1ee3e5e49" alt="Du kan tilgå serie-visningen ved at klikke på Redigér hele serien her" caption="Du kan tilgå serie-visningen ved at klikke på Redigér hele serien her" %} 

Årsagen til, at der ved enkeltstående arrangementer også er en serie-visning (master), er, at det skal være muligt at omdanne enkeltstående arrangementer til serier.
