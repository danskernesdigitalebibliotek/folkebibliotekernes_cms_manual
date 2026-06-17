---
title: "Logo, identitetsfarve og favicon"
click-path: "Udseende > Novel > Indstillinger"
category: "Konfiguration"
---
I topmenuen klik på **{{ page.click-path }}**

Eller åbn via URL (udskift mit-domænenavn.dk):\
`https://mit-domænenavn.dk/admin/appearance/settings/novel`

Folkebibliotekernes CMS bruger et standard tema, der hedder "Novel". 
I kan ændre nogle få ting i standard-temaet:
- Logo
- Identitetsfarve
- Favicon

For at kunne rette i jeres udseende skal I være logget ind, som en lokal administrator.

## Logo

### Format
1. Logoet bør være en PNG eller SVG på transparent baggrund.
2. Du får bedste resultat med formatet 11:5 (f.eks. 220 px bred og 100 px høj). Du må gerne uploade et større billede, bare forholdet mellem bredde og højde er 11:5. Om muligt, så start altid med at redigerer en billedfil i høj opløsning.
3. Biblioteker uden logo kan benytte sig af en såkaldt fall back-version, hvor bibliotekets navn skrives med en prædefineret typografi.

### Sådan ændrer I logoet
1. Klik på **Udseende** i toppen af siden.
2. Klik på **Indstillinger** for Novel temaet.
3. Fold rubrikken **Logo billede** ud.
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/4f896db3-9388-40c5-989f-b2972bcf6aec" alt="Tilføj et nyt logo" caption="Tilføj et nyt logo" %}

4. Afmarkér knappen med titlen **Use the logo supplied by the theme**.
5. Klik på knappen **Vælg fil** og upload dit billede.
6. **Vigtigt!** Husk at udfylde felterne **Title** og **Place**. De bliver vist *i stedet* for logoet på små skærme. Title bliver vist med fed skrift og Place med normal skrift nedenunder. Title SKAL være udfyldt. Place er frivillig. Slet standardteksten i Place, så den er tom, hvis I ikke har indhold til feltet.
   {% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2125544f-ee50-4e54-9082-9f88a009c085" alt="På små skærme vises Title og Place i stedet for jeres logo" caption="På små skærme vises Title og Place i stedet for jeres logo" %}
7. Klik på knappen **Gem indstillinger** i bunden af siden.

## Identitetsfarve

I skal vælge en identitetsfarve til jeres hjemmeside. I må kun vælge én farve. Det skal være en stærk og ren farve, da den vil blive brugt i forskellige toner på hjemmesiden.

For at sikre god læsbarhed og overholdelse af krav til kontrast, må bibliotekets identitetsfarve aldrig bruges i direkte forbindelse med tekst. Det vil sige at I ikke skal skrive tekst med jeres farve.

1. Klik på **Udseende** i toppen af siden.

2. Klik på **Indstillinger** for Novel temaet.

3. Klik på **Identity Color** og vælg en identitetsfarve. Farven kan også vælges ved at indsætte RGB (red-green-blue) farvekode. {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/03cd2d76-43d6-48c7-ae83-ffd714ca352e" alt="Tilføj et ny identitetsfarve" caption="Tilføj et ny identitetsfarve" %}

4. Klik på knappen **Gem indstillinger** i bunden af siden.

## Favicon

Et favicon vises i browserens adresselinje og som bogmærke ikon. 

### Format
- Det skal være et kvadratisk billede fx 512x512.
- Det skal være simpelt visuelt fx det grafiske element i jeres logo, da bliver nedskaleret kraftigt og bliver udtydelig, hvis det er for komplekst visuelt.
- Er pænest med gennemsigtig baggrund.
- Vi anbefaler at uploade det som PNG, da det kan have en gennemsigtig baggrund og bliver ikke komprimeret når det nedskaleres. JPG og GIF understøttes også.

### Sådan ændrer I favicon

1. Klik på Udseende i toppen af siden.
2. Klik på Indstillinger for Novel temaet.
3. Knappen "Use the favicon supplied by the theme" skal være slået fra.
4. Tryk på 'Vælg fil' knappen under 'Upload favicon image' og upload jeres favicon.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/de88e2f6-29f8-4237-866a-8ad0adae4d11" alt="Tilføj et nyt favicon" caption="Tilføj et nyt favicon" %}
