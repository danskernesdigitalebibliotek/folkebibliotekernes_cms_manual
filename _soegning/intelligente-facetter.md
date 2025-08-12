---
title: "Intelligente facetter"
category: "Om søgning"
---
Et søgeresultat vises sådan her. Facet-båndet er markeret med rødt.

{% include figure class="seventy" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/159251423/17db49c3-5d86-4552-be9a-aa486173c532" alt="Søgefacetter i et søgeresultat" caption="Søgefacetter i et søgeresultat" %}

Der findes 12 forskellige facet-bånd, der kan vises for brugerne: Studerende, Børnebøger, Ebøger, Faglitteratur, Film, Film for børn, Lydbøger, Lydbøger for børn, Musik, Skønlitteratur, Spil og Spil for børn.

Ud fra det søgeresultat, brugerens søgning har returneret, vælger sitet ét af dem. Hvis fx næsten alle posterne i søgeresultatet er værker, der findes som ebøger, så giver det ikke mening at give brugeren mulighed for at vælge kun at se ebøger, for det gør han allerede i forvejen.

Hvilket af de 12 bånd der vælges, og hvilke facetter der udleveres i disse bånd, afgøres ikke af en logik, der ligger i selve sitet – det bliver afgjort ”længere nede”, nemlig i den service, sitet benytter sig af – FBI API. Det er altså ikke noget, der kræver konfiguration.
