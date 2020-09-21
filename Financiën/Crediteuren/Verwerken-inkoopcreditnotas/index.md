# Verwerken inkoopcreditnota's

In dit werkproces worden de ontvangen inkoopcreditnota's gecontroleerd, gecodeerd en geboekt.

## Boeken verplichting
Zodra de algemene inkoopcreditnotagegevens in uw systeem geregistreerd zijn kan de correctie van de betalingsverplichting geboekt worden. Voorafgaand aan deze boeking kunnen de gegevens op de inkoopcreditnota gecontroleerd en aangevuld worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Inkoopcreditnota's**. Stel een filter in op het veld **Boekstatus** = 'Ongeboekt'. De pagina toont nu een overzicht van de creditnota's waarvoor de verplichting nog niet geboekt is.
2. Open één van de creditnota's. Klik op **Factuur tonen** om de factuur te openen in DMS. 
3. Controleer de volgende velden en pas waar nodig de gegevens aan:
	- **Leverancier**
	- **Boekingsdatum**: **Let op!** Wanneer u de boekingsdatum aanpast wordt ook de documentdatum aangepast. De documentdatum dient u weer terug te zetten naar de op de factuur vermelde datum. 
	- **Documentdatum**
	- **Factuurnr. leverancier**
	- **Omschrijving**: Dit is niet de omschrijving die meekomt op de grootboekposten. Deze omschrijving wordt opgegeven in de factuurregels. 
	- **Factuurbedrag**
	- **Verl. BTW-productboekingsgroep**: De betalingsverplichting van de factuur wordt geboekt o.b.v. de gegevens op de creditnotakop. Wanneer verlegde BTW van toepassing is wordt bij het boeken van de verplichting al af te dragen BTW geboekt. In dit veld geeft u aan met welke BTW-productboekingsgroep de verlegde BTW o.b.v. de factuurkop geboekt dient te worden. Het BTW-bedrag dat geboekt wordt is het bedrag uit het veld **Factuur BTW-bedrag**. Indien zowel hoog als laag tarief BTW van toepassing is op de factuur selecteert u hier de BTW-productboekingsgroep voor hoog tarief. Nadat de BTW per factuurregel gespecificeerd is en de factuur definitief geboekt is, wordt de BTW-post o.b.v de verplichting tegengeboekt en worden nieuwe BTW-posten aangemaakt o.b.v. de factuurregels. 
	- **Factuur BTW-bedrag**: Wanneer het veld **Verl. BTW-productboekingsgroep** gevuld is wordt dit bedrag aan verlegde BTW geboekt wanneer u de verplichting boekt. 
	- **Bedrag naar G-rekening**
4. Nadat u bovenstaande gegevens gecontroleerd en aangevuld heeft boekt u de verplichting door op **Boeken verplichting** te klikken. De **Boekstatus** van de creditnota wijzigt naar 'Verplichting geboekt'.
5. Nadat de verplichting geboekt is dienen de factuurregels aangemaakt te worden:
	- Als er een **minderwerk ordernummer** vermeld staat op de factuur, ga dan verder bij **[Ophalen orderregels](#ophalen-orderregels)**.
	- Ligt er aan de creditnota een debit factuur ten grondslag gaan dan verder met **[Kopiëren inkoopfactuur](#kopiëren-inkoopfactuur)**.
	- Wanneer er geen debitfactuur ten grondslag ligt aan de creditnota, ga dan verder met processtap **[Coderen inkoopcreditnotaregel(s)](#coderen-inkoopcreditnotaregel(s))**.

## Ophalen orderregels

Voor inkoopcreditnota's waarvoor een minderwerkorder verstrekt is dienen de orderregels opgehaald te worden. 

1. Klik op de pagina **Inkoopcreditnota** op **Orderregels ophalen**. De gelijknamige pagina opent. 
2. Zoek het ordernummer op dat op de factuur vermeld staat. 
>Wanneer het ordernummer dat vermeld staat op de creditnota niet op te halen is, kan dit betekenen dat het minderwerk nog niet gereed gemeld is. Ga verder bij de stap **[Toewijzen inkoopcreditnota](#toewijzen-inkoopcreditnota)** om de factuur toe te wijzen aan de persoon die actie dient te ondernemen.  
4.  Selecteer de orderregel(s) met de juiste ordernummer(s) en klik op **OK**. De inkoopcreditnotaregels worden aangemaakt op basis van de orderregels. Ga verder naar processtap **[Controleren factuurregels](#controleren-factuurregels)**.

## Kopiëren inkoopfactuur

Wanneer er een debitfactuur ten grondslag ligt aan de creditnota kan deze gebruikt worden als basis voor de creditnota. Vooral bij het crediteren van facturen die een integratie hebben met een sub-administratie - bijvoorbeeld facturen voor niet-planmatig onderhoud - is het van belang om de originele factuur te kopiëren. De creditering van de kosten wordt op deze manier namelijk ook in de sub-administratie(s) verwerkt. 

1. Klik op **Document kopiëren**. Selecteer in het veld **Documenttype** 'Factuur'. 
2. Selecteer in het veld **Documentnr.** het document dat u wilt kopiëren. 
3. Klik op **OK**. 
4. U kunt nu verder gaan naar de stap **[Controleren creditnotaregel(s)](#controleren-creditnotaregel(s))**.

## Controleren creditnotaregel(s)

Wanneer creditnotaregels aangemaakt zijn op basis van minderwerk orderregels of op basis van een gekopieerd document dienen de regels gecontroleerd te worden. 

1. Controleer de volgende gegevens in de factuurregels en pas aan wanneer nodig:
	- **Omschrijving**: Dit is de omschrijving die meegegeven wordt aan de grootboekposten. 
	- **Btw-productboekingsgroep**: Dit is de BTW-productboekingsgroep die van toepassing is. 
	- **Directe kostprijs Excl. btw**: Regelprijs zonder BTW.
	- **Dimensie waarden velden**: Velden die eindigen met de het woord 'code' zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld zijn. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  
4. Wanneer alle velden gecontroleerd zijn en er zijn geen aanpassingen nodig, ga dan verder bij de processtap **[Aanmaken goedkeuringsverzoek](#aanmaken-goedkeuringsverzoek)**.

## Coderen inkoopcreditnotaregel(s)

Wanneer er geen minderwerkorder beschikbaar is voor de creditnota en er ligt geen debitfactuur ten grondslag aan de creditnota, dan dienen de factuurregels handmatig aangemaakt en ingevuld te worden. Wanneer er vragen zijn over de te selecteren waarden, bijvoorbeeld op welke grootboekrekening de creditnota geboekt dient te worden of welke afdelingsdimensie geselecteerd dient te worden, verzamel dan eerst deze informatie door de creditnota toe te wijzen aan de persoon die de informatie kan verschaffen, via **[Toewijzen inkoopcreditnota](#toewijzen-inkoopcreditnota)**. 

> Wanneer u meerdere regels aan wilt maken kunt u de regels ook bewerken in Excel. 
> 1. Selecteer 1 of meer regels. Kopieer de regels met Ctrl+C en plak de regels in een Excel-bestand.
> 2. Voer onderstaande stappen uit voor alle regels.
> 3. Selecteer de regels in het Excel-bestand (zonder de kopregel). Selecteer een lege regel in de creditnota en plak de regels met Ctrl+V terug in de creditnota.

1. Wanneer alle benodigde informatie beschikbaar is kan de creditnotaregel gevuld worden. Vul de volgende velden:
	- **Soort**: Selecteer in geval van Service- en Verbruiksnota's 'Kostencode'. In geval van reguliere kosten kiest u **Grootboekrekening**.
	- **Nr.**: Selecteer het grootboekrekeningnummer of de kostencode (in geval van service- en verbruiksfacturen). 
	- **Omschrijving**: Dit is de omschrijving die meegegeven wordt aan de grootboekposten. 
	- **Btw-productboekingsgroep** 
	- **Clusternummer**: Vullen wanneer van toepassing; als 'Kostencode' geselecteerd is in het veld **Soort** is dit veld verplicht. 
	- **Eenheidsnummer**: Vullen wanneer van toepassing.
	- **S&V afrekenbatch**: Selecteer de afrekenbatch waar de service- en verbruikskosten op van toepassing zijn (alleen invullen bij service- en verbruiksfacturen).
	- **Directe kostprijs Excl. btw**: Regelprijs zonder BTW.
	- **Dimensie waarden velden**: Velden die eindigen met het woord 'code' zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen. 
2. Wanneer de gegevens in de creditnotaregel gevuld zijn kan deze goedgekeurd worden: **[Aanmaken goedkeuringsverzoek](#aanmaken-goedkeuringsverzoek)**.

## Toewijzen inkoopcreditnota

Wanneer er vragen zijn over een creditnota, of er zijn vragen m.b.t. (de status van) de order die ten grondslag ligt aan de creditnota, of iemand dient een actie uit te voeren, dan kan er op de creditnota  een notitie toegevoegd worden met de vraag of het verzoek tot actie. Vervolgens kan de creditnota toegewezen worden aan de gebruiker die de vraag dient te beantwoorden of de actie dient uit te voeren. 

1. Klik op de pagina **Inkoopcreditnota** aan de rechter kant van het scherm op **Bijlagen**. 
2. Klik om een vraag of verzoek toe te voegen op het +-teken naast **Notities**. Het scherm **Een opmerking toevoegen** opent. Vul in dit scherm de notitie en klik op **OK** om de notitie toe te voegen. 
3. Vul op de pagina **Inkoopcreditnota** in het veld **Toegewezen gebruikers-ID** de gebruiker aan wie u de factuur toe wilt wijzen. De factuur wordt nu toegevoegd aan het bakje 'toegewezen facturen' van de desbetreffende gebruiker. 

## Behandelen toegewezen inkoopcreditnota

Wanneer een inkoopcreditnota aan u toegewezen is betekent dit dat er een vraag of verzoek tot actie is die betrekking heeft op deze creditnota. 

1. Navigeer naar u Rolcenter (startpagina van Dynamics Empire). Klik op de tegel **Toegewezen inkoopcreditnota's**.  De pagina toont de inkoopcreditnota's die aan u toegewezen zijn en waarop u actie dient te ondernemen. 
2. U opent de factuur door op het factuurnummer te klikken.  
3. Klik op de pagina **Inkoopcreditnota** aan de rechter kant van het scherm op **Bijlagen**.  De notitie(s) wordt (worden) getoond. Hier vindt u de vraag of het verzoek. 
4. Wanneer u wordt gevraagd iets te doen, bijvoorbeeld het gereedmelden van een order, voer dan eerst deze actie(s) uit. 
5. Heeft u de actie uitgevoerd of wilt u een vraag beantwoorden, klik op het +-teken naast **Notities**. Het scherm **Een opmerking toevoegen** opent. Vul in dit scherm de notitie en klik op **OK** om de notitie toe te voegen. 
6. Maak op de pagina **Inkoopcreditnota** het veld **Toegewezen gebruikers-ID** leeg. Hiermee wordt de factuur weer toegewezen aan de afdeling die de inkoopfacturen verwerkt. Heeft u een vervolgvraag aan een specifiek iemand of dient iemand anders een actie uit te voeren, vul dan in het veld **Toegewezen gebruikers-ID** de desbetreffende gebruiker. De inkoopcreditnota wordt nu toegevoegd aan het bakje 'toegewezen facturen' van de desbetreffende gebruiker. 

## Aanmaken goedkeuringsverzoek

Wanneer de creditnotaregels zijn aangemaakt kan het document worden goedgekeurd. 

1. Klik op **Goedkeuringsaanvraag verzenden**. Er een goedkeuringspost toegewezen aan een gebruiker. 

## Boeken inkoopcreditnota's

Wanneer het document door alle personen die het document goed moeten keuren, goedgekeurd is, kan de creditnota geboekt worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Inkoopcreditnota's**. Stel een filter in op het veld **Status** = 'Vrijgegeven'. De pagina toont nu een overzicht van de facturen die vrijgegeven zijn en geboekt kunnen worden. 
2. Klik op **Batchboeken (verplichting)**. 
3. Zet het veld **Boekstatus** op 'Verplichting geboekt' en zet het veld **Status** op 'Vrijgegeven'.
4. Klik op **OK**. Alle creditnota's waarvoor dit mogelijk is worden definitief geboekt. 
5. Creditnota's waarbij de boekingsdatum in afgesloten periode valt worden niet geboekt. Om deze facturen toch in batch te kunnen boeken kan bij stap 3  in het veld **Boekingsdatum** de aangepaste boekingsdatum ingevuld worden. Alle facturen binnen het filter worden dan met deze nieuwe boekingsdatum geboekt. 

## Goedkeuren inkoopfactuur

Nadat de inkoopcreditnota verwerkt is kan ook de oorspronkelijke debitfactuur goedgekeurd en geboekt worden, via **[Goedkeuren documenten](../inkopen/inkoop/goedkeuren-documenten/)**.

## Zie ook

[Ontvangen inkoopfacturen](../ontvangen-inkoopfacturen/)  
[Verwerken inkoopfacturen](../verwerken-inkoopfacturen/)  
[Beheren rekening-courant-crediteuren](../beheren-rekening-courant-crediteuren/)  
[Verwerken terugkoopfactuur onroerend goed](../verwerken-terugkoopfactuur-onroerend-goed/)
