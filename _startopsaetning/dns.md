---
title: "DNS opsætning"  
category: Go-live
---
**DNS** står for Domain Name Service. Det er DNS registreringen der gør, at jeres hjemmeside adresse virker og peger hen på det rigtige website. 
Biblioteket har ansvaret for at lave DNS registreringen. 

I nogle kommuner er det biblioteket selv står selv for DNS-opsætningen, mens andre får hjælp af IT-afdelingen i deres kommune.

**I skal finde ud af, hvem der står for jeres DNS-opsætning, og sikre jer at I har adgang til at få lavet en ny DNS registrering, den dag I vil lancerer jeres website.**

## Find ud af hvem der står for jeres DNS-opsætning
Sådan gør du:
1.	Gå til: [https://who.is/](https://who.is/) og indtast jeres nuværende domænenavn f.eks. *albertslundbibliotek.dk*
2.	Vælg punktet **DNS record**:
      {% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d58f2bb4-308b-4434-b9af-b1d0a83877a7" alt="Slå op på https://who.is og find ud af hvem der hoster jeres DNS-opsætning" caption="Slå op på https://who.is og find ud af hvem der hoster jeres DNS-opsætning" %}
3.	I dette tilfælde kan du se at udbyderen Gigahost.dk er ansvarlig for DNS opsætningen (andre eksempler er drabib.dk som anvender eurodns.com, bibliotek.kk.dk anvender One.com og bronderslevbib.dk anvender både DBC og KMD).
4. Kontakt den person eller afdeling hos kommunen som er ansvarlig for jeres hjemmesides tekniske drift og har adgang til Gigahost.dk (spørg efter en som kender alt til A-records, MX-records, CNAME m.v.)

## Aftal go-live dato med DDF
- Med DDF aftales hvilken dato og tidspunkt, I går live.  I kan selv vælge hvilken ugedag I ønsker at gå live - dog ikke en fredag aht muligheden for at kunne tilrette div. opsætninger inden weekenden, såfremt det skulle være nødvendigt.
- Hvis I har kommunens IT-afdeling til at hjælpe jer med DNS-opsætningen, så book dem på go-live dagen
- Send nedenstående vejledning til teknikerne der skal ændre jeres DNS-indstillinger

## DNS opgaven (skrevet til teknikere)
### Nogle dage før go-live dagen
 - I bør bede jeres leverandør om at sænke TTL (time-to-live) til **600** på jeres domæne, for at sikre en hurtig overgang. Ellers kan der gå flere timer, før alle ser den nye side.
 - Har man CAA records, skal man følge denne guides eksempel 1, 2 eller 3, for at sikre at vi kan udstede et certifikat til sitet: https://help.zerossl.com/hc/en-us/articles/360060119753-Invalid-CAA-Records. Hvis ikke man ved hvilket eksempel der er bedst, så kontakt DDF for hjælp.
   
### På go-live dagen
1. Ret alle DNS A-records for jeres biblioteksdomæner til at pege på følgende IP-adresse: **20.86.109.250**

2. Ret alle DNS CNAME-records for jeres biblioteksdomæner til at pege på følgende domæne: **cluster-1.folkebibliotekernescms.dk**

3. Opret to nye DNS CNAME records til GO subdomænerne.

      Begge subdomæner SKAL oprettes. Også selvom I tænker, at I kun vil bruge det ene.
      
         
      | Hostname                   | Alias for                              | TTL  |
      |----------------------------|----------------------------------------|------|
      | go.biblioteksdomæne.dk     | cluster-1.folkebibliotekernescms.dk     | 3600 |
      | www.go.biblioteksdomæne.dk | cluster-1.folkebibliotekernescms.dk     | 3600 |
      
      
   Her er vist et eksempel med *herningbib.dk*. I skal  udskifte *biblioteksdomæne.dk* med jeres domænenavn.
      
      | Hostname                   | Alias for                              | TTL  |
      |----------------------------|----------------------------------------|------|
      | go.herningbib.dk    | cluster-1.folkebibliotekernescms.dk     | 3600 |
      | www.go.herningbib.dk | cluster-1.folkebibliotekernescms.dk     | 3600 |


### Efter go-live:
 - I skal bede jeres DNS udbyder om at hæve TTL på jeres domæner igen.
 - Bed den teknisk ansvarlige om at teste, at alle dele af den nye opsætning fungerer: e-mail, domæne omdirigeringer, certifikater m.m.

## SSL-certifikater
I skal ikke gøre noget ifm. **SSL certifikater**, som dannes fra vores side vha. Lets Encrypt af Reload. I kan dog først de dem efter go live.

## Nyt domænenavn
Hvis I ønsker at købe nye domænenavne eller tjekke oplysninger for eksisterende, sker det her: punktum.dk (tidligere kaldet DK-Hostmaster)
Bemærk at nye .dk domæner både kan købes hos Punktum.dk samt via forhandlere af webhotel, typisk som en del af en pakke. 
