---
title: "Mapp Intelligence"
category: "Konfiguration"
emneord: 
- "Statistik"
---
Webstatistik indgår også som en del af den hjemmesidepakke, Det Digitale Folkebibliotek tilbyder. Vi benytter det statistikværktøj, der hedder Mapp. Mapps danske leverandør hedder KPI Index.

Alle spørgsmål om Mapp sendes til Tue Gaston [ext-pu6z@kk.dk](mailto:ext-pu6z@kk.dk). Det er også Tue I skal
skrive til, hvis I har forlist jeres password til Mapp.
{: .notice--info}

[Læs mere om Mapp](https://detdigitalefolkebibliotek.dk/section/i-brug-paa-
biblioteket/bibliotekernes-web-og-appstatistik). Og besøg også vores [”Kom-godt-i-gang-med-Mapp-side”](https://detdigitalefolkebibliotek.dk/node/103)

For at data fra hjemmesiden sendes til Mapp skal to felter være rigtig udfyldt – ”Domæne” og ”Tag
Integration ID”.

## Her finder du indstillinger for Mapp
I topmenuen klik på **Indstillinger > System > Mapp Intelligence indstillinger**

Eller åbn via direkte link (udskift mit-domænenavn.dk):\
https://mit-domænenavn.dk`/admin/config/system/dpl-mapp`


## Anbefalede indstillinger for Mapp

|Feltnavn|Værdi|
|---|---|
|Domæne|`responder.wt-safetag.com`|
|ID|Et tal der udleveres af DDF (henvendelse til Tue Gaston)|

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/1228c354-f4de-4547-b1a4-98e308c8d955" alt="MAPP indstillinger" caption="MAPP indstillinger" %} 

## Egenkontrol
Tjek om der er forbindelse til Mapp. Bemærk! Det kan kun udføres fra et difts-site. Ikke fra et staging-site.
1. Åbn en tilfældig side på jeres website i en browser.
2. Tjek at alle browser-udvidelser (extensions) er deaktiverede
3. Tryk F12 for at åbne udvikler-værktøjer.

4. Vælg den fane der hedder "Network"
    {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/b3778132-0fde-4aae-bf3f-799f205addc6" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} 

5. Sørg for at ”Request types” står til ”All”
    {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/62a176bb-c0fe-4c77-aa59-68bd4f5651f9" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} 

6. Under ”Filter” skriver du ”wt” (for ”Webtrekk”, som Mapp hed i gamle dage)
    {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/c7ed1115-1b9b-4adc-aa87-a720bbf25549" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} 

7. Genindlæs nu siden (tryk F5)
8. Nu kan du se alt, hvad der bliver sendt til Mapp.
- Hvis du har konfigureret forkert, er der sandsynligvis tomt.
- Hvis du har konfigureret korrekt, står der en masse linjer. Det kan se lidt forskelligt ud fra browser til browser.

9. Sådan ser det ud når der er forbindelse til Mapp. Har du en Name-kolonne skal du kigge efter linjer der starter med ”wt?p=”.
    {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/d7d65bb9-a419-4d6e-b54e-a92e2e8e5470" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} Har du en URL-kolonne ser resultatet sådan ud.
  
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/335ed487-4223-4d65-976b-b9b215650d13" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} 

## Alternativ egenkontrol
Alternativt kan du naturligvis også logge ind i Mapp og tjekke, om de handlinger, du foretager, bliver sporet i Mapp.
Hvis du vælger den fremgangsmåde, skal du blot være opmærksom på to ting:

- Eventuel anti-sporings-software på din browser skal være deaktiveret
- Du skal tjekke at det tidspunkt, der står under ”Last raw data update” i nederste højre hjørne, er senere end det tidspunkt, hvor du har udført de handlinger, du gerne vil se derinde.
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/feef5056-e591-43d7-be3e-cfef384c6ecb" alt="Mapp egenkontrol" caption="Mapp Egenkontrol" %} 

 
