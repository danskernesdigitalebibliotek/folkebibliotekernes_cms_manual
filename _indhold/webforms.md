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

## Indlejring af webformularer på sider, artikler og arrangementer
Webformularer er designet til at skulle indlejres i sider, artikler eller arrangementer via et paragraph-element. Først ved indljring ser webformularer pæne ud. Derfor skal de ikke bruges selvstændigt, men altid indlejres via paragraph element på en side, ariklel eller arrangement. 
   {% include figure class="sixty" image_path="https://github.com/user-attachments/assets/7e6b7669-2ff3-4621-9748-dbe3f29b2711" alt="Webforms skal indlejres på sider, artikler eller arrangementer vha. webforms paragraphs element" caption="Webforms skal indlejres på sider, artikler eller arrangementer vha. webforms paragraphs element" %}

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


## Kvittering og besvarelser
Når en bruger indsender en formular, er det god stil at vise en **kvitteringsside eller kvitteringsbesked**, hvor der står at deres besvarelse er modtaget. Her skal de også kunne læse, hvornår de evt. kan forvente svar. Samme indhold bør sendes til dem i en **kvitterings-email**. 

Besvarelserne modtager biblioteket pr. email. I kan registrere en eller flere email-adresser, hvortil besvarelserne skal sendes.

### Kvitteringsside / kvitteringsbesked
1. Opsæt kvitteringsside eller kvitteringsbesked ved at åbne formularens **Indstillinger** og så **Bekræftelse**
   {% include figure class="eighty" image_path="https://github.com/danskernesdigitalebibliotek/folkebibliotekernes_cms_manual/assets/1641342/da8767c8-42be-49cb-af1d-27335a066ef8" alt="Tilføj formularelementer" caption="Tilføj formularelementer" %}

   Er kvitteringsteksten meget kort, kan den vises som en besked øverst på formularen (message). Er kvitteringsteksten længere fungerer det bedre, at vise den som en selvstændig side (inline).
   
   Kvitteringstekster skal indeholde information om, hvordan henvendelsen behandles.
   - Hvornår kan de forvente svar
   - Hvem kan de kontakte, hvis de har spørgsmål
  
### Kvitterings email og besvarelser via email
Der skal oprettes to forskellige mail-skabeloner pr. formular. 
- En kvitteringsskabelon, der har borgeren som modtager
- En besvarelsesskabelon, der har biblioteket som modtager
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/b1f529b4-ee8f-4d39-a9f2-a7b3ccab9956" alt="Formularer skal have en kvitteringsskabelon og en besvarelsesskabelon" caption="Formularer skal have en kvitteringsskabelon og en besvarelsesskabelon" %}

#### Kvitteringsemail
Man kan kun sende en kvitteringsemail til borgeren, hvis man har sørget for at oprette et påkrævet email-felt på formularen. Det gøres med felttypen **Email**.

Tilføj en ny mailskabelon  via **Indstillinger** og så **Emails/handlers**. Tryk så på knappen **+ Tilføj Email** øverst til højre.

I **Send til** feltet vælg email-feltet fra formularen.
{% include figure class="fifty" image_path="https://github.com/user-attachments/assets/35313895-1e2c-4def-8cfd-faa439b7bccc" alt="Vælg formularfeltet med borgerens email i 'Send til'" caption="Vælg formularfeltet med borgerens email i 'Send til'" %}

Tilpas overskrift på den automatisk genererede kvitteringsemail ved i **Emne** at vælge **Custom subject**.
Tilpas brødteksten ved i **Brødtekst** vælg **Custom body** og tilpasse teksten rundt om formulartokens. Formulartokens er placeholders for værdier indsendt via formularen. Man kan udfolde en komplet oversigt over alle tilgængelige formulartokens via et linket **Gennemse tilgængelige tokens**.

Herunder er kvitteringsskabelonen for kontaktformularen. Den kan bruges som inspiration.
{% include figure class="eighty" image_path="https://github.com/user-attachments/assets/dc184f71-b8d1-409c-b223-6dc9659a5d7d" alt="Tilret emne og brødtekst på kvitteringsmail" caption="Tilret emne og brødtekst på kvitteringsmail" %}

#### Besvarelser via email
Det er meget vigtigt at oprette en mailskabelon for besvarelser. Gør I ikke det, modtager I ganske enkelt ikke de indsendte besvarelser.

Tilføj en ny mailskabelon via **Indstillinger** og så **Emails/handlers**. Tryk så på knappen **+ Tilføj Email** øverst til højre.

I **Send til** feltet vælg **Custom To email address** og indtast emailadresser på de kolleger, der skal modtage besvarelser fra formularen. Adskil med komma.
{% include figure class="fifty" image_path="https://github.com/user-attachments/assets/0d821cf0-faf6-431c-b5d8-f7c5729a01bd" alt="Vælg 'Custom to email address' og indtast emails" caption="Vælg 'Custom to email address' og indtast emails" %}

Hvis I ønsker det, kan I også tilrette **Emne og brødtekst** på den email, der genereres. Standardteksten er dog helt ok, da indholdet fra alle formularfelter automatisk kommer med.






  




