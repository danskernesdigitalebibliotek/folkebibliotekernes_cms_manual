---
title: "Værkvisningsside"
category: "Om visning og reservering"
---

Når en bruger foretager en søgning i Folkebibliotekernes CMS, vil det altid være værker, der vises i søgeresultatet. Også selvom man f. eks. filtrerer på en materialetype. Filtrerer man på ”Online lydbog”, da vises kun de værker, der er manifesteret i materialetypen ”Online lydbog”. 

Fra DDB CMS er vi vant til materialevisningssider for hver udgave og hver materialetype, som en bog er udkommet i. Materialevisningssider findes ikke i Folkebibliotekernes CMS.  

I Folkebibliotekernes CMS er der i stedet en **værkvisningsside**, der rummer alle de materialetyper og udgaver, som et værk findes i.
## Handleknappen
På værkvisningssiden kan man skifte mellem de tilgængelige materialetyper. Én materialetype vil altid være den aktive, og handleknappen vil afspejle den valgte materialetype.
{% include figure class="fourty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/deb9a210-26ff-46ed-a92d-c1ef38b0562f" alt="Skift mellem materialetyper på værkvisningssiden" caption="Skift mellem materialetyper på værkvisningssiden" %} 


Her er en oversigt over materialetyper og deres handleknapper.

| Materialetype| Handleknap |
| -------- | ------- |
| Alle fysiske materialetyper  | Reservér |
| E-bog	| Gå til ereolen |
| Film (online) eller tv-serie (online)	| Gå til filmstriben |
| Artikel fra digital artikelservice | Bestil digital kopi |
| Artikel fra Infomedia	| Læs artikel |
| Artikel (online) | Se online |

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/f737d72c-b376-466e-9f44-bca1030661b3" alt="Handleknapperne for de forskellige materialetyper" caption="Handleknapperne for de forskellige materialetyper" %} 
## Værkvisningssidens opbygning
På værkvisningssiden kan brugerne finde rigtig mange metadata om det valgte værk.
Siden er organiseret sådan, at de vigtigste (titel, forfatter og beholdning) vises øverst sammen med handleknappen.
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/45051913-2cef-48b8-9a45-cd6cba509102" alt="Øverste del af en værkvisningsside" caption="Øverste del af en værkvisningsside" %} 

Klik på **Find på hylden** for at se hvor materialet er hjemme. Oversigten er blevet gjort mere overskuelig da man skal "udfolde" biblioteket før beholdningsdetaljerne vises.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bd651637-480d-4043-852c-0085c84087e3" alt="Beholdningsoversigt" caption="Beholdningsoversigt" %} 

Nedenunder vises de næstvigtigste (beskrivelse, emnetal – hvis værket er faglitterært, serie – hvis værket er en del af en serie, emneord osv.
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/cbefaabe-ae05-4b87-8232-ea55636e9376" alt="Midterste del af en værkvisningsside" caption="Midterste del af en værkvisningsside" %} 

Nederst vises de metadata, der vurderes kun at være relevante for et mindretal af brugere – udgave, forlag, isbn mv, samt oplysninger om de enkelte udgaver og manifestationer.
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/58b125da-b134-4cfe-b778-2711d799a5de" alt="Nederste del af en værkvisningsside" caption="Nederste del af en værkvisningsside" %} 

De nederste metadata er ”foldet ind”, og kan først ses efter klik på de relevante ”folde-ud-pile”.
## Metadata knyttet til værk / manifestation
Nogle metadata er værk-specifikke, andre er manifestations-specifikke.

De manifestations-specifikke metadata vises under ”Udgaver” -> ”Detaljer for materialet”
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/bdb4757c-7e2a-4c47-b6d2-8d3f9cb3d927" alt="Manifestations-specifikke metadata" caption="Manifestations-specifikke metadata" %} 

De værk-specifikke metadata vises under ”Detaljer”:
{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/7d0f2006-61b4-4ab6-84f7-fec7649c08e8" alt="værk-specifikke metadata" caption="værk-specifikke metadata" %} 

Hvilket så ikke er helt sandt. For der er ikke ret mange metadata, der er værkspecifikke. Selv titlen kan variere, som f. eks. når ”Krabben med de Gyldne Kløer” bliver nyoversat til ”Krabben med de Gyldne Klosakse”, og en ny udgave af en artikelsamling kan få en ny redaktør, osv. Men eftersom der er en række metadata, som brugerne forventer at se om værket, som strengt taget ikke er værk-specifikke, så ”snyder” vi lidt, og udvælger ud fra forskellige kriterier en manifestation i den valgte materialetype, som repræsenterer værket under ”Detaljer”.






