---
title:  "Release Notes 2026.4.1"
category: "Release Notes"
weight: 314
---  
Releasedato: 22-01-2026

**Redaktør**: Produktionssites: 2026.4.1

**Webmaster**: Produktionssites: 2026.2.4, Moduletestsites: 2026.4.1

### Hotfix 2026.4.1
- Blacklist ift. søgning: Vi har fikset en fejl introduceret i 2026.2.4. omkring blacklist af filialer ift. søgning, som kun påvirkede simpel søgning. Fejlen medførte, at sites uden blacklist af mindst én filial ift. søgning reelt skjulte materialer i søgeresultatet fra alle filialer i stedet, hvis der kun fandtes fysiske udgaver af materialet i beholdningen, når man lavede en simpel søgning.": [CMS-1872](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1872)

---  

Releasedato: 22-01-2026

**Redaktør**: Produktionssites: 2026.4.0

**Webmaster**: Produktionssites: 2026.2.4, Moduletestsites: 2026.4.0 


## Ny udvikling

•	Værkvisningssiden: Oplysninger om konkret indhold (når de findes i brønden) bliver vist sammen med Beskrivelse på værkvisningssiden samt for hver udgave på værkvisningssiden. [CMS-1618](https://detdigitalefolkebibliotek.atlassian.net/servicedesk/customer/portal/4/CMS-1618)

Bemærk: Overskrifterne Beskrivelse, Delindhold og Indhold vises kun, når der er indhold i de respektive felter, så tomme overskrifter ikke længere vises. Oplysninger om konkret indhold er f.eks. de enkelte kapitler i en antologi eller fagbog, de enkelte noveller i en novellesamling eller sanglisten fra en musik CD.

•	Avanceret søgning: "Enten eller" funktion til filtrene: Online/Fysisk, Fiktion/Nonfiktion og Voksne/Børn kan nu vælges som gensidigt udelukkende filtre, og den tidligere listebaserede adgangstype-filtrering er fjernet i samme omgang.

## Forbedringer og fejlrettelser
•	GO: Billeder i kategori bånd er nu korrekt placeret (Safari mobil)

•	GO skal ikke vise afpublicerede noder. Tidligere har der været en fejl i caching, som har bevirket, at afpublicerede noder har kunnet vises. 

•	Der bør være besked til redaktører i backend om at indhold er låst, når man forsøger at slette det låste indhold, fremfor at det bare fejler. Bemærk: Der vises nu altid en advarsel, når man forsøger at slette indhold, der er låst – uanset om låsen ligger på ens egen bruger eller en anden brugers.

