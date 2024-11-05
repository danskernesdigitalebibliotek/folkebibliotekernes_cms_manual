---
title: "Produktions- og testmiljø"
category: "Webmasterplanen"
weight: 1
---


Webmasterbiblioteket har adgang til to selvstændige installationer af Folkebibliotekernes
CMS: Et produktions- og et testmiljø.

Produktionsmiljøet er den installation af hjemmesiden de primære brugere (aka lånerne) har
adgang til og kan tilgås via bibliotekets domænenavn.

Testmiljøet er som udgangspunkt udelukkende beregnet til internt brug og er konfigureret så
det ikke indekseres af søgemaskiner. Miljøet findes på en særlig web-adresse.

## Testmiljø
Testmiljøet findes på en URL formateret a la:
`https://nginx.moduletest.BIBLIOTEKSNAVN.dplplat01.dpl.reload.dk/`. \
`BIBLIOTEKSNAVN` erstattes med navnet på webmasterbiblioteket.

Testmiljøet er baseret på en kopi af produktionsmiljøet og er, som navnet indikerer, beregnet
til test (se også afsnittet ”Synkronisering og nulstilling af testmiljø”). Det kan f.eks. være at:

- Teste at de moduler du lokalt har installeret på produktionsmiljøet fungerer med seneste
release af Folkebibliotekernes CMS.
- Teste nyudviklede moduler, som led i udviklingsforløb, inden de kommer i produktion.
- Teste opgraderinger af moduler, inden de kommer i produktion.

## Synkronisering og nulstilling af testmiljø
Den sidste torsdag i måneden synkroniseres testmiljøet som udgangspunkt med
produktionsmiljøet i forbindelse med opgraderingen til den seneste release af
Folkebibliotekernes CMS. Har du valgt at udsætte opgradering af produktionsmiljøet (Se afsnittet "Udsættelse af opdatering af produktionsmiljø") vil testmiljøet som udgangspunkt stadig blive synkroniseret med produktionsmiljøet. 

I forbindelse med synkroniseringen vil databasetabeller- og filer blive kopieret fra
produktionsmiljøet til testmiljøet. Databasetabeller indeholder bl.a. redaktionelt oprettet
indhold (f.eks. artikler og arrangementer), struktur (taksonomier og menuer) og konfiguration
(f.eks. sitets navn eller specifikke indstillinger til et modul). Filindholdet er redaktionelt
uploadede filer (f.eks. billeder, pdf’er) og lokalt tilføjede moduler. Testmiljøet er efterfølgende
tilnærmelsesvis et spejl af produktionsmiljøet. Pt. vil databasetabeller og filer der alene
findes på testmiljøet stadig være der efter synkronisering. I nærmere fremtid (se manualen
her for opdatering af procedurer) vil en synkronisering komme til at indebære en reel
”nulstilling” af testmiljøet hvor alt database- og filindhold, der ikke findes på
produktionsmiljøet, men udelukkende på testmiljøet, forsvinder.

Har du brug for at få synkroniseret testmiljøet på andre tidspunkter skal du oprette en
supportsag i [Servicedesk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portals).
Det kan f.eks. være relevant, hvis du har ændret konfigurationen væsentligt på testmiljøet og
efterfølgende skal lave ny test, hvor du vil sikre, at det miljø, du bruger til test har samme
konfiguration som produktionsmiljøet.
