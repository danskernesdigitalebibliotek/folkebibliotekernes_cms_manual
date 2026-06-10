---
title:  "Release Notes 2026.24.0"
category: "Release Notes"
weight: 304
---  

Releasedato: 11-06-2026

**Redaktør**: Produktionssites: 2026.24.0  
**Webmaster**: Produktionssites: 2026.23.4, Moduletestsites: 2026.24.0


## Ny udvikling

- **Klon arrangementer** – det er nu muligt at klone et arrangement. Serien klones, men alle instanser nulstilles, så redaktører nemt kan genoprette arrangementer på nye lokationer. [CMS-1000](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1000)

- **Sortering af arrangementer på kategori eller bibliotek** – arrangementer sorteres nu alfabetisk ved filtrering på kategorier og/eller biblioteker i stedet for efter antal. [CMS-578](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-578)

- **Reader/player-funktion til e-bøger og lydbøger kan nu tilgås direkte i lånerstatus** – ikke blot ved henvisning til værkvisningen. Det giver færre klik og sikrer, at lån stadig kan læses/lyttes, selv hvis titlen midlertidigt fjernes fra eReolen. [CMS-1760](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1760)

- **Implementering af status på selve arrangements-siden** – statuslabels som "Aflyst" og "Udsolgt" vises nu direkte på arrangementssiden, så brugere der kommer fra fx Google eller Facebook umiddelbart kan se arrangementets status. [CMS-1828](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1828)

<br>


## Forbedringer og fejlrettelser 

- **Eventlist automatic viser nu også seriearrangementer** – paragraffen "Eventlist au-tomatic" viser fremover alle instanser af seriearrangementer, i stedet for kun det førstkommende.
**Bemærk**: Dette nu kontrolleres via et toggle i den enkelte paragraf, sådan at redaktøren selv kan vælge, om en given paragraf skal vise første instans eller alle instanser af en serie. [CMS-714](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-714)

- **Mailadresse skal være obligatorisk ifm. fjernlån – igen** - Reserveringsknappen for overbygningsmaterialer var fejlagtigt blevet aktiv for brugere uden mailadresse. Knappen er nu igen inaktiv, hvis der ikke er registreret en mailadresse.
**Bemærk**: Denne fejl blev oprindeligt rettet i 2025 men gik i stykker igen. Fejlen betød, at biblioteker modtog fjernlånsbestillinger uden brugerens mailadresse. Rettelsen sikrer, at brugere ikke kan bestille overbygningsmaterialer uden først at angive en mailadresse. Oprindelig sag. [CMS-689](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-689)

