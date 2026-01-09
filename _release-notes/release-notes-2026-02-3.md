---
title:  "Release Notes 2026.02.3"
category: "Release Notes"
weight: 315
---  
Releasedato: 09-01-2026

**Redaktør**: Produktionssites: 2026.02.3

**Webmaster**: Produktionssites: 2025.50.1, Moduletestsites: 2026.02.3

### Hotfix 2026.02.3
- Løser fejlen i heroen på filialvisningssiden, hvor kontaktoplysninger manglede.

---  


Releasedato: 09-01-2026

**Redaktør**: Produktionssites: 2026.02.2

**Webmaster**: Produktionssites: 2025.50.1, Moduletestsites: 2026.02.2

### Hotfix 2026.02.2
- Retter kode der bliver kørt når det bliver rullet ud som sørger for at nedarvede felter er up-to-date også på eksisterende events. Det er ikke noget brugerne ser. 

---  

Releasedato: 08-01-2026

**Redaktør**: Produktionssites: 2026.02.1

**Webmaster**: Produktionssites: 2025.50.1, Moduletestsites: 2026.02.1


### Ny udvikling

- Søgning fravælger materialer fra blacklistede filialer i stedet for at tilvælge materialer fra ikke-blacklistede filialer.
- Visning af reserveringer klar til afhentning ("Klar til dig" i Dit overblik + "Klar til lån" under Alle reserveringer) sorteres i nummerrækkefølge efter afhentningsnumre. [CMS-1109](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1109)
- Arrangementssiden har fået flere tilretninger i designet. [CMS-1800](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1800) + [CMS-1328](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1328)
- Webmasterbiblioteker: Mulighed for at fejlrette lokale moduler. [CMS-1742](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1742)


### Forbedringer og fejlrettelser

- Arrangementer: Brug af All day-knappen viser nu korrekt arrangementsdato [CMS-1658](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1658)
- Arrangementssiden: Manglende class'er på arrangementsiden er nu rettet. [CMS-1822](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1822)
- Problem løst når man var logget ind og skiftede til en anden biblioteksside man ikke var oprettet hos, så blev man logget ind som pseudobruger, og siden fejlede efterfølgende. [CMS-630](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-630)
- Fejl ved søgning fra iOS og MacOS enheder rettet. [CMS-1774](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1774)
- Åbningstidsmodul fejler – rettelser træder først i kraft efter timeout eller slår slet ikke igennem. Fejlen burde være rettet, så der igen kan lægges åbningstider ind. Test gerne og opret en ny sag, hvis I fortsat oplever fejl i modulet. [CMS-1785](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1785)
- Delingstjenesten: Opdateringer overskriver ikke længere indhold trods frakobling. Dette testes endeligt i liveversion. [CMS-1804](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1804)
- "Lån lydbog"-knappen fryser ikke længere siden, hvis man forsøger at låne et materiale med mere end én manifestation. [CMS-1793](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1793)
- Link fra lånerstatus (Alle lån + Lån-modaler Dit overblik) til værkvisningssiden. Dele er sagen blev løst i 2025.50.1. [CMS-971](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-971)
