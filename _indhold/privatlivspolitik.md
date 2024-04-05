---
title: "Privatlivspolitik"
emneord:
- "Faste sider"
---

**Privatlivspolitik** er en oplysningsside om behandling af personoplysninger. Det er et lovkrav at have en privatlivspolitik på hjemmesiden.

Der link til privatlivspolitik to steder i Folkebibliotekernes CMS:

- Fra servicemenuen i footeren under “Behandling af persondata”. (Denne er på nuværende tidspunkt hardcoded, hvilket rettes i kommende release. Det ønskes at titlen på linket skal være “Privatlivspolitik” så det matcher “Privatlivspolitik” siden. XX)
  
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c166ec9c-d227-4070-bd76-0c30305ceaed" alt="Der er link til privatlivspolitik fra servicemenuen i footeren" caption="Der er link til privatlivspolitik fra servicemenuen i footeren" %} 

- Fra bunden af brugerprofilen (/user/me), hvor linket hedder "Sådan sletter du din brugerprofil".

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d5250e9e-20c7-495f-9946-6056a9950067" alt="Der er link til privatlivspolitik fra bunden af brugerprofilen" caption="Der er link til privatlivspolitik fra bunden af brugerprofilen" %} 


## Tilret teksten på siden Privatlivspolitik

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/955e98ec-3af8-4841-b620-eafcf313a86a" alt="Find siden Privatlivspolitik under indhold og tilret teksten efter jeres behov" caption="Find siden Privatlivspolitik under indhold og tilret teksten efter jeres behov" %} 

Standardteksten må gerne tilrettes:
1. Find siden der hedder **Privatlivspolitik**. Den kan fremsøges under **Indhold**.
2. Tryk på **Rediger siden** og tilret teksten efter ønske.
3. Tryk **Gem**

## Erstat den faste side Privatlivspolitik med en anden side

Er du kommet til at slette siden Privatlivspolitik, kan du oprette en ny side, og få de indbyggede links til at pege på den.

### Sådan ændrer du linket i bunden af brugerprofilen:
1. Opret en ny side, der skal erstatte den faste side Privatlivspolitik. Læg mærke til sidens URL. Den kan du se i browserens adresselinje. Det er den sidste del der er interessant. Den hedder noget med **node/xxx**. (xxx er et tal)
2. Nu skal du registerer den nye sides URL i indstillinger for websiden. Log ind med en bruger, der har rollen **Lokal administrator**.
3. I topmenuen klik på **Indstillinger > Biblioteksindstillinger > Indstillinger for brugerprofil**\
Eller åbn via URL: https://mit-domænenavn.dk/admin/config/dpl-library-agency/patron-page-settings (udskift mit-domænenavn.dk)
4. På siden **Indstillinger for brugerprofil** find feltet **Url til side om hvordan man bliver slettet som bruger af biblioteket**
5. Udfyld med den relative URL på den nye side. Dvs. `node/xxx`, hvor xxx er et tal.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/69bc79be-20e9-42a6-a10f-18cb52aff1b7" alt="Læg mærke til den nye sides URL" caption="Læg mærke til den nye sides URL." %} 

### Sådan ændrer du linket i footerens servicemenu
Pt. er linket i servicemenuen hardcodet og kan ikke ændres. XX

Der linkes til denne side under “Delete patron link” på /admin/config/dpl-library-agency/patron-page-settings . 
Se eksempel på Privatlivspolitik | DPL CMS (reload.dk)

Denne side linkes der til fra brugeroprettelsessiden.

## Privatlivspolitik standardteksten
Har du mistet standardteksten, så er den her:
[Standardteksten til siden Privatlivspolitik](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/takster-standardtekst/)


Nederst på Brugerprofil (user/me)


