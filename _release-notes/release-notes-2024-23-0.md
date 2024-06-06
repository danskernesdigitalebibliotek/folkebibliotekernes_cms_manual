---
title:  "Release Notes 2024.23.0"
category: "Release Notes"
weight: 993
---

# Mere brugervenligt dashboard, stylet loginside for redaktionelle brugere, avanceret funktionalitet til webforms og cookiebanner


## Nye features
- Overskredne lån: Henvisning og information om overskredne lån på ”Gebyr og erstatninger” user/me/fees.

- Loginside for redaktionelle brugere: Nyt design på /user/login.

- Webforms: Nu muligt at tilføje en lang række nye felttyper bl.a. ”Hidden”, ”Number”, ”Telephone” og ”Date”.

- Webforms: Nu muligt at tilføje conditions til felter, så f.eks. et felt vises på baggrund af brugerens tidligere valg.

- Webforms: Nu muligt at styre hvor bekræftelsesbesked vises, f.eks. om det skal være på samme side som formularen eller på separat side. 

- Arrangementer: Nu muligt at angive andre start- og sluttidspunkter end :00 og :30. 

- Cookie Information: Cookiebanner installeret. 




## Fejlrettelser og forbedringer

- Dashboard: /user/me/dashboard er justeret til efter input fra brugertest. Det er nu tydeligt hvad der er  overskrifter på siden og link til alle reservering og lån er tydeliggjort. 

- Arrangement: Brødtekstfelt er nu flyttet op under descriptionfeltet på arrangementer.
  
- Arrangement: Manchet på arrangementer ser nu ud som manchetten på artikler.
  
- Filialer: På /biblioteker vises der nu ikke billedkreditering på filialbilleder.
  
- Paragraph ”Navigation Spot”: Nu vises billedtekster ikke på Navigation Spot.
  
- Tilgængelighed: Størrelse af målområde for søgeikon er skiftet fra 20x20 til 24x24 som mindstekrav for at efterleve WCAG 2.2 2.5.8.
  
- Tilgængelighed: Aria-label ”Åbn brugermenu” til login-ikon. 

- Tilgængelighed: Ved brug af tastaturnavigation: Efter man har slettet en søgerække under ”Avanceret søgning” sættes fokus aktivt. 

- Tilgængelighed: Flere elementer i gruppemodaler for lån havde tidligere samme ID. Alle ID’er er nu unikke. 

- Tilgængelighed: Dropdown med link til avanceret søgning formidler nu tilstand (at elementet kan foldes ud og at det er foldet ud) til skærmlæser.

- Digitale lån vises ikke længere på listen over materialer, der snart skal fornys.
   
- Digitale lån: Brugerprofilen user/me afspejler nu korrekt antal mulige digitale lån.
   
- Webforms: Nu ikke muligt at ændre e-mailadresse under admin/config/system/site-information og afsendernavn i forbindelse med konfiguration af webforms. Hvis disse oplysninger ændres videresendes data ikke fra webforms.  



