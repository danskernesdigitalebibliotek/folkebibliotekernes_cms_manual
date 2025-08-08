---
title: "Opgave 12: Redirects fra søgeresultater på Google"
weight: 12
category: "Basis konfiguration"
emneord:
  - "URL omdirigeringer"
---
Jeres nye website er ikke identisk med det gamle. I har sikkert oprettet nyt indhold, fjernet noget gammelt og flyttet rundt med ting.

Søgemaskinerne kender jeres gamle website, og har indekseret strukturen herfra. Når I skifter til den nye hjemmeside, vil mange af de links, som Google har registreret ikke længere fungere. 

Mange bruger Google som trinbræt til at finde ind på jeres hjemmeside. Det kan derfor være en god investering for jer, at sørge for at de links som Google viser i søgeresultatet, bliver ved med at fungere og at de peger på relevant indhold på jeres nye website.

I kan sagtens oprette redirects til Google-links på den nye hjemmeside inden I går live. De påvirker ikke noget i Google eller på den gamle hjemmeside.

## Få overblik over URLer som Google peger på
1. I skal starte med at lave en søgning i Google. Søg på navnet på jeres bibliotek.
2. Google viser et søgeresultat med nogle links, der peger ind på jeres hjemmeside. Hold musen henover hvert af disse links og læg mærke til den URL, der peges på.
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3e26f6ed-4931-4aa8-8ff0-3b1c37685226" alt="Få overblik over links i Google søgeresultater der peger på jeres hjemmeside" caption="Få overblik over links i Google søgeresultater der peger på jeres hjemmeside" %}

4. Sæt linknavn og URL ind i et dokument, så I kan arbejde videre med det. F. eks.

|Linknavn|URL|
|---|---|
|Åbningstider|/biblioteker|
|Arrangemneter|/arrangementer|
|Netbiblioteket|/netmedier|

Biblioteker der bruger **Google Search Console** kan via dette værktøj finde en komplet oversigt over sider som Google har indekseret. Efter go live vil I også kunne få værdifuld information om døde søgeresultat-links, som Google registerer.
{: .notice--info}

## Opret omdirigering for links, der ikke virker
Nu har I har et overblik over hvilke URLer, der er linkes til fra Googles søgeresultater. De links URLer skal også fungere når I lancerer jeres nye hjemmeside.
1. Afprøv om de virker på jeres staging-site, ved at sætte stien ind bag staging-domænenavnet. F. eks. `https://nginx.main.sonderborg.dplplat01.dpl.reload.dk/biblioteker`
   (Vi kan røbe at `/biblioteker` virker :-))
2. De links der ikke virker, skal der oprettes en omdirigering på.
3. Find ud af, hvilken side på det nye website, som I ønsker at linket skal pege på. Det kan faktisk være svært, hvis linket peger på indhold, som ikke er medtaget på det nye website. I så fald må I omdirigere til noget, der ligner lidt.
4. I hovedmenuen på jeres nye website vælg **Omdirigeringer** og tryk på den blå knap **Tilføj omdirigering**
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/47bdf0e6-bec7-4328-bf3d-1ef7b624e904" alt="Opret omdirigering" caption="Opret omdirigering" %}
6. Tast URL fra den gamle hjemmeside i feltet **Sti**\
   Tast URL på den nye hjemmeside i feltet **Til**
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/a53d88db-95bd-4e8e-9b38-819c97c70fd9" alt="Opret omdirigering" caption="Opret omdirigering" %}
8. Husk at trykke **Gem** nederst.


