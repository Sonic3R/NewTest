# Beheren clusterinformatie

In dit werkproces worden nieuwe clusters aangemaakt en worden bestaande clusters beheerd.

## Aanmaken cluster

In deze stap maakt u een nieuw cluster aan en voert u de benodigde basisgegevens op.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Klik op **Nieuw | + Nieuw** om een nieuwe clusterkaart aan te maken. Druk op **Enter**; selecteer in het scherm dat opent de clustersoort die van toepassing is op het nieuwe cluster en klik op **OK**.
2. U keert terug naar de clusterkaart. Het clusternummer wordt automatisch toegekend door het systeem. Pas het clusternummer desgewenst aan.

## Aanpassen basisgegevens

In deze stap worden de basisgegevens van het cluster opgevoerd of aangepast.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waarvoor u basisgegevens aan wilt passen.
2. De volgende basisgegevens dient u bij nieuwe clusters op te voeren en kunt u desgewenst aanpassen:
	- **Naam**
	- **Onderdeel van cluster**: Alleen bij clusters van het clustersoort 'Bouwblok'.
	- **Divisie**: Alleen wanneer u gebruikt maakt van divisies.
	- **Servicebureau**: Alleen wanneer het een service- of verbruikscluster betreft en de afrekening (gedeeltelijk) plaatsvindt via een servicebureau. 
	- **Budgethouder**: Alleen wanneer de clustersoort gekenmerkt is als 'Technisch'.
3. De **Dimensiewaarde** kunt u toevoegen of wijzigen door te navigeren naar **Dimensies**. 
	- Geef in de kolom **Dimensiecode** aan welk type dimensiewaarde u toe wilt voegen. 
	- Geef in de kolom **Dimensiewaardecode** de dimensiewaarde op. 
4. Wanneer het cluster gebruikt wordt om contactpersonen te koppelen aan eenheden kunt u op tabblad **Contactbeheer** van de clusterkaart medewerkers of andere contactpersonen toevoegen of verwijderen. Kies bovenin het tabblad voor **Nieuwe regel** en geef de **Functie** en het **Contactnr.** van de contactpersoon op.

## Toevoegen OG Eenheid

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waaraan u eenheden toe wilt voegen. Kies voor de actie/functie **Eenheden toevoegen**.
2. Selecteer op de pagina die opent de eenheden die u toe wilt voegen aan het cluster en klik op **OK**.  
Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'Financieel' heeft, krijgt u een waarschuwing dat mogelijk de clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaatsvinden.

## Verwijderen OG Eenheid

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waaruit u eenheden wilt verwijderen. Navigeer naar **Eenheden**.
2. Selecteer de eenheden die u wilt verwijderen en kies voor **Verwijderen**. Klik op **Sluiten** om terug te keren naar de clusterkaart.  
Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'Financieel' heeft, krijgt u een waarschuwing dat mogelijk de clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaatsvinden.

## Toevoegen collectief object

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waaraan u collectieve objecten toe wilt voegen. Kies voor de actie/functie **Collectieve objecten toevoegen**.
2. Selecteer op de pagina die opent de collectieve objecten die u toe wilt voegen aan het cluster en klik op **OK**.  
Wanneer de clustersoort van het cluster waaraan u collectieve objecten toegevoegd heeft het kenmerk 'Financieel' heeft, krijgt u een waarschuwing dat mogelijk de clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaatsvinden.

## Verwijderen collectief object 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waaruit u collectieve objecten wilt verwijderen. Navigeer naar **Eenheden**.
2. Selecteer de collectieve objecten die u wilt verwijderen en klik op **Verwijderen**. Klik op **Sluiten** om terug te keren naar de clusterkaart.  
Wanneer de clustersoort van het cluster waaraan u eenheden toegevoegd heeft het kenmerk 'Financieel' heeft krijgt u een waarschuwing dat mogelijk de clusterverdeelsleutel aangepast dient te worden. Deze kunt u voor nu negeren. Het actualiseren van de verdeelsleutel zal in een latere stap plaatsvinden.

## Aanmaken clusterverdeelsleutels

In deze stap worden de eerste clusterverdeelsleutels aangemaakt. Dit hoeft alleen te gebeuren wanneer de clustersoort van het cluster het kenmerk 'Financieel' heeft. Alleen eenheden die in exploitatie zijn (**Status** = 'Verhuurd' of 'Leegstand') worden toegevoegd aan een clusterverdeelsleutel.
1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waarvoor u clusterverdeelsleutels aan wilt maken. Navigeer naar de **Clusterverdeelsleutels**.
2. Klik op **+Nieuw** en vul de volgende velden op de **Clusterverdeelsleutelkaart**:
	- **Verdeelsleuteltype**
	- **Ingangsdatum**: Advies is om hier altijd te kiezen voor 1 januari van het huidige jaar. 
3. Wanneer u bij het verdeelsleuteltype gekozen heeft voor een type dat niet gelijk is aan lineair dient u de wegingsfactoren per eenheid op te geven. U kunt de wegingsfactor opgeven in de kolom **Teller** op tabblad **OG Eenheden**. 
4. Klik op **Verdeelsleutel activeren** om de verdeelsleutel te activeren. 
5. Herhaal stap 2 t/m 4 wanneer u verdeelsleutels met verschillenden verdeelsleuteltypes aan wilt maken.

## Actualiseren individuele clusterverdeelsleutels

Wanneer u in een eerdere stap eenheden toegevoegd heeft aan het cluster of verwijderd heeft uit het cluster, en er waren al clusterverdeelsleutels aanwezig voor het cluster, dan kunt u de clusterverdeelsleutels behorende bij het cluster actualiseren. Alleen eenheden die in exploitatie zijn (**Status** = 'Verhuurd' of 'Leegstand') worden toegevoegd aan een clusterverdeelsleutel.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Clusteroverzicht**. Open de clusterkaart van het cluster waarvoor u clusterverdeelsleutels wilt actualiseren. Navigeer naar de **Clusterverdeelsleutels**.
2. Selecteer de meest recente clusterverdeelsleutel van het clusterverdeelsleuteltype. Klik op **Verdeelsleutel actualiseren**. De nieuwe clusterverdeelsleutelkaart wordt geopend.
3. Vul in het veld **Ingangsdatum** de ingangsdatum van de nieuwe verdeelsleutel in. Deze moet altijd na vandaag liggen. 
4. Wanneer u eenheden toegevoegd hebt aan het cluster en het type verdeelsleutel is niet LINEAIR, dan dient u in de kolom **Teller** de wegingsfactor voor de nieuwe eenheden op te geven. 
5. Klik op **Verdeelsleutel activeren** om de verdeelsleutel te activeren. 
6. Herhaal stap 2 t/m 5 wanneer u verdeelsleutels met verschillenden verdeelsleuteltypes wilt actualiseren.

## Muteren service- en verbruikselementen

Wanneer een cluster gebruikt wordt binnen het proces 'Service- en verbruiksafrekening' dienen de elementen die afgerekend worden beheerd te worden. Deze processtap beschrijft hoe u elementen toekent aan een cluster en hoe u deze elementen beheert. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Elementen**. Kies in het veld **Elementsjabloon** voor **Cluster** en vul in het veld **Clusternr.** het clusternummer waarvoor u elementen wilt muteren. 
2. Wanneer u een nieuw element wilt toevoegen aan een cluster vult u in de regel in het veld **Nr.** het elementnummer in. Klik daarna in de lege regel onder de nieuw aangemaakte regel om de regel te activeren. 
3. In de kolom **Teller bepalen** geeft u aan op welke wijze de kosten die betrekking hebben op het element verdeeld dienen te worden. Er zijn drie opties:
	- 'Handmatig': U geeft per eenheid aan hoeveel kosten toegerekend dienen te worden.
	- 'Voorschot (berekend)': De kosten worden verdeeld o.b.v. het betaalde voorschot.
	- 'Lineair': De kosten worden lineair verdeeld over alle eenheden. Elke eenheid krijg evenveel kosten toegerekend. 
4. Wanneer in de kolom **Teller bepalen** gekozen is voor 'Handmatig' kunt u de verdeling per eenheid aanpassen door op **Tellers** te klikken. Onder de tab **Teller per OG eenheid** geeft u in de kolom **Teller** de weging per eenheid op. Wanneer u de tellers aangepast heeft drukt u op F5 om de pagina te verversen. De waarde in het veld **Noemer berekend** is bijgewerkt. Kopieer de waarde uit het veld **Noemer berekend** en plak deze waarde in het veld **Noemer**. Klik op **Sluiten** om terug te keren naar de pagina **Elementen**.

## Zie ook

[Afsluiten jaar](../afsluiten-jaar/)  
[Beheren dimensies](../beheren-dimensies/)  
[Beheren grootboekbudgetten](../beheren-grootboekbudgetten/)  
[Boeken memoriaal](../boeken-memoriaal/)  
[Boeken periodiek dagboek](../boeken-periodiek-dagboek/)  
[Dichtzetten periode](../dichtzetten-periode/)  
[Overboeken categoriaal naar functioneel](../overboeken-categoriaal-naar-functioneel/)  
[Periodiek actualiseren clusterverdeelsleutels](../periodiek-actualiseren-clusterverdeelsleutels/)  
[Verdelen posten naar eenheidsniveau](../verdelen-posten-naar-eenheidsniveau/)  
[Vereffenen grootboekposten](../vereffenen-grootboekposten/)  
[Verwerken DAEB/niet-DAEB-verdeling](../verwerken-daeb-niet-daeb-verdeling/)  
