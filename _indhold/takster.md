---
title: "Takster"
---
**Takster** er en informationsside om gebyrtakster, erstatninger og betaling.
Der linkes til denne side flere steder, bla. fra Gebyrer & Erstatninger, men også fra materialer, som er ved at udløbe.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/9cc5c619-8716-434b-8122-77ab2df80bcc" alt="Fra Gebyrer & erstatninger er der link til siden Takster" caption="Fra Gebyrer & erstatninger er der link til siden Takster" %} 

## Tilret teksten på siden Takster
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/2965b5e9-631f-4def-96c1-a9ecc1989de3" alt="Find siden Pausefunktion under indhold og tilret teksten efter jeres behov" caption="Find siden Pausefunktion under indhold og tilret teksten efter jeres behov" %} 

Standardteksten må gerne tilrettes:
1. Find siden der hedder **Takster**. Den kan fremsøges under **Indhold**.
2. Tryk på **Rediger siden** og tilret teksten efter ønske.
3. Tryk **Gem**

## Erstat den faste side Takster med en anden side

Er du kommet til at slette siden Takster, kan du oprette en ny side, og få de indbyggede links til at pege på den.

1. Opret en ny side, der skal erstatte den faste side Takster. Læg mærke til sidens URL. Den kan du se i browserens adresselinje. Det er den sidste del der er interessant. Den hedder noget med **node/xxx**. (xxx er et tal)
2. Nu skal du registerer den nye sides URL i indstillinger for websiden. Log ind med en bruger, der har rollen **Lokal administrator**.
3. I topmenuen klik på **Indstillinger > Biblioteksindstillinger > Indstillinger for gebyrside**\
Eller åbn via URL: https://mit-domænenavn.dk/admin/config/dpl-library-agency/fees (udskift mit-domænenavn.dk)
4. På siden **Gebyrindstillinger** find feltet **URL**
5. Udfyld med den relative URL på den nye side. Dvs. `node/xxx`, hvor xxx er et tal.

{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/69bc79be-20e9-42a6-a10f-18cb52aff1b7" alt="Læg mærke til den nye sides URL" caption="Læg mærke til den nye sides URL." %} 

## Takster standardteksten
Har du mistet standardteksten, så er den her:

>
> ## Takster
>
> Her kan du se gældende regler og satser for lånetider, gebyrer og erstatninger.
>
> Du skal betale gebyr efter gældende takst, hvis du afleverer for sent. Gebyrerne er fastsat af Kommunalbestyrelsen i **[Dannevang Kommune]**.
>
> Du kan på hjemmesiden under Gebyrer & Erstatninger se, om du skylder et eller flere gebyrer.
> Eventuelle rykkergebyr fremgår ikke på hjemmesiden, men dem vil du kunne få oplyst ved henvendelse til Opkrævningen tlf. **[XXXXXXX]**
>
> Du er selv ansvarlig for løbende at kontrollere, hvad du har lånt og få det afleveret til tiden. Du kan se dine lån under Lån, hvor du også har mulighed for at forny.  Du kan også kontrollere din lånerstatus på > udlånsautomaterne på biblioteket.
> 
> Gebyr påløber fra dagen efter den dato, der fremgår af din kvittering og af din lånerstatus.
>
> ### Gebyrtakster:
> **Børn under 18 år**
>
> 1 - 7 dage: kr. 10,-
>
> 8 - 14 dage kr. 40,-
>
> 15 - 30 dage kr. 55,-
>
> Efter 30 dage kr. 120,-
>
> **Voksne fra 18 år**
>
> 1 - 7 dage: kr. 20,-
>
> 8 - 14 dage kr. 70,-
> 
> 15 - 30 dage kr. 120,-
>
> Efter 30 dage kr. 230,-
>
>
> Hvis du ikke afleverer til tiden, skal du betale et gebyr, og efter 30 dage også en erstatning. Afleverer du materialet i god stand senest 30 dage efter rettidig afleveringsdato, skal du kun betale gebyrerne. Afleveringskvitteringen er din dokumentation for at have afleveret de lånte materialer. Kontrollér ved aflevering, at alle materialer er korrekt registreret og står på din kvittering.
>
> Ved overskridelse af afleveringsdatoen gælder:
> 
> - Hvis man låner flere materialer samtidig og afleverer/fornyer materialerne samlet, vil man få ét gebyr.
> - Hvis man låner flere materialer samtidig, men afleverer/fornyer materialerne af flere omgange, vil man få ét gebyr pr. aflevering.
> Du vil blive udelukket fra at låne og reservere materialer, hvis du skylder 200 kr. eller mere.
>  
> 
> ### Erstatninger
> Hvis du ødelægger, mister eller ikke afleverer bibliotekets materialer, skal du erstatte dem. Du har som den sidst registrerede låner erstatningspligten, hvis du ikke har gjort opmærksom på en eventuel skade, før du lånte materialet.
> 
> Hvis du ikke har afleveret det lånte materiale 30 dage efter lånetidens udløb, betragter vi det som bortkommet og du vil få sendt en erstatning i din digitale post.
> 
> Bortkommet eller beskadiget materiale, skal erstattes med bibliotekets indkøbspris inkl. moms. Udover erstatningsbeløbet skal du betale for udgifter til fx indbinding og licensrettigheder. For DVD, video og multimedier som cd-rom og konsolspil bliver din udgift typisk flere gange den pris, varen fås til i almindelig detailhandel. Det skyldes, at bibliotekets pris indeholder betaling til rettighedshaverne for at få tilladelse til udlån.
> 
> ### Advis og hjemkaldelse på sms, e-mail eller App
> Hvis du har oplyst din e-mailadresse og/eller dit mobilnummer, vil du få tilsendt en advis **[XX]** dage før afleveringsfristen. Du kan indsætte dit mobilnummer og/eller din e-mail under brugerprofil, når du er logget ind. Du kan også få adviseringer som Push-beskeder i App’en ”Biblioteket”.
>  
> ### Vi rykker kun én gang
> Vær opmærksom på, at biblioteket kun udsender én hjemkaldelse ved overskridelse af lånetiden. Vi sender hjemkaldelsen **[XX]** dage efter, at lånetiden er udløbet. Du skal altid betale gebyr, hvis du afleverer for sent, også selvom du ikke har modtaget en påmindelse eller hjemkaldelse før afleveringsfristen.
>  
> ### Hold styr på udlåns- og afleveringsdatoerne
> På din udlånskvittering og i din lånerstatus står datoen for, hvornår du skal aflevere dine lånte materialer. Dette er sidste dag, du kan aflevere materialet, uden gebyr.
> 
> Bemærk at der kan gå op til 72 timer før din betaling kan ses på hjemmesiden og i Biblioteket app’en. Derfor vil du kunne opleve, at der stadig vises gebyrer/erstatninger på din konto, når du logger ind på hjemmesiden/app’en, selvom du lige har betalt din regning.
> På Mit Betalingsoverblik kan du altid se en opdateret status på dine betalinger til biblioteket.
>  
> ### Sådan betaler du
> Betaling af regninger skal ske via **[Dannevang Kommunes]** Mit Betalingsoverblik, Netbank med MitID eller i banken. Har du spørgsmål til selve betalingen, skal du kontakte **[XX]** på tlf. **[XXXX]**
>
> ### Det er vigtigt få betalt
> Betaler du ikke inden betalingsfristen, vil der komme rykkergebyrer på regningen:
> 
> - For gæld under 500 kr. er rykkergebyret 150 kr.
> - For gæld over 500 kr. er rykkergebyret 250 kr.
> Har du spørgsmål til din regning kan du kontakte Opkrævningen tlf. **[XXXXXXX]**
