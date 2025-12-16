---
title: "Produktions- og testmiljø"
category: "Driftsforhold"
weight: 1
---


Webmasterbiblioteket har adgang til to selvstændige installationer af Folkebibliotekernes
CMS: Et produktions- og et testmiljø.

Produktionsmiljøet er den installation af hjemmesiden de primære brugere (aka lånerne) har
adgang til og kan tilgås via bibliotekets domænenavn.

Testmiljøet er som udgangspunkt udelukkende beregnet til internt brug og er konfigureret, så
det ikke indekseres af søgemaskiner. Miljøet findes på en særlig web-adresse.

## Testmiljø
Testmiljøet findes på en URL formateret a la:
`https://nginx.moduletest.BIBLIOTEKSNAVN.dplplat01.dpl.reload.dk/`. \
`BIBLIOTEKSNAVN` erstattes med navnet på webmasterbiblioteket.

Testmiljøet er baseret på en kopi af produktionsmiljøet og er, som navnet indikerer, beregnet
til test.  Det kan f.eks. være at:

- Teste at de moduler du lokalt har installeret på produktionsmiljøet fungerer med seneste
release af Folkebibliotekernes CMS.
- Teste nyudviklede moduler, som led i udviklingsforløb, inden de kommer i produktion.
- Teste opgraderinger af moduler, inden de kommer i produktion.

## Opgradering og synkronisering af testmiljø

Jeres testmiljø vil også blive omtalt som jeres modultestsite.

### Modultetssites opgraderes og synkroniseres ugentligt 
Webmasterbibliotekernes modutestsites synkroniseres med produktionssitet og opgraderes hver anden torsdag (lige uger), når en ny release af FBCMS udkommer. I forbindelse med ferier kan den faste releasedag ændre sig. Det vil da fremgå af [release notes](https://www.folkebibliotekernescms.dk/main/overblik/release-notes/). 

Er der problemer med udrulningen bliver opgradering af produktionssites prioriteret over opgradering af modultestssites. Hvis opgraderingen af modultetstsites må udsættes, vil den blive foretaget så hurtigt som muligt herefter. Man kan altid sammenholde versionsnummeret i CMS med seneste release note, hvis man er i tvivl, om man er på den seneste version.

Har du valgt at udsætte opgradering af produktionsmiljøet (Se [Udsættelse af opdatering af produktionsmiljø](https://www.folkebibliotekernescms.dk/main/webmasterplanen/udsaettelse-af-opdatering/)) vil testmiljøet som udgangspunkt stadig blive opgraderet og synkroniseret med produktionsmiljøet. 

### Teknikken bag synkronisering og opgradering af modultestsitet

1. Der tages en kopi af driftssitets database og filsystem. Kopien lægges på modultestssitet og den overskriver ALT, der ligger der i forvejen. Har I på modultetstsitet oprettet indhold, installeret moduler eller uploadet filer, så forsvinder det.
2. Modultetssitet opgraderes til nyeste release af FBCMS

Fordelen ved den model er, at I rent faktisk kan stole på de de tests, som I udfører på jeres modultestsite. Blev jeres modultetstsite ikke synkroniseret med produktionssitet, vil de to sites hurtigt komme så meget ud af sync, så kode der virker fint på modultetssitet fejler eller i værste fald ødelægger produktionssitet.


**Udviklertips**: Arbejd aldrig med kode direkte på modultestsitet, uden at gemme lokalt også. Du risikerer at miste timevis af arbejde, når sitet slettes.
{: .notice }






