---
title:  "Release Notes 2026.24.1"
category: "Release Notes"
weight: 304
---  

Releasedato: 11-06-2026

**Redaktør**: Produktionssites: 2026.24.1  
**Webmaster**: Produktionssites: 2026.23.4, Moduletestsites: 2026.24.1


## Ny udvikling

- **Klon arrangementer** – det er nu muligt at klone et arrangement. [CMS-1000](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1000)
  **OBS:** Burde have været med i denne release, men en teknisk detalje gjorde at det ikke kom med i releasen. Men det kommer med i release 2026.26, så redaktørbibliotekerne får funktionen inden sommerferien.

- **Sortering af arrangementer på kategori eller bibliotek** – arrangementer sorteres nu alfabetisk ved filtrering på kategorier og/eller biblioteker i stedet for efter antal. [CMS-578](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-578)

- **Reader/player-funktion til e-bøger og lydbøger kan nu tilgås direkte i lånerstatus** – ikke blot ved henvisning til værkvisningen. Det giver færre klik og sikrer, at lån stadig kan læses/lyttes, selv hvis titlen midlertidigt fjernes fra eReolen. [CMS-1760](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1760)

- **Implementering af status på selve arrangements-siden** – statuslabels som "Aflyst" og "Udsolgt" vises nu direkte på arrangementssiden, så brugere der kommer fra fx Google eller Facebook umiddelbart kan se arrangementets status. [CMS-1828](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1828)

<br>


## Forbedringer og fejlrettelser 

- **Eventlist automatic viser nu også seriearrangementer** – paragraffen "Eventlist au-tomatic" viser fremover alle instanser af seriearrangementer, i stedet for kun det førstkommende.
**Bemærk**: Dette nu kontrolleres via et toggle i den enkelte paragraf, sådan at redaktøren selv kan vælge, om en given paragraf skal vise første instans eller alle instanser af en serie. [CMS-714](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-714)

- **Mailadresse skal være obligatorisk ifm. fjernlån – igen** - Reserveringsknappen for overbygningsmaterialer var fejlagtigt blevet aktiv for brugere uden mailadresse. Knappen er nu igen inaktiv, hvis der ikke er registreret en mailadresse.
**Bemærk**: Denne fejl blev oprindeligt rettet i 2025 men gik i stykker igen. Fejlen betød, at biblioteker modtog fjernlånsbestillinger uden brugerens mailadresse. Rettelsen sikrer, at brugere ikke kan bestille overbygningsmaterialer uden først at angive en mailadresse. Oprindelig sag. [CMS-689](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-689)

- **Værkvisningssiden:** "Udgave"-feltet under Udgaver samt i reserveringsmodalen bruger ikke længere samme label som "Nr." ved tidsskrifter. Derfor står der nu korrekt “Udgave” ved udgaverne og “Nr.” ved valg af nr. af tidsskrift. [CMS-1856](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1856)

