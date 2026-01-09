---
title: "Sådan opretter du indhold på GO"
category: GO
weight: 2
---
**Indhold på GO redigeres og oprettes i samme backend, som du bruger til jeres hovedsite.**

**OBS!** Vær opmærksom på, at GO på nogle områder opfører sig anderledes end Folkebibliotekernes CMS - det er derfor vigtigt, at du læser manualen for at sikre, at jeres GO indhold vises korrekt. Vær især opmærksom på, at indhold I selv opretter og placerer på GO-forsiden vil blive overskrevet, når Bibliotekernes Nationale Redaktion opdaterer siden hver torsdag. 

### Side til lokal formidling ###
For at undgå, at indhold bliver overskrevet anbefaler vi derfor, at I opretter en kategoriside fx kaldet ”Mit bibliotek”, som I opretter i jeres egen backend. Se [Sådan opretter du en kategoriside](https://www.folkebibliotekernescms.dk/main/go/opret-kategoriside/) Katergorisider, som I selv opretter bliver *ikke* overskrevet, når der sendes nyt indhold ud fra BNR. Den kommer til at ligge oppe i toppen af siden ved siden af ”Gys”, ”venskab” osv. 
På [delingstjenesten.dk/ereolen-gos-logoer-og-pr-materialer](https://delingstjenesten.dk/kampagner-pr/ereolen-gos-logoer-og-pr-materialer) finder du [en mappe](https://detdigitalefolkebibliotek.sharepoint.com/:f:/s/BibliotekernesNationaleRedaktion/IgBsGNBTuFaCRq0Q9PpjY2ofATTC2YvW5OoZhNbiwNTQe1k?e=3NzYYG) med billeder, der kan bruges til ikon på Mit Bibliotek-siden. 

Vær opmærksom på at nyoprettet indhold eller ændringer i indhold kan have en forsinkelse, fra du gemmer til det er synligt på sitet.

På [delingstjenesten.dk/go](https://delingstjenesten.dk/go) kan du læse mere om Bibliotekernes Nationale Redaktions arbejde og se, hvornår siden senest er opdateret med redaktionelt indhold.


### Sådan opretter du nyt indhold

Når du er logget ind i jeres backend på jeres hovedsite, kan du under menupunktet ‘Indhold’ vælge ‘Tilføj indhold’: 
{% include figure class="sixty" image_path="https://github.com/user-attachments/assets/1978866e-2f69-4c51-b09f-7bd8d099dd5a" alt="Under 'Indhold' vælg 'Tilføj indhold" %}

Under ‘Tilføj indhold’ kan du enten vælge elementer fra ‘Opret indhold fra bunden’ eller fra ‘Opret indhold fra skabelon’. 
{% include figure class="ninety" image_path="https://github.com/user-attachments/assets/6e4cd446-9d00-4827-82fd-331d27a30173" alt="Vælg 'opret indhold fra bunden' eller fra opret indhold fra skabelon" %}

De GO specifikke indholdselementer, der kan oprettes er hhv. GO artikel, GO kategori og GO side.


- [Sådan opretter du en artikel på GO](https://www.folkebibliotekernescms.dk/main/go/opret-artikel/)
- [Sådan opretter du en kategoriside på GO](https://www.folkebibliotekernescms.dk/main/go/opret-kategoriside/)
- [Sådan opretter du en side på GO](https://www.folkebibliotekernescms.dk/main/go/opret-side/)
- [Paragraph komponenter på GO](https://www.folkebibliotekernescms.dk/main/go/paragraphs-go/)



### Udviklingsønsker til GO i forbindelse med oprettelse af indhold
**Arrangementer** 
Der er et ønske om at kunne integrere arrangementer direkte på GO-sitet. Som det er nu, kan arrangementer til målgruppen 6-16 år formidles på GO ved at lave en linkboks, som henviser til arrangementet på hovedsitet. Tilmelding til arrangementer vil oftest kræve assistance fra en voksen.

**Reservering af fysiske bøger** 
På GO-sitet vises de fysiske bøger fra bibliotekets kommunale beholdning i søgningen. Dette er for at synliggøre over for børnene, at bogen også kan lånes i fysisk form på det lokale bibliotek. Som det er nu, kan bogen ikke reserveres på GO-hjemmesiden. Dette er et udviklingsønske, som vil blive implementeret, når der er ressourcer til det.  

Reservering af bøger er en omkostningstung funktion at udvikle, som kompliceres af, at der på GO både er mulighed for UNI-login og bibliotekslogin.  

Vi ved fra både reserveringsstatistikker og fokusgruppeundersøgelser, at børnene meget sjældent benytter reservering, kan have svært ved at forstå konceptet, og at de som udgangspunkt ikke ser det som noget, de skal eller kan gøre uden en voksens assistance.  

I første omgang har prioriteten derfor været at udvikle funktionalitet, der tilgodeser de mange digitale børnebrugere, der benytter ereolengo.dk til streaming af e-bøger og lydbøger for ikke tabe disse biblioteksbrugere. Ereolengo.dk kører på uddateret teknologi og skal derfor udfases.

Nogle har spurgt, om man ikke blot kan lave et link over til materialet på hovedsitet. Når vi ikke bare kan lave et link til bibliotekernes hovedsites eller bibliotek.dk for den sags skyld, er det fordi at LANGT hovedparten af de besøgende på nuværende tidspunkt vil være UNI-loginbrugere, der ikke kender deres bibliotekslogin. Og for dem er det en decideret obstruerende brugerrejse at skulle sendes ud på et voksenrettet site, hvor de ikke kan logge ind.
Derfor er det en dyrere sag at inkorporere, fordi det kalder på, at løsningen hele tiden skal lytte på, om der er tale om en anonymbruger, en biblioteksbruger eller en UNI-loginbruger.


**Dedikeret område til lokal formidling på forsiden** 
Som udgangspunkt overskrives evt. lokalt tilføjet indhold på forsiden, når Bibliotekernes Nationale Redaktion opdaterer den. Det er et ønske at udvikle et dedikeret område på forsiden, hvor de lokale biblioteker kan tilføje indhold, som ikke overskrives.
