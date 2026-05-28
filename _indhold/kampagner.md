---
title: "Kampagner"
category: "Indholdstyper"
weight: 1
---
Kampagner er en selvstændig indholdstype, der vises på søgeresultat-siden – men kun hvis det, som brugeren søger på, udløser den.

Kampagner kan derfor bruges målrettet til at skabe opmærksomhed om arrangementer, særlige materialer, eller andet, som biblioteket ønsker at give særlig promovering.

{% include figure class="seventy" image_path="https://github.com/user-attachments/assets/cbeb9a28-e63d-463c-b818-50c43e8db9bb" alt="En kamoagne på et søgeresultat" caption="En kamoagne på et søgeresultat" %}

## Sådan opretter du en kampagne
1. I topmenuen klik på **Indhold** eller åbn https://mit-domænenavn.dk/admin/content (udskift mit-domænenavn.dk)
2. Klik så på **Tilføj indhold** i øverste højre hjørne:
3. Klik på **Kampagne**

### Opret din kampagne

{% include figure class="seventy" image_path="https://github.com/user-attachments/assets/a0520c44-85b4-4009-ae91-7c58911fe940" alt="Formularen til at oprette en kampagne" caption="Formularen til at oprette en kampagne" %}

**Titel**
”Titel” må ikke være tom. Det er kampagnens titel, som IKKE vises for slutbrugerne.

**Vægt**
"Vægt" er en måde at vægte kampagner efter prioritet. Så hvis flere kampagner burde blive vist, så er det den med den højeste vægt, som vises. Er der flere med samme vægt, så vises en tilfældig. Dette kan bruges til fx at give kampagnen om den vigtige litteraturfestival vægten 'Højest' og en kampagne, som linker hen til en fast litteratur sektionsside 'Lav' eller 'Medium'. Vægten er mest vigtig for dem, som laver mange kampagner, og skal sikre at de rigtige vises. 'Medium' er standardindstillingen.

**Link**    
”Link” må heller ikke være tom. Det er det sted, hvor brugeren kommer hen, hvis han klikker på kampagnen. Det kan både være en side på hjemmesiden, eller det kan være et eksternt site. Hvis du linke til et arrangement, så sæt den absolutte URL ind fx https://www.naesbib.dk/naestved-bibliotek/arrangementer/foredrag/om-murakami-og-japansk-litteratur

**Tekst**    
”Tekst” er den tekst, som vises for slutbrugeren, når kampagnen udløses, fx ”Foredrag med Forfatter Skriversen d. 13/7” eller ”Lån koncertfilm online med Qello” ell. lign. Skriv ikke for lange tekster, da kampagnen så bliver meget stor på mobil.

**Media**    
Her kan du uploade et billede.

Dette beskæres automatisk, så det passer til den valgte kampagnevisning. Der kan ikke gives præcise formater, da beskæringen tilpasser sig skærmstørrelsen, men som tommelfingerregel bør dit billede være en smule bredere end 16:9, hvis det vises sammen med tekst (altså hvis du ikke har ladet feltet ”Text” være tomt), og omkring 5:1, hvis det vises uden tekst. 
Du kan med fordel eksperimentere lidt med det; husk at tjekke forskellige skærmstørrelser.

### Triggers
Under triggers vælger du, hvilke kriterier der skal være opfyldt for at kampagnen vises.

Det kan tilføjes to typer af triggers: 1. Facet eller 2. Søgeord. Tryk på de to 'Tilføj...' knapper for at oprette triggers.
{% include figure class="seventy" image_path="https://github.com/user-attachments/assets/073d99be-b99a-4668-bb40-08a3779b3426" alt="Triggers til kampagner" caption="Triggers til kampagner" %}

**Trigger Facet**    
Under ”Facet” vælges hvilken facet, triggeren baseres på.

Under ”Term” vælges hvilken værdi, triggeren skal udløses af. Bemærk, at denne værdi skal skrives som den vises under ”flere filtre” i søgeresultatet. Hvis der står ”A. CONAN DOYLE” under forfatter, så udløses kampagnen ikke, hvis man har skrevet ”conan doyle”. Bemærk også, at feltet er case sensitivt, og at alle værdierne udelukkende skal skrives med små bogstaver. Tjek, at du kan udløse din kampagne for at sikre, at du har skrevet værdierne rigtigt.

Under ”Term Ranking Maximum” vælges hvor højt på listen over de hyppigst forekommende værdier i søgesættet, den valgte værdi skal figurere under den valgte facet, for at kampagnen vises.

**Trigger Søgeord**    
Søgeordene vil trigger kampagnen, hvis brugerne bruger de samme ord i en simple search. Det er en fuzzy søgning, så "fiction" vil matche "science-fiction bøger".

**Triggerlogik**    
Under ”Triggerlogik” vælger du, om dine regler skal kombineres med AND (alle triggers skal være opfyldt for at kampagnen vises) eller OR (kun én trigger behøver være opfyldt for at kampagnen vises). Denne indstilling er selvfølgelig irrelevant, hvis man kun opretter én trigger.

### Eksempel på hvordan facet triggere virker:
Ønsker man fx at oprette en kampagne, der vises på alle søgesæt, hvori Sara Blædel er blandt de forfattere, der er repræsenteret hyppigst, vælges ”Facet” -> ”Creators”, og i ”Term” skrives så ”sara blædel”.

Ønskes kampagnen vist, hvis Sara Blædel fx er blandt de 7 hyppigst repræsenterede forfattere i søgesættet, sættes ”Most common values” til 7.
Ønskes kampagnen derimod kun vist, hvis Sara Blædel er forfatter til flere poster i søgesættet end nogen anden, sættes ”Most common values” til 1.

I mange tilfælde er ”Emne” den mest meningsfulde facet-type at vælge. Vær opmærksom på, at vælge emne-ord, der svarer til sprogbrugen i de katalogiserede materialer. Skriv fx ikke ”EU”, men ”den europæiske union”, da det er det emneord, DBC ved katalogisering tildeler materiale om EU.

Ønskes flere triggers, klik da på ”Tilføj Campaign Rule”.

Foretag gerne nogle søgninger på dit site, for at tjekke at den rent faktisk bliver udløst af de søgninger, du ønsker, og tilret, indtil dens adfærd er som du ønsker.
