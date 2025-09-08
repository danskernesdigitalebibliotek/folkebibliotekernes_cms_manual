---
title: "Nyt filtreringsindeks firstaccessiondateitem"
category: "Søgning"
weight: 30
---

Med virkning fra 1. oktober 2025 nedlægges søgekoden `firstaccessiondate` i Complex Search / Avanceret søgning. Den erstattes af et nyt filtreringsindeks med navnet `firstaccessiondateitem`.

Bemærk at firstaccessiondateitem ikke kan bruges til at søge digitale materialer frem fx fra eReolen.

## Baggrund

Søgekoden `firstaccessiondate` har desværre aldrig fungeret hensigtsmæssigt i forhold til at afgrænse nyindkøb i lokale beholdninger. Det har derfor været svært for biblioteker at bygge inspirationssider med nyindkøbte materialer på deres hjemmesider. Det vil det nye filreringsindeks råde bod på.

Det er *Det Digitale Folkebibliotek*, der har taget initiativ til ændringen. 

## Betydning for hjemmesiderne

Materialekomponenter bygget på søgestrenge, som indeholder søgekoden *firstaccessiondate* vil holde op med at virke pr. 1. oktober.

Det samme gælder, hvis I har bygget avancerede søgninger med *firstaccessiondate* og lagt dem som links på jeres side.

**VIGTIGT!** Alle materialekomponenter og links til avancerde søgninger, der gør brug af *firstaccessiondate*, skal tilrettes inden den **1. oktober**. Ellers holder de op med at virke.
{: .notice--warning}

Problemet er typisk knyttet til **Nyt på hylderne** oversigter. Nogle biblioteker har rigtig mange - andre har slet ingen af dem.

<img width="1889" height="919" alt="image" src="https://github.com/user-attachments/assets/265d0345-fb84-4830-8012-c79e447aaae0" />

### Hjælpeværktøj til at identificere problem-indhold
I backend på jeres CMS kan I se en liste over sider med materialekomponenter, hvor *firstaccessiondate* er anvendt. Tjek den, for at se om I er ramt.

1. Log ind i backend på jeres hjemmeside. 
2. Åbn siden
`https://mit-domænenavn.dk/admin/content/firstaccessiondate` (udskift mit-
domænenavn.dk)


3. Nu åbner en tabel med alle forekomster af *Material Grid Automatic* der bruger *firstaccessiondate*.

4. Klik på **Rediger** knappen ud for hver enkelt søgning for at rette den.

**TIP:** I kan sortere listen efter feltet `Forfatter på siden` for at få et overblik over hvilke medarbejdere, der har oprettet indholdskomponenter, der skal tilrettes. Den person, der i sin tid skrev CQL-søgestrengen, vil måske være den bedste til at kontrollere om den virker som den skal efter tilretning.

**BEMÆRK** Listen indeholder desværre også *GO-indhold*, som I IKKE MÅ tilrette. Det styrer DDF via Delingstjenesten. I skal kun behandle indhold i selv har oprettet. GO-indhold kan kendes på at siden er oprettet af **Anonym**. 
{: .notice--info}

<img width="799" height="294" alt="image" src="https://github.com/user-attachments/assets/6dd4fa37-54a7-414b-96af-c21aea1d721d" />



### Sådan tilrettes indhold

Alle **Material Grid Automatic**-komponenter, der bruger **firstaccessiondate** i CQL-søgestrengen, skal tilrettes.

Der er to trin:

#### 1. Slet *firstaccessiondate* i CQL-søgestrengen
<img width="752" height="181" alt="image" src="https://github.com/user-attachments/assets/212a71c7-0c3a-47a2-ab1a-648bed3359da" />

Inden du sletter, så bemærk værdien. Det er jo den, der hidtil har fungeret som aldersafgrænsning. Den kan være sat til alt fra nogle få måneder til flere år.


#### 2. Tilføj dato-interval under *Firstaccessiondateitem: Værdi*
Nu skal du tilføje aldersafgrænsningen som et filter i feltet **Firstaccessiondateitem: Værdi**

Inden du bare indsætter en kopi af den værdi, som du lige slettede, så overvej om det kan gøres smartere.

Dato kan angives som en bestemt dato, f.eks. 2025-07-08. Men det kan også gøres via termerne “NOW”, “DAYS” og “MONTHS”. 

Eksempler:
- “NOW - 90 DAYS” viser indkøb inden for de sidste 90 dage
- "NOW - 12 MONTHS" viser indkøb inden for det seneste år

Fordelen ved at angive en periode med “NOW” og x antal dage eller måneder, er at den filtrering vedligeholder sig selv, mens en filtrering på “senere end” plus en bestemt dato kræver, at man periodisk retter datoen manuelt.

<img width="758" height="561" alt="image" src="https://github.com/user-attachments/assets/905cad04-f0b1-4c83-9b0c-00b16481c7f0" />




