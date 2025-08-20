---
title: "7 Adgangsplatformen - omdiriger link til brugeroprettelsesside"
category: "Opgaver - Basiskonfiguration"
weight: 9
---
Adgangsplatformens login-side har et link med teksten "Ny bruger?". Det henviser til en side med adressen `/registration` på jeres hjemmeside. Problemet er at den side ikke findes i Folkebibliotekernes CMS.

I Folkebibliotekernes CMS ligger oprettelsessiden på adressen `/opret-bruger`. Der skal derfor laves en omdirigering, så forespørgsler til `/registration` viderestilles til `/opret-bruger`. Det hedder et **redirect** og det skal I selv oprette. 

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/27deb1eb-6372-4d24-beff-47b36e52569f" alt="Få Adgangsplatformen til at pege på den rigtige brugeroprettelsesside" caption="Få Adgangsplatformen til at pege på den rigtige brugeroprettelsesside" %}

## Opret redirect fra /registration til /opret-bruger

For at sikre at Adgangsplatformen peger på den rigtige brugeroprettelsesside, skal I tilføje et redirect til jeres site.
1. Log ind med en bruger, der har rollen **Lokal administrator**
2.	Vælg **Redirects** i hovedmenuen
3.	I feltet **Sti** skriver du `registration`
4.	I feltet **Til** skriver du `/opret-bruger`
5.	**Gem**

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f667990e-fa06-43da-8a55-c51ff41e8ce8" alt="Opret redirect fra Adgangsplatformen til siden Opret bruger" caption="Opret redirect fra Adgangsplatformen til siden Opret bruger" %}

