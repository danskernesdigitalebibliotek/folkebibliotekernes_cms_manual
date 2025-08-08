---
title: "Opgave 1: OpenID Connect (Adgangsplatformen)"
weight: 1
category: "Basis konfiguration"
emneord:
  - Adgangsplatformen
---

Adgangsplatformen er meget vigtig for Folkebibliotekernes CMS. Både søgning og brugerlogin forudsætter at bibliotekets adgangsnøgler til Adgangsplatformen er indsat korrekt i backend. Adgangsplatformen bygger på en teknologi der hedder OpenID Connect. Derfor omtales de ofte synonymt.

I denne opgave skal I kopiere jeres OpenID Connect adgangsnøgler fra DDB CMS over i Folkebibliotekernes CMS.

## Kopier nøgler fra DDB CMS

Log ind i DDB CMS med en bruger der har "Lokal administrator" rollen. I topmenuen klik på **Indstillinger > Ding > Adgangsplatformen**

Eller åbn via direkte link (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/ding/adgangsplatformen`

Kopier Client ID og Client Secret. Vær omhyggelig så det hele kommer med!

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c2318e78-7318-4384-91b7-358b613b0e70" alt="Kopier Client ID og Client secret fra DDB CMS" caption="Kopier Client ID og Client secret fra DDB CMS" %} 


## Indsæt nøgler i Folkebibliotekernes CMS

Log ind i Folkebibliotekernes CMS. I topmenuen klik på **Indstillinger > Web-services > OpenID Connect**

Eller åbn via direkte link (udskift mit-staging-domæne.dk):\
`https://mit-staging-domæne.dk/admin/config/services/openid-connect`


1. Indsæt Client ID og Clent Secret. Vær igen omhyggelig så det hele kommer med!
2. Udfyld feltet Agency ID (6 tal - ingen DK foran)
3. Tryk på **Save configuration** nederst på siden

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3cf6e2ff-7993-4b5a-a924-754563244a0f" alt="Indsæt Client ID, Client secret og Agency ID i Folkebibliotekernes CMS" caption="Indsæt Client ID, Client secret og Agency ID i Folkebibliotekernes CMS" %} 
