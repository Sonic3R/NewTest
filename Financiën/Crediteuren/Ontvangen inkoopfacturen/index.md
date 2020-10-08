# Ontvangen inkoopfacturen

In dit werkproces wordt de factuur ontvangen, vindt een eerste beoordeling plaats en wordt de factuur geregistreerd.

## Het scannen en e-mailen van de factuur die via de post is binnengekomen.
Deze processtap vind buiten Dynamics Empire plaats. Via de post binnengekomen facturen dienen gescand te worden en verzonden te worden naar de facturen inbox. 

## Registreren document
Facturen die binnen zijn gekomen in de facturen inbox worden automatisch geregistreerd in Dynamics Empire als een **Inkomend document**. 
Wanneer het aangemaakt document 1 PDF bevindt zal deze direct doorgezet worden naar de herken software van ReadSoft waarna u de herkende gegevens kunt aanvullen of accorderen. Hoe u dit doet wordt uitgelegd in processtap **Controleren herkenning**. 
Wanneer er meer dan 1 PDF aanwezig is op het inkomende document dan dient het document beoordeeld en handmatig afgehandeld te worden. Hou dit werkt wordt uitgelegd in de de processtap. **Beoordelen document**. 

## Beoordelen document
Wanneer het inkomende document wat aangemaakt is vanuit de facturen mailbox niet direct doorgezet kan worden naar de herken software dient u het document te beoordelen. 

 - Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Inkomende documenten**. en zet een filter op alle inkomende documenten met de status **Nieuw**. Dit zij de documenten die nog niet doorgestuurd zijn naar de herken software en die beoordeeld dienen te worden. 
 - Open het document wat u wilt beoordelen. Vind de geïmporteerde bijlage in het veld **Hoofdbijlage** en extra bijlage in de fasttab **Ondersteunende bijlage**. 
- Wanneer het inkomende document geen factuur betreft of de factuur is onjuist kunt u het inkomende document verwijderen door op **Verwijderen te klikken**. Daarna kunt u desgewenst de leverancier informeren  (processtap **Informeren leverancier**)
- Kan het document als nog doorgezet worden naar de herkensoftware of dienen er zaken aangepast te worden voor het document doorgezet kan worden ga dan verder bij processtap **Aanpassen document**. 

## Aanpassen document
Wanneer na de processtap **Beoordelen document** gebleken is dat het inkomende document wel degelijk een factuur betreft dan kan na eventueel aanpassingen het document alsnog handmatig doorgezet worden naar de herken software. Alleen de bijlage die gepresenteerd wordt in het veld **Hoofdbijlage** wordt verstuurd naar de herken software. 

Bevat het **Inkomende document** meer dan 1 factuur? 
- Sla de extra facturen in dit geval eerst op, op uw harde schijf. Selecteer vervolgens de regel(S) met de extra factuur(en) in de fasttab **Ondersteunende bijlage** en klik vervolgens op **Regels verwijderen**. Wanneer de **Hoofdbijlage** doorgezet kan worden naar de herken functionaliteit klikt u op **Verzenden naar OCR-service**.
- U kunt een nieuw inkomend document aanmaken voor de opgeslagen extra facturen door terug te keren naar de lijst met **Inkomende documenten ** en vervolgens op **Maken van bestand** te klikken. U selecteert het opgeslagen bestand. Er wordt vervolgens een nieuw inkomend document aangemaakt met de factuur gekoppeld als **Hoofdbijlage**.  Zet het aangemaakte document door naar de herkensoftwarde door op **Verzenden naar OCR-service** te klikken. 

Is de hoofdbijlage niet het document wat doorgezet moet worden naar de herken software? 

-Sla de bijlage die wel doorgezet dient te worden als bijlage op, op uw hardeschijf. Selecteer vervolgens de rege met de  in de fasttab **Ondersteunende bijlage** en klik vervolgens op **Regels verwijderen**.
- Klik op **Hoofdbijlage vervangen** en selecteer het zojuist opgeslagen bestand. 
- Klik op **Verzenden naar OCR-service** om het inkomende document door te zetten naar de herkensoftware. 

Is de hoofdbijlage het document dat doorgezet moet worden naar de herken software? 

- Klik op **Verzenden naar OCR-service** om het inkomende document door te zetten naar de herkensoftware. 

## Herkennen factuur

In deze stap zal de herken software de tekens op het PDF document gaan herkennen en proberen te koppelen aan een in Dynamics Empire geregistreerde leverancier. Dit proces verloop automatisch. 

## Controleren herkenning

Wanneer de factuur herkend is door de herken software dient de herkenning bevestigd, aangepast of aangevuld worden. Dit doet u binnen de herken software. De stappen die u hier dient te ondernemen zijn geen onderdeel van deze werkinstructie. De inkomende documenten die te controle klaar staan in de herken software hebben in het veld **OCR status** de waarde **In afwachting van verificatie**. 

## Aanpassen status
Deze processtap wordt uitgevoerd binnen de herken software en is geen onderdeel van deze werkinstructie.

## Registreren herkende gegevens

Wanneer de factuur herkend en aangevuld is in de herken software worden de herkende gegeven terug gestuurd naar Dynamics Empire en geregistreerd op het inkomende document. Dit gebeurt automatisch. 

## Aanmaken factuur
Nadat de herkende gegevens geregistreerd zijn in Dynamics Empire wordt er o.b.v. de geregistreerde gegevens een inkoopfactuur aangemaakt. Dit gebeurd automatisch. Kan o.b.v. de herkende gegevens geen factuur aangemaakt worden dat wordt de **Status** van het inkomend document aangpast naar **Mislukt**. 

## Corrigeren herkende gegevens

Wanneer in de processtap **Aanmaken factuur** de factuur niet aangemaakt kon worden doordat de herkende gegevens niet juit waren dan kunnen deze gegevens gecorigeerd worden op het inkomende document. 

 - Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Inkomende documenten**. en zet een filter op alle inkomende documenten met de status **Mislukt**. Op het inkomende document. 
 - In het de fasttab **Fouten en waarschuwingen** vindt u de reden waarom er geen inkoopfactuur aangemaakt kon worden. 
 - Wanneer dit veroorzaakt wordt door niet volledig of juist herkende gegevens kunt u deze gegevens corrigeren door op **OCR-gegevens corrigeren** te klikken. Vul de niet juist herkende velden aan en sluit het scherm. 
 - Klik op **Document maken** om de inkoopfactuur aan te maken. 

## Informeren leverancier
Wanneer het document of de factuur niet juist of volledig is dient de leverancier hiervan op de hoogte gesteld te worden. Dit gebeurd buiten de ERP. Bijvoorbeeld doormiddel van het sturen van een email. 



## Zie ook

[Verwerken inkoopfacturen](../verwerken-inkoopfacturen/)  
[Verwerken inkoopcreditnota's](../verwerken-inkoopcreditnotas/)  
[Beheren rekening-courant-crediteuren](../beheren-rekening-courant-crediteuren/)  
[Verwerken terugkoopfactuur onroerend goed](../verwerken-terugkoopfactuur-onroerend-goed/)
