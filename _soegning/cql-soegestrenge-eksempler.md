---
title: "CQL Søgestrenge Eksempler"  
category: "Søgning"
weight: 15
---

### DBCs CQL dokumentation: [FBI-API's Complex Search Documentation](https://fbi-api.dbc.dk/indexmapper/){:target="_blank" rel="noopener"}
{: .notice--info}

Mette Kulmbach har været så venlig at dele nogle søgestrenge, som hun har bygget for Billund Bibliotekerne. De er til inspiration og er ikke perfekte eller udtømmende. Har du lavet søgestrenge, der er smartere eller mere korrekte, da send dine eksempler til cms-info@fddf.dk. Så lægger vi dem ud her på siden.

30/10-2024 - Opdateret med NOW - X days afgrænsninger

## For børn

#### Nyt på hylderne for børn - 6 til 8 år
`phrase.language=dansk AND ages within "6 8" and firstaccessiondate >= NOW - 90 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS`

#### Pegebøger
`term.genreandform=pegebøger AND  firstaccessiondate >= NOW - 90 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS`
 
#### Helt ny fantasy
`term.genreandform=fantasy AND ages within "6 14" and firstaccessiondate >= NOW - 90 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS`
 
#### Mere fantasy
`term.genreandform=fantasy AND  firstaccessiondate >= NOW - 60 DAYS AND publicationyear >= NOW - 180 DAYS AND datefirstedition >= NOW - 180 DAYS AND ages within "6 14"`

## For voksne

#### Nye krimier
`dk5="sk" and term.childrenoradults="til voksne"  and  term.genreandform="krimi" AND firstaccessiondate >= NOW - 60 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS`

#### Flere krimier
`firstaccessiondate >= NOW - 4 MONTHS AND publicationyear >= NOW - 8 MONTHS AND datefirstedition >= NOW - 8 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND phrase.genreandform=krimi AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Alle krimier
`term.childrenoradults="til voksne" AND phrase.genreandform=krimi AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Nye historiske romaner
`firstaccessiondate >= NOW - 60 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND (term.genreandform="historiske romaner" OR term.subject="historiske romaner") AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Humor
`firstaccessiondate >= NOW - 4 MONTHS AND publicationyear >= NOW - 8 MONTHS AND datefirstedition >= NOW - 8 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=humor* AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Mere humor
`firstaccessiondate >= NOW - 18 MONTHS AND publicationyear >= NOW - 36 MONTHS AND datefirstedition >= NOW - 36 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=humor* AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Ny bøger om kærlighed
`firstaccessiondate >= NOW - 60 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=kærlig* AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Nye bøger om erotik
 firstaccessiondate >= NOW - 8 MONTHS AND publicationyear >= NOW - 8 MONTHS AND datefirstedition >= NOW - 8 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" and term.subject="erotik*" not term.genreandform="krimi"

 #### Ny chick lit
 `firstaccessiondate >= NOW - 90 MONTHS AND publicationyear >= NOW - 12 MONTHS AND datefirstedition >= NOW - 12 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=chick* AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Fantasy
`firstaccessiondate > 2024-01-01 and dk5="sk" and term.childrenoradults="til voksne" and term.subject="fantasy*" not term.genreandform="krimi" and term.generalmaterialtype="bøger" and hascover=true`

#### Faglitteratur
`firstaccessiondate >= NOW - 90 DAYS AND publicationyear >= NOW - 90 DAYS AND datefirstedition >= NOW - 90 DAYS and term.childrenoradults="til voksne" and term.fictionnonfiction="nonfiction" and phrase.specificmaterialtype="bog”`

#### Biografier
`firstaccessiondate >= NOW - 6 MONTHS AND publicationyear >= NOW - 12 MONTHS AND datefirstedition >= NOW - 12 MONTHS AND ((dk5=99.4 AND (term.subject=biografi* OR term.subject=erindring*)) OR (term.genreandform=biografi* NOT dk5=sk)) AND term.childrenoradults="til voksne" NOT dk5=77.*`

#### Tegneserier
`firstaccessiondate >= NOW - 6 MONTHS AND publicationyear >= NOW - 12 MONTHS AND datefirstedition >= NOW - 12 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND phrase.language=dansk AND phrase.specificmaterialtype="tegneserie"`

#### Digte
`firstaccessiondate >= NOW - 6 MONTHS AND publicationyear >= NOW - 12 MONTHS AND datefirstedition >= NOW - 12 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=digte AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`

#### Noveller
`firstaccessiondate >= NOW - 12 MONTHS AND publicationyear >= NOW - 24 MONTHS AND datefirstedition >= NOW - 24 MONTHS AND term.fictionnonfiction="fiction" AND term.childrenoradults="til voksne" AND term.genreandform=noveller AND phrase.language=dansk AND phrase.specificmaterialtype="bog"`
