---
title: "Generelle indstillinger"
category: "Biblioteksindstillinger"
emneord: 
- "Søgning"
---
De generelle biblioteksindstillinger skal udfyldes så de stemmer overens med de systemindstillinger i har valgt i Cicero. Sæt dig sammen med jeres lokale Cicero Sysadmin og gå felterne igennem ét for ét.

## Her finder du Generelle Indstillinger
I topmenuen klik på **Indstillinger > Biblioteksindstillinger > Generelle indstillinger**

Eller åbn via direkte link (udskift mit-domænenavn.dk):\
https://mit-domænenavn.dk`/admin/config/dpl-library-agency/general-settings`

## Blacklistede filialer
Mange biblioteker har filialer, hvis materialer ikke er tilgængelige for slutbrugerne (fx på gymnasier,
hospitaler, fængsler, plejehjem), og disse skal skjules på hjemmesiden. Dette gøres ved at blackliste
de pågældende filialer.

- Blacklist i **Søgning** hvis filialens materialer ikke skal vises i søgeresultater.
- Blacklist i **Tilgængelighhed** hvis filialens materialer ikke skal indgå  i beholdningsvisning og heller ikke indgå når tilgængelighed beregnes
- Blacklist i **Afhentningsbibliotek** så det ikke bliver muligt for slutbrugere at vælge filialen som afhentningsbibliotek 

## SMS notifikationer
Nogle kommuner tilbyder at sende SMS notifikationer til brugerne om deres lån og reserveringer, mens andre kommuner af økonomiske hensyn har fravalgt dette tilbud. SMS beskederne sendes fra FBS. 

Her skal I angive, om I tilbyder SMS notifikationer eller ej. Hvis denne indstilling er grøn, betyder det, at slutbrugerne får mulighed for at tilvælge SMS i deres brugerprofil.

## Interesseperiode for reserveringer
Her sættes default-værdien for Interesseperiode. Alle reserveringer, der bliver oprettet, tildeles en interesseperiode. Hvis slutbrugeren ikke selv vælger en interesseperiode, bruges som udgangspunkt default-værdien. Slutbrugeren har mulighed for at tilpasse interesseperioden på hver enkelt reservering. 

Jeres site fødes med værdien "180-6 måneder". Dvs. en interesseperiode på 180 dage. Teksten, der vises til slutbrugeren er "6 måneder".
I må meget gerne tilpasse denne værdi til jeres behov.

**Bemærk det særlige format!** [Antal dage]-[Tekst der vises til slutbrugeren]


## FBI Profiles
Inden I kan udfylde disse felter skal I have oprettet de to påkrævede [søge- og visningsprofiler i VIP](/bliv-klar-til-folkebibliotekernes-cms/10vip-profiler/). 

### Anbefalede indstillinger for FBI Profiles

|Feltnavn|Værdi|
|---|---|
|Default profile|Navnet på jeres **søgeprofil** i VIP|
|Search profile|Navnet på jeres **søgeprofil** i VIP|
|Material profile|Navnet på jeres **visningsprofil** i VIP|

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d8edea7f-ba6c-4b1e-b1b1-47487c9630e0" alt="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" caption="Udfyld de to øverste felter med navnet på søgeprofilen. Nederste felt udfyldes med navnet på visningsprofilen" %} 

