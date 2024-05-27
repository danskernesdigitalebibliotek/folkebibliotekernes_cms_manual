---
title: "CQL Søgestrenge Eksempler"  
category: "Generelt"
---
Mette Kulmbach har været så venlig at dele nogle søgestrenge, som hun har bygget for Billund Bibliotekerne. De er til inspiration og er ikke perfekte eller udtømmende. Har du lavet søgestrenge, der er smartere eller mere korrekte, da send dine eksempler til cms-info@kk.dk. Så lægger vi dem ud her på siden.

## For børn

#### Nyt på hylderne for børn - 6 til 13 år
`firstaccessiondate > 2024-01-01 and dk5="sk" and term.childrenoradults="til børn"  and term.genreandform="krimi" and term.generalmaterialtype="bøger" and hascover=true`

#### Nye bøger (2024) for 1-2 årige
`phrase.language=dansk AND (firstaccessiondate >= 2024-01-01 OR datefirstedition=2024) AND ages within "1 2" AND hascover=true`
 
#### Nye bøger for (2024) for 13-17 årige
`phrase.ages="for 16 år" OR phrase.ages="for 17 år" OR phrase.ages="for 13 år" OR phrase.ages="for 14 år" OR phrase.ages="for 15 år" AND datefirstedition=2024 AND hascover=true AND phrase.mainlanguage=dansk`
 
#### Nye bøger på engelsk for 13-17 årige (2022-2024)
`phrase.ages="for 16 år" OR phrase.ages="for 17 år" OR phrase.ages="for 13 år" OR phrase.ages="for 14 år" OR phrase.ages="for 15 år" AND (datefirstedition within "2022 2024") AND hascover=true AND phrase.mainlanguage=engelsk`
 
#### Letlæsningsbøger børn (slet ikke udtømmende)
`term.series="læs lydret. trin 0" OR term.series="læs lydret. trin 1" OR term.series="læs lydret. trin 2" OR term.series="læs lydret. trin 3" OR term.series="lydret dingo. mini"`
 
#### Børnefødselsdage (2020-2024) brugt til vores side "Hold børnefødelsdag på biblioteket"
`term.title="fødselsdag*" AND term.mainlanguage=dansk AND term.childrenoradults="til børn" AND publicationyear within "2020 2024" AND hascover=true`

#### Nye bøger (2024) for 6-13 årige
`phrase.language=dansk AND (firstaccessiondate >= 2024-01-01 OR datefirstedition=2024) AND ages within "6 8" AND hascover=true`

#### Nye bøger (2024) for 9-11 årige
`phrase.language=dansk AND (firstaccessiondate >= 2024-01-01 OR datefirstedition=2024) AND ages within "9 11" AND hascover=true`

#### Nye bøger for børn mellem 12 til år 13 år købt i 2024
`phrase.language=dansk AND ages within "12 13" AND hascover=true and (firstaccessiondate >= 2024-01-01 OR datefirstedition=2024)`

