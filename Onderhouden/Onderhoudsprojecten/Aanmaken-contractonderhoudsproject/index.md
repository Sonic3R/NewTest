# Aanmaken contractonderhoudsproject

In dit werkproces worden één of meerdere contractonderhoudsprojecten per onderhoudscontract aangemaakt en aan het onderhoudscontract gekoppeld. Door middel van contractonderhoudsprojecten worden de verplichtingen en de voortgang van het onderhoud voor het lopend boekjaar bewaakt.

## Aanmaken contractclusters (optioneel)
Budgetten van contractonderhoudsprojecten worden in Dynamics Empire vastgelegd op basis van clusters en de binnen deze clusters aanwezige eenheden. Omdat contractonderhoud regelmatig betrekking heeft op meerdere technische clusters, neemt het aantal budgetregels binnen contractonderhoudsprojecten al snel toe op het moment dat ook het aantal clusters binnen het specifieke contractonderhoud toeneemt. Contractclusters beperken deze administratieve workload doordat voor een contractonderhoudsproject binnen één contractcluster alle eenheden gekoppeld worden die administratief verbonden zijn met het specifieke contractonderhoud.

 1. Ga naar de lijst **Clusters** dit kan via de ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon") ZOEKKNOP rechts
    bovenin.
 2. Klik op **+ Nieuw** in het lint. Dynamics Empire opent een lege **Clusterkaart**
 3. Activeer het invoerveld **Naam** binnen het tabblad **Algemeen** en Dynamics Empire opent het venster genaamd **Clustersoorten**.
 4. Staat het contractclustersoort van uw keuze niet in de getoonde lijst? Vervolg dan bij punt **5**. Wenst u geen nieuwe clustersoort aan te maken selecteer dan de bestaande regel en sluit het venster clustersoorten door op **OK** te klikken en ga vervolgens verder bij punt **6**.
 5. Om een nieuw contractclustersoort aan te maken klikt u in het venster clustersoorten in het lint op **Nieuw** en ga op de nieuwe
    invoerregel als volgt te werk:
	- Geef uw invoer  in op de **Code**-kolom voor de nieuw aan te maken  		       contractclustersoort.
	- Geef uw omschrijving in op de **Omschrijving**-kolom voor de nieuw aan te maken contractclustersoort.
	- Geef t.b.v. het automatisch nummeren de gewenste nummerreeks in  op de **Clusternummerreeks**-kolom voor de nieuw aan te maken  
contractclustersoort.
	- Activeer tot slot het aanvinkveld **Financieel cluster** op de regel voor de nieuw aan te maken contractclustersoort en sluit
					       het    venster clustersoorten door op de knop **OK** te klikken u keert terug op de clusterkaart.
 6. Navigeer nu in het lint naar **Acties** vervolgens **Functies** en voeg vervolgens met de menuoptie **Eenheden toevoegen** de eenheden toe die binnen het betreffende contractcluster vallen. 
 7. Na de selectie en het toevoegen van eenheden krijgt u de melding "U heeft een wijziging aangebracht.....mogelijk moet u ook de clusterverdeelsleutel aanmaken". 
 8.  Ga tot slot in het lint naar **Navigeren** vervolgens **Cluster** daarna **Clusterverdeelsleutels** het overzicht Clusterverdeelsleuteloverzicht wordt geopend.
 9. Druk in het lint van het Clusterverdeelsleuteloverzicht op **Nieuw** om een nieuwe clusterverdeelsleutel aan te maken voor alle gekoppelde eenheden aan het betreffende contractcluster. Kies op de clusterverdeelsleutelkaart die wordt geopend vervolgens op het tabblad **Algemeen** achter het keuzeveld **Verdeelsleuteltype** voor de optie **gewogen**.
 10.  Stel vervolgens op het tabblad **Algemeen** van de betreffende clusterverdeelsleutelkaart achter het keuzeveld **Ingangsdatum** de datum in waarop de nieuwe gewogen clusterverdeelsleutel geactiveerd moet worden door het systeem.
 11. Klik in het lint op **Clusterverdeelsleutels exporteren**. Stel vervolgens de begindatum (=systeemdatum+1 dag). Klik vervolgens op **afdrukken** Dynamics Empire genereerd een MSexcel-exportbestand. Pas dit bestand aan met de gewenste waarden en sla dit op.
 12.   Sluit clusterverdeelsleutelkaart af. U komt terug op het Clusterverdeelsleuteloverzicht. Klik in het lint vervolgens op **Clusterverdeelsleutels importeren**. In het venster selecteert u de bestandsnaam kiest u voor de knop **Afdrukken**. Dynamics Empire geeft melding van de wijzigingen.
 13.  Klik tot slot in het lint op **Verdeelsleutel activeren**. De status van de verdeelsleutel staat nu op geactiveerd.
 14. Het contractcluster is nu volledig ingericht. Sluit het clusterverdeelsleuteloverzicht.  

## Aanmaken project 
### Handmatige aanmaken van individueel project
 1.  Ga naar **Projectoverzicht** dit kan via de![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  ZOEKKNOP rechts
    bovenin.
2. Kies in het lint van het projectoverzicht voor **Nieuw**  en maak in de lijst de overzicht projecttypen de keuze voor **Contractonderhoud**.
3. Vul op het tabblad **Algemeen** van de projectkaart die verschijnt het veld **Naam** en **Omschrijving** en merkt dat het contractonderhoudsproject automatisch een projectnummer heeft gegenereerd.
4. Voer vervolgens ook op het tabblad **Algemeen** de invulvelden in voor de **Startdatum** en **Opleverdatum**.
5. Op het tabblad **Contactpersonen** kan u vervolgens contactpersonen koppelen aan het project door op een blanco regel in de keuzelijst van de kolom **contactnr.** de juiste contactpersoon te kiezen. Door vervolgens ook in de keuzelijst van de kolom **Functiecode** een functie te koppelen aan de gekoppelde contactpersoon en in de kolom **Prioriteit** een nummer 1, 2 of 3 te kiezen, zijn 3 gekoppelde contactpersonen met hun functie zichtbaar te maken op het tabblad Algemeen.
6. Controleer op het tabblad **Boekingsinfo** op de juiste budgethouders als **Orderbudgethouders,  Factuurbudgethouders** en **Verkoopbudgethouders** op het project staan ingesteld. Deze personen geven binnen dit werkproces vanuit hun procuratie goedkeuring op orders en facturen.
7. Sluit de projectkaart en het projectoverzicht.


### Het in bulk aanmaken van meerdere projecten inclusief budgetregels door middel van importeren vanuit een excel bestand
 1.  Ga naar **Kladblokimportoverzicht** dit kan via de![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  ZOEKKNOP rechts bovenin. Hierin zijn alle in het verleden geïmporteerde begrotingen te zien.
 2. Klik op **+ Nieuw** in het lint. Dynamics Empire maakt een zogenaamde **Kladblokbudgetimportkaart** aan met een volgnummer. 
 3. Een Kladblokbudgetimportkaart is een scherm waarin begrotingsregels kunnen worden geïmporteerd en verwerkt tot projecten. Deze kaart bestaat uit vier onderdelen: 
* **Algemeen**: Op dit tabblad vind je algemene gegevens terug, zoals een volgnummer, een omschrijving voor de geïmporteerde begrotingsregels, en pad naar het geïmporteerde bestand, een begrotingsjaar en uiteraard het totaal bedrag excl. En incl. BTW van alle geïmporteerde regels ter controle.
 * **Kladblokimportregels**: Op dit tabblad staan de geïmporteerde begrotingsregels.
 * **Voorlopige projectregels**: Na verwerking/ kopieëren  van de kladblokimportregels vind je op dit tabblad de voorlopige budgetsregels voor de aan te maken projecten.
 * **Functies**: Op dit tabblad kun je functies toekennen aan de contactpersonen (projectteam) van geïmporteerde begrotingsregels.
4. Kies voor de actie/functie **Budget importeren** om een bestand met begrotingsregels te importeren. Dynamics Empire opent een venster genaamd **Import budget planmatig onderhoud**. Vul de velden in dit venster in als volgt:
* **Importsjablooncode**: Dit is de code van het te gebruiken importsjabloon. 
* **Omschrijving**: Hier staat de omschrijving van het importsjabloon; deze is aan te passen naar een omschrijving voor het geïmporteerde bestaand (bijvoorbeeld begroting CO jjjj). 
* **Bestandsnaam**: Selecteer met behulp van de knop assistedit (…) het te importeren bestand. 
* **Projecttype**: Dit betreft het projecttype van de begrotingsregels die u wilt importeren (in dit geval: CO). 
* **Begrotingsjaar**: Dit betreft een boekjaar van de begrotingsregels. 
 7. Klik op **Import**. Wanneer de import slaagt, krijgt u hiervan een melding: 'De import is succesvol verlopen.' Sluit de melding. 
 8. Het resultaat is te zien op de bovenste twee onderdelen van de Kladblokbudgetimportkaart. Sluit de kaart.
 9. Terug op het Kladblokimportoverzicht ziet u nu een nieuw record waarin handmatige begrotingsregels zijn geïmporteerd. Wanneer u een foutief bestand heeft geïmporteerd, selecteer dan de betreffende regel en klik op **Verwijderen**. De Kladblokbudgetimportkaart wordt dan in zijn geheel verwijderd. 
 10. Voor het verder verwerken van de begrotingsregels selecteert u het nieuwe record en kiest u voor **Bewerken**, waarmee de Kladblokbudgetimportkaart in een bewerkbare vorm wordt geopend.
 11. Selecteer vervolgens de begrotingsregels vanuit het tabblad  **Kladblokimportregels** ga in het lint van dit tabblad naar **Beheren** en vervolgens naar **Kopieëren** om deze selectie regels naar het tabblad  **Voorlopige projectregels** te kopieëren.
> **Tip!** Controleer voor het aanmaken van onderhoudsprojecten of alle regels op tabblad  **Kladblokimportregels**  zijn verwerkt. Dit is het geval als het clusternummer groen kleurt. Met de optie **Gekopieerde regels verbergen** worden de nog te verwerken regels op het tabblad naar voren gefilterd. Herhaal stap 11 voor deze regels tot alle regels zijn verwerkt tot voorlopige projectregels.

###Indien u zelf de geïmporteerde regels mag doorzetten doet u de volgende actie:
1. Plaats nu een vinkje in veld  **Definitieve versie**  op tabblad  **Algemeen**.
2. Ga in het lint naar de knop **Acties** vervolgens **Functies** en dan **Aanmaken onderhoudsprojecten**
3. Na het voltooien van deze actie geeft Dynamics Empire aan dat er een X aantal projecten is aangemaakt. Klik op OK om de melding te sluiten. Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de Kladblokbudgetimportkaart. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd.

###Indien u niet zelf de geïmporteerde regels mag doorzetten doet u de volgende actie:
5. Maak nu een nieuwe taak aan voor de persoon de voorlopige projecten dient goed te keuren. Ga hiervoor via het zoekveld  ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  naar  **Gebruikerstaken**.
6.  Klik op  **+ Nieuw**  en vul de verschillende velden in, waaronder in ieder geval  **Onderwerp**,  **Toegewezen aan gebruiker**,  **Taak koppelen aan**  en  **Rapport**.
7. Specificeer in het veld  **Taakbeschrijving**  wat er van de persoon wordt verwacht (bijvoorbeeld "Ik ben klaar met de voorbereiding, graag controleren en projecten aanmaken.") en licht zonodig de exacte locatie in Dynamics Empire toe. 
8. De betreffende gebruiker krijgt hiervan een notificatie op zijn startpagina in het mapje  **Mijn gebruikerstaken**. 
9. De controle zoals benoemd in de vorige stap, houdt in dat wordt gecheckt of het totaalbedrag in dit scherm overeenkomst met het bedrag dat door de bestuurder is goedgekeurd voor Contract onderhoud (velden  **Regelbedrag excl. BTW**  en  **Regelbedrag incl. BTW**). Voer indien gewenst een detailcontrole uit.
10. Kies nu voor de functie  **Aanmaken onderhoudsprojecten**. 
11. Na het voltooien van deze actie geeft Dynamics Empire aan dat er een X aantal projecten is aangemaakt. Klik op  **OK**  om de melding te sluiten. Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de  **Kladblokbudgetimportkaart**. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd. 
12. Maak een taak aan (zie stap 13), gericht aan uw collega die de Projectvoorbereiding heeft uitgevoerd, en geef de stand van zaken door (bijvoorbeeld "Er zijn 5 onderhoudsprojecten aangemaakt."). 
13. Sluit de Kladblokbudgetimportkaart.
14. Het verbeteren van projectnaam en -omschrijving is een actie die de projectleider moet uitvoeren, direct na het aanmaken van onderhoudsprojecten.

15.  Navigeer via het zoekveld  ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  naar de lijst  **Projectoverzicht**.
16.  Open een projectkaart door de juiste regel te selecteren en op  **Bewerken**  te klikken.
17.  Op de  **Projectkaart**  is op tabblad  **Algemeen**  een  **Naam**  en  **Omschrijving**  te zien. Deze worden door het systeem bepaald op basis van de bovenste voorlopige projectregel op de Kladblokbudgetimportkaart en dekken mogelijk niet de lading voor alle regels die aan het project zijn gekoppeld. Deze regels zijn terug te zien op tabblad  **Budgetregels**. Doorloop alle projecten en pas waar nodig de  **Naam**  en  **Omschrijving**  aan. U kunt hiervoor gebruik maken van de pijlknoppen links en rechts in het scherm, aan weerszijden van de projectkaart.
 
## Opvoeren van budgetregels handmatig
1. Ga naar **Projectoverzicht** dit kan via de ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon") ZOEKKNOP rechts bovenin.
2. Selecteer de regel van het handmatig ingevoerde project waarop u nu ook budgetregels wil vastleggen en klik in het lint van het projectoverzicht op **Bewerken**. De projectkaart wordt nu geopend.
3. Selecteer een blanco regel in het tabblad **Budgetregels** en leg de keuze vast vanuit de keuzelijst onder de kolom **Clusternr.**. Veelal is dit het contractcluster waarop de projectadministratie wordt gevoerd.
4. Leg op dezelfde budgetregel nu ook de keuze vast vanuit de keuzelijst onder kolom **Werksoort**.  Met de keuze voor een werksoortcode vult Dynamics Empire automatisch de bijhorende Werksoort en Werksoortboekingsgroep in.
5. Vul vervolgens de verwachte **Startdatum** en **Opleverdatum** in op de betreffende budgetregel.
6. Voer tot slot in de kolom **Begroot** het begrotingsbedrag van de budgetregel in. Dynamics Empire vraag u vervolgens reden aan te geven op het ingevoerde bedrag.

## Koppelen contract met project
1. Ga naar **Projectoverzicht** dit kan via de ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon") ZOEKKNOP rechts bovenin.
2. Selecteer de regel van het project waarop u het contract wil koppelen en klik in het lint van het projectoverzicht op **Bewerken**. De projectkaart wordt nu geopend.
3. Ga nu naar het tabblad **Boekingsinfo** en kies in de keuzelijst bij het invoerveld **Contractnr.** het contractnummer dat aan het project gekoppeld dient te worden.

## Zie ook

[Actualiseren prognose](../actualiseren-prognose/)  
[Registreren (onderhouds) jaarbegroting](../registreren-(onderhouds)-jaarbegroting/)  
[Voorbereiden onderhoudsproject](../voorbereiden-onderhoudsproject/)  
[Bewaken project](../bewaken-project/)  
[Uitvoeren contractonderhoud](../uitvoeren-contractonderhoud/)  
