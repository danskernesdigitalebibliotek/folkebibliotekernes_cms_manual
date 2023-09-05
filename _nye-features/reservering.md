---
title: "Reservering"
category: "Lånerstatus og brugerprofil"
---
## Samlet overblik over reserveringer
Under menupunktet Reserveringer får man det samlede overblik over sine reserveringer. Siden er opdelt i: "Klar til afhentning", "Fysiske reserveringer" og "Digitale reserveringer" med angivelse af antallet ved hver type. I forhold til DDB CMS er de to sider ‘Reserveringer klar’ og ’Reserveringer i kø’ blevet samlet under ét menupunkt.

![Dine reserveringer](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/4c83748d-12d4-4b43-9796-6c7a27b24115)


## Interesseperiode ##
Interesseperiode ændres på den enkelte materiale reservering - ikke via brugerprofilen, som man gør det i DDB CMS. Interesseperioden angives stadig i måneder. Det er ikke længere muligt at ændre Interesseperiode fra brugerprofilen.

Årsagen til denne ændring er at brugerne for det meste kun har behov for at forlænge interesseperioden på udvalgte reserveringer. Når interessedatoen i DDB CMS ændres i brugerprofilen gælder ændringen for alle reserveringer. Det er unødvendigt. 

Mange brugere har desuden svært ved at forstå hvad interesseperiode er for noget. Det håber vi bliver lettere når indstillingen flyttes til sin rette kontekst - ud på reserveringerne.

![Interessedato](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bdf0f7b7-236a-4062-947f-b2ee041031c8)


## Digitale reserveringer ##
Digitale reserveringer fra Publizon vises som noget nyt i Folkebibliotekernes CMS.




‘Overskredne lån’ og ‘lån’ bliver slået sammen under samme menupunkt
De to menupunkter under ”Min Konto” er slået sammen til ét menupunkt: ”Lån”.  Som i dag vises samlet antal lån med et lille tal ved menupunktet: ”Lån”.  
Ved valg af menupunktet vises alle typer af lån samlet på én side og opdelt i: "Klar til lån", "Fysiske" og "Digitale" med angivelse af antallet ved hver.
OK



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
