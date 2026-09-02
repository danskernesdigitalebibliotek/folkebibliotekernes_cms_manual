---
title:  "Release Notes 2026.36.0"
category: "Release Notes"
weight: 300
---  
Releasedato: 03-09-2026

**Redaktør**: Produktionssites: 2026.36.0
**Webmaster**: Produktionssites: 2026.34.2, Moduletestsites: 2026.36.0

## Ny udvikling

- Reservering af fysiske bøger på GO-web: Med bibliotekslogin kan børn nu søge efter fysiske bøger og reservere dem til afhentning på deres bibliotek på samme måde, som I kender det fra voksenhjemmesiden. Brugere med Unilogin kan ikke reservere, men får besked om, at reservering og lån af fysiske bøger kræver login med bibliotekslogin. Bemærk: Børnebrugere som har lånt voksenmaterialer, kan pt. ikke kan få dem vist på deres GO!-side. 

- Mulighed for at vælge en prioriteret materialetype i "Malerialekomponent – automatisk", så brugere ved klik på et værk i komponenten ledes direkte til den materialetype, som man som formidler har valgt at fokusere på (f.eks. lydbog frem for bog). [CMS-2072](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2072)

- Tilføjelse af forklarende tekst på værkvisning for materialer uden handleknap, så brugere vejledes om alternative adgangsmuligheder som at kontakte biblioteket (som måske giver adgang på biblioteket via f.eks. IP-adgangen til Retriever) eller prøve Bibliotek.dk. Bemærk: Vi arbejder fortsat på denne funktionalitet, så løsningen er kun delvist sat i drift.

- Ny landingsside til serier, der samler serietitel, beskrivelse og materialer sorteret efter delnummer og udgivelsesår samt mulighed for at klikke videre til en søgning på hvad seriens forfatter/ophav ellers står bag. Bemærk: “Begynd med denne” er ikke nødvendigvis Del 1 i en serie. 

- Logisk styring af billetfelter: For at undgå forvirring i backend bliver felterne til "Billetlink" og "Billetkapacitet" nu automatisk deaktiveret (grået ud) eller aktiveret, afhængigt af om muligheden "Opret billet i billetsystem" er valgt eller ej. Dette sikrer, at redaktører ikke ved en fejl indtaster data, der alligevel overskrives af det eksterne billetsystem.

- Opgradering af Drupal til version 11. Bemærk til webmasterbiblioteker: Opgradering kræver, at alle anvendte moduler er kompatible med Drupal 11.

## Forbedring og fejlrettelser

- Tilføjelse af arrangørinformation til API-feedet for KulturNaut, så biblioteker kan koble arrangementer til det rette bibliotek, selvom de foregår eksternt.  [CMS-1633](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1633)

- Rettelse af fejl på GO!, hvor værkvisningen automatisk hoppede ned til detaljevisning ved indgang fra karruseller. 

- Rettelse af fejl, hvor målgruppeoplysninger ikke blev vist korrekt på serieinstanser for arrangementer.  [CMS-2104](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2104)


