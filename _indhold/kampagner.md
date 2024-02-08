---
title: "Kampagner"
category: "Indholdstyper"
weight: 1
---
Kampagner er en selvstændig indholdstype, der vises på søgeresultat-siden – men kun hvis det,
som brugeren søger på, udløser den.

Kampagner kan derfor bruges målrettet til at skabe opmærksomhed om arrangementer, særlige
materialer, eller andet, som biblioteket ønsker at give særlig promovering.

Hvis du ønsker at oprette en kampagne, skal du gå ind på /admin/content
Klik på ”Tilføj indhold” i øverste højre hjørne:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/5d5b8807-fc0a-45aa-ad24-1f2eb6b0f972" alt="Opret en ny kampagne med knappen Tilføj indhold" caption="Opret en ny kampagne med knappen Tilføj indhold" %}

Klik på ”Campaign”:

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/6765297d-82c6-4743-a310-661a56db4c27" alt="Klik på knappen Campaign under overskriften Add content" caption="Klik på knappen Campaign under overskriften Add content" %}

Og så er du klar til at gå i gang.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/224dd688-4913-46c1-a7c5-da84e4e44d7b" alt="Formularen til at oprette en kampagne" caption="Formularen til at oprette en kampagne" %}

**Title**   
”Title” må ikke være tom. Det er kampagnens titel, som IKKE vises for slutbrugerne.

**Link**    
”Link” må heller ikke være tom. Det er det sted, hvor brugeren kommer hen, hvis han klikker på kampagnen. Det kan både være en side på hjemmesiden, eller det kan være et eksternt site.

**Text**    
”Text” behøver du ikke udfylde. Det er den tekst, som vises for slutbrugeren, når kampagnen udløses, fx ”Foredrag med Forfatter Skriversen d. 13/7” eller ”Lån koncertfilm online med Qello” ell. lign.
BEMÆRK: Udfylder du dette felt, vises billedet beskåret til venstre i kampagne-båndet. Udfylder du IKKE dette felt, fylder billedet HELE kampagnebåndet. Du skal med andre ord vælge et billede i forskelligt format, alt efter om du vil supplere med tekst eller ej.

**Image**    
Her kan du uploade et billede.

Dette beskæres automatisk, så det passer til den valgte kampagnevisning. Der kan ikke gives præcise formater, da beskæringen tilpasser sig skærmstørrelsen, men som tommelfingerregel bør dit billede være en smule bredere end 16:9, hvis det vises sammen med tekst (altså hvis du ikke har ladet feltet ”Text” være tomt), og omkring 5:1, hvis det vises uden tekst. 
Du kan med fordel eksperimentere lidt med det; husk at tjekke forskellige skærmstørrelser.

**Triggers**    
Under triggers vælger du, hvilke kriterier der skal være opfyldt for at kampagnen vises.

Under ”Trigger logic” vælger du, om dine regler skal kombineres med AND (alle triggers skal være opfyldt for at kampagnen vises) eller OR (kun én trigger behøver være opfyldt for at kampagnen vises). Denne indstilling er selvfølgelig irrelevant, hvis man kun opretter én trigger.

Under ”Facet” vælges hvilken facet, triggeren baseres på.
Under ”Term” vælges hvilken værdi, triggeren skal udløses af. Bemærk, at denne værdi skal skrives som den vises under ”flere filtre” i søgeresultatet. Hvis der står ”A. CONAN DOYLE” under forfatter, så udløses kampagnen ikke, hvis man har skrevet ”conan doyle”. Bemærk også, at feltet er case sensitivt, og at alle værdierne udelukkende skal skrives med små bogstaver. Tjek, at du kan udløse din kampagne for at sikre, at du har skrevet værdierne rigtigt.
Under ”Term Ranking Maximum” vælges hvor højt på listen over de hyppigst forekommende værdier i søgesættet, den valgte værdi skal figurere under den valgte facet, for at kampagnen vises.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/a8b96d14-6d81-421d-a253-a0a026d9496a" alt="Tilføj triggers" caption="Tilføj triggers" %}

### Eksempel:
Ønsker man fx at oprette en kampagne, der vises på alle søgesæt, hvori Sara Blædel er blandt de forfattere, der er repræsenteret hyppigst, vælges ”Facet” -> ”Creators”, og i ”Term” skrives så ”sara blædel”.

Ønskes kampagnen vist, hvis Sara Blædel fx er blandt de 7 hyppigst repræsenterede forfattere i søgesættet, sættes ”Most common values” til 7.
Ønskes kampagnen derimod kun vist, hvis Sara Blædel er forfatter til flere poster i søgesættet end nogen anden, sættes ”Most common values” til 1.

I mange tilfælde er ”Emne” den mest meningsfulde facet-type at vælge. Vær opmærksom på, at vælge emne-ord, der svarer til sprogbrugen i de katalogiserede materialer. Skriv fx ikke ”EU”, men ”den europæiske union”, da det er det emneord, DBC ved katalogisering tildeler materiale om EU.

Ønskes flere triggers, klik da på ”Tilføj Campaign Rule”.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/87397e42-6872-416c-8bdd-2d92fd78cf25" alt="Tryk på Save for at gemme den nye kampagne" caption="Tryk på Save for at gemme den nye kampagne" %}

Foretag gerne nogle søgninger på dit site, for at tjekke at den rent faktisk bliver udløst af de søgninger, du ønsker, og tilret, indtil dens adfærd er som du ønsker.
