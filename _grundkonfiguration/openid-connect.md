---
title: "Opgave 1: OpenID Connect (Adgangsplatformen)"
category: "Grundkonfiguration"
emneord:
  - Adgangsplatformen
---

Adgangsplatformen er meget vigtig for Folkebibliotekernes CMS. Både søgning og brugerlogin forudsætter at bibliotekets adgangsnøgler til Adgangsplatformen er indsat korrekt i backend. Adgangsplatformen bygger på en teknologi der hedder OpenID Connect. Derfor omtales de ofte synonymt.

I denne opgave skal i kopiere jeres OpenID Connect adgangsnøgler fra DDB CMS over i Folkebibliotekernes CMS.

## Kopier nøgler fra DDB CMS

Log ind i DDB CMS. I topmenuen klik på **Indstillinger > Ding > Adgangsplatformen**

Eller åbn via direkte link (udskift mit-domænenavn.dk):

https://mit-domænenavn.dk`/admin/config/ding/adgangsplatformen`
{: .notice--primary}

Kopier Client ID og Clent Secret. Vær omhyggelig så det hele kommer med!


## Indsæt nøgler i Folkebibliotekernes CMS

Log ind i Folkebibliotekernes CMS. I topmenuen klik på **Indstillinger > Web-services > OpenID Connect**

Eller åbn via direkte link (udskift mit-staging-domæne.dk):

https://mit-staging-domæne.dk`/admin/config/services/openid-connect`
{: .notice--primary}

1. Indsæt Client ID og Clent Secret. Vær igen omhyggelig så det hele kommer med!
2. Udfyld feltet Agency ID (6 tal - ingen DK foran)
3. Tryk på **Save configuration** nederst på siden



## Egenkontrol
Du kan tjekke om Open ID Connect er korrekt konfigureret ved at forteage en søgning i Folkebibliotekernes CMS. Får du søgeresultater frem er der hul igennem.