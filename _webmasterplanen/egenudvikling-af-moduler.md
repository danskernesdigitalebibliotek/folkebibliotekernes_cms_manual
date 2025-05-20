---
title: "Egenudvikling af moduler"
weight: 5
---
# Drupal-modulet: Config Ignore Auto

## Hvad er det?

**Config Ignore Auto** er et Drupal-modul, der automatiserer håndtering af konfigurationer ved at registrere og ignorere ændringer, der foretages gennem administrationsgrænsefladen i backend. Det forhindrer utilsigtet overskrivning af disse ændringer ved fremtidige opdateringer af core.

## Funktioner

- **Automatisk sporing**  
  Når modulet er aktiveret, overvåger det ændringer foretaget gennem administrationsgrænsefladen og tilføjer dem til listen over ignorerede konfigurationer.


- **Brugsscenarie**
Modulet er nyttigt, når redaktører eller site-administratorer foretager ændringer, der ikke bør overskrives når core opdateres – fx ændringer i Views, blokke eller webformularer. Det reducerer behovet for koordination mellem udviklere og redaktører.



Selvom **Config Ignore Auto** kan være nyttigt, medfører det visse risici.

## ⚠️ 1. Konfigurationsdrift
- **Forklaring**: Ændringer på live-sitet ignoreres ved import, så live-sitet afviger gradvist fra versioneret konfiguration.
- **Problem**: Gør det svært at genskabe fejl eller udviklingsmiljøer.

## ⚠️ 2. Utilsigtet ignorering af vigtig konfiguration
- **Forklaring**: Modulet tilføjer automatisk ændringer til ignore-listen.
- **Problem**: Vigtige ændringer kan blive udeladt fra deploys, hvilket kan skabe fejl eller sikkerhedsproblemer.

## ⚠️ 3. Forvirring blandt teammedlemmer
- **Forklaring**: Det er uklart, hvorfor nogle konfigurationer ikke importeres.
- **Problem**: Tid spildes på fejlsøgning og fejlagtige rettelser.

---

## 🛡️ Sådan afbøder du problemer

- Brug kun modulet til specifikke undtagelser (fx pr. miljø-konfigurationer som sitenavn).
- Gennemgå jævnligt listen over ignoreret konfiguration.
- Dokumentér ændringer foretaget på live-sitet.
- Informér teamet om hvordan og hvorfor konfiguration ignoreres.

---

