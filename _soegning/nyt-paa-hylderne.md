---
title: "'Nyt på hylderne' komponent via Avanceret søgning"
category: "Søgning"
weight: 10
---

Mange biblioteker vil gerne bruge hjemmesiden til at fremhæve nyindkøbte materialer. F. eks. nye YA-titler, krimier eller Blu-ray film. Nogen gør det på hjemmesidens forside, mens andre opretter særskilte  “Nyt på hylderne”-sider.
Materialerne præsenteres i den paragraph type der hedder **Material grid automatic**. Man kan sagtens have flere af dem på samme side, som vist herunder.

<img width="1889" height="919" alt="image" src="https://github.com/user-attachments/assets/265d0345-fb84-4830-8012-c79e447aaae0" />
  
Når man på en side indsætter en ny Material grid automatic paragraph opdager man, at der er mange felter, der skal udfyldes. Der skal angives både *søgestreng* og *sortering* og *filtrering*. Og selv den mindste tastefejl resulterer i 0 resutater.
Derfor anbefaler vi at opbygge søgestreng, sortering og filtrering i Avanceret søgning og så bruge den indbyggede kopi-funktion til at udfylde felterne i sit Material Grid Automatic paragraph.

### Her er en trin for trin guide:

**CASE: Vi opretter en Material Grid Automatic paragraph, der viser nye krimier, som er indkøbt inden for de seneste 6 måneder og som sorteres med nyeste først.**

### 1. Gå ind i **CQL-søgning** under **Avanceret søgning**
<img width="899" height="188" alt="image" src="https://github.com/user-attachments/assets/e6f81a6c-5618-4d1e-82e3-60e362c0cfc6" />

### 2. Lav en søgning på emnet. 

Glem i første omgang alt om sortering og filtrering på alder. Det kommer senere.

<img width="901" height="288" alt="image" src="https://github.com/user-attachments/assets/c5a1eabf-bc8d-4856-b295-1aadae2a34f6" />

Søgning kan enten opbygges via brugergrænsefladen i Avanceret søgning eller skrives direkte som CQL søgning. Forfin din søgning indtil du er tilfreds med din søgning i forhold til at ramme den ønskede slags materialer.
[Læs mere om CQL-søgning her](https://www.folkebibliotekernescms.dk/main/soegning/cql-soegestrenge/)

### 3. Afgræns på alder
Aldersafgrænsingen skal du IKKE forsøge at bygge ind i din søgning, for det kan man ikke. 

- Aldersafgrænsning laver man ved at **filtrere** på **firstaccessiondateitem**.
- Hvis man vil have det allernyeste først tilføjer man også **sortering** på **Nyeste først**.

Når man filtrerer på *firstaccessiondateitem*, kan man gøre det på forskellige måder:
- Man kan indstille datointervallet som “senere end” (standard), “præcis dato” eller “tidligere end“
- Dato kan angives enten som en bestemt dato, f.eks. 2025-07-08, eller via termerne “NOW”, “DAYS” og “MONTHS”

<img width="991" height="331" alt="image" src="https://github.com/user-attachments/assets/3e4e6ec9-bc9c-457c-8ae8-5dafcf8f95fe" />

*Filtrering på firstaccessiondateitem*

<img width="991" height="331" alt="image" src="https://github.com/user-attachments/assets/80b7695c-e7fc-4225-aaba-2e2fbfa9fc17" />

*Sortering efter nyeste først*

  
I tilfældet med nye materialer giver det bedst mening at vælge “senere end” og så angive f.eks. “NOW - 90 DAYS” for at vise indkøb indenfor de sidste 90 dage.
Fordelen ved at angive en periode med “NOW” og x antal dage eller måneder, er at den søgning + filtrering vedligeholder sig selv, mens en filtrering på “senere end” + en bestemt dato kræver, at man periodisk retter datoen manuelt.

**Hvilket aldersinterval skal man vælge?**: Det afhænger af hvor meget der indkøbes. Gør man intervallet for smalt, så man f. eks. kun viser matetialer indkøbt de seneste 3 måneder, da risikerer man måske tomme displays i perioder med mindre asccession.
{: .notice--info}

**OBS vedr. digitale materialer**: Filteret *firstaccessiondateitem* virker ikke på e-bøger og andre digitale materialer.  
{: .notice--info}

### 3. Tryk på kopier-knappen
Når man er tilfreds med sin søgning/sortering/filtrering trykker man på knappen **Link til denne søgning**, hvilket kopierer søgningen over i ens udklipsholder, og er lige til at indsætte i en Material grid automatic i link-feltet.


<img width="793" height="205" alt="image" src="https://github.com/user-attachments/assets/23249457-5119-447d-aa15-9e5695f7a9cb" />

*Kopier søgning til udklipsholder*

### 4. Indsæt i CQL Søgestreng feltet i Material Grid Automatic
Ovre i din Material Grid Automatic paragraph stiller du curseren i feltet CQL Søgestreng og vælger **Indsæt** eller **Ctrl + V**.
Der indsættes en lang ulæselig URL

<img width="1157" height="313" alt="image" src="https://github.com/user-attachments/assets/aeb03ccf-76e8-48ea-870d-6ce7dfb0449d" />

### 5. Tryk på knappen Hent filtre fra URL
Tryk så på knappen **Hent filtre fra URL**.

Nu sker der noget magisk! 
- Den ulæselige URL i CQL Søgestreng feltet omdannes til en pæn CQL søgestreng
- Feltet Sortering udfyldes med værdien fra din CQL Søgning
- Feltet Filtrering på Firstaccessiondateitem udfyldes med værdien fra din CQL Søgning
- "På hylden" indstilling udfyldes med værdien fra din CQL Søgning

<img width="942" height="817" alt="image" src="https://github.com/user-attachments/assets/56649502-2263-4203-96e4-326b20c4ccd4" />



