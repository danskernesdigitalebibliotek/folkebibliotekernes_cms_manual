---
title: "Opdatering der mislykkes"
category: "Webmasterplanen"
weight: 4
---

Når webmasterbiblioteker overstyrer konfigurationer via indstillinger i backend detekteres ændringerne af modulet Config Ignore Auto. Det er et modul, der sikrer at lokale ændringer ikke overskrives i forbindelse med opdatering af core. Dermed bevares webmasterbibliotekets særlige backend-indstillinger ved opdatering af sitet. 

Ulempen ved den løsning er, at biblioteket kan komme til at sætte en indstilling, der senere viser sig at være i konflikt med core-koden uden at vide det. Det er umuligt at forudsige om en bestemt indstilling i backend sikkert kan ændres lokalt.

**Ved en konfigurationskonflikt kan websitet ikke opdateres. Det kan ske for både modultestsite og driftssite.**

Kan et biblioteks modultestsite eller driftssite ikke opdateres sker følgende:
- Reload kontakter DDF support med detaljeret information om problemet (stack trace)
- DDF support videresender detaljeret fejlinformation til bibliotekets kontaktpersoner 
- Biblioteket løser problemet ved at ændre de konfigurationer, der forårsager fejlen.
- Biblioteket melder deres site klar til DDF Support, som giver oplysningen videre til Reload.
- Reload gør et nyt forsøg på opdatering

Opdatering udsættes til ugen efter, hvis bibliotekets kontaktpersoner ikke svarer eller hvis det ikke muligt for biblioteket hurtigt at tilrette de berørte konfigurationer.
