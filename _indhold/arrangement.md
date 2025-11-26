---
title: "Arrangement"
category: "Indholdstyper"
weight: 1
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

#### Vigtigt! Uanset om du opretter et enkeltstående arrangement eller en arrangementsserie oprettes der en master-visning og en eller flere instans-visninger. Det er vigtigt at forstå. [Læs mere om master- og instansvisning af arrangementer.](https://www.folkebibliotekernescms.dk/main/indhold/arrangement/#vigtig-viden-om-arrangementers-struktur-i-back-enden)
{: .notice--info}

## Enkeltstående arrangement
Skal du kun oprette et enkelt arrangement (ikke en serie), vælges **Enkeltstående arrangement** i dropdown under
**Gentagelsesmønster**.

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/fc0f0e3e-249e-4886-8b7b-3453c987feda" alt="Vælg gentagelsesmønster" caption="Vælg gentagelsesmønster" %} 

## Arrangementsserier

Vil du oprette en serie af arrangementer, vælger du gentagelsestypen i dropdown under **Gentagelsesmønster**.

Du kan vælge mellem **fortløbende**, **ugentlig** eller **månedligt**.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/cfdd915f-84a8-4d8b-85a0-15b133bb1d95" alt="Vælg gentagelsesmønster for arrangementsserie" caption="Vælg gentagelsesmønster for arrangementsserie" %} 

## Indhold

Arrangementets indhold opbygges via et hovedindholdsfelt til venstre og et sidebar-panel til højre.

- Hovedindholdsfeltet indeholder bl.a. Titel, Manchet, Gentagelsesmønster, Dato og tid, Billetkategorier og Paragraphs.
- Sidebar-panelet indeholder bl.a. Status, Teasertekst, Teaserbillede, Tagging, Planlægning mv.

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/8e8fc55c-01c0-4bed-9961-52a72f08a0b2" alt="Hovedindholdsfelt til venstre, sidebar til højre" caption="Hovedindholdsfelt til venstre, sidebar til højre" %} 

## Opbygning af arrangements-indhold

### Titel
Titel må ikke være tom. Det er navnet på dit arrangement.

### Manchet
Manchet er dit arrangements indledningstekst. 

Bemærk at manchet ikke er det samme som Teasertekst. Teasertekst er den tekst, der trækkes ud som appetizer for arrangementet andre steder på sitet. Teasertekst tilføjes i sidebar-panelet. 

Manchet-teksten lægger sig ved siden af feltet med praktisk information i slutbruger-visningen.

### Gentagelsesmønster
Påkrævet felt. Valg af enkeltstående eller gentagende arrangement. Se beskrivelse ovenfor. 

### Dato/tid
Bemærk at udseendet af dette felt og valgmulighederne i det ændrer sig, afhængigt af hvilken type arrangement, der er valgt i Gentagelsesmønster.

### Adresse
Adresse, hvor arrangementet afholdes, hvis det ikke er på et bibliotek.

### Billetlink
Hvis der er billetsalg til dit arrangement, lægges link til billetkøb ind her. 
Bruger I Place2book? [Guide til billetintegration med Place2book](https://www.folkebibliotekernescms.dk/main/integrationer/place2book/)

### Billetkategorier
Her tilknyttes billetkategorinavn (Navn) og pris (Price). Pris kan også være 0 kr. (gratis).

Arrangementer har pt ved oprettelse ingen billetkategori. Dette er for at tilgodese, at arrangementer ikke nødvendigvis kræver billet. Hvis dit arrangement kræver billet, skal du altså manuelt tilføje Billetkategori.

Det er muligt at tilføje flere billetkategorier, hvis dit arrangement har billetter i forskellige prisklasser.

### Sted
Her kan angives specifik lokation, hvor arrangementet afholdes, fx Børnebiblioteket eller Store Sal.

### I samarbejde med
Eventuelle samarbejdspartnere kan indtastes her.

### Paragraphs
Du kan nu opbygge din sides indhold og udseende ved hjælp af Paragraphs-komponenterne.

[Læs om Paragraphs-komponenterne og deres funktioner](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/paragraphs-komponenter/)

## Sidebar-panel

### Planlægning
Udgivelse af arrangementet kan planlægges via sidebar-panelet.
Der kan sættes et fremtidigt publicerings-tidspunkt og/eller et fremtidigt afpublicerings-tidspunkt.

### Billede
Her kan du tilføje et billede, som vises øverst på selve dit arrangement.

### Status
Obligatorisk felt. Dit arrangements tilstand, fx udsolgt eller aflyst, angiver du via dropdown’en. 
Som default er feltet sat til til Aktiv.

Status vises på:
- Billetknappen på arrangementssider
- Arrangementsoversigten under /arrangementer

Status vises IKKE på:
 - Arrangementssider, når billetlink-feltet er tomt
 - I paragraphs (Arrangementsliste og Arrangementsliste Automatisk)
 - På tagsamlesider

{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d77b689a-d4a9-44f2-bef0-0556aba9dee7" alt="Status er obligatorisk felt" caption="Status er et obligatorisk felt" %} 

Andre Status-valgmuligheder er:
- Billetsalget er ikke åbnet
- Udsolgt
- Aflyst
- Er afholdt

### Teasertekst og teaserbillede
Teaser-felterne er det indhold, som trækkes ud i visningskort (udtræk, der fungerer som appetizers for artiklen andre steder på sitet). 

*Tip: Måske ønskes samme tekst i Teaser text-feltet som i Description-feltet. Det vil i en del tilfælde være oplagt. Man kan så manuelt kopiere teksten fra det ene felt og indsætte den i det andet.*

Teaserbillede vælges via knappen **Tilføj media**. Teaserbillede er dog ikke påkrævet. Hvis man ikke vælger et teaserbillede, vises teaserteksten på farvet baggrund i kort-udtrækkene.

### Kategorier
Kategori, fx ’Litteratur’ eller ’Digitalt’, kan vælges i dropdown-menu.
Du opretter selv dine kategorier via **Struktur > Taksonomi**

### Tagging
Her kan du tilknytte valgfrie ’tags’, emneord, til dit arrangement.
Vil du tilknytte flere tags, skal de adskilles af et komma.


## Publiceret/Gem

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/eb881bd7-8bf9-41b0-86b5-9f557008d720" alt="Gem findes i øverste højre hjørne" caption="Gem findes i øverste højre hjørne" %} 

Tryk på **Gem** for at gemme/publicere arrangementet.

Det er muligt at gemme arrangementet uden at publicere ved at slukke for **den grønne knap** ved **Publiceret**.



## Vigtig viden om arrangementers struktur i back-end'en

I FB CMS' backend har alle arrangementer både en serie-visning **(master)** og en visning af det enkelte arrangement **(instans)**. 

Det gælder også for arrangementer, som er enkeltstående og ikke indgår i en serie - og det skal man lige vænne sig til.

Selve arrangementets indhold ligger i masteren. 

Ændrer du indholdet i masteren, slår det igennem i alle instanserne i serien. Det er altså nemt at redigere alle arrangementer i en serie hurtigt ved at rette i masteren (serie-visningen).

Klikker du ind på den enkelte instans i back-end’en (altså et af arrangementerne i serien), så fremstår den tom, fordi den trækker indholdet fra masteren. 

Hvis du kun vil ændre indholdet i én eller nogle af instanserne i serien, skal du klikke ind på den eller de instanser, som du vil rette. I første omgang vil de fremstå med tomme indholdsfelter. Her skal du fylde indhold i disse felter. 

Det kan være irriterende at felterne er tomme, hvis man ønsker at tage udgangspunkt i masterens indhold. Du kan trække indeholdet fra masteren ind i instanserne via fanebladet *Indsæt værdier fra arrangementsserier*.
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/4e14eb2f-b890-44c0-a75f-0d1ccd6c8a39" alt="Kopier indhold fra masteren ind på instanserne via Indsæt værdier fra arrangementsserier" %} 

#### Enkeltstående arrangementer har også en master og en instans
Ved enkeltstående arrangementer har man på samme måde en serie-visning (master) og en instans-visning. Her kan det virke ulogisk med denne to-delte struktur - altså at der også er en serie-visning - eftersom der kun er tale om ét arrangement, ikke en serie. 

Alligevel vil man ved enkeltstående arrangementer også som udgangspunkt blive bedt af systemet om at lave indholdsændringer i masteren - ikke i instansen.

Systemet viser en dialogboks, der fortæller, når man befinder sig i instans-visning og tilbyder mulighed for at tilgå masteren (serie-visningen) ved at klikke på **Redigér hele serien her**.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/162300593/627ed5b1-2a31-469a-860e-e0a1ee3e5e49" alt="Du kan tilgå serie-visningen ved at klikke på Redigér hele serien her" caption="Du kan tilgå serie-visningen ved at klikke på Redigér hele serien her" %} 

Årsagen til, at der ved enkeltstående arrangementer også er en serie-visning (master), er, at det skal være muligt at omdanne enkeltstående arrangementer til serier.
