---
title: "Url-omdirigeringer og omdøbninger"  
category: "Generelt"
---

Der er flere måder at ændre url'erne til jeres sider. 

## Brødkrummestien
Den bedste måde at ændre url'er er ved at opbygge sidens struktur ved brødkrummer. Fordelen ved dette er at man både opbygger brødkrummestien og url'erne på en gang, og de afspejler hinanden fx hvis jeres brødkrummesti ser således ud: Inspiration > Litteratur > Læseklubber, så vil url'en se således ud: www.eksempelbibliotek.dk/inspiration/litteratur/laeseklubber.

[Se hvordan man laver en brødkrummesti]({{ site.baseurl }}{% link _indhold/broedkrummesti.md %}).

## Url-omdiringering
Dette giver mulighed for at lave en eller flere andre url'er, der peger hen til siden. Dette er smart til, hvis I har en plakat, hvor I ønsker en kort url, som borgerne let kan taste ind i en browser. Fx læseklubben 'Tove Ditlevsen klubben' har url'en: www.eksempelbibliotek.dk/inspiration/litteratur/laeseklubber/tove-ditlevsen-klubben, men I ønsker at url'en på plakaten er www.eksempelbibliotek.dk/ditlevsen.
{: .notice--primary}

Fold **URL-omdirigeringer** ud i den højre menu. Tryk på **Add URL redirect**.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/624401a4-c837-4b0f-9bde-e4d1526e4165" alt="Tryk på Add URL redirect" caption="Tryk på Add URL redirect" %}

Indtast den ønskede nye url ind i **Sti**.

{% include figure class="sixty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/150667350/096ab0e3-3504-4d7c-8844-d6f299b872e2" alt="Indtast sti" caption="Indtast sti" %}

## Url-omdøbning
Denne løsning overskriver den automatiske logik, der opretter url'erne i CMS'et.

Dette er kun muligt for webmaster- og programmørbiblioteker. Denne løsning er ikke anbefalet, og skal kun bruges, hvis man er helt sikker på at det er den korrekte løsning. 
