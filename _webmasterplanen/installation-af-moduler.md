---
title: "Installation af contribmoduler og egenudviklede moduler"
category: "Webmasterplanen"
weight: 4
---

Som webmasterbibliotek er det muligt at installere moduler lokalt, som ikke er en del af
standardudgaven af Folkebibliotekernes CMS (core). Det kan være contribmoduler (gratis
moduler hentet fra drupal.org, som er lavet og vedligeholdt af udviklere fra
drupal-communitiet) og egenudviklede moduler.

## Installation af moduler

### Testmiljø:
For at installere moduler på testmiljøet skal du logge på med en bruger med rollen
”Administrator”. Hvis du mangler de nødvendige rettigheder, skal du oprette en sag på
[Servicedesk](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portals).

Fremgangsmåden for at uploade og installere moduler på testmiljøet er overordnet set
følgende:

1. Log på testmiljøet med en bruger, som har rollen **Administrator**.
2. Under menupunktet **Udvid** (`/admin/modules`) vælges knappen **+Add new module**.
3. **Vælg fil** og find frem til den komprimerede fil (tar, zip) med modulet og upload
modulet. Når modulet først er uploadet, kan det installeres.
4. Find modulet vha. søgefunktionen på `/admin/modules`. Installer modulet ved at markere
checkboksen ud for modulet og vælg knappen **Installér** nederst på siden.
5. Tildel tilladelser/permissions til modulet for de forskellige brugerroller på site.
Indstillinger for tilladelser kan f.eks. findes ved at fremsøge modulet under
`/admin/modules` og vælge **permissions**.


### Produktion:
Inden et modul installeres på produktionsmiljøet, er det vigtigt først at teste modulet grundigt
på testmiljøet.

For at installere moduler på produktionsmiljøet skal du logge på med en bruger med rollen
”Administrator”.

Hvis du mangler de nødvendige rettigheder, skal du oprette en sag på [Servicedesk](
https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portals).

Fremgangsmåden for at installere og aktivere moduler på produktionsmiljøet er overordnet
set følgende:

1. Log på produktionsmiljøet med en bruger, som har rollen **Administrator**.
2. Under menupunktet **Udvid** (`/admin/modules`) vælges knappen **+Add new module**
3. **Vælg fil** og find frem til den komprimerede fil (tar, zip) med modulet og upload modulet
til sitet. Når modulet først er uploadet, kan det installeres.
4. Find modulet vha. søgefunktionen på `/admin/modules`. Installér modulet ved at markere
checkboksen ud for modulet og vælg knappen **Installér** nederst på siden.
5. Gå til redigering af din brugerprofil. For at tildele tilladelser til de forskellige roller oprettet
på produktionssitet, er det i øjeblikket nødvendigt at skifte sprogindstillinger for din
administratorbruger som beskrevet nedenunder. Læs om den specifikke fejl på
[https://www.folkebibliotekernescms.dk/main/overblik/status#udfordringer-med-webmaster
biblioteker](https://www.folkebibliotekernescms.dk/main/overblik/status#udfordringer-med-webmaster
biblioteker).
6. Skift administrationssproget for brugeren til engelsk.
7. Tildel tilladelser/permissions til modulet for de forskellige brugerroller på site.
Indstillinger for tilladelser kan f.eks. findes ved at fremsøge modulet under
`/admin/modules` og vælge **permissions**.
8. Skift administrationssproget for brugeren tilbage til dansk.
