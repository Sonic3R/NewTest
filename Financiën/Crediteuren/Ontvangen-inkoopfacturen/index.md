# Ontvangen inkoopfacturen

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=6b1&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces wordt de factuur ontvangen, vindt een eerste beoordeling plaats en wordt de factuur geregistreerd.

## Scannen en e-mailen van de factuur die via de post is binnengekomen.

Deze processtap vindt buiten Dynamics Empire plaats. Via de post binnengekomen facturen dienen gescand te worden en verzonden te worden naar de factureninbox. 

## Registreren document

Facturen die zijn binnengekomen in de factureninbox worden automatisch geregistreerd in Dynamics Empire als een **Inkomend document**. Wanneer het aangemaakte document één PDF betreft zal deze direct doorgezet worden naar de herkensoftware van ReadSoft, waarna u de herkende gegevens kunt aanvullen of accorderen. Hoe u dit doet wordt uitgelegd in processtap **[Controleren herkenning](#controleren-herkenning)**.
Wanneer er meer dan één PDF aanwezig is op het inkomende document dient het document beoordeeld en handmatig afgehandeld te worden. Hoe dit werkt wordt uitgelegd in de processtap **[Beoordelen document](#beoordelen-document)**. 

## Beoordelen document

Als het inkomende document dat aangemaakt is, niet direct vanuit de facturenmailbox doorgezet kan worden naar de herkensoftware, dient u het document te beoordelen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Inkomende documenten**.
2. Zet een filter op alle inkomende documenten met de status **Nieuw**. Dit zijn de documenten die nog niet doorgestuurd zijn naar de herkensoftware en die beoordeeld dienen te worden. 
3. Open het document dat u wilt beoordelen. Vind de geïmporteerde bijlage in het veld **Hoofdbijlage** en extra bijlage op tabblad **Ondersteunende bijlage**. 
4. Als het inkomende document geen factuur betreft, of de factuur is onjuist, dan kunt u het inkomende document verwijderen door op **Verwijderen** te klikken. Daarna kunt u desgewenst de leverancier informeren (processtap **[Informeren leverancier](#informeren-leverancier)**).
5. Kan het document alsnog doorgezet worden naar de herkensoftware, of dienen er zaken aangepast te worden voor het document doorgezet kan worden, ga dan verder bij processtap **[Aanpassen document](#aanpassen-document)**. 

## Aanpassen document

Wanneer na de processtap **[Beoordelen document](#beoordelen-document)** gebleken is dat het inkomende document wel degelijk een factuur betreft, dan kan na eventuele aanpassingen het document alsnog handmatig doorgezet worden naar de herkensoftware. Alleen de bijlage die gepresenteerd wordt in het veld **Hoofdbijlage** wordt verstuurd naar de herkensoftware. 

### Bevat het **Inkomende document** meer dan één factuur? 

1. Sla de extra facturen in dit geval eerst op, op uw harde schijf. Selecteer vervolgens de regel(s) met de extra factuur (facturen) op tabblad **Ondersteunende bijlage** en klik vervolgens op **Regels verwijderen**. Wanneer de **Hoofdbijlage** doorgezet kan worden naar de herkenfunctionaliteit klikt u op **Verzenden naar OCR-service**.
2. U kunt een nieuw inkomend document aanmaken voor de opgeslagen extra facturen door terug te keren naar de lijst met **Inkomende documenten** en vervolgens op **Maken van bestand** te klikken. U selecteert het opgeslagen bestand. Er wordt vervolgens een nieuw inkomend document aangemaakt met de factuur gekoppeld als **Hoofdbijlage**.  Zet het aangemaakte document door naar de herkensoftwarde door op **Verzenden naar OCR-service** te klikken. 

### Is de hoofdbijlage niet het document dat doorgezet moet worden naar de herkensoftware? 

1. Sla de bijlage die wel doorgezet dient te worden als bijlage op, op uw harde schijf. Selecteer vervolgens de juiste regel op tabblad **Ondersteunende bijlage** en klik vervolgens op **Regels verwijderen**.
2. Klik op **Hoofdbijlage vervangen** en selecteer het zojuist opgeslagen bestand. 
3. Klik op **Verzenden naar OCR-service** om het inkomende document door te zetten naar de herkensoftware. 

### Is de hoofdbijlage het document dat doorgezet moet worden naar de herkensoftware? 

Klik op **Verzenden naar OCR-service** om het inkomende document door te zetten naar de herkensoftware. 

## Herkennen factuur

In deze stap zal de herkensoftware de tekens op het PDF-document gaan herkennen en proberen te koppelen aan een in Dynamics Empire geregistreerde leverancier. Dit proces verloopt automatisch. 

## Controleren herkenning

Wanneer de factuur herkend is door de herkensoftware dient de herkenning bevestigd, aangepast of aangevuld te worden. Dit doet u binnen de herkensoftware. De inkomende documenten die ter controle klaar staan in de herkensoftware hebben in het veld **OCR-status** de waarde 'In afwachting van verificatie'.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Inkomende documenten** en zet een filter op alle inkomende documenten met OCR-status 'In afwachting van verificatie'. Dit zijn de documenten die doorgestuurd zijn naar de herkensoftware en die binnen de herkenapplicatie beoordeeld dienen te worden. 
2. Klik op **In afwachting van verificatie** om de factuur te openen in de herkensoftware. 
3. Aan de rechterkant van het scherm kunt u de herkende velden controleren. De oranjegekleurde velden dient u altijd te bevestigen of aan te vullen. Ook velden die oranjegekleurd zijn en terecht leeg zijn dient u met een **Enter** te bevestigen.
4. Is een veld niet of niet juist herkend, dan kunt u de applicatie de herkenning leren verbeteren. Ga met uw cursor in het niet (juist) herkende veld staan. Klik vervolgens twee keer de positie in de factuur aan waar de te herkennen waarde zich bevindt. U zult zien dat het veld gevuld wordt met de geselecteerde waarde. 
5. Zijn alle velden aan de rechterkant juist herkend of aangevuld, dan kunt u met de groene knop rechts onderin de herkende waarde terugsturen naar Dynamics Empire. U keert nu terug naar de lijst met facturen die gecontroleerd dienen te worden. U kunt de volgende factuur openen door te dubbelklikken op de regel met de volgende factuur.  

## Aanpassen status

Als het aanvullen van de factuurgegevens in de herkensoftware niet direct plaats kan vinden, bijvoorbeeld doordat de leverancier nog niet bekend is in Dynamics Empire, dan kunt u de factuur in de herkensoftware op 'Afwachten' zetten. 

1. Klik in het scherm met de herkende factuur op de knop met het Pauze-teken. U kunt een reden opgeven waarom u deze factuur de afwachtstatus mee wilt geven. Klik op **OK**.
2. U keert nu terug naar de lijst met facturen die nog gecontroleerd dienen te worden. U zult zien dat de factuur op 'Afwachten' staat en dat de reden die u opgegeven heeft getoond wordt. 

## Registreren herkende gegevens

Wanneer de factuur herkend en aangevuld is in de herkensoftware worden de herkende gegevens teruggestuurd naar Dynamics Empire en geregistreerd op het inkomende document. Dit gebeurt automatisch. 

## Aanmaken factuur

Nadat de herkende gegevens geregistreerd zijn in Dynamics Empire wordt er op basis van de geregistreerde gegevens een inkoopfactuur aangemaakt. Dit gebeurt automatisch. Kan op basis van de herkende gegevens geen factuur aangemaakt worden, dan wordt de **Status** van het inkomende document aangepast naar 'Mislukt'. 

## Corrigeren herkende gegevens

Als in de processtap **Aanmaken factuur** de factuur niet aangemaakt kon worden doordat de herkende gegevens niet juist waren, dan kunnen deze gegevens gecorigeerd worden op het inkomende document. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Inkomende documenten**.
2. Zet een filter op alle inkomende documenten met de status **Mislukt**. Op het inkomende document. 
3. In het de fasttab **Fouten en waarschuwingen** vindt u de reden waarom er geen inkoopfactuur aangemaakt kon worden. 
4. Wanneer dit veroorzaakt wordt door niet volledig of juist herkende gegevens kunt u deze gegevens corrigeren door op **OCR-gegevens corrigeren** te klikken. Vul de niet juist herkende velden aan en sluit het scherm. 
5. Klik op **Document maken** om de inkoopfactuur aan te maken. 

## Informeren leverancier

Wanneer het document of de factuur niet juist of volledig is dient de leverancier hiervan op de hoogte gesteld te worden. Dit gebeurt buiten Dynamics Empire om, bijvoorbeeld door middel van het sturen van een e-mail. 

## Zie ook

[Verwerken inkoopfacturen](../verwerken-inkoopfacturen/)  
[Verwerken inkoopcreditnota's](../verwerken-inkoopcreditnotas/)  
[Beheren rekening-courant-crediteuren](../beheren-rekening-courant-crediteuren/)  
[Verwerken terugkoopfactuur onroerend goed](../verwerken-terugkoopfactuur-onroerend-goed/)
