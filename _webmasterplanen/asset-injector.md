---
title: "Asset Injector og Add to Head"
category: "Webmaster-funktionalitet"
weight: 5
---

Stort set alle webmasterbiblioteker har valgt at installere tredjepartsmodulerne Asset Injector samt Add to Head.

Fordi de er så bredt anvendt, behandles de her i manualen. Vær dog opmærksom på, at de ikke er en del af FB CMS og som sådan ikke er supporterede af DDF.

## Asset Injector
Asset Injector-modulet gør det muligt for administratorer at tilføje egne CSS- og JavaScript-koder til Drupal-sitet uden at ændre i tema- eller kodefiler.
CSS- og JS-injektioner tilføjes gennem en brugervenlig grænseflade i backend. Her kan du målrette injektionen til bestemte sider, indholdstyper, brugerroller eller hele sitet, hvilket giver stor fleksibilitet.

Asset Injector er nem at komme i gang med og har flere fordele i forhorld til FB CMS.

- **Dit site kan altid opdateres**: Udvikling på hjemmesiden lavet med Asset Injector vil aldig spænde ben for at jeres site kan opdateres. Det værste der kan ske er at dine tilpasninger holder op med at virke når sitet opdateres.
- **Du lægger ikke sitet ned**: Du kan ikke lave noget, der får dit site til at gå ned. 
- **Du kan nemt rulle tilbage**: Får du lavet noget kode, der ikke opfører sig som tiltænkt, går du bare ind på Asset Injector i backend og deaktiverer din injection. Du skal være meget uheldig, hvis din kode gør backend utilgængelig.

- Når det er sagt er Asset Injector stadig et udviklingsværktøj, der kræver viden og omtanke. Man kan sagtens skrive kode der ødelægger funktionalitet på sitet og smadrer styling.
- Tjek op på dine injections efter hver core opdatering for at sikre dig at alting stadig fungerer som det skal.

## Add to Head-modulet
Add to Head-modulet gør det muligt at injicere indhold direkte i HTML-sidens <head>, samt i $scripts og $styles elementerne i page.tpl.php-skabelonen.

Add to Head har samme fordele som Asset Injector. 
