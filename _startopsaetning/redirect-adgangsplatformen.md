---
title: "Opgave 9: Få Adgangsplatformen til at pege på den rigtige brugeroprettelsesside"
category: "Basis konfiguration"
weight: 9
---
Fra **Adgangsplatformen** er der et link til siden registration på jeres gamle hjemmeside. Det link skal ændres, så det peger på siden **Opret bruger**, fra den dag I går live. Det skal I selv sørge for, ved at lave et redirect. 

I må gerne oprette redirect nu med det samme. Det har ingen effekt før I går live, så det ødelægger ikke noget.
{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/27deb1eb-6372-4d24-beff-47b36e52569f" alt="Få Adgangsplatformen til at pege på den rigtige brugeroprettelsesside" caption="Få Adgangsplatformen til at pege på den rigtige brugeroprettelsesside" %}

## Lav et redirect fra Adgangsplatformen til Opret bruger siden
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f667990e-fa06-43da-8a55-c51ff41e8ce8" alt="Opret redirect fra Adgangsplatformen til siden Opret bruger" caption="Opret redirect fra Adgangsplatformen til siden Opret bruger" %}

For at sikre at Adgangsplatformen peger på den rigtige brugeroprettelsesside, skal I tilføje et redirect til jeres site.
1. Log ind med en bruger, der har rollen **Lokal administrator**
2.	Vælg **Redirects** i hovedmenuen
3.	I feltet **Sti** skriver du `registration`
4.	I feltet **Til** skriver du `/opret-bruger`
5.	**Gem**

