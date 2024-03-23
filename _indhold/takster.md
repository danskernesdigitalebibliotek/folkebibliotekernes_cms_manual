---
title: "Takster"
---
**Takster** er en informationsside om gebyrtakster, erstatninger og betaling.
Der linkes til denne side flere steder, bla. fra Gebyrer & Erstatninger, men også fra materialer, som er ved at udløbe.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/9cc5c619-8716-434b-8122-77ab2df80bcc" alt="Fra Gebyrer & erstatninger er der link til siden Takster" caption="Fra Gebyrer & erstatninger er der link til siden Takster" %} 

## Tilret teksten på siden Takster
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2965b5e9-631f-4def-96c1-a9ecc1989de3" alt="Find siden Takster under indhold og tilret teksten efter jeres behov" caption="Find siden Takster under indhold og tilret teksten efter jeres behov" %} 

Standardteksten må gerne tilrettes:
1. Find siden der hedder **Takster**. Den kan fremsøges under **Indhold**.
2. Tryk på **Rediger siden** og tilret teksten efter ønske.
3. Tryk **Gem**

## Erstat den faste side Takster med en anden side

Er du kommet til at slette siden Takster, kan du oprette en ny side, og få de indbyggede links til at pege på den.

1. Opret en ny side, der skal erstatte den faste side Takster. Læg mærke til sidens URL. Den kan du se i browserens adresselinje. Det er den sidste del der er interessant. Den hedder noget med **node/xxx**. (xxx er et tal)
2. Nu skal du registerer den nye sides URL i indstillinger for websiden. Log ind med en bruger, der har rollen **Lokal administrator**.
3. I topmenuen klik på **Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside**\
Eller åbn via URL: https://mit-domænenavn.dk/admin/config/dpl-library-agency/fees (udskift mit-domænenavn.dk)
4. På siden **Gebyrindstillinger** find feltet **URL**
5. Udfyld med den relative URL på den nye side. Dvs. `node/xxx`, hvor xxx er et tal.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/69bc79be-20e9-42a6-a10f-18cb52aff1b7" alt="Læg mærke til den nye sides URL" caption="Læg mærke til den nye sides URL." %} 

## Takster standardteksten
Har du mistet standardteksten, så er den her:
