---
title: "Generelle indstillinger"
click-path: "Indstillinger > Biblioteksindstillinger > Generelle indstillinger"
category: "Konfiguration"
emneord: 
- "Søgning"
- "Reserveringer"
- "SMS"
- "Interesseperiode"
- "VIP og søgeprofiler"
- "X mangler indhold"
---

I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/general-settings`

## Om Generelle indstillinger
De generelle biblioteksindstillinger skal udfyldes, så de matcher de forretningsgange, I benytter jer af på biblioteket. De er ofte udtrykt i via indstillinger i Cicero. Sæt dig derfor sammen med jeres lokale Cicero Sysadmin og gå felterne igennem ét for ét.

## SMS notifikationer
Nogle kommuner tilbyder at sende SMS notifikationer til brugerne om deres lån og reserveringer, mens andre kommuner af økonomiske hensyn har fravalgt dette tilbud. SMS beskederne sendes fra FBS. 

Her skal I angive, om I tilbyder SMS notifikationer eller ej. Hvis denne indstilling er grøn, betyder det, at slutbrugerne får mulighed for at tilvælge SMS i deres brugerprofil.

## Interesseperiode for reserveringer
Alle reserveringer, der bliver oprettet, tildeles en interesseperiode. Hvis slutbrugeren ikke selv vælger en interesseperiode, bruges som udgangspunkt default-værdien. Slutbrugeren har mulighed for at tilpasse interesseperioden på hver enkelt reservering. I bestemmer default interesseperioden og hvilke interesseperioder, der skal kunne vælges imellem.

### Opret interesseperiode valgmulighederne
Jeres site fødes med kun én værdi. Det er "180-6 måneder". Det betyder en interesseperiode på 180 dage. Denne periode er også default-værdien. Hvis I har brug for at sætte en anden default interesseperiode, eller gerne vil give jeres brugere adgang til flere valgmuligheder gør sådan:

1. I feltet **Interesseperiode for reserveringer** tilføjer I en eller flere nye interesseperiode. Hvis I vil tilføje interesseperioden 1 år, tilføjer I linjen "365-1 år" Bemærk det særlige format: [Antal dage]-[Tekst der vises til slutbrugeren].
2. Nu gemmer I formularen. Tryk på **Gem indstillinger** nederst på siden.
3. Nu er de nye interesseperioder gemt som valgmuligheder, som slutbrugerne kan vælge imellem på dreres reserveringer.

### Default interesseperiode for reserveringer
Efter I har gemt bliver de nye interesseperiode tilgængelige i **Default interesseperiode for reserveringer** dropdown. Vælg den nye default-interesseperiode og tryk så igen på **Gem indstillinger** nederst på siden. 

{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/800a5193-e413-473f-8dd6-4e0cb78a53b5" alt="Default interesseperiode for reserveringer" caption="Default interesseperiode for reserveringer" %} 
 
## Tillad sletning af opfyldte reserveringer
Her vælger I, om brugerne må slette en reservering, der er opfyldt. Som standard er det ikke tilladt. Hvis det skal være tilladt, skal det aktiveres her.

## Link til Min side på eReolen
Er som standard korrekt udfyldt. Den skal der ikke pilles ved.

|Feltnavn|Værdi|
|---|---|
|Link til Min side på eReolen|https://ereolen.dk/user/me|

## Link til eReolen
Er som standard korrekt udfyldt. Den skal der ikke pilles ved.

|Feltnavn|Værdi|
|---|---|
|Link til eReolen|https://ereolen.dk|

## Link til side om reserveringspause
Her skal du indsætte link til [siden Pausefunktionen, som I selv har oprettet]({{ site.baseurl }}{% link _startopsaetning/5obligatoriske-sider.md %}). Er du i tvivl om, hvordan du finder sidens URL kan denne denne guide hjælpe dig.
XX URL'er til indhold XX

Som standard er feltet ikke udfyldt. Det skal udfyldes. Ellers vises der et uvirksomt link til jeres brugere, når de benytter pausefuktionen.

|Feltnavn|Anbefalet værdi|
|---|---|
|Link til side om reserveringspause|URL til side om Pausefunktionen. Siden skal I selv oprette.|

## Blokeret bruger -  Link i modal til blokeret bruger (til fx Mit betalingsoverblik)
Hvis en bruger er blokeret pga. af overskredet gebyrgrænse vises en pop-up til brugeren ved login. I den pop-up har i mulighed for at tilføje link til jeres betalingsløsning - f. eks. Mit betalingsoverblik. Det er ikke påkrævet at udfylde feltet. Hvis det ikke er udfyldt vises der bare ingen link i pop-op vinduet. XX uddybende tekst om betalingsmuligheder XX
![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2585e42e-af01-44cc-a543-4df5494c22a7)

|Feltnavn|Anbefalet værdi|
|---|---|
|Link i modal til blokeret bruger|Link til betalingsside / alternativ side om betalingsmuligheder. (Ikke påkrævet)|



## FBI Profiles
Inden I kan udfylde disse felter skal I have oprettet de to påkrævede [søge- og visningsprofiler i VIP]({{ site.baseurl }}{% link _bliv-klar-til-folkebibliotekernes-cms/10vip-profiler.md %}).

### Anbefalede indstillinger for FBI Profiles

|Feltnavn|Værdi|
|---|---|
|Default profile|Navnet på jeres **søgeprofil** i VIP|
|Search profile|Navnet på jeres **søgeprofil** i VIP|
|Material profile|Navnet på jeres **visningsprofil** i VIP|

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d8edea7f-ba6c-4b1e-b1b1-47487c9630e0" alt="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" caption="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" %} 

## Blacklistede filialer
Mange biblioteker har filialer, hvis materialer ikke er tilgængelige for slutbrugerne (fx på gymnasier,
hospitaler, fængsler, plejehjem), og disse skal skjules på hjemmesiden. Dette gøres ved at blackliste
de pågældende filialer.

- Blacklist i **Søgning** hvis filialens materialer ikke skal vises i søgeresultater.
- Blacklist i **Tilgængelighhed** hvis filialens materialer ikke skal indgå  i beholdningsvisning og heller ikke indgå når tilgængelighed beregnes
- Blacklist i **Afhentningsbibliotek** så det ikke bliver muligt for slutbrugere at vælge filialen som afhentningsbibliotek 


