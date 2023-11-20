---
title: "Opgave 6: Forbered indhold til det nye site"
category: "Overgangsaktiviter"
---

## Beskrivelse
Ikke alle komponenter og indholdstyper i det gamle CMS findes i det nye CMS. Nogle udvikles slet ikke og andre når ikke at blive klar inden indflytningsdatoen.

Her er en oversigt over indhold, som I skal gentænke, hvis det skal overføres til Folkebibliotekernes CMS. 

## Metode og fremgangsmåde
Læs dette afsnit grundigt og beslut jer for, hvad I vil gøre med jeres indhold. Vi foreslår en løsning, men I beslutter selv, hvad der fungerer bedst for jer.

### Medarbejderoversigten
Medarbejderoversigten og staff brugertypen findes ikke i Folkebibliotekernes CMS. Hvis I ønsker en oversigt over medarbejdere, skal den laves i en liste på en side, som I manuelt vedligeholder.

Vi anbefaler at I gør medarbejderoversigten klar, inden I får adgang til det nye CMS. Lav den i Notepad eller en anden editor, der ikke indsætter skjult formatering (ikke Microsoft Word). Listen kan I så kopiere ind på en side, når I får adgang til det nye CMS.

Lav en linje pr. medarbejder, som her:
```
Publikum og Rum
Rikke Hansen, Bibliotekar, Tlf: 88889999, E-mail: riha@kommune.dk
Kirsten Nielsen, Assistent, Tlf: 22225555, E-mail; kini@kommune.dk

```
### E-ressourcer
E-ressource oversigtssiden og e-ressource indholdstypen findes ikke i Folkebibliotekernes CMS. Det betyder, at I skal beslutte, hvad I stiller op med jeres e-ressourcer.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d62c12f0-21dd-4f37-9035-40a29434b99e" alt="E-ressource oversigtssiden findes ikke i FBCMS" caption="E-ressource oversigtssiden findes ikke i FBCMS" %}

Den simple løsning er, at I laver en side, der viser en liste over jeres e-ressourcer med navn, kort beskrivelse og proxy-link. Også den kan forberedes i Notepad i god tid inden flyningen.

Lav en liste over e-ressoucer som denne:
```
Europa World
Europa World har opdateret information om verdens 9 regioner og information om mere end 250 lande og landeområder.
https://bibxxx.bibbaser.dk/login?url=http://www.europaworld.com/

Gale in Context: Science
Med Gale in Context: Science har du adgang til en naturvidenskabelig database med emneoversigter, eksperimenter, biografier, billeder og illustrationer.
https://bib751.bibbaser.dk/login?url=http://find.galegroup.com/menu/start?userGroupName=45aarkomm&prod=SCIC

```
Hvis det er vigtigt for jer med længere beskrivelser og billeder til hver e-ressource, kan I lave en side for hver ressource og bruge en navigationsside til at skabe det samlede overblik. Den skal I selv opbygge og holde opdateret. 

### Sektionssider, karruseller og nodelists
*Dette afsnit er under udarbejdelse*

Sektionssider findes i det nye CMS, men med lidt andre visningsmuligheder og komponenter. Desværre ved vi allerede nu, at ikke alle features er klar, når I flytter ind på jeres site. F. eks. materialekarruseller. I skal derfor dokumentere, hvordan jeres nuværende sektionssider er opbygget, så I kan genopbygge dem i det nye site, når det bliver muligt.

Vi anbefaler at I går jeres sektionssider igennem én for én og beslutter om de skal overføres til det nye site. (I finder en samlet oversigt xxxx)
For hver sektionsside, der skal bevares, skal I registere, hvordan den er bygget. Her er et eksempel: 
```
Navn: Krimi
Teaser: Blodtørstig? Læs en krimi eller spændingsroman
Image: krimi.jpg 

Karrusel:Nyt på hylderne
- Krimier 
  facet.type=bog and facet.literaryForm=skøn* and facet.language=dansk and facet.category=voksen* and em=krimi*

- Spændingsromaner
  facet.type=bog and facet.language=dansk and facet.category=voksen* and facet.literaryform=skøn* and (em=spænding* or em=thriller*)

Karrusel: Virkelighedens verden

- Kriminalsager
  (facet.type=bog and facet.category=voksen* and (facet.nonfictionsubject=forbrydelse* or facet.nonfictionsubject=kriminal*)) or (facet.category=voksen* and facet.genreCategory=nonfiktion and facet.acSource=ereolen*global and "true crime")

```
Bemærk! Vi kan ikke garantere at jeres CQL-søgninger virker i det nye CMS. Søgning i Folkebibliotekernes CMS fungerer på en helt anden måde. Læs mere XXXX

### URL omdirigeringer
URL omdirigeringer bruges til at lave korte læsbare URL'er, som fungerer godt på plakater og i tryksager.
Hvis I har oprettet URL omdirigeringerer i DDB CMS, som I bruger i jeres markedsføring, skal I huske at få dem med over i Folkebibliotekernes CMS. Ellers opstår der døde links. 

Kig på jeres URL omdirigeringer i DDB CMS og tjek om der er nogen der er vigtige. Af oversigten fremgår om de bliver brugt. Bemærk at omdirigeringer til arrangementer opstår automatisk. Dem skal I ikke gøre noget ved. Det er kun de omdirigeringer, I selv har oprettet, som I skal tage hånd om.

Lav en liste i Notepad over de URL omdirigeringer, som I skal huske at oprette i det nye CMS.

## Resultat ##
I får styr på det indhold, der skal omarbejdes, inden det kan kan lægges på den nye hjemmeside. 

## Involverede parter ##
Webredaktion
