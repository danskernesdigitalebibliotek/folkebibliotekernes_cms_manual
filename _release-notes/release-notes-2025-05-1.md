---
title:  "Release Notes 2025.05.1"
category: "Release Notes"
weight: 351
---

### Åbningstider og arrangementer kan igen automatisk blive overført til Biblioteket Appen.

Releasedato: 30-01-2025

**Redaktørbiblioteker**: Produktionssites opgraderes til 2025.05.1\
**Webmasterbiblioteker**: Produktionssites opgraderes til 2025.04.0. Modultestsites opgraderes til 2025.05.1.

## Nye features
Fra 31/1-2025 kan åbningstider og arrangementer igen automatisk blive overført til Biblioteket Appen. Dvs. når I opdaterer åbningstider og arrangementer på hjemmesiden bliver ændringerne automatisk synkroniseret over i Biblioteket Appen.

**Det virker først når I har ændret jeres profil i Redias administrationssystem til automatisk synkronisering.**

Følg Redias vejledning: [https://email.redia.dk/integrationer-mellem-biblioteket-appen-og-folkebibliotekernes-cms](https://email.redia.dk/integrationer-mellem-biblioteket-appen-og-folkebibliotekernes-cms){:target="_blank"}

Helt konkret er det en udvidelse af åbningstids-API til Biblioteketet app'en med åbningstids-kategorinavn, der er det nye i denne version og som muliggører synkronisering.

## Fejlrettelser
**Flerdags-arrangementer vises nu korrekt**: Der har været problemer med visning af arrangementer, der strækker sig over flere dage. De er nu løst. Paragraph Event list - automatic viser nu flerdags-arrangementet alle dage i stedet for kun den første dag.
På selve siden for flerdags-arrangementet står der ikke længere ”udløbet” efter den første dag.

**Biblioteker med mange filialer kan igen se hele åbningstider-sidebaren.** Fejlen opstod i forbindelse med sidste uges opgradering til version 2025.04.0.
