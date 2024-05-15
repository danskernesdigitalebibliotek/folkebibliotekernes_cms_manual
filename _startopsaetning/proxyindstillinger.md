---
title: "Opgave 7: Fjernadgang - Proxy indstillinger"
category: "Startopsætning"
weight: 7
emneord:
  - Elektroniske ressourcer
---
test
Formålet med fjernadgang er at give biblioteksbrugerne adgang hjemmefra til elektroniske ressourcer - databaser, e-tidsskrifter osv. - som bibliotekerne har købt adgang til.

Det foregår på samme måde i DDB CMS, så du kan kopiere jeres indstillinger herfra.

## Kopier proxy indstillinger fra DDB CMS

Log ind i DDB CMS med en bruger der har "Lokal administrator" rollen. I topmenuen klik på **Indstillinger > Ding > Materialer > Proxy Settings**

Eller åbn via direkte link (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/ting/proxy`

- Kopier Proxy server URL prefix
- Kopier værtsnavne og replacements

**Bemærk!** Replacement skal foldes ud, før man kan se, om der er indhold i. De fleste kilder har en tom Replacement, men der er undtagelser. F. eks. Ebook Central. Det er meget vigtigt, at få replacement med, hvis den er der.

**Bemærk!** Det er ikke alle licenser der kræver et Hostname / Værtsnavn. Der kan sagtens ligge flere hostnavne til samme udbyder f.eks. gale, som har tre forskellige hvis man har flere licenser fra dem. Der kan også være flere hostnavne end I har licenser i dag - disse behøver I ikke at kopiere over.

Få inspiration til e-materiale side visninger her:

https://www.herlevbibliotek.dk/digitale-tilbud
https://nginx.main.kobenhavn.dplplat01.dpl.reload.dk/medier

## Indsæt proxy indstillinger i Folkebibliotekernes CMS

Proxy-indstillinger indsættes som beskrevet i vejledningen herunder. Det er præcis samme fremgangsmåde som i DDB CMS.

[Vejledningen om opsætning af proxy URLer](https://www.folkebibliotekernescms.dk/main/konfiguration/url-proxy-indstillinger/).


