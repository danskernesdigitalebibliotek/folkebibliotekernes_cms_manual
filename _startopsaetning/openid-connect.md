---
title: "Opgave 1: OpenID Connect (Adgangsplatformen)"
weight: 1
category: "Basis konfiguration"
---

Adgangsplatformen er meget vigtig for Folkebibliotekernes CMS. Både søgning og brugerlogin forudsætter at bibliotekets adgangsnøgler til Adgangsplatformen er indsat korrekt i backend. Adgangsplatformen bygger på en teknologi der hedder OpenID Connect. Derfor omtales de ofte synonymt.

I denne opgave skal I indsætte OpenID Connect adgangsnøgler i Folkebibliotekernes CMS.

## Rekvirer nøgler fra DBC

Det er DBC, der kan udlevere adgangsnøgler til Adgangsplatformen. Ikke DDF.

Hvis I ikke har dem, skal I oprette en supportsag hos DBC, hvor I beder om at få udleveret jeres Client ID og Client Secret til Adgangsplatformen. 


## Indsæt nøgler i Folkebibliotekernes CMS

Log ind i Folkebibliotekernes CMS med jeres admin-login. I topmenuen klik på **Indstillinger > Redaktionelle brugere > OpenID Connect**

Eller åbn siden via direkte link (udskift mit-staging-domæne.dk):\
`https://mit-staging-domæne.dk/admin/config/people/openid-connect`

På billedet her er Adgangsplatformen allerede oprettet. 

- Hvis jeres oversigt er tom, så tryk på den blå **+Adgangsplatformen** knap øverst.

<img width="1273" height="328" alt="image" src="https://github.com/user-attachments/assets/f8db206a-41ec-4cb3-9a7b-ea296499b9c1" />

- Indsæt Client ID og Clent Secret. Vær igen omhyggelig så det hele kommer med!
- Udfyld feltet Agency ID (6 tal - ingen DK foran)
- Tryk på **Gem** nederst på siden

<img width="671" height="852" alt="Adgangsplatformen" src="https://github.com/user-attachments/assets/285558d1-164c-4f9a-8690-61174a7761d9" />
