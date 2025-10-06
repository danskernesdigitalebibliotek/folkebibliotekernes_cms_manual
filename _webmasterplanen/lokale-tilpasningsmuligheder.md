---
title: "Lokale tilpasningsmuligheder"
category: "Webmaster-funktionalitet"
weight: 1
---

Webmaster-bibliotekerne kan lave lokale tilpasninger af Folkebibliotekernes CMS.

Følgende metoder bliver beskrevet:

- [Konfigurationsændring via brugergrænsefladen](https://www.folkebibliotekernescms.dk/main/webmasterplanen/konfigurationsaendringer-via-gui/)
- [Asset Injector / Add to Head](https://www.folkebibliotekernescms.dk/main/webmasterplanen/asset-injector/) 
- [Contrib / Lokale Drupal moduler](https://www.folkebibliotekernescms.dk/main/webmasterplanen/lokal-moduludvikling/)

Desuden dokumenteres det, hvordan man 

- [installere moduler](https://www.folkebibliotekernescms.dk/main/webmasterplanen/installation-af-moduler/)
- [sætter et lokalt udviklingsmiljø op](https://www.folkebibliotekernescms.dk/main/webmasterplanen/udviklingsmiljoe/)

Der er følgende begrænsninger i den lokale tilpasning, men ellers er der mange muligheder.

- det kan skabe konflikter, hvis man overskriver eksisterende konfiguration - anbefales ikke, se [Konfigurationsændring via brugergrænsefladen](https://www.folkebibliotekernescms.dk/main/webmasterplanen/konfigurationsaendringer-via-gui/)
- det er ikke muligt, at rette i det React-genererede indhold, hvilket primært er alt omkring materialer f.eks. søgning, reservering og afspilning af e-materialer
- der er ikke muligt, at tilføje et nyt tema
- det er ikke muligt at installere med composer install, så ekstra php pakker skal loades direkte i et lokalt modul, hvilke ikke er best practice
- der er begrænsede muligheder for at se og rette i de moduler, som man uploader til test eller produktion

Der findes desuden dokumentation på:
[DPL-Docs](https://danskernesdigitalebibliotek.github.io/dpl-docs/)
