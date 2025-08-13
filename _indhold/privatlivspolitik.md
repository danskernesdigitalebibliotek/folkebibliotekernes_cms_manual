---
title: "Privatlivspolitik"
category: "Faste sider"
---

**Privatlivspolitik** er en oplysningsside om behandling af personoplysninger. Det er et lovkrav at have en privatlivspolitik på hjemmesiden og at linke til den fra forsiden.

Vi anbefaler, at I oprette et link til privatlivspolitikken i [servicemenuen](https://www.folkebibliotekernescms.dk/main/indhold/footermenu/#servicemenuen-og-links-til-sociale-medier), der er en del af footeren, og som vises i bunden af alle sider. Det link skal I selv oprette.

Der linkes desuden til privatlivspolitik fra bunden af brugerprofilen (/user/me), hvor linket hedder "Sådan sletter du din brugerprofil".

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d5250e9e-20c7-495f-9946-6056a9950067" alt="Der er link til privatlivspolitik fra bunden af brugerprofilen" caption="Der er link til privatlivspolitik fra bunden af brugerprofilen" %} 

## Privatlivspolitik og cookie information
Det er med vilje, at der ikke står noget om cookies i privatlivspolitikken. Folkebibliotekernes CMS kommer til at implementere cookie dialogboksen fra Cookie Information. Via teksten i denne dialogboks informeres korrekt og lovformeligt om cookies anvendt på sitet. Reglerne omkring cookie deklaration er komplekse, og vælger I selv at skrive om cookies, kan DDF ikke validere tekstens gyldighed.


## Tilret teksten på siden Privatlivspolitik

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/955e98ec-3af8-4841-b620-eafcf313a86a" alt="Find siden Privatlivspolitik under indhold og tilret teksten efter jeres behov" caption="Find siden Privatlivspolitik under indhold og tilret teksten efter jeres behov" %} 

Standardteksten må gerne tilrettes:
1. Find siden der hedder **Privatlivspolitik**. Den kan fremsøges under **Indhold**.
2. Tryk på **Rediger siden** og tilret teksten efter ønske.
3. Tryk **Gem**

## Erstat den faste side Privatlivspolitik med en anden side

Er du kommet til at slette siden Privatlivspolitik, kan du oprette en ny side, og få de indbyggede links til at pege på den.

### Sådan ændrer du linket i bunden af brugerprofilen:
1. Opret en ny side, der skal erstatte den faste side Privatlivspolitik. Læg mærke til sidens URL. Den kan du se i browserens adresselinje. Det er den sidste del efter domænenavnet, der er interessant.
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/6789dd1c-b697-40bc-92e6-489a2caf97f3" alt="Læg mærke til den nye sides URL" caption="Læg mærke til den nye sides URL." %} 
3. Nu skal du registerer den nye sides URL i indstillinger for websiden. Log ind med en bruger, der har rollen **Lokal administrator**.
4. I topmenuen klik på **Indstillinger > Biblioteksindstillinger > Indstillinger for brugerprofil**\
Eller åbn via URL: https://mit-domænenavn.dk/admin/config/dpl-library-agency/patron-page-settings (udskift mit-domænenavn.dk)
5. På siden **Indstillinger for brugerprofil** find feltet **Url til side om hvordan man bliver slettet som bruger af biblioteket**
6. Udfyld med den relative URL på den nye side. (den del der ligger efter domænenavnet)
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/172c1528-0518-48b4-ab07-131b15bebb71" alt="Indæt her" caption="Indsæt her" %} 

## Privatlivspolitik standardteksten
Har du mistet standardteksten, så er den her:
[Standardteksten til siden Privatlivspolitik](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/privatlivspolitik-standardtekst/)
