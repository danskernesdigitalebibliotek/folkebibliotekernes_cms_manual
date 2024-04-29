---
title: "Opgave 10: Reparer link fra Adgangsplatformen til Opret bruger"
category: "Startopsætning"
weight: 10
emneord:
  - Adgangsplatformen
---
Fra **Adgangsplatformen** er der et link til siden **Opret bruger** på jeres gamle hjemmeside. Det link skal pege på den nye hjemmeside fra den dag I går live. Det kan I selv sørge for, ved at lave et redirect. 

I må gerne oprette redirect med det samme. Det har ingen effekt før I går live, så det ødelægger ikke noget.
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/27deb1eb-6372-4d24-beff-47b36e52569f)

## Sådan opretter i et redirect fra Adgangsplatformen til Opret bruger siden
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/7a8cc0a8-38b3-412d-94d2-b95501cd8447)

For at sikre at Adgangsplatformen peger på den rigtige brugeroprettelsesside, skal I tilføje et redirect til jeres site.
1. Log ind med en bruger der har rollen **Lokal administrator**
2.	Vælg **Redirects** i hovedmenuen
3.	I feltet **Sti** skriver du `registration`
4.	I feltet **Til** skriver du `/opret-bruger`
5.	**Gem**
