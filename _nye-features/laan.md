---
title: "Lån"
category: "Lånerstatus og brugerprofil"
---
## Samlet overblik over alle lån ##
I Folkebibliotekernes CMS vises **Overskredne lån**, **Lån** og **Digitale lån** under menupunktet **Lån**. Derved samles alle lån på én side der giver et samlet overblik.

![Lån oversigt](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c517eee0-03e9-4804-950d-55a10abd3095)

## Ny visningsmulighed -  Lån grupperet efter afleveringsdato ##
Oversigten over alle lån har to visningsmuligheder. Man kan få materialerne vist ét ad gangen eller grupperet efter afleveringsdato. Man skifter mellem de to visninger i øverste højre hjørne af listen.

![Grupperet visning](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/1642595d-a20d-48a9-9a79-675f3fd9f455)


Mulighed for at linke til oprettelse af flere brugertyper
I administrationsgrænsefladen er det nu muligt at angive en specifik URL for oprettelse efter brugertype:
•	Bruger over alder X
•	Alder for voksne brugere
•	Ung/barn under X
•	Institution
Det her ved jeg ikke hvordan er implementeret – kan Agnete tjekke det?
Efter login lander brugeren på brugerens dashboard (medmindre det er i reserver-flowet)
Hvor brugeren i dag lander på bibliotekets forside, vil brugeren lande på sit personlige dashboard??? – jeg i tvivl om denne.
Sådan er det ikke implementeret – det er rigtigt at det er intentionen. Lige nu lander man på forsiden. Jeg ved ikke om det har høj nok prioritet til at blive lavet om. Ligger som en bug: Bug #5879: KRAV: Efter login omdirigeres låner ikke til lånerstatus Dashboard (Din side) - Folkebibliotekernes CMS - Udvikling - Det Digitale Folkebiblioteks projektplatform (dandigbib.org)

Jeg tænker vi skal have Lotte til at dobbelttjekke ovenstående. 

Måske det ville give værdi meget kort at beskrive ”værdi/UX” rationalet bag hver ændring? At slå menupunkter sammen giver brugeren færre valg (overskuelighed), at flytte ”Interesseperiode” fra en generisk profilside til hvert materiale flytter funktionen tættere på der hvor den giver værdi osv. 
