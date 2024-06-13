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

3. Kontakt [support@place2book.com](mailto:support@place2book.com) for at få åbnet for integrationen. Når Place2book har aktiveret integrationen og I har fuldført denne guide, da vil arrangementer oprettet efter dette tidspunkt bliver overført til Place2book. Bemærk! Hvis I allerede har oprettet arrangementer, som I ønsker overført til Place2book, skal I skrive det i emailen. Place2book kan da køre et ekstra job, der henter tidligere oprettede arrangementer.
   
4. På [Place2book.com](https://www.place2book.com/) log ind som **Arrangør**. I topmenuen vælg **Generelt > DPL CMS**. (Menupunktet bliver først synligt, når der er blevet åbnet for integrationen)
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3f90dac1-06a4-4cbc-9efb-6dfa51af375d" alt="Log ind i Place2book og gå til menupunktet DPL CMS" caption="Log ind i Place2book og gå til menupunktet DPL CMS" %} 
5. I vinduet der åbner skal der indtastes nogle oplysninger:   
   - I **Brugernavn & Password** indsæt brugernavn og adgangskode for den bruger i oprettede i trin 1. (Den skelner mellem store/små bogstaver, så tast rigtigt)
   - I **DPL CMS Url** indsætter I `https://mit-domænenavn.dk/api/v1/events` (udskift mit-domænenavn.dk)
   - Marker **Importer arrangementer uden priser** hvis I ønsker arrangementer uden billet (passive arrangementer) overført til Kultunaut via Place2book. (Pt. er der fejl i denne funktion. Fluebenet betyder lige nu at gratis arrangementer med billet overføres. Arrangementer uden billet overføres ikke, selvom fluebenet er sat)
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f9a0b3fe-8f45-4c34-9a76-e0438ea52b20" alt="Indtast API-url og brugernavn + adgangskode i Place2book" caption="Indtast API-url og brugernavn + adgangskode i Place2book" %} 

## Arbejdsgang omkring arrangementer og Place2book
Når jeres Place2book integration er opsat korrekt, skal I arbejde med arrangementer på denne måde:

### Sådan oprettes arrangement med billet
1. Opret et [arrangement](https://www.folkebibliotekernescms.dk/main/indhold/arrangement/). Det er vigtigt, at I tilknytter en eller flere **Billetkategorier**. Det er dem der får Place2book til at tilknytte billetsalg til arrangementet. **Billetlink** skal ikke udfyldes.
2. Vent i en time. Place2book tjekker om der er nye arrangementer/ændrede arrangementer på jeres hjememside en gang i timen. Der kan derfor gå op til en time før jeres arrangement dukker op på Place2book.
3. Log ind på Place2book som arrangør. Find arrangementet og kopier **Salgslink**.
   ![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/378e3903-4e5b-44d6-8318-6690b0692dc2)

1. Når I har oprettet et arrangement, der kræver billet, skal I vente op til en time på at jeres arrangement dukker op på Place2book. Lige nu henter Place2book kun arrangementer fra jres hjemmeside en gang i timen.
2. Når I har ventet en time logger I ind som Arrangør på Place2book. I finder jeres 

Under udarbejdelse...



### For yderligere information, læs [Place2books vejledning til intgrationsløsningen](https://support.place2book.com/support/solutions/articles/80001143841-kom-i-gang){:target="_blank"}
{: .notice--info}
