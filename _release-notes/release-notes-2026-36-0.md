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

- Mulighed for at vælge en prioriteret materialetype i "Material grid automatic", så brugere ledes direkte til den ønskede materialetype (f.eks. lydbog frem for bog). [CMS-2072](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2072)

- Tilføjelse af forklarende tekst på værkvisning for materialer uden knap, så brugere vejledes om alternative adgangsmuligheder via biblioteket eller Bibliotek.dk. 

- Ny landingsside til serier, der samler serietitel, beskrivelse og materialer sorteret efter delnummer og udgivelsesår. Bemærk: “Begynd med denne” er ikke nødvendigvis Del 1 i en serie. 

- Logisk styring af billetfelter: For at undgå forvirring i backend bliver felterne til "Billetlink" og "Billetkapacitet" nu automatisk deaktiveret (grået ud), når muligheden "Opret billet i billetsystem" er valgt. Dette sikrer, at redaktører ikke ved en fejl indtaster data, der alligevel overskrives af det eksterne billetsystem.

- Opgradering af Drupal til version 11. Bemærk til webmasterbiblioteker: Opgradering kræver, at alle anvendte moduler er kompatible med Drupal 11.

## Forbedring og fejlrettelser

- Tilføjelse af arrangørinformation til API-feedet for KulturNaut, så biblioteker kan koble arrangementer til det rette bibliotek, selvom de foregår eksternt. [CMS-1633](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1633)

- Rettelse af fejl på GO!, hvor værkvisningen automatisk hoppede ned til detaljevisning ved indgang fra karruseller. 

- Rettelse af fejl, hvor målgruppeoplysninger ikke blev vist korrekt på serieinstanser for arrangementer. [CMS-2104](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-2104)


