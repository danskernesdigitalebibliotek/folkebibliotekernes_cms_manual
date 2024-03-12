---
title: "Rankering af fuzzy match"
category: "Søgning"
---
Der er kun ét søgefelt i Folkebibliotekernes CMS, og der er rigtig mange, meget forskelligartede brugerbehov. For at kunne understøtte så mange som muligt af disse, benyttes ”fuzzy match”.

Ordet "fuzzy" betegner noget der er uskarpt, sløret, ikke helt præcist, og det er dækkende for, hvad der sker. Systemet finder nogle svar, der ikke passer præcist med det, der er spurgt efter, men som dog er i nærheden af det.

Det gør, at brugerne får resultater, selv hvis de laver stavefejl i forfatternavne, og at det heller ikke gør så meget, om man skriver dostojevsky, dostojevskij, dostoyevsky eller dostoevsky.

Desuden benytter flertallet af brugerne – og en stadig stigende andel af dem – naturligt søgesprog, sådan som de er vant til det fra google, dvs de søger på “nye film” eller ”playstation spil” eller ”hobbitten illustreret” eller ”wimpy kid nummer 3”, og her får de noget meningsfuldt ved søgning i Folkebibliotekernes CMS.

Fuzzy match gør også 0-hits-søgninger meget sjældnere.

Men for at fuzzy match ikke afstedkommer at brugerne drukner i irrelevante poster, stiller det store krav til rankeringen, og for at sikre at dén er tilfredsstillende, integreres der rigtig mange nøgleparametre.

Eksempelvis, men langt fra udtømmende:

Det evalueres, hvor nøjagtigt brugernes søgetermer matcher indeksernes indhold, således at eksakt match gives en højere placering end en tilnærmet.

Værker på dansk vægtes i de fleste søgninger højere end andre værker, ligesom nyhedsværdi også tælles ind som en faktor – der vejer endnu tungere, hvis der fx er mange artikler i søgeresultatet.

Popularitet spiller også en central rolle i rankeringen, hvor der anvendes data om brugeradfærd og antallet af eksemplarer på danske biblioteker til at vurdere et værks popularitet.

Kompleksiteten er dermed også så stor, at logikken primært er en ”black box” hos DBC. Enhver, der ønsker yderligere dokumentation, kan få dette ved henvendelse til DBC – men der er ikke udstillet nogen muligheder for at foretage lokal tilretning af match eller rankering i Folkebibliotekernes CMS.
