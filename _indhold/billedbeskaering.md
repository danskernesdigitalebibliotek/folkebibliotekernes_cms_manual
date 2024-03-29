---
title: "Billedbeskæring"  
category: "Generelt"
---
I Folkebibliotekernes CMS resizes og beskæres billeder automatisk. alt efter hvilken kontekst de indgår i. Når man lægger et billede ind, bruger man det nye fokusværktøj til at udpege et fokuspunkt i billedet, som beskæring skal ske omkring. Det skulle gerne lette arbejdet med billederne.

Der er ingen faste krav til billedstørrelser, men det gælder om at bruge billeder i så høj opløsning som muligt. Billederne beskæres i fire forskellige billedratioer: 1:1, 3:4, 4:3 og 16:9. Når man uploader et billede, får man vist de mulige beskæringer inden udgivelsen.

De fleste steder vil billeder i bredformat fungere godt, men f. eks. i brødteksten på artikler kan man sagtens sætte billeder i højformat ind.

Her ses et eksempel, hvor flere billedratioer er i brug:
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3a16390f-78a0-4172-af3b-68a7cd58018e" alt="Billeder beskæres automatisk i fire forskellige billedratioer" caption="Billeder beskæres automatisk i fire forskellige billedratioer" %} 

## Billeder med grafik eller logoer
I nogle få situationer bliver resultatet af den automatiske billedbeskæring ikke optimal. Det gælder især, hvis man vil bruge noget grafik eller et logo som sit billede. Hvis man absolut må bruge den type billede, har Herning bibliotek lavet en guide til, hvordan man får det til at lykkes.

1. I dit billedbehandlingsprogram: Opret et billede/en canvas på 896x670 px. Så er du sikker på at billedet er stort nok til alle de forskellige formater i CMS'et.
2. På dette canvas kan du arbejde med et kvadrat på 500x500 px, som du kan være sikker på ikke bliver beskåret i alle de mange formater som CMS'et anvender.
Om kvadratet er i midten, i et hjørne eller helt ude i siden betyder ikke noget.
Du kan/skal selvfølgelig anvende hele canvas'et, men vær opmærksom på at alt udenfor kvadratet på de 500x500 px kan risikere at blive beskåret, alt efter hvilken sammenhæng billedet anvendes i.
3. Upload billedet til CMS'et, og sæt fokuspunktet i midten af kvadratet - and Bob's your uncle: nu kan du være sikker på at beskæringerne ikke ødelægger det indhold, som du har placeret inden i kvadratet.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/944267d4-9d48-431e-b28f-d67b15ee19f8" alt="Se hvordan HER ER DET VIGTIGE bliver ikke berørt af beskæringen" caption="Se hvordan HER ER DET VIGTIGE bliver ikke berørt af beskæringen" %} 

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/0a499fcd-1722-4241-8b7c-11bf172f1f41" alt="Grafik med pæn beskæring uanset billedratio" caption="Grafik med pæn beskæring uanset billedratio" %} 

