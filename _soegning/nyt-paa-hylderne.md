---
title: "'Nyt på hylderne' komponent via Avanceret søgning"
category: "Søgning"
weight: 10
---

Mange biblioteker vil gerne bruge hjemmesiden til at fremhæve nyindkøbte materialer. F. eks. nye YA-titler, krimier eller Blu-ray film. Nogen gør det på hjemmesidens forside, mens andre opretter særskilte  “Nyt på hylderne”-sider.
Materialerne præsenteres i den paragraph type der hedder **Material grid automatic**. Man kan sagtens have flere af dem på samme side, som vist herunder.

<billede>
  
Når man på sin side indsætter en ny Material grid automatic paragraph opdager man, at der er mange felter, der skal udfyldes. Der skal angives både *søgestreng* og *sortering* og *filtrering*. Og selv den mindste tastefejl resulterer i 0 resutater.
Derfor er anbefaler vi at opbygge søgestreng, sortering og filtrering i Avenceret søgning og så bruge den indbyggede kopi-funktion til at udfylde felterne i sit Material Grid Automatic paragraph.

### Her er en trin for trin guide:

**CASE: Vi opretter en Material Grid Automatic komponent, der viser nye krimier, som er indkøbt inden for de seneste 6 måneder og som sorteres med nyeste først.**

### 1. Gå ind i **CQL-søgning** under **Avanceret søgning**
Lav en søgning på emnet. Glem i første omgang alt om sortering og filtrering på alder. Det kommer senere.
Søgning kan enten opbygges via brugergrænsefladen i Avanceret søgning eller skrives direkte som CQL søgning. Forfin din søgning indtil du er tilfreds med din søgning i forhold til at ramme den ønskede slags materialer.
[Læs mere om CQL-søgning her](https://www.folkebibliotekernescms.dk/main/soegning/cql-soegestrenge/)

### 2. Afgræns på alder
Aldersafgrænsingen skal du IKKE forsøge at bygge ind i din søgning, for det kan man ikke. 

- Aldersafgrænsning laver man ved at **filtrere** på **firstaccessiondateitem**.
- Hvis man vil have det allernyeste først tilføjer man også **sortering** på **Nyeste først**.

Når man filtrerer på *firstaccessiondateitem*, kan man gøre det på forskellige måder:
- Man kan indstille datointervallet som “senere end” (standard), “præcis dato” eller “tidligere end“
- Dato kan angives enten som en bestemt dato, f.eks. 2025-07-08, eller via termerne “NOW”, “DAYS” og “MONTHS”
  
I tilfældet med nye materialer giver det bedst mening at vælge “senere end” og så angive f.eks. “NOW - 90 DAYS” for at vise indkøb indenfor de sidste 90 dage.
Fordelen ved at angive en periode med “NOW” og x antal dage eller måneder, er at den søgning + filtrering vedligeholder sig selv, mens en filtrering på “senere end” + en bestemt dato kræver, at man periodisk retter datoen manuelt.

**Hvilket aldersinterval skal man vælge?**: Det afhænger af hvor meget der indkøbes. Gør man intervallet for smalt, så man f. eks. kun viser matetialer indkøbt de seneste 3 måneder, da risikerer man måske tomme displays i perioder med mindre asccession.
{: .notice--info}

**OBS vedr. digitale materialer**: Filteret *firstaccessiondateitem* virker ikke på e-bøger og andre digitale materialer.  
{: .notice--info}

### 3. Tryk på kopier-knappen
Når man er tilfreds med sin søgning/sortering/filtrering trykker man på knappen “Link til denne søgning”, hvilket kopierer søgningen over i ens udklipsholder, og er lige til at indsætte i en Material grid automatic i link-feltet.
Når man trykker på knappen “Load filters from URL” i sin Material grid automatic, trækkes ens søgning (inkl. “på hylden”), sortering og filtering ind i Material grid automatic, der herefter blot skal navngives og vælges antal materialer der skal vises og evt. suppleres med en beskrivelse. Man gentager samme procedure for alle de Material grid automatic, man vil oprette på sin “Nyt på hylderne”-side.
