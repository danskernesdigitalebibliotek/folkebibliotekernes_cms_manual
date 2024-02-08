---
title: "Opgave 2: Mapp Intelligence"
category: "Startopsætning"
weight: 2
emneord:
  - Statistik
---

Via Mapp indsamles statistik for jeres hjemmeside. I skal have overflyttet jeres Mapp ID fra DDB CMS til Folkebibliotekernes CMS.



## Kopier Mapp ID fra DDB CMS

Log ind i DDB CMS. I topmenuen klik på **Indstillinger > Ding > Webtrekk**

Eller åbn via direkte link (udskift mit-domænenavn.dk):\
https://mit-domænenavn.dk`/admin/config/ding/webtrekk`


Kopier **TagIntegration ID**. Vær omhyggelig så det hele kommer med!

## Indsæt Mapp ID i Folkebibliotekernes CMS
I topmenuen klik på **Indstillinger > System > Mapp Intelligence indstillinger**

Eller åbn via direkte link (udskift mit-staging-domæne.dk):\
https://mit-staging-domæne.dk`/admin/config/system/dpl-mapp`

Indsæt i feltet **ID**

{% include figure image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/3ffdbb57-b309-49b2-80a8-6a34ab2a0f7f" alt="Kopier Mapp ID fra DDB CMS til Folkebibliotekernes CMS" caption="Kopier Mapp ID fra DDB CMS til Folkebibliotekernes CMS" %} 

## Egenkontrol
Det er ikke muligt at tjekke Mapp konfigurationen så længe i arbejder på et staging-site. Når I er overgået til drift kan I udføre Egenkontrol, som beskrevet i  [Konfiguration for MAPP Intelligence](/konfiguration/mapp-intelligence/). 

## Yderligere dokumentation 
[Se konfiguration for MAPP Intelligence](/konfiguration/mapp-intelligence/)
