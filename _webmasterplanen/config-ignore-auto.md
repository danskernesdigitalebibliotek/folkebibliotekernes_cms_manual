---
title: "Drupal-modulet: Config Ignore Auto"
weight: 5
---
Drupal-modulet **Config Ignore Auto** er som standard aktiveret i Folkebibliotekernes CMS og kan ikke deaktiveres. Det er et modul som alle webmasterudviklere bør kende til.

## Hvad er det?

**Config Ignore Auto** er et Drupal-modul, der opdager og registrerer alle ændringer, som du foretager gennem administrationsgrænsefladen i backend. Det kan være en oversættelse du ændrer, eller et flueben, som du sætter på en indstillingsside.  

## Sådan virker det

- **Automatisk sporing**  
  Når modulet er aktiveret, overvåger det ændringer foretaget gennem administrationsgrænsefladen og tilføjer dem til listen over ignorerede konfigurationer.


- **Brugsscenarie**
De indstillinger, som Config Ignore Auto har tilføjet til sin liste overskrives ikke når core opdateres. Dvs. de bevarer den værdi som du har sat - også selvom standardværdien ændrer sig.


Hvis **Config Ignore Auto** ikke var installeret ville webmasterbibliotekerne miste deres lokale konfiguration hver uge, når ders site opdateres.

## Hvad skal jeg være opmærksom på
Det er let og hurtigt at ændre en indstilling via administrationsgrænsefladen men det kommer med en risiko.

Hvis du har ændret en indstilling, som en core 
Men det kommer med en risisko som men skal være opmærksom på som 
Men det lægger også et stort ankan være nyttigt, medfører det visse risici.

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

