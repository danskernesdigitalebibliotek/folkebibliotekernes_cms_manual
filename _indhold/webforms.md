---
title: "Webformularer"
category: "Indholdstyper"
weight: 1
emneord:
- "X Mangler tekst"
---

## Webformular oversigten
I topmenuen klik på **Struktur > Webformularer** eller åbn `https://mit-domænenavn.dk/admin/structure/webform` (udskift mit-domænenavn.dk)

Du kommer ind på en oversigt over webformularer, som du har oprettet. Her ligger også jeres **Kontaktformular**. 
Vil du ændre en webformular skal du trykke på **Byg** ude til højre.

## Sådan bygger du en webformular
1. Klik på **Tilføj webform** i øverste højre hjørne.
2. Udfyld **Titel**, **Administrativ beskrivelse** (vises ikke for brugerne) og **Status**, som afgør om formularen er åben for besvarelse eller lukket for besvarelse.
3. Nu kan du tilføje **Elementer** til formularen. Klik på knappen øverst til højre.
   {% include figure class="thirty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/64eadfbe-5c91-4bfa-a449-2f7f97e49bad" alt="Tilføj formularelementer" caption="Tilføj formularelementer" %}

4. Nu åbner elementvælgeren. Du kan vælge mellem mange forskellige elementtyper:
   - **Tekst:** Et lille indtastningsfelt til tekst.
   - **Tekstområde:** Et større indtastningsfelt til tekst med plads til flere tekstlinjer.
   - **Antal:** Indtastningsfelt til tal
   - **E-mail:** Indtastningsfelt til emailadresse
   - **Telefon:** Indtastningsfelt til telefonnummer
   - **Dato:** Datovælger
   - **Dato/tid:** Datovælger + tid
   - **Valg:** Drop-down med valgmuligheder. Der kan kun vælges *en* valgmulighed. Du kan selv definere valgmulighederne, eller vælge mellem prædefinerede lister som f. eks. ugedage eller landenavne.
   - **Select other:** Listevisning af valgmuligheder. *Flere* valgmuligheder kan markeres. Du kan selv definere valgmulighederne på listen, eller vælge mellem prædefinerede lister som f. eks. ugedage eller landenavne.
   - **Send knap(per):** Tilføjer en Send-knap til formularen.
   - **Simpel HTML:** Til at vise ekstra tekst på formularen. 
   - **Term select:** Avanceret element. der gør det muligt at bruge websites taksonomier, som valgmuligheder i en drop-down.
   - **Skjult:** Avanceret element. Gør det muligt at medsende ekstra information på formularen, som brugeren ikke selv indtaster. (En programmør-ting)
  
   Hver elementtype har mange indstillingsmuligheder.
   - Der er indstillinger, der relaterer til **inputvalidering**. Dvs. hvilke værdier, man lovligt kan indtaste, uden at formularen brokker sig.
   - Der er indstillinger, der relaterer til **hjælpetekster**. Der skelnes mellem beskrivelse, hjælpetekst og more-tekst, som kan placeres ret frit i forhold til formularelementet. 
   Leg med det og se hvordan det virker. Holder du musen hen over de små spørgsmålstegn, er der fine små forklarende tekster.

5. Elementerne lægger sig på formularens **Byg-fane**. De ligger i den rækkefølge som du har tilføjet dem.
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/6b269a63-86a8-41c1-8f76-de52ed9c7219" alt="Formularens Byg-faneblad" caption="Formularens Byg-faneblad" %}
   Der er fire faneblade på en formular:
   - **Byg:** Her kan du se alle elementerne på formularen. Du kan ændre deres placering, ved at trække dem op og ned i forhold til hinanden.
   - **Vis:** Her kan du se, hvordan formularen kommer til at se ud. Stylingen er ikke helt perfekt. Det bliver den først, når du indlejrer formularen på en side.
   - **Test:** Her kan du afprøve formularen med mail-afsendelse og det hele.
   - **Indstillinger:** Her skal du ind for at redigere teksten på kvitteringssiden og ordlyden på den kvitteringsemail, der bør sendes til brugeren. Det er også her, du vælger, hvilke email-adresser der skal modtage besvarelsen.
     
   **Obligatoriske felter:** Det er i elementoversigten, at man vælger om et element skal være obligatorisk at udfylde. Det er ikke i elementets indstillinger. Man skal huske at trykke på **Gem elementer** efter man har markeret et element som obligatorisk.


## Kvittering og modtagelse af besvarelser
Når en bruger indsender en formular, er det god stil at vise en **kvitteringsside eller kvitteringsbesked**, hvor der står at deres besvarelse er modtaget. Her skal de også kunne læse, hvornår de evt. kan forvente svar. Samme indhold bør sendes til dem i en **kvitterings-email**. 

Besvarelsen modtager biblioteket pr. email. I kan registrere en eller flere email-adresser, hvortil besvarelserne skal sendes.

### Kvitteringsside / kvitteringsbesked
1. Opsæt kvitteringsside eller kvitteringsbesked ved at åbne formularens **Indstillinger** og så **Bekræftelser**
   ![image](https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/da8767c8-42be-49cb-af1d-27335a066ef8)

   Er kvitteringsteksten meget kort, kan den vises som en besked øverst på formularen (message). Er kvitteringsteksten længere fungerer det bedre, at vise den som en selvstændig side (inline).
   
   Kvitteringstekster skal indeholde information om, hvordan henvendelsen behandles.
   - Hvornår kan de forvente svar
   - Hvem kan de kontakte, hvis de har spørgsmål
  




