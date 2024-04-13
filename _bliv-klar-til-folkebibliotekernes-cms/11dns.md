---
title: "Opgave 11: DNS opsætning"
category: "Overgangsaktiviter"
weight: 11
---

**DNS** står for Domain Name Service. Det er DNS registreringen der gør, at jeres hjemmeside adresse virker og peger hen på det rigtige website. Når I skifter fra DDB CMS til Folkebibliotekernes CMS skal jeres hjemmeside adresse (domænenavn) pege på en ny webserver (ip-adresse).

I er selv ansvarlige for at lave DNS registreringen. Det gør I allerede i dag. Nogle biblioteker står selv for DNS-opsætningen, mens andre får hjælp af IT-afdelingen i deres kommune.
I skal finde ud af, hvem der står for jeres DNS-opsætning, og sikre jer at I har adgang til at få lavet en ny DNS registrering, den dag I skal skifte til Folkebibliotekernes CMS.

Sådan gør du:
1.	Gå til: https://who.is/ og indtast jeres nuværende domænenavn f.eks. albertslundbibliotek.dk
2.	Vælg punktet ”DNS records”:
   {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d58f2bb4-308b-4434-b9af-b1d0a83877a7" alt="Slå op på https://who.is, ud af hvem der hoster jeres DNS-opsætning" caption="Slå op på https://who.is, ud af hvem der hoster jeres DNS-opsætning" %} 
4. I dette tilfælde kan du se at udbyderen Gigahost.dk er ansvarlig for DNS opsætningen (andre eksempler er drabib.dk som anvender eurodns.com, bibliotek.kk.dk anvender One.com og bronderslevbib.dk anvender både DBC og KMD).
5. Kontakt den person eller afdeling hos kommunen som er ansvarlig for jeres hjemmesides tekniske drift og har adgang til Gigahost.dk (spørg efter en som kender alt til A-records, MX-records, CNAME m.v.)
6. I forbindelsen med overgangen til ny hjemmeside har I modtaget en række tekniske informationer fra Reload omkring IP-adresser m.v. Disse informationer skal indtastes hos Gigahost.dk (eller hvem der er nu er jeres DNS ansvarlige) af den teknisk kyndige.
7. Bed den teknisk ansvarlige om at teste, at alle dele af den nye opsætning fungerer: e-mail, domæne omdirigeringer, certifikater m.m.
   
Hvis I ønsker at købe nye domænenavne eller tjekke oplysninger for eksisterende, sker det her: punktum.dk (tidligere kaldet DK-Hostmaster)
Bemærk at nye .dk domæner både kan købes hos Punktum.dk samt via forhandlere af webhotel, typisk som en del af en pakke. 

Detaljeret forklaring af hvad der sker i praksis når en bruger indtaster jeres biblioteksdomæne navn i en browser eller klikker på et link med jeres domænenavn:
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/deac92ed-a010-4183-9b54-28a9a0f7a9a6" alt="Sådan virker DNS opslag i praksis" caption="Sådan virker DNS opslag i praksis" %} 




