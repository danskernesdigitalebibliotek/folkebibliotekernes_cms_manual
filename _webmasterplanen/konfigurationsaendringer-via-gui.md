---
title: "Konfigurationsændring via brugergrænsefladen"
category: "Webmaster-funktionalitet"
weight: 3
---

Som webmasterbibliotek har man mulighed for at ændre konfiguration for DPL-CMS via brugergrænsefladen. 
- Man kan **tilføje ny konfiguration** som f.eks. en helt ny indholdstype. 
- Man kan **rette i en eksisterende konfiguration**. F. eks. ændre om et felt er påkrævet/ikke-påkrævet i en eksisterende indholdtype som f.eks. Artikel. 

Rettelser i eksistende konfiguration via brugergrænsefladen frarådes kraftigt!
{: .notice--warning}

Hvis man retter i eksisterende konfiguration, vil man **ikke** modtage kommende rettelser til denne konfiguration.

Eksterne sites som Go! eller andre elementer på sitet, som f.eks. en paragraph, kan være afhængig af, at man får disse rettelser. I værste fald kan dele af hjemmesiden pludselig holde op med at virke, hvis man retter i eksisterende konfiguration. 

## Således fungerer konfigurationsflowet i DPL-CMS

1. Når sitet opdateres, hentes konfigurationsfilerne fra ./config/sync i rod folderen af projektet - ca. tusind filer.
2. Konfigurationer, som DPL-CMS på forhånd har defineret til ikke at skulle overskrives vha. [Config Ignore modulet](https://www.folkebibliotekernescms.dk/main/webmasterplanen/konfigurationsaendringer-via-gui/#om-config-ignore) f.eks. client id/secret til DBC, trækkes fra ca. 20 filer.  
3.  Konfigurationer, som man selv har ændret / tilføjet via brugergrænsefladen, som f.eks. en ny indholdtype eller rettelser i en eksisterende indholdtype som f.eks. Artikel opdages af [Config Ignore Auto modulet] og trækkes fra.
4. Konfigurationer, som man har tilføjet via en service i et modul, lægges til. Læs mere om [udvikling af lokale moduler](https://www.folkebibliotekernescms.dk/main/webmasterplanen/konfigurationsaendringer-via-gui/#om-config-ignore-auto).
5. Filerne fra punkt 1-4 indlæses til den nye konfiguration efter en opdatering af sitet.

## Om Config Ignore
I projektetet er der installeret config_ignore modulet, hvor der er sat en række konfigurationer, som ikke skal overskrives, når sitet opdateres.

Sti til Config Ignore indstillinger i backend: `/admin/config/development/configuration/ignore`

[Læs mere om Config Ignore](https://www.drupal.org/project/config_ignore){:target="_blank"}

## Om Config Ignore Auto
Der er desuden installeret config_ignore_auto, som automatisk (når man retter på sitet) danner en liste over konfigurationer, som ikke skal overskrives ved opdatering,

Sti til Config Ignore indstillinger i backend: `/admin/config/development/configuration/ignore_auto`

[Læs mere om Config Ignore Auto](https://www.drupal.org/project/config_ignore_auto){:target="_blank"}

## Tjek om I har rettet i eksisterende konfiguration
For at kunne se config_ignore og config_ignore_auto skal man slå modulet *Configuration Manager* til og sættet permission, så man må importere konfigurationer.

Hvis man ønsker sig et overblik over, hvilke konfigurationer man har fået overskrevet og hvad man har lavet af nye, skal man sammenligne

- filerne i ./config/sync
- config ignore linjerne der ligger i /admin/config/development/configuration/ignore
- config ignore auto linjer der ligger i /admin/config/development/configuration/ignore_auto

**Det er ok:** \
Hvis der er konfigurationer i "ignore auto", som ikke optræder i sync, så er det nye konfigurationer. 

**Det kan give problemer:** \
Hvis der er konfigurationer i "ignore auto", som også optræder i sync, så har man overskrevet standard konfigurationer. (Med mindre disse også optræder i "ignore", så er det fint)

## Udvikling

Der er vide muligheder for at ændre og tilføje konfiguration, som på et normalt Drupal site.
Dog skal man være meget varsom med at ændre konfiguration, som DPL-CMS allerede har sat - det er bedre at tilføje ny konfiguration, som et helt nyt view eller indholdstype.  

Hvis man har en række konfigurationer, som danner en samlet funktion - kan det være en fordel at lave disse konfigurationer i et modul. Se [udvikling af lokale moduler](https://www.folkebibliotekernescms.dk/main/webmasterplanen/lokal-moduludvikling/).

## Anbefalinger

- Lav kun konfigurationsændringer som påvirker DPL-CMS generelle konfigurationsfiler, hvis det er meget nødvendigt. Hvis man gør det, vil man ikke få ændringer i disse konfigurationsfiler i fremtidige releases med + der er ting som kan breake, måske specielt ikke-Drupal elementerne som React laget, Go sitet ...
- Navngiv nye konfigurationer, så de ikke får sammenfald med DPL-CMS konfigurationer. Hvis man f.eks. opretter et nyt view kan man med fordel f.eks. give det maskinnavnet BIBLIOTEKSNAVN_personaleoversigt.
- Hvis man virkelig har brug for at ændre en indstilling i f.eks. en formular til oprettelser af aktiviteter, skal man undlade at rette direkte i "indholdstypen" - man kan i stedet rette formularen via asset injector javascript eller et hook i et modul.

## Eksempler

- Oprette et View som viser arrangementer på en anden måde f.eks. til print.
- Lave en paragraph, som kan præsentere indhold på en ny måde f.eks. i et andet layout.
- Lave en ny indholdtype f.eks. personale som kan bruges andre steder på sitet f.eks. i et View.