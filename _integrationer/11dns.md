---
title: "Opgave 11: DNS opsætning"
category: "Overgangsaktiviter"
weight: 11
---

**DNS** står for Domain Name Service. Det er DNS registreringen der gør, at jeres hjemmeside adresse virker og peger hen på det rigtige website. Når I skifter fra DDB CMS til Folkebibliotekernes CMS skal jeres hjemmeside adresse (domænenavn) pege på en ny webserver (ip-adresse).

I er selv ansvarlige for at lave DNS registreringen. Det gør I allerede i dag. Nogle biblioteker står selv for DNS-opsætningen, mens andre får hjælp af IT-afdelingen i deres kommune.
I skal finde ud af, hvem der står for jeres DNS-opsætning, og sikre jer at I har adgang til at få lavet en ny DNS registrering, den dag I skal skifte til Folkebibliotekernes CMS.

Sådan gør du:
1.	Gå til: [https://who.is/](https://who.is/) og indtast jeres nuværende domænenavn f.eks. *albertslundbibliotek.dk*
2.	Vælg punktet **DNS record**:
      {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d58f2bb4-308b-4434-b9af-b1d0a83877a7" alt="Slå op på https://who.is og find ud af hvem der hoster jeres DNS-opsætning" caption="Slå op på https://who.is og find ud af hvem der hoster jeres DNS-opsætning" %}
4.	I dette tilfælde kan du se at udbyderen Gigahost.dk er ansvarlig for DNS opsætningen (andre eksempler er drabib.dk som anvender eurodns.com, bibliotek.kk.dk anvender One.com og bronderslevbib.dk anvender både DBC og KMD).
5. Kontakt den person eller afdeling hos kommunen som er ansvarlig for jeres hjemmesides tekniske drift og har adgang til Gigahost.dk (spørg efter en som kender alt til A-records, MX-records, CNAME m.v.)
6. Med DDF aftales hvilken dato og tidspunkt, I går live.  I kan selv vælge hvilken ugedag I ønsker at gå live - dog ikke en fredag aht muligheden for at kunne tilrette div. opsætninger inden weekenden, såfremt det skulle være nødvendigt.
7. Før golive dagen:\
   a. I bør bede jeres leverandør om at sænke TTL (time-to-live) til **600** på jeres domæne, for at sikre en hurtig overgang. Ellers kan der gå flere timer, før alle ser den nye side.
   b. Har man CAA records, skal man følge denne guides eksempel 1, 2 eller 3, for at sikre at vi kan udstede et certifikat til sitet: https://help.zerossl.com/hc/en-us/articles/360060119753-Invalid-CAA-Records. Hvis ikke man ved hvilket eksempel der er bedst, så kontakt DDF for hjælp.
9. På golive dagen:\
   a. Ret alle DNS A-records for jeres domæner til at pege på følgende IP-adresse: **20.86.109.250**
   b. Ret alle DNS CNAME-records for jeres domæner til at pege på følgende domæne: **cluster-1.folkebibliotekernescms.dk**
10. Efter golive:\
   a. I skal bede jeres DNS udbyder om at hæve TTL på jeres domæner igen.
11. Bed den teknisk ansvarlige om at teste, at alle dele af den nye opsætning fungerer: e-mail, domæne omdirigeringer, certifikater m.m.
12. Efter golive kan I finde den gamle hjemmeside på adressen **[kommune].ddbcms.dk** Her vil den være tilgængelig indtil jeres kontrakt med DBC udløber.

I skal ikke gøre noget ifm. **SSL certifikater**, som dannes fra vores side vha. Lets Encrypt af Reload. I kan dog først de dem efter go live.
{: .notice--primary}

Hvis I ønsker at købe nye domænenavne eller tjekke oplysninger for eksisterende, sker det her: punktum.dk (tidligere kaldet DK-Hostmaster)
Bemærk at nye .dk domæner både kan købes hos Punktum.dk samt via forhandlere af webhotel, typisk som en del af en pakke. 

Detaljeret forklaring af hvad der sker i praksis når en bruger indtaster jeres biblioteksdomæne navn i en browser eller klikker på et link med jeres domænenavn:
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/deac92ed-a010-4183-9b54-28a9a0f7a9a6" alt="Sådan virker DNS opslag i praksis" caption="Sådan virker DNS opslag i praksis" %} 





