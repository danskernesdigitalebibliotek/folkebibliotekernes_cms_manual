---
title:  "Release Notes 2025.03.2"
category: "Release Notes"
weight: 353
---  

### XML sitemap til søgemaskineoptimering samt fejlrettelser

Releasedato: 16-01-2025

**Redaktørbiblioteker**: Produktionssites opgraderes til 2025.03.2\
**Webmasterbiblioteker**: Produktionssites opgraderes til 2024.50.0. Modultestsites opgraderes til 2025.03.2.

**OBS**: De indledende øvelser til integration af børnesitet er gået i gang. Hvis I opdager nye menupunkter eller valgmuligheder i backend, der hedder noget med GO! eller børnesite, så rør ikke ved dem. Det er stadig i proces.

## Nye features
SEO – For at søgemaskiner nemmere kan indeksere indholdet af hjemmesiden, er der blevet tilføjet et xml sitemap. Det indeholder arrangementer, artikler og hjælpesider. Det holdes automatisk opdateret. Vil man se det, ligger det på adressen MITDOMÆNENAVN.dk/sitemap.xml

## Fejlrettelser
Åbningstidsmodal kan nu lukkes i mobil- og tabletvisning.

Event API –Det er nu muligt at afgrænse med parameteren ``from_date``, så man kan undgå at få de afholdte arrangementer med ud, når arrangementer udtrækkes gennem OpenAPI.

Fejlsikring af kald til Publizon-adapteren, så kald uden identifier undgås.

## For udviklere:
Opdaterede kodebiblioteker: vite (4.4.11), vitest (0.34.6), @tsconfig/create-react-app (2.0.1), stylelint-config-recommended-scss (13.0.0), webpack-version-file-plugin (0.5.0)



