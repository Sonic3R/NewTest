# Aanmaken contractonderhoudsproject

In dit werkproces worden één of meerdere contractonderhoudsprojecten per onderhoudscontract aangemaakt en aan het onderhoudscontract gekoppeld. Door middel van contractonderhoudsprojecten worden de verplichtingen en de voortgang van het onderhoud voor het lopend boekjaar bewaakt.

## Aanmaken contractclusters (optioneel)

Budgetten van contractonderhoudsprojecten worden in Dynamics Empire vastgelegd op basis van clusters en de binnen deze clusters aanwezige eenheden. Omdat contractonderhoud regelmatig betrekking heeft op meerdere technische clusters, neemt het aantal budgetregels binnen contractonderhoudsprojecten al snel toe op het moment dat ook het aantal clusters binnen het specifieke contractonderhoud toeneemt. Contractclusters beperken deze administratieve workload doordat voor een contractonderhoudsproject binnen één contractcluster alle eenheden gekoppeld worden die administratief verbonden zijn met het specifieke contractonderhoud.

 1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusters**.
 2. Klik op **Nieuw | + Nieuw**, waarna Dynamics Empire een lege **Clusterkaart** opent.
 3. Klik in het veld **Naam** op tabblad **Algemeen** en Dynamics Empire opent het venster genaamd **Clustersoorten**.
 4. Kies een bestaande clustersoort en klik op **OK**, of maak een nieuw contractclustersoort aan door op **+Nieuw** te klikken. In het laatstgenoemde geval doet u het volgende:
	- Geef een **Code** en **Omschrijving** op.
	- Geef t.b.v. het automatisch nummeren de gewenste **Clusternummerreeks** in.
	- Activeer het veld **Financieel cluster** en sluit het venster **Clustersoorten** door op **OK** te klikken.
 5. Terug op de clusterkaart navigeert u naar de actie/functie **Eenheden toevoegen** en selecteert u de eenheden die binnen het betreffende contractcluster vallen. 
 6. Na de selectie en het toevoegen van eenheden krijgt u de melding "U heeft een wijziging aangebracht (...) Mogelijk moet u ook de clusterverdeelsleutel voor dit cluster actualiseren." Klik op **OK** om de melding te sluiten.
 7. Navigeer nu vanaf de clusterkaart naar het menu-item **Clusterverdeelsleutels**.
 8. Klik op het **Clusterverdeelsleuteloverzicht** op **+Nieuw** om een nieuwe clusterverdeelsleutel aan te maken voor alle gekoppelde eenheden aan het betreffende contractcluster. Kies op de nieuwe kaart op tabblad **Algemeen** in het keuzeveld **Verdeelsleuteltype** voor de waarde **Gewogen**.
 9. Stel vervolgens bij **Ingangsdatum** de datum in waarop de nieuwe gewogen clusterverdeelsleutel geactiveerd moet worden door het systeem.
 10. Kies voor de actie **Clusterverdeelsleutels exporteren**. Stel vervolgens de begindatum (= systeemdatum + 1 dag) en klik op **Afdrukken**, waarna Dynamics Empire een MS Excel-exportbestand genereert. Pas dit bestand aan met de gewenste waarden en sla dit op.
 11. Sluit de clusterverdeelsleutelkaart af. U komt terug op het overzicht met clusterverdeelsleutels.
 12. Kies voor **Clusterverdeelsleutels importeren**. In het venster selecteert u de bestandsnaam en kiest u voor de knop **Afdrukken**. Dynamics Empire geeft melding van de wijzigingen.
 13. Selecteer tot slot **Verdeelsleutel activeren**. De status van de verdeelsleutel staat nu op 'Geactiveerd'.
 14. Het contractcluster is nu volledig ingericht. Sluit het clusterverdeelsleuteloverzicht.  

## Aanmaken project 

### Handmatig aanmaken van individueel project

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projecten**.
2. Kies op het **Projectoverzicht** voor **+ Nieuw** en kies in het overzicht met projecttypen voor **Contractonderhoud**. Klik op **OK**.
3. Druk op de nieuwe projectkaart die is verschenen op TAB, waarna automatisch het veld **Nr.** op tabblad **Algemeen** van een waarde wordt voorzien.
4. Geef een waarde in bij velden **Naam**, **Omschrijving**, **Startdatum** en **Opleverdatum**.
5. Op het tabblad **Contactpersonen** kunt u vervolgens contactpersonen koppelen aan het project door op een blanco regel in de keuzelijst van de kolom **Contactnr.** de juiste contactpersoon te kiezen. Door vervolgens ook in de keuzelijst van de kolom **Functiecode** een functie te koppelen aan de gekoppelde contactpersoon en in de kolom **Prioriteit** een nummer 1, 2 of 3 te kiezen, zijn 3 gekoppelde contactpersonen met hun functie zichtbaar te maken op het tabblad **Algemeen**.
6. Controleer op tabblad **Boekingsinfo** of de juiste budgethouders als **Orderbudgethouders**, **Factuurbudgethouders** en **Verkoopbudgethouders** op het project staan ingesteld. Deze personen geven binnen dit werkproces vanuit hun procuratie goedkeuring op orders en facturen.
7. Sluit de projectkaart en het projectoverzicht.

### In bulk aanmaken van meerdere projecten inclusief budgetregels door import vanuit Excel-bestand

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Kladblokimportoverzicht**. Hierin zijn alle in het verleden geïmporteerde begrotingen te zien.
2. Klik op **+ Nieuw** in het lint. Dynamics Empire maakt een zogenaamde **Kladblokbudgetimportkaart** aan met een volgnummer. Een kladblokbudgetimportkaart is een scherm waarin begrotingsregels kunnen worden geïmporteerd en verwerkt tot projecten.
3. Kies voor de actie/functie **Budget importeren** om een bestand met begrotingsregels te importeren. Dynamics Empire opent een venster, genaamd **Import budget planmatig onderhoud**. Vul de volgende velden:
* **Importsjablooncode** 
* **Omschrijving**: Deze is aan te passen naar een omschrijving voor het geïmporteerde bestand (bijvoorbeeld begroting CO jjjj). 
* **Bestandsnaam**: Selecteer met behulp van de knop assistedit (…) het te importeren bestand. 
* **Projecttype**: Dit betreft het projecttype van de begrotingsregels die u wilt importeren (in dit geval: CO). 
* **Begrotingsjaar**: Dit betreft een boekjaar van de begrotingsregels. 
4. Klik op **Import**. Wanneer de import slaagt, krijgt u hiervan een melding. Het resultaat is vervolgens te zien op de bovenste twee onderdelen van de Kladblokbudgetimportkaart. Sluit de kaart.
6. Terug op het kladblokimportoverzicht ziet u nu een nieuw record waarin handmatige begrotingsregels zijn geïmporteerd. Wanneer u een foutief bestand heeft geïmporteerd, selecteer dan de betreffende regel en klik op **Verwijderen**. De kladblokbudgetimportkaart wordt dan in zijn geheel verwijderd. 
7. Voor het verder verwerken van de begrotingsregels selecteert u het nieuwe record en kiest u voor **Bewerken**, waarmee de kladblokbudgetimportkaart in een bewerkbare vorm wordt geopend.
8. Selecteer vervolgens de begrotingsregels op tabblad **Kladblokimportregels**, kies in het menu van dit tabblad voor **Kopiëren** onder **Beheren**, om deze selectie regels naar het tabblad **Voorlopige projectregels** te kopiëren.
> **Tip!** Controleer voor het aanmaken van onderhoudsprojecten of alle regels op tabblad **Kladblokimportregels** zijn verwerkt. Dit is het geval als het clusternummer groen kleurt. Met de optie **Gekopieerde regels verbergen** worden de nog te verwerken regels op het tabblad naar voren gefilterd. Herhaal voorgaande stappen voor deze regels tot alle regels zijn verwerkt tot voorlopige projectregels.

### Als u zelf de geïmporteerde regels mag doorzetten doet u het volgende:

1. Zet het veld **Definitieve versie** op tabblad **Algemeen** op 'AAN'.
2. Kies voor de actie/functie **Aanmaken onderhoudsprojecten**.
3. Na het voltooien van deze actie geeft Dynamics Empire aan dat er een X aantal projecten is aangemaakt. Klik op **OK** om de melding te sluiten. Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de kladblokbudgetimportkaart. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd.

### Als u niet zelf de geïmporteerde regels mag doorzetten doet u het volgende:

1. Maak een nieuwe taak aan voor de persoon die de voorlopige projecten dient goed te keuren. Ga hiervoor via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Gebruikerstaken**.
2.  Klik op **+ Nieuw** en vul de verschillende velden in, waaronder in ieder geval **Onderwerp**, **Toegewezen aan gebruiker**, **Taak koppelen aan** en **Rapport**.
3. Specificeer in het veld **Taakbeschrijving** wat er van de persoon wordt verwacht (bijvoorbeeld "Ik ben klaar met de voorbereiding, graag controleren en projecten aanmaken.") en licht zonodig de exacte locatie in Dynamics Empire toe. De betreffende gebruiker krijgt hiervan een notificatie op zijn startpagina in het mapje  **Mijn gebruikerstaken**. 
4. De controle, zoals benoemd in de vorige stap, houdt in dat wordt gecheckt of het totaalbedrag in dit scherm overeenkomst met het bedrag dat door de bestuurder is goedgekeurd voor contractonderhoud (velden **Regelbedrag excl. BTW** en **Regelbedrag incl. BTW**). Voer indien gewenst een detailcontrole uit.
5. Kies nu voor de functie **Aanmaken onderhoudsprojecten**. 
6. Na het voltooien van deze actie geeft Dynamics Empire aan dat er een X aantal projecten is aangemaakt. Klik op **OK** om de melding te sluiten. Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de **Kladblokbudgetimportkaart**. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd. 
7. Maak een taak aan, gericht aan uw collega die de Projectvoorbereiding heeft uitgevoerd, en geef de stand van zaken door (bijvoorbeeld "Er zijn 5 onderhoudsprojecten aangemaakt."). Sluit de Kladblokbudgetimportkaart.
8. Het verbeteren van projectnaam en -omschrijving is een actie die de projectleider moet uitvoeren, direct na het aanmaken van onderhoudsprojecten.
9.  Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst  **Projectoverzicht**.
10.  Open een projectkaart door de juiste regel te selecteren en op **Bewerken** te klikken.
11.  Op de **Projectkaart** is op tabblad **Algemeen** een **Naam** en **Omschrijving** te zien. Deze worden door het systeem bepaald op basis van de bovenste voorlopige projectregel op de kladblokbudgetimportkaart en dekken mogelijk niet de lading voor alle regels die aan het project zijn gekoppeld. Deze regels zijn terug te zien op tabblad **Budgetregels**. Doorloop alle projecten en pas waar nodig de **Naam** en **Omschrijving** aan. U kunt hiervoor gebruik maken van de pijlknoppen links en rechts in het scherm, aan weerszijden van de projectkaart.
 
## Opvoeren van budgetregels handmatig

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projecten**.
2. Selecteer de regel van het handmatig ingevoerde project waarop u nu ook budgetregels wil vastleggen en klik op **Bewerken**. De projectkaart wordt nu geopend.
3. Selecteer een blanco regel op tabblad **Budgetregels** en leg de keuze vast vanuit de keuzelijst onder de kolom **Clusternr.**. Veelal is dit het contractcluster waarop de projectadministratie wordt gevoerd.
4. Leg op dezelfde budgetregel nu ook de keuze vast vanuit de keuzelijst onder kolom **Werksoort**. Met de keuze voor een werksoortcode vult Dynamics Empire automatisch de bijhorende **Werksoort** en **Werksoortboekingsgroep** in.
5. Vul vervolgens de verwachte **Startdatum** en **Opleverdatum** in op de betreffende budgetregel.
6. Voer tot slot in de kolom **Begroot** het begrotingsbedrag van de budgetregel in. Dynamics Empire vraagt u vervolgens een reden op te geven voor het ingevoerde bedrag.

## Koppelen contract met project

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projecten**.
2. Selecteer de regel van het project waarop u het contract wil koppelen en klik op **Bewerken**. De projectkaart wordt nu geopend.
3. Ga nu naar het tabblad **Boekingsinfo** en kies in de keuzelijst bij het invoerveld **Contractnr.** het contractnummer dat aan het project gekoppeld dient te worden.

## Zie ook

[Actualiseren prognose](../actualiseren-prognose/)  
[Registreren (onderhouds) jaarbegroting](../registreren-(onderhouds)-jaarbegroting/)  
[Voorbereiden onderhoudsproject](../voorbereiden-onderhoudsproject/)  
[Bewaken project](../bewaken-project/)  
[Uitvoeren contractonderhoud](../uitvoeren-contractonderhoud/)  
