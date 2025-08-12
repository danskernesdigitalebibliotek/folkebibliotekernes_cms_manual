---
title: "Paragraph komponenterne på GO"
category: GO
weight: 6
---

De komponenter, som du bygger dit indhold op af på sider, kategorisider og artikler kaldes **Paragraphs** og på GO findes følgende: GO Video, GO Video Bundle – Automatic, GO Video Bundle - Manual, GO Material Slider – Automatic, GO Material Slider - Manual og GO Linkbox. 

**OBS!** Husk at læse nedenstående vejledning vedr. søgestrenge i karruseller og videobundle, da det er afgørende for, at karrusellerne vises rigtigt.

Klik på '**+ Add**' for at tilføje de paragraphs, som du ønsker, at din side eller formidlingselement skal bestå af. 
{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/1cadc8ad-7c55-413d-b5f8-9076d571957b" alt="Klik på '+ Add' for at tilføje paragraphs" %}
Paragraphs kan tilføjes både over og under allerede indsatte paragraphs


#### Sådan opretter du en GO Video paragraph 

- Gå ind på/opret den side, kategoriside eller artikel, som du ønsker at tilføje en video på. 

- Klik på ‘+Add’ under ‘Paragraphs’. En visning af de tilgængelige paragraffer vises nu. Vælg ‘GO Video’ og følgende vises:  
  {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/86111349-565c-4b90-a62f-d38b13089784" alt="Vælg 'GO Video' " %}

- Giv din video en titel eller ‘Title’: Dette er titlen, der vises ovenover din video: 
  {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/f4232bc6-10ae-424e-b3d9-1d08ba907451" %}

- Under ‘Embed video’ klikkes på ‘Add media’. Her kan du tilføje en video-URL fra VideoTool. Klik på ‘Add’ og videoen bliver tilføjet nede i Videobiblioteket.  
Fra Videobiblioteket kan der nu vælges den nytilføjede video eller der kan vælges en video, som allerede er uploadet til biblioteket.
Klik på ‘Indsæt det valgte’, når videoen er valgt (flueben). 



#### Sådan opretter du en GO Video Bundle paragraph 

- Gå ind på/opret den side, kategoriside eller artikel, som du ønsker at tilføje en video bundle på. 

- Klik på ‘Add’ under ‘Paragraphs’. En visning af de tilgængelige paragraffer vises nu. Vælg enten ‘GO Video Bundle – Automatic’ eller ‘GO Video Bundle – Manual’ alt efter om du vil oprette en video bundle ved hjælp af en CQL-søgestreng eller manuelt tilvælge materialer.  

For automatisk vises:
  {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/058025e0-1373-4408-b173-2a9f100210ac" alt="Vælg 'GO Video Bundle Automatic' " %}

For manuel vises:  
  {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/db26ff25-e5a9-4fdd-a0c4-5aa267e3df17" alt="Vælg 'GO Video Bundle Manual' " %}

- For begge typer video bundles angives en ’Titel’. Dette er titlen, der vises ovenover din video bundle.
  {% include figure class="eighty" image_path="https://github.com/user-attachments/assets/0fba6dfe-aaeb-4365-b7f5-61d64807a1ed" %}

- Under ‘Embed video’ klikkes på ‘Add media'. Her kan du tilføje en video-URL fra VideoTool. Klik på ‘Add’ og videoen bliver tilføjet nede i Videoarkivet.  
Fra Videoarkivet kan der nu vælges den nytilføjede video eller der kan vælges en video, som allerede er uploadet til arkivet.  
Klik på ‘Indsæt det valgte’, når videoen er valgt (flueben). 

- For ‘Video Bundle – Automatic’ indsættes den CQL-søgestreng, som indeholder de materialer, din video bundle skal shuffle imellem.

  - **OBS:** Husk at afgrænse CQL-søgestrengen til kun at søge på materialer for børn af typen, ‘bog, ebog og lydbog’, da søgningen ellers vil tage resultater med, som ligger uden for GOs beholdning.  
For at være sikker på, at sitet understøtter visning af de materialer, I lægger i automatiske karruseller (complex search), anbefaler vi derfor, at I indsætter følgende i søgestrengen:  
*and term.childrenoradults="til børn" and (term.specificmaterialtype="lydbog (online)" or term.specificmaterialtype="e-bog" or term.specificmaterialtype="podcast" or term.specificmaterialtype="bog" ) and phrase.language=dansk* 

    Det er selvfølgelig muligt blot at indsætte udvalgte af de "specific material types", der er i ovenstående søgestreng (fx kun *term.specificmaterialtype="bog"*), men det er vigtigt at benytte mindst én af de nævnte -typer for ikke risikere at søge materialer frem, som ikke er understøttet i visningen. 

    For hjælp til generering af CQL søgestrenge se følgende sider i Manualen: [CQL Søgestrenge](https://www.folkebibliotekernescms.dk/main/indhold/cql-soegestrenge/), [CQL Søgestrenge Eksempler](https://www.folkebibliotekernescms.dk/main/indhold/cql-soegestrenge-eksempler/) eller [Avanceret søgning og CQL Søgning](https://www.folkebibliotekernescms.dk/main/soegning/avanceret-sogning/) 

- Under ‘Amount of materials’ angives, hvor mange materialer, der skal vises og shuffles imellem. Der kan angives op til 10.

- For ‘Video Bundle – Manual' fremsøges de materialer, du ønsker, at dine video bundle skal shuffle imellem.
  - **OBS:** Husk først at lave en søgning på de materialer, du ønsker at tilføje til din 'Video Bundle Manual' i GOs frontend, for at sikre dig, at materialet kan vises på GO. De materialetyper der er understøttet og kan vises på nuværende tidspunkt, er: e-bog, lydbog, podcast og fysiske bøger.  
  - Funktionen ‘Select material type’, hvor man kan angive om det skal være e-bog, lydbog eller podcast er desværre ikke mulig at anvende i øjeblikket - i stedet vises værket med alle de tilknyttede materialetyper for titlen.  
 

- Klik på ‘Gem’, når du har sat din(e) video bundle(s) op.


#### Sådan opretter du en GO Materialekarrusel paragraph

Gå ind på/opret den side, kategoriside eller artikel, som du ønsker at tilføje en Materialekarrusel på. 

Klik på ‘Add’ under ‘Paragraphs’. En visning af de tilgængelige paragraffer vises nu. Vælg enten ‘GO Material Slider – Automatic’ eller ‘GO Material Slider – Manual’ alt efter om du vil oprette en Video bundle ved hjælp af en CQL-søgestreng eller manuelt tilvælge materialer.  

For automatisk vises:
{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/6ad4def3-c21e-459f-9d75-50f48d82809b" alt="Vælg 'GO Material Slider Automatic' " %}

For manuel vises:
{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/d832b3b2-b1d2-4fa7-8c9d-c365cc76710a" alt="Vælg 'GO Material Slider Manual' " %}

- For begge typer materialekarruseller angives en ’Titel’. Dette er titlen, der vises ovenover din karrusel.
  {% include figure class="eighty" image_path="https://github.com/user-attachments/assets/7c3cbac7-f39c-4612-930a-1815b1f36992" %}


- For ‘Material Slider – Automatic’ indsættes den CQL-søgestreng, som indeholder de materialer, din karrusel skal indeholde. 

  - **OBS:** Husk at afgrænse CQL-søgestrengen til kun at søge på materialer for børn af typen, ‘bog, ebog og lydbog’, da søgningen ellers vil tage resultater med, som ligger uden for GOs beholdning.  
For at være sikker på, at sitet understøtter visning af de materialer, I lægger i automatiske karruseller (complex search), anbefaler vi derfor, at I indsætter følgende i søgestrengen:  
*and term.childrenoradults="til børn" and (term.specificmaterialtype="lydbog (online)" or term.specificmaterialtype="e-bog" or term.specificmaterialtype="podcast" or term.specificmaterialtype="bog" ) and phrase.language=dansk* 

    Det er selvfølgelig muligt blot at indsætte udvalgte af de "specific material types", der er i ovenstående søgestreng (fx kun *term.specificmaterialtype="bog"*), men det er vigtigt at benytte mindst én af de nævnte -typer for ikke risikere at søge materialer frem, som ikke er understøttet i visningen. 

    For hjælp til generering af CQL søgestrenge se følgende sider i Manualen: [CQL Søgestrenge](https://www.folkebibliotekernescms.dk/main/indhold/cql-soegestrenge/), [CQL Søgestrenge Eksempler](https://www.folkebibliotekernescms.dk/main/indhold/cql-soegestrenge-eksempler/) eller [Avanceret søgning og CQL Søgning](https://www.folkebibliotekernescms.dk/main/soegning/avanceret-sogning/)

- Under ‘Amount of materials’ angives, hvor mange materialer, der skal vises i karrusellen. Der kan angives op til 100 – angives der højere end 100, vil karrusellen desværre ikke fungere.  

- For ‘Material Slider – Manual' fremsøges de materialer, du ønsker, at dine video bundle skal shuffle imellem.
  - **OBS:** Husk først at lave en søgning på de materialer, du ønsker at tilføje til din 'Materialekarrusel Manual' i GOs frontend, for at sikre dig, at materialet kan vises på GO. De materialetyper der er understøttet og kan vises på nuværende tidspunkt, er: e-bog, lydbog, podcast og fysiske bøger. 
  - Funktionen ‘Select material type’, hvor man kan angive om det skal være e-bog, lydbog eller podcast er desværre ikke mulig at anvende i øjeblikket - i stedet vises værket med alle de tilknyttede materialetyper for titlen.

- Klik på ‘Gem’, når du har sat din(e) Materialekarrusel(ler) op.


#### Sådan opretter du en GO Linkbox paragraph
Gå ind på/opret den side, kategoriside eller artikel, som du ønsker at tilføje en linkboks på. 

Klik på ‘Add’ under ‘Paragraphs’. En visning af de tilgængelige paragraffer vises nu. Vælg ‘GO Linkbox’ og følgende element vises:  
{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/9a92e521-7192-4a4b-8455-c3f490984e36" alt="Vælg 'GO Linkbox' " %}

- Under ‘Image’ klikkes på ‘Add media’. Her kan du uploade en billedfil fra din computer eller vælge et allerede tilføjet billede i billedarkivet nedenfor. Vælger du at uploade et billede, klikker du på ‘Vælg fil’ og finder det billede, du vil uploade og klikker på ‘Åbn’. Følgende bliver nu vist:
  {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/caafc657-22a4-4ca1-9b6f-9b91096d52e3" alt="Tilføj eller vælg et medie' " %}
   - **Name** er obligatorisk og præudfyldt med det navn billedet havde på din computer - ønsker du, at ændre det kan du gøre det.  

   - **Byline** er valgfrit, men kan bruges, hvis du ønsker kreditering og angivelse af copyright information. Bylinen vil blive placeret sammen med billedet.  

   - **Alternative text** er valgfrit, men brugbart i forbindelse med øget tilgængelighed. Her kan du angive en kort beskrivelse af billedet, som skærmlæsere kan bruge og som vil fremgå, når billedet ikke indlæses.   

   - **URL alias** er valgfrit, men kan bruges til at angive en alternativ sti til hvor formidlingselementet/siden kan tilgås. Angiv f.eks. “/om”, når du opretter en ‘Om-side’. 

   - Klik på ‘Gem’, når du har udfyldt de relevante informationer og billedet uploades nu til arkivet, hvor det er forhåndsvalgt (flueben). Herefter klikkes der på ‘Indsæt det valgte’.

- Angiv en ‘Titel’ på din Linkboks. Dette er overskriften, der vises ud for billedet på dit Linkboks-element.

- Tilføj en beskrivelse af indholdet til din Linkboks.

- Under ‘Link’ indsættes:
   - selve linket (URL’en), som linkboksen skal lede til – dette link kan enten lede ud af GO-sitet eller linke ind til andre sider eller artikler* på GO-sitet.

     **OBS!** For nuværende kan du desværre ikke linke med relative links til jeres CMS' sider og/eller artikler altså eksempelvis anvende "/node/591". Du skal i stedet anvende din sides eller artikels fulde URL, når du linker. 

   - en linktekst, som er obligatorisk. Denne linktekst vises på knappen for linket. 

   - evt. angives en ‘Aria label’ som tilgængelig tekst, så brugere der anvender skærmlæsere kan få teksten læst op. 

   - evt. en farve, som indrammer det tilføjede billede. Der kan vælges imellem 4 forskellige farver i en dropdown menu. Indsætter man ikke en farve, vil billedet være større, se eksemplerne nedenfor med og uden baggrundsfarve:
      {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/96936c20-14f6-4a43-b7bc-c24f35ab151a" alt="Linkbox med farvet baggrund' " %}
      {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/516d17fd-f9b8-4845-8a90-7d2a6a30bb1a" alt="Linkbox uden farvet baggrund' " %}

     * **OBS!** For at få vist en [oprettet artikel](https://www.folkebibliotekernescms.dk/main/go/opret-artikel/#s%C3%A5dan-opretter-du-en-artikel), skal der oprettes en linkbox, som beskrevet ovenfor. Under ‘Link’ indsættes selve artiklens link, som kan fremsøges ved at indtaste artiklens titel i feltet.

