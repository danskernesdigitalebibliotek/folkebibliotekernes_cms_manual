---
title:  "Release Notes 2026.16.0"
category: "Release Notes"
weight: 308
---  

**Redaktør**: Produktionssites: 2026.16.0
**Webmaster**: Produktionssites: 2026.13.0, Moduletestsites: 2026.16.0 


## Ny udvikling

**Flere materialetyper på GO:GO!** understøtter nu flere materialetyper på børnesitet: billedbøger, graphic novels og tegneserier (både fysiske og digitale). Det betyder, at børnene får flere valg i både søgning, materialelister og på værksiden, så det er nemmere at finde den ønskede version. Den nye værkvisning er sammen med 5 andre prototyper testet på 40 børn i målgruppen. Børnene var utvetydigt tilhængere af denne værkvisning.

## Forbedringer og fejlrettelser

**Landekoder på materialer overholder nu standarden for landekoder (ISO 639-2):** 
Rettelsen er en forudsætning for at efterleve tilgængelighedskrav. Den sikrer, at skærmlæsere oplæser titler med korrekt sprog - f.eks. at engelske titler oplæses på engelsk og ikke dansk.

**Låner logges ud af sitet, når browseren lukkes:** Tidligere ville låneren stadig være logget ind, når browseren blev åbnet igen. 

**Synkronisering med place2Book:** Synkroniseringen mellem DDF-arrangementer og Place2Book er justeret, så lokationsvisning nu stemmer overens. Tidligere kunne arrangementer, der afholdes på f.eks. Medborgerhuset, fremstå med filialnavn (f.eks. Taastrup Bibliotek) kombineret med Medborgerhusets adresse i Place2Book. Den bagvedliggende håndtering af sted-felter er nu rettet, så Place2Book ikke længere viser en misvisende kombination af filial og adresse.


**Afholdte arrangementer fjernes nu fra samlesider:** Fejl rettet, hvor udløbne/afholdte arrangementer blev vist på samlesider for kategorier og tags. 

**Bedre adresseopslag i Danmarks Adresseregister (DAR):** Under indholdstypen "Bibliotek" kan man udfylde bibliotekets adresse. I den forbindelse laves et opslag i DAR. Opslaget er forbedret, så alle adresser i registret nu kan fremsøges. 

**Fejl ved brug af filtre Lix og Let i Simple Search rettet:** Ved brug af Simple Search i Folkebibliotekernes CMS opstod der en uventet fejl, når filtrene Lix- eller Let-tal blev anvendt i venstre filtermenu.

**Forbedret redaktøroplevelse når man tilføjer adresse til arrangement**: Ved oprettelse af arrangementer med en anden adresse end filialens er det nu tydeligt, at man skal vælge land, før man kan indtaste en adresse.
