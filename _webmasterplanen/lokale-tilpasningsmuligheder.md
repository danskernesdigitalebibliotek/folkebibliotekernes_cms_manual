---
title: "Lokale tilpasningsmuligheder"
category: "Webmaster-funktionalitet"
weight: 1
---

Webmaster-bibliotekerne kan lave lokale tilpasninger af Folkebibliotekernes CMS.

Følgende udviklingsmetoder bliver beskrevet:

- Konfigurationsændring via brugergrænsefladen
- Asset Injector / Add to Head
- Lokale Drupal moduler

Desuden dokumenteres det, hvordan man sætter et lokalt udviklingsmiljø op.

Der er følgende begrænsninger i den lokale tilpasning, men ellers er der mange muligheder.

- det kan skabe konflikter, hvis man overskriver eksisterende konfiguration - anbefales ikke, se webmaster-2-konfiguration
- det er ikke muligt, at rette i det React-genererede indhold
- der er ikke muligt, at tilføje et nyt tema
- det er ikke muligt at installere med composer install, så ekstra php pakker skal loades direkte i et lokalt modul, hvilke ikke er best practice
- der er begrænsede muligheder for at se og rette i de moduler, som man uploader til test eller produktion

Der findes desuden dokumentation på:

DPL-Docs
https://danskernesdigitalebibliotek.github.io/dpl-docs/

