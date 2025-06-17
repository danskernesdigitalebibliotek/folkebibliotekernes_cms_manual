---
title: "Konfiguration af Unilogin på nyt GO i CMS-backend"
category: GO
nav_order: 7
---

Du skal gå ind på jeres eget CMS’ backend og logge ind (du skal have enten rollen ’Administrator’ eller ’Lokaladministrator’). 
Dernæst kopierer du følgende: */admin/config/services/unilogin-configuration* og sætter ind bag-ved url’en i jeres browser. Eksempel fra GOs demo-backend:*https://cms-demo.dpl-cms.dplplat01.dpl.reload.dk/admin/config/services/unilogin-configuration* 
Du kan også finde det, når du er logget ind i jeres backend og ved at føre musen henover ’Indstillinger’ og ’Web-services’, og vælge ’Unilogin configuration’.

---
*For Webmaster biblioteker:* 
Hvis du ikke kan se konfigurationen i jeres backend, så skal du logge ind som ’Administrator’ og gå ind på /admin/people/permissions, filtrere på "unilogin" og give jer selv denne permission.
Så burde du også under fanen ’Configuration’ kunne se ’Unilogin configuration’.
---

Du kommer nu til følgende side, hvor du skal sætte konfigurationerne op. Husk at gemme, når du har sat det op:
{% include figure class="ninety" image_path="https://github.com/user-attachments/assets/cfa18268-3442-4c16-97de-37ccfd7a9e56" %}

Her er oplysningerne, som du skal sætte ind:
- **Unilogin API client secret** = 5b31715e-c2d7-4542-ae7d-99157a150910
- **Unilogin webservice username** = wsereolen
- **Unilogin webservice password** = mDsbp2ha8zv2
- **Retailer key code** = der89pot 
- **Unilogin Municipality ID = BEMÆRK**, at du her skal indsætte kommunenummeret for jeres specifikke kommune. Listen med kommunenumre findes nedenfor.

#### Kommunekodeliste
Find jeres kommune i listen og kopier det ind i konfigurationen:
101: København  
147: Frederiksberg  
151: Ballerup  
153: Brøndby  
155: Dragør  
157: Gentofte  
159: Gladsaxe  
161: Glostrup  
163: Herlev  
165: Albertslund  
167: Hvidovre  
169: Høje-Taastrup  
173: Lyngby-Taarbæk  
175: Rødovre  
183: Ishøj  
185: Tårnby  
187: Vallensbæk  
190: Furesø  
201: Allerød  
210: Fredensborg  
217: Helsingør  
219: Hillerød  
223: Hørsholm  
230: Rudersdal  
240: Egedal  
250: Frederikssund  
253: Greve  
259: Køge  
260: Halsnæs  
265: Roskilde  
269: Solrød  
270: Gribskov  
306: Odsherred  
316: Holbæk  
320: Faxe  
326: Kalundborg  
329: Ringsted  
330: Slagelse  
336: Stevns  
340: Sorø  
350: Lejre  
360: Lolland  
370: Næstved  
376: Guldborgsund  
390: Vordingborg  
400: Bornholm  
410: Middelfart  
411: Christiansø  
420: Assens  
430: Faaborg-Midtfyn  
440: Kerteminde  
450: Nyborg  
461: Odense  
479: Svendborg  
480: Nordfyns  
482: Langeland  
492: Ærø  
510: Haderslev  
530: Billund  
540: Sønderborg  
550: Tønder  
561: Esbjerg  
563: Fanø  
573: Varde  
575: Vejen  
580: Aabenraa  
607: Fredericia  
615: Horsens  
621: Kolding  
630: Vejle  
657: Herning  
661: Holstebro  
665: Lemvig  
671: Struer  
706: Syddjurs  
707: Norddjurs  
710: Favrskov  
727: Odder  
730: Randers  
740: Silkeborg  
741: Samsø  
746: Skanderborg  
751: Aarhus  
756: Ikast-Brande  
760: Ringkøbing-Skjern  
766: Hedensted  
773: Morsø  
779: Skive  
787: Thisted  
791: Viborg  
810: Brønderslev  
813: Frederikshavn  
820: Vesthimmerlands  
825: Læsø  
840: Rebild  
846: Mariagerfjord  
849: Jammerbugt  
851: Aalborg  
860: Hjørring
---
