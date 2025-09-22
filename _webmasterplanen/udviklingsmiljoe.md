---
title: "Udviklingsmiljø"
category: "Webmaster-funktionalitet"
weight: 25
---

Reload har i DPL-CMS projektet lavet et Docker miljø, som kan bruges til lokal udvikling og indeholder webserver, database etc.

Installation af lokalt udviklingsmiljø kræver installation af en Docker klient f.eks. [Docker Desktop](https://www.docker.com/products/docker-desktop/) eller [Orbstack](https://orbstack.dev/).

Derudeover skal [Task](https://taskfile.dev/) være installeret.
Kan afvikles på Linux, Mac, Windows og Windows Subsystem for Linux.

```sh
git clone https://github.com/danskernesdigitalebibliotek/dpl-cms.git
cd dpl-cms
# hvis man ønsker særlige udgaver af Dpl Cms kan man bruge følgende ellers får man den seneste develop udgave.
# lister releases
git tag -l
# bruge den bestemt branch f.eks. en release
git checkout -b 2025-33-0
# bygger et helt nyt Dpl Cms site og henter DPL React
task dev:reset
# sætter bruger 1 adgangskode
task dev:cli -- drush upwd admin etHeltNytUniktPassword
# list kørende docker tjenester
docker ps
```

Url'en / ip adressen til sitet kan fåes på flere måder.

1. Virtual host vha. Dory eller nginx-proxy er beskrevet i den officielle dokumentation
   [https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/local-development/#docker-setup](https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/local-development/#docker-setup){:target="_blank"}

2. Via Docker klient.\
   Hvis man f.eks. bruger Orbstack kan man under DPL-CMS Varnish containeren se IP adresse f.eks. http://localhost:32769/ og en url f.eks. dpl-cms.local

3. Manuelt finde IP adressen.\
   Kommandoen "docker ps" lister kørende docker container og der vil være en Varnish docker for DPL CMS, som er den man skal tilgå for at se sitet i en browser. \
   Find varnish under Images hedder f.eks. dpl-cms-varnish og tjek porten under PORTS f.eks. 80/tcp, 8443/tcp, 0.0.0.0:32770->8080/tcp, [::]:32770->8080/tcp. \
   Sitet kan tilgåes i en browser på f.eks. localhost:32770.

Når sitet er klart, skal man indsætte api nøgler til fbi - men ellers burde indstillinger og rettigheder være klar til, at man kan starte med at udvikle.

Se desuden den officielle dokumentation for flere detaljer såsom certifikater og virtual host.
[https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/local-development/#docker-setup](https://danskernesdigitalebibliotek.github.io/dpl-docs/DPL-CMS/local-development/#docker-setup){:target="_blank"}

Der er lavet en masse task kommandoer til f.eks. at starte Xdebug, køre drush kommandoer osv. De kan ses i Taskfile.yml i roden af DPL CMS projektet.

Her er nogle af

```sh
# kør drush kommando
task dev:cli -- drush ...
# slå dev moduler og indstillinger til
task dev:enable-dev-tools
# slå xdebug til
task dev:enable-xdebug
# stop og start site
task dev:stop
task dev:start
# bygger sitet helt forfra
task dev:reset
```

## Udviklingsindstillinger

Slå caching fra på /admin/config/development/settings og sæt eventuelt Twig i debug mode.

## Xdebug

Slå xdebug til med

```sh
task dev:enable-xdebug
```

Tilføj browser plugin f.eks. Xdebug Helper by JetBrains
(chrome) https://chromewebstore.google.com/detail/xdebug-helper-by-jetbrain/aoelhdemabeimdhedkidlnbkfhnhgnhm

Ved VS Code, lave en launch.json fil i .vscode mappen eller brug et IDE med Xdebug som PhpStorm

```json
{
  "configurations": [
    {
      "name": "Listen for Xdebug",
      "type": "php",
      "request": "launch",
      "port": 9003,
      "pathMappings": {
        "/app": "${workspaceFolder}"
      }
    }
  ]
}
```

Sæt breakpoints og start debugger (ved VScode).

## Tokens

Når fbi nøgler er indsat, kan man få udleveret et fbi token på /dpl-react/user-tokens.

```
window.dplReact = window.dplReact || {};
window.dplReact.setToken("library", "0a4e11b2e3b90c350cf7a440cf9ddfda504051c2")
```

Man kan ikke logge ind som låner, i det lokale udviklingsmiljø. Hvis man har brug for at kunne logge ind som bruger / få et user token - er det nødvendigt, at udvikle direkte på en server (eller bruge en tunnel) og DBC skal tilføje ekstra adresser, som kan logge ind via login.dbc.dk.

## DPL React / DPL Designsystem

Det er muligt, at hente og starte både DPL React og DPL Designsystem, men det er ikke praktisk muligt at implementere ændringer herfra på de lokale sites. Derfor dokumenteres disse dele af tech stacken ikke.