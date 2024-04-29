---
title: "Url-omdirigeringer og omdøbninger"  
category: "Generelt"
---

Der er flere måder at ændre url'erne til jeres sider. 

## Brødkrummestien
Den bedste måde at ændre url'er er ved at opbygge sidens struktur ved brødkrummer. Fordelen ved dette er at man både opbygger brødkrummestien og url'erne på en gang, og de afspejler hinanden fx hvis jeres brødkrummesti ser således ud: Inspiration > Litteratur > Læseklubber, så vil url'en se således ud: www.eksempelbibliotek.dk/inspiration/litteratur/laeseklubber.

[Se hvordan man laver en brødkrummesti]({{ site.baseurl }}{% link _indhold/broedkrummesti.md %}).

## Url-omdiringering
Dette giver mulighed for at lave en eller flere andre url'er, der peger hen til siden. Dette er smart til, hvis I har en plakat, hvor I ønsker en kort url, som borgerne let kan taste ind i en browser. Fx læseklubben 'Tove Ditlevsen klubben' har url'en: www.eksempelbibliotek.dk/inspiration/litteratur/laeseklubber/tove-ditlevsen-klubben, men I ønsker at url'en på plakaten er www.eksempelbibliotek.dk/ditlevsen. Denne løsning beholder den automatisk oprettede url, som CMS'et genererer.

I topmenuen klik på **Omdirigeringer** eller åbn https://mit-domænenavn.dk/admin/config/search/redirect (udskift mit-domænenavn.dk)

Tryk på **Tilføj omdirigering**

Indtast den ønskede nye url ind i **Sti** fx "ditlevsen", hvis urlen skal være www.eksempelbibliotek.dk/ditlevsen.

Enten kopier en URL ind eller søg efter indhold på hjemmesiden i **To**

## Url-omdøbning
Denne løsning overskriver den automatiske logik, der opretter url'erne i CMS'et. Dette er kun muligt for rollerne **Administrator** og **Lokal administrator**. Denne løsning er ikke anbefalet, og skal kun bruges, hvis man er helt sikker på at det er den korrekte løsning. 
{: .notice--danger}

Fold **Alternativ URL** ud. Slå **Opret automatisk URL alias** fra. Og indtast ny url i feltet **Alternativ URL**.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/08eceda5-0bd7-4dfa-a84b-64dcbe9c44bd" alt="Indtast url" caption="Indtast url" %}
