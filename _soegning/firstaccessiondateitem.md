---
title: "Nyt filtreringsindeks firstaccessiondateitem"
category: "Søgning"
weight: 30
---

Med virkning fra 1. august 2025 nedlægges søgekoden `firstaccessiondate` i Complex Search / Avanceret søgning. Den erstattes af et nyt filtreringsindeks med navnet `firstaccessiondateitem`.

## Baggrund

Søgekoden `firstaccessiondate` har desværre aldrig fungeret hensigtsmæssigt i forhold til at afgrænse nyindkøb i lokale beholdninger. Det har derfor været svært for biblioteker at bygge inspirationssider med nyindkøbte materialer på deres hjemmesider. Det vil det nye filreringsindeks råde bod på.

Det er *Det Digitale Folkebibliotek*, der har taget initiativ til ændringen. 

## Betydning for hjemmesiderne
Materialekomponenter bygget på søgestrenge, som indeholder søgekoden *firstaccessiondate* vil holde op med at virke pr. 1. oktober.

Det samme gælder, hvis I har bygget avancerede søgninger med *firstaccessiondate* og lagt dem som links på jeres side.

**VIGTIGT!** Alle materialekomponenter og links til avancerde søgninger, der gør brug af *firstaccessiondate*, skal tilrettes inden den **1. oktober**. Ellers holder de op med at virke.
{: .notice--warning}

Problemet er typisk knyttet til *Nyt på hylderne* oversigter. Nogle biblioteker har rigtig mange - andre har slet ingen. Har I ikke den type lister på jeres hjemmeside, så er I ikke ramt af problemstillingen.

### Hjælpeværktøj til at identificere problem-indhold

I backend på jeres CMS har I adgang til en liste over sider med materialekomponenter, der gør brug af *firstaccessiondate*. Tjek den for at se om I er ramt.

1. Log ind i backend på jeres hjemmeside. 
2. Åbn siden
`https://mit-domænenavn.dk/admin/content/firstaccessiondate` (udskift mit-
domænenavn.dk)


3. Nu åbner en tabel med alle forekomster af *Material Grid Automatic* der bruger *firstaccessiondate*.
  TIP: I kan sortere listen efter feltet `Forfatter på siden` for at få et overblik over hvilke medarbejdere, der har oprettet indholdskomponenter, der skal tilrettes. Den der i sin tid skrev CQL-søgestrengen, vil måske være den bedste til at kontrollere om den virker efter den er tilrettet.

  

Listen indeholder desværre også *GO-indhold*, som I IKKE MÅ tilrette. Det klarer DDF via Delingstjenesten. I skal kun behandle indhold i selv har oprettet. GO-indhold kan kendes på at siden er oprettet af *Anonym*. 
{: .notice--info}

4. Klip på **Rediger** knappen ud for hver enkelt søgning for at rette den.

### Tilretning af *Material Grid Automatic*-komponenter, der bruger *firstaccessiondate*

Problem-indhold er alle *Material Grid Automatic*-komponenter, der bruger *firstaccessiondate* i CQL-søgestrengen.

Det der skal ske med dem er følgende:
- Slet *firstaccessiondate* under **CQL-søgning**
- Tilføj dato-interval under **firstaccessiondateitem**

