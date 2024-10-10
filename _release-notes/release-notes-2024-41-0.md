---
title:  "Release Notes 2024.41.0"
category: "Release Notes"
weight: 368
---

# Feed til appen og flere forbedringer og fejlrettelser

Releasedato: 10-10-2024

Opgraderingen rulles ud til: Redaktørbiblioteker: Produktionssites opgraderes. Webmasterbiblioteker: Kun testsite opgraderes.

## Nye features

- Arrangementsfeed og åbningstidsfeed udviklet specifikt til appen "Biblioteket". Dette er kun implementeret i CMS'et, og mangler stadig konfiguration i appen. Redia kontakter jer med mere information.

## Fejlrettelser og forbedringer

- Listen over brugere (/admin/people), vil nu som standard kun vise redaktionelle brugere. Der vises ikke længere brugere med patronrollen (lånere) og brugere uden en rolle tildelt. Derudover er der tilføjet flere filtreringsværktøjer til listen.

- Event-API: Ændring af dato på arrangement ændrer nu ikke længere på UUID (Universal Unique Identifier).

- Straks-låns-notifikation: Nu et krav at man under /admin/config/dpl-library-agency/instant-loans angiver, hvilke materialegrupper der er ikke-reserverbare. I forbindelse med reservation af materiale med lang reservationskø gør "straks-låns-nofitifikationer" låneren opmærksom på evt. ikke-reserverbare udgaver af materialet, der er opstillet på biblioteket.  

- Paragraph "Enkel-linkliste": Links kan nu åbne i nyt vindue, og standardindhold peger ikke længere på forkert node. 
