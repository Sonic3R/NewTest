# Uitvoeren tussentijdse huuraanpassing

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=2e6&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

Dit werkproces betreft het doorvoeren van tussentijdse huuraanpassingen. Tussentijdse huuraanpassingen zijn alle aanpassingen van de huurprijs van verhuurde en leegstaande OG Eenheden die gedurende het jaar worden doorgevoerd naast de jaarlijkse huurverhoging. 

Voorbeelden van tussentijdse huuraanpassingen zijn: 
 - toevoegen van nieuwe service-elementen of aanpassen van het bedrag van bestaande service-elementen; 
 - doorvoeren van huurverhoging in verband met woningverbetering; 
 - toekennen of laten vervallen van huurkorting; 
 - aanpassen voorschotten voor service en verbruik. 

In de praktijk kan het initiatief voor het doorvoeren van tussentijdse huuraanpassingen komen van de corporatie (b.v. aanpassen voorschotten of doorvoeren huurverhoging in verband met renovatie of planmatig onderhoud) of van de huurder (bijvoorbeeld afnemen extra service, aanvragen woningverbetering in verband met WMO, aanvragen van individuele verhoging van eigen voorschot). In deze werkinstructie wordt daartussen geen onderscheid gemaakt. 

In de werkinstructie wordt wel onderscheid gemaakt tussen: 
 1. uitvoeren tussentijdse huuraanpassing van een individuele OG Eenheid (individuele huuraanpassing) 
	 a. standaard aanpassing van service-elementen 
	 b. uitzonderlijke aanpassingen 
 2. uitvoeren tussentijdse huuraanpassing van meerdere OG Eenheden tegelijk (collectieve huuraanpassing) 
	 a. doorvoeren aanpassing voorschotten 
	 b. doorvoeren overige collectieve huuraanpassingen 

## Aanmaken en doorvoeren standaard individuele huuraanpassing 

Deze stap betreft het toevoegen of aanpassen van service elementen aan het huurcontract. Deze variant is bijvoorbeeld van toepassing wanneer een klant een serviceabonnement wil afsluiten of opzeggen of het voorschot voor service en verbruik wil verhogen.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Toekomstige huurmutaties**. Een pagina wordt geopend waarop u één of meer huuraanpassingen kunt specificeren: één regel voor elke aanpassing. Vul voor elke regel de volgende kolommen in:  
	- **Klantnr.**: Nummer van de klant voor wie de huuraanpassing is bestemd.
	- **Eenheidnr.**: Nummer van de eenheid waar de huuraanpassing betrekking op heeft. 
	- **Ingangsdatum**: Datum per wanneer de huuraanpassing moet ingaan. 
	- **Omschrijving**: Korte omschrijving van de huuraanpassing. 
	- **Reden huurmutatie** Selecteer de juiste huurmutatiereden. 
	- **Elementnr.** Nummer van het element waarop de huuraanpassing betrekking heeft. Dit kan een bestaand element zijn dat al aanwezig is in het contract van de klant, of een nieuwe element dat moet worden toegevoegd aan het contract van de klant. 
	- **Mutatiebedrag**: Het bedrag van de huuraanpassing, of:  
	- **Mutatiepercentage**: Het percentage van de huuraanpassing. In het geval van een nieuw element moet **Mutatiebedrag** worden gevuld. 
	- **Element verwijderen**: Vink dit veld aan als het service-element moet komen te vervallen binnen het contract van de klant. 
2. Selecteer alle regels en klik op de optie **Controle**. Het systeem controleert nu of de geselecteerde regels voldoen een de voorwaarden om te kunnen worden verwerkt. 
	- Als een regel voldoet aan de voorwaarde, dan wordt de **Status** van de regel aangepast in 'Compleet'. 
	- Als een regel niet voldoet aan de voorwaarden, dan wordt de **Status** van de regel aangepast in 'Niet verwerkbaar' en toont het systeem een **foutmelding**. 
3. Los eventuele fouten op en herhaal de voorgaande stap. 
4. Selecteer alle regels en kies voor **Verwerken**. Het systeem verwerkt alle huuraanpassingen die zijn gespecificeerd op de geselecteerde regels. Daarbij maakt het systeem een nieuwe contractregel aan met als ingangsdatum de ingangsdatum van de huuraanpassing. 

## Aanmaken en doorvoeren uitzonderlijke individuele huuraanpassing 

Deze stap betreft het aanpassen van elk element van het huurcontract. Hieronder valt ook het verhogen of verlagen van de nettohuur. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden** en selecteer de OG Eenheid waarvoor de huuraanpassing moet worden doorgevoerd door op het eenheidnummer te klikken.
2. Navigeer naar de **Verhuurcontracten**. Een pagina genaamd **Contractoverzicht** wordt geopend, waarop alle bestaande contractregels van de geselecteerde OG Eenheid worden getoond. 
3. Klik op de knop **+Nieuw**. Een nieuwe regel wordt getoond bovenaan het overzicht. 
4. Voer in kolom **Ingangsdatum** de datum in per wanneer de huuraanpassing moet ingaan. Het systeem maakt een nieuwe contractregel aan d.m.v. het kopiëren van de voorgaande contractregel en bijbehorende elementen.  
5. Navigeer naar de **Elementen**. Het systeem toont een overzichtspagina met de elementen van de nieuwe contractregel (gekopieerd van de voorgaande contractregel). 
6. Als u het bedrag van een bestaande element wilt aanpassen, selecteer dan het element en pas de waarde van kolom **Eenheidsprijs** aan. 
7. Als u een nieuw element wilt toevoegen aan het contract van de OG Eenheid, klik dan op de lege regel onderaan het overzicht, klik op de drie puntjes in kolom **Nr.**, selecteer het juiste element in het overzicht met alle standaard elementen en voer een waarde in kolom **Eenheidsprijs** in. 
8. Als u een bestaand element wilt verwijderen uit het contract van de OG Eenheid, selecteer dan de betreffende regel, klik op de drie puntjes in de tweede kolom en klik op de optie **Regel verwijderen**. 
9. Sluit de overzichtspagina met de elementen van de nieuwe contractregel. 
10. Sluit de overzichtspagina genaamd **Contractoverzicht**. 

## Informeren klant 

In deze stap informeert u de klant over de doorgevoerde tussentijdse huuraanpassing, 

## Doorvoeren aanpassing voorschotten

In deze stap voert u de aanpassingen door van de voorschotten voor service en verbruikskosten. In het proces van Service en Verbruik zijn deze aanpassingen al exact bepaald en vastgelegd in de vorm van een importbestand. Dit importbestand bevat één regel voor elk element van elke contractregel waarvan het bedrag moet worden aangepast, waarbij elke regel de volgende gegevens bevat (gescheiden door punt-komma's): 
- Eenheidsnr. 
- Klantnr. 
- Contractvolgnr. 
- Elementnr. 
- Verhogingsoort (0=Niet, 1=Percentage, 2=Bedrag, 3=Vervalt, 4=Toevoegen, 5=Was/Wordt) 
- Verhoging 
- Elementbedrag was (moet waarde '0' bevatten als Verhogingsoort <> 5) 
- Elementbedrag wordt (moet waarde '0' bevatten als Verhogingsoort <> 5) 

Nu moeten deze aanpassingen nog worden doorgevoerd in de desbetreffende contractregels. Dit doet u door het importeren en verwerken van het importbestand. Verwerking van het importbestand gaat op basis van een huurverhogingsbatch. Na verwerking van het importbestand zijn de aanpassingen vastgelegd in de bestaande contractregels, en wel in de vorm van een verhoging en verhogingssoort. Hierbij wordt ervan uitgegaan dat de huuraanpassing m.b.t. aanpassing van voorschotten tegelijkertijd met de jaarlijkse huurverhoging worden doorgevoerd. De stappen voor het aanmaken van de nieuwe contractregels d.m.v. het verwerken van de huurverhoging en het informeren van de klant vinden om die reden plaats binnen het proces van de jaarlijkse huurverhoging. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Huurverhoging-import**. 
2. Selecteer het importbestand dat is aangemaakt binnen het proces van Service en Verbruik. 
3. Klik op **OK**. Het importbestand wordt geïmporteerd en de gegevens worden weggeschreven in een tussentabel. 
4. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Huurverhoging-import**. Een pagina wordt geopend met een overzicht van alle geïmporteerde regels. De kolom **Verwerkt** geeft aan welke regels al wel zijn verwerkt en welke nog niet. Controleer of alle regels uit het importbestand zijn geïmporteerd. 
5. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Verwerken huurverhoging-import**. Een pagina met opties wordt geopend. 
6. Klik op de drie puntjes binnen de optie **Batchnaam**. De pagina genaamd **Huurverhogingsbatch** wordt geopend. 
7. Open het veld **Batch** en klik op **+Nieuw**. 
8. Voer de **Code** en **Omschrijving** van de nieuwe batch in en klik op **OK**. U keert terug in pagina **Huurverhoginsgbatch**.
9. Laat de lijst met elementen leeg en klik op **OK**. U keert terug naar de pagina met opties van taak **Verwerken huurverhoging-import**. 
10. Voer de **Huurverhogingsdatum** in. 
11. Klik op **OK**. De geïmporteerde regels worden verwerkt, waarbij de aanpassing van elke regel wordt vastgelegd in de kolommen **Verhogingssoort** en **Verhoging** van het desbetreffende element van de desbetreffende bestaande contractregel. 
12. Controleer of alle aanpassingen die waren gespecificeerd op de regels van het importbestand, correct zijn verwerkt. Zoek en selecteer de lijst **Huurverhoging-import** en filter op de kolom **Verwerkt** = 'Nee'. Bij de niet-verwerkte regels staat de reden vermeld waardoor de regel niet is verwerkt.

## Specificeren collectieve huuraanpassing 

In deze stap specificeert u de inhoud van de collectieve huuraanpassing in termen van wijzigingen van elementen. In de volgende stap voert u deze aanpassing door op een selectie van OG Eenheden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Tussentijdse huuraanpassingen**. Een pagina met opties en filtermogelijkheden wordt geopend. 
2. Klik op de drie puntjes in veld **Batchnaam**. Een pagina genaamd **Huurverhogingsbatch** wordt geopend. 
3. Open het veld **Batch** en klik op **+Nieuw**. 
4. Voer de **Code** en **Omschrijving** van de nieuwe batch in en klik op **OK**. U keert terug op pagina **Huurverhogingsbatch**. 
5. Specificeer de huuraanpassing in termen van elementen: elke aanpassing van een element op een aparte regel. Doe dit per element door een nieuwe regel aan te maken en de volgende kolommen in te vullen:
	- **Elementnr.**: Het nummer van het element dat u wilt toevoegen, wijzigen of verwijderen. 
	- **Verhogingsoort**: Het soort aanpassing dat u wilt doorvoeren. Als u een element wilt toevoegen aan de contracten van de OG Eenheden, kies dan voor 'Toevoegen'. Als u een element wilt verwijderen van de contracten van de OG Eenheden, kies dan voor 'Vervalt'. Als u het bedrag van een element wilt aanpassen, kies dan voor 'Bedrag' of '%' of 'Was/wordt'. 
	- **Verhoging**: Als u in de vorige kolom hebt gekozen voor 'Bedrag' of '%', voer dan de concrete waarde (bedrag resp. percentage) in waarmee u het bedrag van het element wilt verhogen. Voer een negatief getal in als u het bedrag wilt verlagen. 
	- Als u in kolom **Verhogingsoort** hebt ingevuld 'Was/wordt', vul dan concrete waarden in kolommen **Elementbedrag was** en **Elementbedrag wordt** in. 
	- Als u in kolom **Verhogingssoort** hebt ingevuld 'Toevoegen', vul dan een concrete waarde in kolom **Elementbedrag wordt** in. 
6. Klik op **OK**. U keert terug naar de pagina met opties van taak **Tussentijdse huurprijsaanpassingen**. 

## Doorvoeren collectieve huuraanpassing

In de volgende stap voert u deze huuraanpassing door met ingang van een opgegeven datum op een selectie van OG Eenheden. Daarmee maakt het systeem direct nieuwe contractregels aan voor de desbetreffende OG Eenheden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Tussentijdse huuraanpassingen**. Een pagina met opties en filtermogelijkheden wordt geopend. 
2. Selecteer in optie **Batchnaam** de batch die in de voorgaande stap is aangemaakt. 
3. Voer in optie **Huuraanpassingsdatum** de datum in waarop de tussentijdse huuraanpassingen moeten ingaan. 
4. Selecteer in optie **Huuraanpassingsreden** de reden waarom de huuraanpassing wordt doorgevoerd. 
5. Selecteer de OG Eenheden waarop de tussentijdse huuraanpassing moet worden doorgevoerd. Doe dit door een filtering te specificeren in termen van **Clusternr.** en/of **Eenheidnr.**. 
6. Klik op **OK**. De tussentijdse huuraanpassingen worden doorgevoerd op de geselecteerde OG Eenheden. Daarbij maakt het systeem voor elke geselecteerde OG Eenheid een nieuwe contractregel aan met als ingangsdatum de datum die u heeft ingevoerd in optie **Huuraanpassingsdatum**. 

## Zie ook

[Afhandelen huurverhogingsbezwaren](../afhandelen-huurverhogingsbezwaren/)  
[Bepalen huurverhogingsbeleid](../bepalen-huurverhogingsbeleid/)  
[Rappelleren klant](../rappelleren-klant/)  
[Uitvoeren jaarlijkse huurverhoging](../uitvoeren-jaarlijkse-huurverhoging/)  
[Voorbereiden jaarlijkse huurverhoging](../voorbereiden-jaarlijkse-huurverhoging/)  
