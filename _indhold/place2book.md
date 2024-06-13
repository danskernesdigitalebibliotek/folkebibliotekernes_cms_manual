---
title: "Place2book integration"  
category: "Generelt"
---

Billetsystemet Place2book har udviklet en integration til Folkebibliotekernes CMS via [arrangements APIet](https://www.folkebibliotekernescms.dk/main/bliv-klar-til-folkebibliotekernes-cms/9integrationer/#arrangements-api-til-brug-for-eksterne-systemer). Arrangements APIet er tilgængeligt for alle billetleverandører, der ønsker at bygge integration til Folkebibliotekernes CMS.



## Opsæt Place2book integration
Denne guide forudsætter at dit bibliotek/kommune er kunde hos Place2book.

1. I Folkebibliotekernes CMS opret en redaktionel bruger med rollen **Eksternt system**. Her er [guide til at oprette redaktionel bruger](https://www.folkebibliotekernescms.dk/main/konfiguration/personer/#opret-ny-redaktionel-bruger).
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/91ca0296-20fb-48d8-926d-af8338471255" alt="Opret bruger til Place2book" caption="Opret bruger til Place2book" %} 

3. Kontakt [support@place2book.com](mailto:support@place2book.com) for at få åbnet for integrationen.
   
4. På [Place2book.com](https://www.place2book.com/) log ind som **Arrangør**. I topmenuen vælg **Generelt > DPL CMS**. (Menupunktet bliver først synligt, når der er blevet åbnet for integrationen)
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3f90dac1-06a4-4cbc-9efb-6dfa51af375d" alt="Log ind i Place2book og gå til menupunktet DPL CMS" caption="Log ind i Place2book og gå til menupunktet DPL CMS" %} 
6. I vinduet der åbner skal der indtastes nogle oplysninger:   
   - I **Brugernavn & Password** indsæt brugernavn og adgangskode for den bruger i oprettede i trin 1. (Den skelner mellem store/små bogstaver, så tast rigtigt)
   - I **DPL CMS Url** indsætter I `https://mit-domænenavn.dk/api/v1/events` (udskift mit-domænenavn.dk)
   - Marker **Importer arrangementer uden priser** hvis I ønsker arrangementer uden billet (passive arrangementer) overført til Kultunaut via Place2book. (Pt. er der fejl i denne funktion. Fluebenet betyder lige nu at gratis arrangementer med billet overføres. Arrangementer uden billet overføres ikke, selvom fluebenet er sat)
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f9a0b3fe-8f45-4c34-9a76-e0438ea52b20" alt="Indtast API-url og brugernavn + adgangskode i Place2book" caption="Indtast API-url og brugernavn + adgangskode i Place2book" %} 




Under udarbejdelse...



### For yderligere information, læs [Place2books vejledning til intgrationsløsningen](https://support.place2book.com/support/solutions/articles/80001143841-kom-i-gang){:target="_blank"}
{: .notice--info}
