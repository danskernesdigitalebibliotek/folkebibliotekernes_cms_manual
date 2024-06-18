---
title: "Place2book integration"  
category: "Generelt"
---

Billetsystemet Place2book har udviklet en integration til Folkebibliotekernes CMS via [arrangements APIet](https://www.folkebibliotekernescms.dk/main/bliv-klar-til-folkebibliotekernes-cms/9integrationer/#arrangements-api-til-brug-for-eksterne-systemer). Arrangements APIet er tilgængeligt for alle billetleverandører, der ønsker at bygge integration til Folkebibliotekernes CMS.



## Opsæt Place2book integration
Denne guide forudsætter at dit bibliotek/kommune er kunde hos Place2book. 
Opsætning skal kun udføres en gang.

1. I Folkebibliotekernes CMS opret en redaktionel bruger med rollen **Eksternt system**. Her er [guide til at oprette redaktionel bruger](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#opret-ny-redaktionel-bruger).
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/91ca0296-20fb-48d8-926d-af8338471255" alt="Opret bruger til Place2book" caption="Opret bruger til Place2book" %} 

2. Kontakt [support@place2book.com](mailto:support@place2book.com) for at få åbnet for integrationen. Når Place2book har aktiveret integrationen og I har fuldført denne guide, da vil arrangementer oprettet efter dette tidspunkt bliver overført til Place2book. Bemærk! Hvis I allerede har oprettet arrangementer, som I ønsker overført til Place2book, skal I skrive det i emailen. Place2book kan da køre et ekstra job, der henter tidligere oprettede arrangementer.
   
3. På [Place2book.com](https://www.place2book.com/) log ind som **Arrangør**. I topmenuen vælg **Generelt > Folkebibliotekernes CMS**. (Menupunktet bliver først synligt, når der er blevet åbnet for integrationen)
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/9f488528-3c6c-466f-a8ac-dcff184c7548" alt="Log ind i Place2book og gå til menupunktet Folkebibliotekernes CMS" caption="Log ind i Place2book og gå til menupunktet Folkebibliotekernes CMS" %}
 
4. I vinduet der åbner skal der indtastes nogle oplysninger:   
   - I **Brugernavn & Password** indsæt brugernavn og adgangskode for den bruger i oprettede i trin 1. (Den skelner mellem store/små bogstaver, så tast rigtigt)
   - I **DPL CMS Url** indsætter I `https://mit-domænenavn.dk/api/v1/events` (udskift mit-domænenavn.dk)
   - Marker **Importer arrangementer uden priser**, hvis I ønsker billetsalg på arrangementer, der HAR en billetkategori og pris = 0kr. (Den bør alle sætte hak ved.)
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f9a0b3fe-8f45-4c34-9a76-e0438ea52b20" alt="Opsæt integration til Place2book" caption="Opsæt integration til Place2book" %} 

## Arbejdsgang omkring arrangementer og Place2book
Når jeres Place2book integration er opsat korrekt, skal I arbejde med arrangementer på denne måde:

### Sådan oprettes arrangement med billet
1. Opret et [arrangement](https://www.folkebibliotekernescms.dk/main/indhold/arrangement/).
   
   I SKAL udfylde:
   - **Total ticket capacity**: Hvor mange billetter, der skal sættes til salg.
   - **Billetkategorier** - en eller flere. Det er dem der får Place2book til at tilknytte billetsalg til arrangementet.
     
   Billetlink skal I ikke udfylde. Det udfyldes automatisk.
     
2. Vent i en op til en time. Place2book tjekker kun om der er nye arrangementer/ændrede arrangementer på jeres hjememside en gang i timen.
   Efter en time sker der to ting:
   - Billetlink-feltet på dit arrangement i cms bliver automatisk udfyldt
   - Arrangementet bliver synligt på Place2books hjemmeside.
   
Kan I ikke vente en time? [Læs her, hvordan man kan gennemtvinge en opdatering via Place2books hjemmeside.](https://www.folkebibliotekernescms.dk/main/indhold/place2book/#gennemtving-opdatering-af-arrangementer-i-place2book)

### Arrangementer med billet og Kultunaut
Place2book kan videresende oplysninger om arrangementer til Kultunaut. Det gælder KUN arrangementer, der har tilknyttet en eller flere billetkategorier, og det sker ikke automatisk.

For hvert arrangement, der skal videresendes til Kultunaut, skal I gør følgende:

1. På [Place2book.com](https://www.place2book.com/) log ind som **Arrangør**.
2. Find dit arrangement, vælg **Rediger** og så **Indstillinger**
3. Gå ned til **Arrangement-specifikke indstillinger** og vælg **Rediger**
   {% include figure class="fifty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/07288fdb-0cd2-4d69-bf32-eba8449b917a" alt="Arrangementet eksporteres til Kultunaut" caption="Arrangementet eksporteres til Kultunaut" %}
5. Kryds af ved **Arrangementet eksporteres til Kultunaut**
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c5912496-3edd-4e25-97e0-f6d7e408068c" alt="Sæt hak ud for Arrangementet eksporteres til Kultunaut" caption="Sæt hak ud for *Arrangementet eksporteres til Kultunaut*" %}
7. Afslut med **Gem**

Bemærk! Arrangementer uden billet (passive arrangementer) kan ikke længere videresendes til Kultunaut via Place2book. Der arbejdes på en direkte integration mellem Folkebibliotekernes CMS og Kultunaut, så Place2book ikke behøver være mellemmand.


### Gennemtving opdatering af arrangementer i Place2book
Place2book tjekker kun om der er nye arrangementer/ændrede arrangementer på jeres hjememside en gang i timen. Nogle gange er det vigtigt at det går hurtigere. I sådan en situation kan I manuelt gennemtvinge en opdatering.

1. På [Place2book.com](https://www.place2book.com/) log ind som **Arrangør**. I topmenuen vælg **Generelt > Folkebibliotekernes CMS**. 
2. Vælg **Hent opdateringer fra Cms**

### For yderligere information, læs [Place2books vejledning til intgrationsløsningen](https://support.place2book.com/support/solutions/articles/80001143841-kom-i-gang){:target="_blank"}
{: .notice--info}
