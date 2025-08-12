---
title: "DNS opsætning"  
category: Go-live
---
Guide til GO subdomæne opsætning
Denne guide informere om hvordan subdomænet skal sættes for jeres bibliotek.
Vejledning
Gå ind på jeres webhotels control panel (eller der, hvor DNS'en for domænet styres fra). Gå til DNS indstillinger. DNS indstillinger kan i nogle tilfælde være gemt væk under en tab eller en side som kan hedde noget i stil med avancerede indstillinger.
Når DNS indstillinger er fundet, tryk da på ny record eller, hvis siden er på engelsk: create new record. Der skal nu være mulighed for at vælge en record type og der vælges CNAME som type.
Der skal nu være mindst 2 felter og helst 3. De felter skulle gerne være hostname, alias for og TTL.
I Hostname skrive for f.eks. Hernings bibliotek www.go.herningbib.dk. I Alias for skrives cluster-1.folkebibliotekernescms.dk og i TTL skrives der 3600.
For de biblioteker som også har et sekundært domæne, er proceduren den samme for det sekundære domæne. Der skal også oprettes en CNAME record for denne. I Hernings tilfælde ville den skulle udfyldes som følger:
Hostname go.herningbib.dk
Alias for cluster-1.folkebibliotekernescms.dk
TTL 3600
Opsummering
Der skal for de domæner biblioteket benytte oprettes en CNAME DNS record per domæne. Alle CNAME records der oprettes for subdomænet skal have Aliaset cluster-1.folkebibliotekernescms.dk
samt en TTL ppå 3600.
Subdomænet, som skal skrives is hostnavn-feltet skal have en af følgende udformninger:
- www.go.biblioteksdomæne.dk
- go.biblioteksdomæne.dk
