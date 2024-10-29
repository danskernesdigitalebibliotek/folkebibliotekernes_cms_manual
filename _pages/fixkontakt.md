---
permalink: /overblik/status/fixkontakt
title:  "Fix kontaktformular"
sidebar: true
nav: "overblik"
---
Hvis man har problemer med at kontaktformularen ikke virker fx ved at den ikke vil sende eller modtage mails, så følg denne guide.

## 1. Opret en ny kontaktformular
1. I topmenuen klik på **Struktur > Webformularer** eller åbn `https://mit-domænenavn.dk/admin/structure/webform` (udskift mit-domænenavn.dk). Du kommer ind på en oversigt over webformularer, som du har oprettet. Her ligger også jeres gamle **Kontaktformular**. 
2. Klik på **Tilføj webform** i øverste højre hjørne.
3. Udfyld **Titel** og evt **Administrativ beskrivelse** (vises ikke for brugerne). Tryk på **Gem**.
4. Nu kan du tilføje **Elementer** til formularen. Klik på knappen øverst til højre.
5. Opbyg din kontaktformular således:

- **Tekstfelt** med titel **Dit navn**
- **E-mail** med titel **Din e-mailadresse**
- **Term select** med titel **Kategori**. Vær opmærksom på at den skal have nøglen **kategori**.
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/b0beaba4-9869-4886-ad10-61784e1e85b7" alt="Nøgle skal være kategori" caption="Nøgle skal være kategori" %}
- **Tekstfelt** med titel **Emne**.
- **Tekstområde** med tiel **Besked**.
- **Send knap(per)** (oprettes automatisk).
- **Simpel HTML** med nøgle **persondata**. Teksten i HTML markup er "BEMÆRK! Indsæt aldrig CPR-nummer eller følsomme oplysninger i formularen. Læs mere om behandling af persondata i vores privatlivspolitik." Link til jeres privatlivspolitik. Er som standard /privatlivspolitik.

## 2. Opsæt modtagere af mails

For at få kontaktformularen til at sende mails til bestemte mail-adresser efter hvilken kategori, som borgerne vælger, så skal **Term select** være tilføjet til webformularen i det foregående punkt. Læs mere i det foregående punkt.

- Tilføj en ny mailskabelon via **Indstillinger** og så **Emails/handlers**. Tryk så på knappen **+ Tilføj Email** øverst til højre.
- Tildel evt. titlen **Modtager på biblioteket**.
- I **Send til** feltet vælg **Custom To email address** og indtast `[webform_submission:values:kategori:entity:field_email:value]`. 

## 3. Opsæt kvitteringsmail

- Tilføj en ny mailskabelon via **Indstillinger** og så **Emails/handlers**. 
- Tryk så på knappen **+ Tilføj Email** øverst til højre.
- Man kan kun sende en kvitteringsemail til borgeren, hvis man har sørget for at oprette et **påkrævet email-felt på formularen**. Det gøres med felttypen **Email**.
- I **Send til** feltet vælg email-feltet fra formularen. Har du fulgt denne vejledning til oprettelse af formularen, så burde den hedde **Din e-mailadresse**.
{% include figure class="fifty" image_path="https://github.com/user-attachments/assets/35313895-1e2c-4def-8cfd-faa439b7bccc" alt="Vælg formularfeltet med borgerens email i 'Send til'" caption="Vælg formularfeltet med borgerens email i 'Send til'" %}
- Tilpas overskrift på emailen ved i **Emne** at vælge **Custom subject**.
- Tilpas brødteksten ved i **Brødtekst** at vælge **Custom body** og tilpasse teksten rundt om formulartokens. Formulartokens er placeholders for værdier indsendt via formularen. Man kan udfolde en komplet oversigt over alle tilgængelige formulartokens via et linket **Gennemse tilgængelige tokens**.

Denne tekst kunne fx være (husk at rette tokens til dem, som I har lavet):

Kære [webform_submission:values:dit_navn]\
\
Mange tak for din henvendelse. Vi besvarer henvendelser indenfor X dage.\
\
*Besked blev modtaget: [webform_submission:created]*\
\
**Din besked**\
[webform_submission:values:emne]\
\
[webform_submission:values:besked]\
\
Med venlig hilsen\
Eksempel Bibliotekerne
{: .notice--primary}

## 4. Opsæt kvitteringsside / kvitteringsbesked
- Opsæt kvitteringsside eller kvitteringsbesked ved at åbne formularens **Indstillinger** og så **Bekræftelse**
{% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/da8767c8-42be-49cb-af1d-27335a066ef8" alt="Tilføj formularelementer" caption="Tilføj formularelementer" %}

Er kvitteringsteksten meget kort, kan den vises som en besked øverst på formularen (message). Er kvitteringsteksten længere fungerer det bedre, at vise den som en selvstændig side (inline).
   
Kvitteringstekster skal indeholde information om, hvordan henvendelsen behandles.
   - Hvornår kan de forvente svar
   - Hvem kan de kontakte, hvis de har spørgsmål

## 5. Skift formularen inde på kontaktsiden
- Gå ind på og rediger den side, hvor jeres kontaktformular er. Det er på `https://mit-domænenavn.dk/kontakt` (udskift mit-domænenavn.dk), hvis I ikke har ændret noget.
- Find paragrafen med webformularen og tryk på **Rediger**.
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/453575df-4da7-47f9-811a-b3e65c3ba96f" alt="Tryk på rediger" caption="Tryk på rediger" %}
- Vælg den nye kontaktformular, som I har lavet
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/c6d58851-76c1-4146-98cb-575231725250" alt="Vælg den nye kontaktformular, som I har lavet" caption="Vælg den nye kontaktformular, som I har lavet" %}
- Tryk på **Gem**.

## 6. Test at det virker
1. Gå ind på kontaktsiden - er som standard /kontakt - og udfyld formularen og tryk på Send.
2. Se at der modtages en kvitteringbesked, en kvitteringsmail og en modtagermail.
