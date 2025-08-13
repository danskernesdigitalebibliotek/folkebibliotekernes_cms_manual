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
- "FBS"
- "Faste sider"
---

I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/config/dpl-library-agency/general-settings`

De generelle biblioteksindstillinger skal udfyldes, så de matcher jeres forretningsgange og indstillinger i Cicero. Sæt dig derfor sammen med jeres lokale Cicero Sysadmin og gå felterne igennem ét for ét.

## SMS notifikationer
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/aab48f76-0977-4f84-8be0-ab1de803330e" alt="Angiv om I sender SMS notifikationer" caption="Angiv om I sender SMS notifikationer" %} 

Nogle kommuner tilbyder at sende SMS notifikationer til brugerne om deres lån og reserveringer, mens andre kommuner af økonomiske hensyn har fravalgt dette tilbud. SMS beskederne sendes fra FBS. 

Her skal I angive, om I tilbyder SMS notifikationer eller ej. Hvis denne indstilling er grøn, betyder det, at slutbrugerne får mulighed for at tilvælge SMS i deres brugerprofil.

## Interesseperiode for reserveringer
Alle reserveringer, der bliver oprettet, tildeles en interesseperiode. Hvis slutbrugeren ikke selv vælger en interesseperiode, bruges som udgangspunkt default-værdien. Slutbrugeren har mulighed for at tilpasse interesseperioden på hver enkelt reservering. I bestemmer default interesseperioden og hvilke interesseperioder, der skal kunne vælges imellem.

### Opret interesseperiode valgmulighederne
Jeres site fødes med kun én værdi. Det er "180-6 måneder". Det betyder en interesseperiode på 180 dage. Denne periode er også default-værdien. Hvis I har brug for at sætte en anden default interesseperiode, eller gerne vil give jeres brugere adgang til flere valgmuligheder gør sådan:

1. I feltet **Interesseperiode for reserveringer** tilføjer I en eller flere nye interesseperiode. Hvis I vil tilføje interesseperioden 1 år, tilføjer I linjen "365-1 år" Bemærk det særlige format: [Antal dage]-[Tekst der vises til slutbrugeren].
2. Nu gemmer I formularen. Tryk på **Gem indstillinger** nederst på siden.
3. Nu er de nye interesseperioder gemt som valgmuligheder, som slutbrugerne kan vælge imellem på dreres reserveringer.

### Standard interesseperiode for reserveringer
Efter I har gemt bliver de nye interesseperiode tilgængelige i **Standard interesseperiode for reserveringer** dropdown. Vælg den nye default-interesseperiode og tryk så igen på **Gem indstillinger** nederst på siden. 

{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/800a5193-e413-473f-8dd6-4e0cb78a53b5" alt="Standard interesseperiode for reserveringer" caption="Standard interesseperiode for reserveringer" %} 
 
## Tillad sletning af opfyldte reserveringer
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/25a42b99-47fa-468d-af1e-b5ad3dc11667" alt="Angiv her, om I vil tillade at brugerne sletter opfyldte reserveringer" caption="Angiv her, om I vil tillade at brugerne sletter opfyldte reserveringer" %} 

Her vælger I, om brugerne må slette en reservering, der er opfyldt. Som standard er det ikke tilladt. Hvis det skal være tilladt, skal det aktiveres her.

## Link til side om reserveringspause
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/4cc4467c-736d-4215-982b-7fa22e3c3067" alt="Angiv her URL til side om reserveringspause" caption="Angiv her URL til side om reserveringspause" %} 

**Pausefunktion** er navnet på en [fast side](https://danskernesdigitalebibliotek.github.io/folkebibliotekernes_cms_manual/main/indhold/faste-sider/) som Folkebibliotekernes CMS leveres med.
Ønsker I ikke at bruge pausefunktion-standardsiden, kan man her udfylde med URL til en alternativ side.

|Feltnavn|Anbefalet værdi|
|---|---|
|Link til side om reserveringspause|URL til side om Pausefunktionen. Standardværdien er `/pausefunktion`|

## Link til åbningstider
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/99ecacda-9899-4b3a-9728-06f4d1e0e79e" alt="Link til åbningstider" caption="Link til åbningstider" %} 

## Advarsel om at udløbsdato nærmer sig
{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c63dc258-09e6-4456-8791-e3444e7c74f6" alt="Advarsel om at udløbsdato nærmer sig" caption="Advarsel om at udløbsdato nærmer sig" %} 

Materialer, der snart skal afleveres, vises fremhævet på brugerens dashboard. I bestemmer, hvor mange dage før afleveringsfriste,n at denne fremhævning starter.

{% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2ac3dcb8-8c9a-4b57-a844-dc5f6663fafc" alt="Sådan fremhæves materialer der snart skal afleveres på dashboard" caption="Sådan fremhæves materialer der snart skal afleveres på dashboard" %} 

Det er vigtigt at denne indstilling passer sammen med FBS-indstillingen "Periode hvor lån kan fornyes", så I undgår at hjemmesiden opfordre til at forny lån, der ikke kan/må fornys.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/b2d1ab40-8592-483b-ac68-7698e5a9d411" alt="Det er vigtigt at synkronisere med FBS-indstillingen 'Periode hvor lån kan fornyes'" caption="Det er vigtigt at synkronisere med FBS-indstillingen 'Periode hvor lån kan fornyes'" %} 

Hvis "Periode hvor lån kan fornys" i FBS er sat til 7, da skal denne indstilling sættes til 6 eller mindre.

## Blacklistede filialer
Mange biblioteker har filialer, hvis materialer ikke er tilgængelige for slutbrugerne (fx på gymnasier,
hospitaler, fængsler, plejehjem), og disse skal skjules på hjemmesiden. Dette gøres ved at blackliste
de pågældende filialer.

- Blacklist i **Søgning** hvis filialens materialer ikke skal vises i søgeresultater.
- Blacklist i **Tilgængelighhed** hvis filialens materialer ikke skal indgå  i beholdningsvisning og heller ikke indgå når tilgængelighed beregnes
- Blacklist i **Afhentningsbibliotek** så det ikke bliver muligt for slutbrugere at vælge filialen som afhentningsbibliotek 

## VIP profiler
Inden I kan udfylde disse felter skal I have oprettet de to påkrævede [søge- og visningsprofiler i VIP]({{ site.baseurl }}{% link _soegning/vip-profiler.md %}).

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d8edea7f-ba6c-4b1e-b1b1-47487c9630e0" alt="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" caption="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" %} 

### Anbefalede indstillinger for VIP profiler

|Feltnavn|Værdi|
|---|---|
|Standardprofil|Navnet på jeres **søgeprofil** i VIP|
|Søgningsprofil|Navnet på jeres **søgeprofil** i VIP|
|Visningsprofil|Navnet på jeres **visningsprofil** i VIP|






