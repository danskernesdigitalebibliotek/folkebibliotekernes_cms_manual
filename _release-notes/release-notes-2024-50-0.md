---
title:  "Release Notes 2024.50.0"
category: "Release Notes"
weight: 354
---  
# Diverse fejlrettelser og forbedringer

Releasedato: 12-12-2024

Opgraderingen rulles ud til: 
Redaktørbiblioteker: Produktionssites opgraderes. 
Webmasterbiblioteker: Testsites opgraderes til 2024.50.0. Produktionssites opgraderes til 2024.49.0. 

## Nye features 

- Webmasterbiblioteker: Mulighed for at opdatere egeninstallerede moduler.  

## Fejlrettelser og forbedringer

- Søgning: Når facetbåndet ”Spil” genereres har sitet tidligere kastet fejlmeddelelse. Fejlen opstod efter fejlrettelse hos DBC på intelligente facetter, som Folkebibliotekerne CMS ikke var kodet til at håndtere.   

- Find på hylden: Fejl rettet (introduceret i release 2024.49.0) hvor klassemærke/DK5 ikke længere blev vist som del af placeringsstrengen i modalen ”Find på hylden”.  

- Webmasterbiblioteker: Fejl rettet hvor det ikke er muligt at opdatere egne moduler uden FTP-bruger.  

- Nulstilling af adgangskode: Forbedret håndtering af nulstilling af adgangskode for redaktionelle brugere. Bl.a. grafisk overhaling af side til nulstilling og mere logisk rækkefølge af felter for side til ændring af adgangskode.  

- Vi har lavet flere rettelser til lister og paragrapher (som lister redaktionelt indhold), der fejlagtigt har vist indhold der er publiceret. Til arrangementer har vi lavet en rettelse, så I kan automatisk afpublicere instanser og/eller serier efter afholdelsestidspunktet er overskredet (læs næste punkt). 

- Automatisk afpublicering af arrangementer: Standardindstillingen for arrangementsinstanser er nu at de afpubliceres seks timer efter de er afholdt. Dette slår igennem på alle arrangementer der ikke i forvejen har et afpubliceringstidspunkt. Alternativt bevares det eksisterende afholdelsestidspunkt. Standardindstillingen for arrangementsserier er nu at de ikke afpubliceres uanset hvad den tidligere indstilling har været. Administratorer og Lokal administratorer kan selv vælge indstillinger for afpublicering for både serier og instanser via /admin/config/dpl-event/settings eller ved at klikke frem via Indstillinger > Biblioteksindstillinger > Arrangementsindstillinger.  
