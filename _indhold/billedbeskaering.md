---
title: "Billedbeskæring"  
category: "Generelt"
---
I Folkebibliotekernes CMS resizes og beskæres billeder automatisk. alt efter hvilken kontekst de indgår i. Når man lægger et billede ind, bruger man det nye fokusværktøj til at udpege et fokuspunkt i billedet, som beskæring skal ske omkring. Det skulle gerne lette arbejdet med billederne.

Der er ingen faste krav til billedstørrelser, men det gælder om at bruge billeder i så høj opløsning som muligt. Billederne beskæres i fire forskellige billedratioer: 1:1, 3:4, 4:3 og 16:9. Når man uploader et billede, får man vist de mulige beskæringer inden udgivelsen.

Her ses et eksempel, hvor flere billedratioer er i brug:
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3a16390f-78a0-4172-af3b-68a7cd58018e" alt="Billeder beskæres automatisk i fire forskellige billedratioer" caption="Billeder beskæres automatisk i fire forskellige billedratioer" %} 

## Fokusfunktion
Når du har uploadet et billede til CMS’en, bør du sikre dig at det ser godt ud i alle beskæringer i de forskellige paragraphs. Dette skal du gøre, fordi du billedet kan bruges flere steder, hvis fx den artikel du skriver bliver fremhævet i en nyhedskomponent på forsiden, eller trukket ind i et inspirationsbånd/slider. 

Jo flere grafiske elementer et billede indeholder, jo sværere kan det være at få det pænt i alle beskæringer, så det er vigtigt at overveje, hvad der er det vigtigste element i et billede.

Sådan gør du:
1. Når billedet er uploadet og gemt i mediebiblioteket, vises det med en lille blyant som indikerer, at du kan redigere det. Tryk på blyanten for at åbne redigeringstilstand.
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/95094189-9cdc-4c5a-8399-cb726e0ef935" alt="Tryk på blyanten for at åbne redigeringstilstand" caption="Tryk på blyanten for at åbne redigeringstilstand" %} 
3. Billedet vises nu i en redigeringstilstand, hvor du kan vælge en lup for at Gennemse. Der vises også et lille hvidt kryds, som indikerer hvor fokus er på billedet (fokusindikator). Som standard er midten af billedet altid i fokus.
   {% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/87437639-c2ed-4a84-8124-b1d8a801cda3" alt="Det lille hvide kryds indikerer, hvor fokus er på billedet" caption="Det lille hvide kryds indikerer, hvor fokus er på billedet" %}
5. For at se et preview af, hvordan billedet tager sig ud i diverse beskæringer, klikker du på luppen. Du får nu vist et preview af de forskellige beskæringer af billedet på en liste. OBS: Det kan være nødvendigt at scrolle horisontalt for at se alle versioner.
   {% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/8f92b0f8-65ed-4d08-9746-02b6fa2f0a9b" alt="Luppen åbner preview af de forskellige beskæringer" caption="Luppen åbner preview af de forskellige beskæringer" %}
7. Du lukker preview, og går tilbage til dit indhold. 
8. Klik på blyanten igen
9. Flyt det lille kryds til det nye fokuspunkt på billedet
10. Gem






## Billeder med grafik eller logoer
I nogle få situationer bliver resultatet af den automatiske billedbeskæring ikke optimal. Det gælder især, hvis man vil bruge noget grafik eller et logo som sit billede. Hvis man absolut må bruge den type billede, har Herning bibliotek lavet en guide til, hvordan man får det til at lykkes.

1. I dit billedbehandlingsprogram: Opret et billede/en canvas på 896x670 px. Så er du sikker på at billedet er stort nok til alle de forskellige formater i CMS'et.
2. På dette canvas kan du arbejde med et kvadrat på 500x500 px, som du kan være sikker på ikke bliver beskåret i alle de mange formater som CMS'et anvender.
Om kvadratet er i midten, i et hjørne eller helt ude i siden betyder ikke noget.
Du kan/skal selvfølgelig anvende hele canvas'et, men vær opmærksom på at alt udenfor kvadratet på de 500x500 px kan risikere at blive beskåret, alt efter hvilken sammenhæng billedet anvendes i.
3. Upload billedet til CMS'et, og sæt fokuspunktet i midten af kvadratet - and Bob's your uncle: nu kan du være sikker på at beskæringerne ikke ødelægger det indhold, som du har placeret inden i kvadratet.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/944267d4-9d48-431e-b28f-d67b15ee19f8" alt="Se hvordan HER ER DET VIGTIGE bliver ikke berørt af beskæringen" caption="Se hvordan HER ER DET VIGTIGE bliver ikke berørt af beskæringen" %} 

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/0a499fcd-1722-4241-8b7c-11bf172f1f41" alt="Grafik med pæn beskæring uanset billedratio" caption="Grafik med pæn beskæring uanset billedratio" %} 

