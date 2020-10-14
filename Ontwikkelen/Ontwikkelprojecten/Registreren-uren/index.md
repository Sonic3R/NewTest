# Registreren uren

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=1a3&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

Uren die zijn besteed aan Investeringsprojecten, Planmatig Onderhoud en Contractonderhoud worden rechtstreeks op het project geboekt. Voordat uren geschreven kunnen worden op een project moet er een Resourcekaart aangemaakt worden en moeten er resources gekoppeld worden aan een project.
 
## Aanmaken resourcekaart

Een resourcekaart is nodig om medewerkers hun uren op een project te kunnen laten schrijven. 

 1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Resources**. 
 2. Klik op **Nieuw | +Nieuw**. 
 3. De volgende velden op het tabblad **Algemeen** moeten worden gevuld:
	* **Nr.:** Initialen van de resource (medewerker). 
	* **Naam:** Naam van de resource (medewerker).
	* **Soort:** 'Persoon'.
	* **Basiseenheid:** 'Uur'.
	* **Resourcegroep:** (laat dit veld leeg) 
 4. Op tabblad **Facturering** vult u in het veld **Directe kostprijs** het uurtarief. Over het algemeen is het een marktconforme uurprijs voor doorbelasting aan projecten. De overige velden kunt u overslaan.
 5. Op tabblad **Projecten** vult u de volgende velden:
	* **Gebruikers-ID:** Selecteer de resource (medewerkersnaam) uit de lijst.
	* **E-mail:** E-mailadres van de resource (medewerker). Dit is nodig als u werkt met een ander weekurensjabloon dan 'NUL' uur, zodat er een herinneringsmail gestuurd kan worden.
	* **Huidig weeknr.:** Dit is de startweek vanaf welke de resource (medewerker) uren dient te schrijven in Dynamics Empire. Het systeem hoogt het weeknummer op nadat de uren van de betreffende week volledig zijn geboekt. De resource wordt hierdoor automatisch geleid naar de eerste niet-geboekte week bij het benaderen van de zogenaamde 'weekbon' en kan uiteraard bladeren naar komende weken.
	* **Huidig jaar:** Vul het jaar in van wanneer de resource uren moet kunnen schrijven op projecten.
	* **Weekurensjabloon:** Selecteer het sjabloon waarin is vastgelegd hoeveel uren een resource (medewerker) moet verantwoorden (contracturen). 'Nul uren' betekent ongelimiteerd: er is géén controle op de hoeveelheid geschreven uren per dag/week. 
	* **Gebruik weekbon:** Zet dit veld op 'AAN'.	 
	
## Registreren uren

Een resource (medewerker) kan alleen uren vastleggen op een project als hij/zij daaraan gekoppeld is.

 1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projectoverzicht**. 
 2. Selecteer het project waarvoor u de gegevens wilt opvoeren en open de kaart.
 3. Selecteer op tabblad **Budgetregels** een regel waarop de resource (medewerker) zijn uren moet gaan schrijven. Kies in het menu van het tabblad voor **Budget** (onder **Beheren**), waarna de budgetkaart wordt geopend. Ga vervolgens naar tabblad **Uren** en vul de volgende velden:
	* **Nr.:** Selecteer de resource (medewerkersnaam) uit de lijst.
	* **Boeken toegest. vanaf** en **Boeken toegest. tot:** Geef eventueel de datum op om de periode aan te geven waarbinnen de resource (medewerker) uren mag schrijven. Standaard staan hier de start- en opleverdatum van het project. 
	* **Aantal:** Geef het budget op in het aantal uren waarvoor de resource (medewerker) werkzaam is op dit project voor dit onderdeel (werksoort).
 
>Als er meerdere resources (medewerkers) zijn op hetzelfde budget, herhaal dan bovenstaande stappen. Doe dit ook als dezelfde resource op een andere budgetregel werkzaamheden gaat verrichten. Sluit dan eerst deze budgetkaart en kies vervolgens de juiste regel.  
>Het resultaat van het aanmaken van de uren is nu zichtbaar in het feitenblok op de Projectkaart, bij het item **Uren**.

## Vastleggen uren

In deze processtap worden de uren per dag verantwoord in Dynamics Empire door de betreffende resource (medewerker).

 1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Urenstaat**. U komt in de zogenaamde Weekbon. Dit is het scherm waarin u uren kunt verantwoorden, in een eerstvolgende niet-geboekte week. Met de knoppen in het menu kunt u tussen de weken bladeren. In de regels van dit scherm staan de projecten waarop u uren mag verantwoorden. Mist u een regel, vraag dan aan de projectleider om de koppeling met het project te controleren (zie vorige stappen).

>U ziet tevens het budget aan uren en de uren die u reeds ingevuld hebt. Mocht u over uw budget heen gaan, bespreek dit dan met de projectleider. Wellicht kan hij het budget verruimen.

 2. U kunt nu uren schrijven door het aantal uren in te vullen op de regel van het project waarvoor de uren gelden. Selecteer die regel en ga naar het veld **Maandag dd-mm-jj** of een van de andere dagen waarvoor u uren wilt vastleggen.
 3. Vul het aantal uren in en klik daarna op de **... Opzoekwaarde**; er opent een scherm waarin u de mogelijkheid hebt om een eigen beschrijving op te geven. Dit kan gespecificeerd worden door de uren op die dag op te delen; u geeft dan per regel het aantal uren en een omschrijving op. Het aantal uren zal dan vetgedrukt worden weergegeven.  Wilt u geen omschrijving, dan laat u deze regel leeg. Als laatste actie klikt u op **Sluiten**.
> Als voor u een urensjabloon is ingesteld met contracturen, dan ziet u onderin de weekbon hoeveel uren u voor de betreffende dag nog dient te verantwoorden. De specificatie ziet u ongeacht welk urensjabloon is gebruikt.

## Controleren uren

Het niet tijdig schrijven, accorderen en boeken van uren kan het afsluiten van boekhoudperioden vertragen. Collega’s dienen daarom eraan herinnerd te worden dat ze nog uren moeten schrijven. Een dergelijke controle door het systeem kan alleen als niet met een zogenaamd NUL-urensjabloon wordt gewerkt.

## Accorderen uren

Alle uren die geschreven behoren te zijn in een bepaalde periode, meestal een week, moeten worden geaccordeerd om uiteindelijk geboekt te kunnen worden. U kunt niet uw eigen uren accorderen, maar alleen die van collega's.

### Invoeren te accorderen uren

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Accorderen uren**. U komt in een overzicht met de lijst van de uren die klaar staan om geaccordeerd te worden. U ziet eerst alleen uw eigen uren, maar die kunt u niet accorderen. Het overzicht toont de week die op dat moment geldt!
2. Ga naar tabblad **Beheren** en kies voor **Toon alle**. Vervolgens zoekt u de week die u wilt gaan accorderen door op de knop **Volgende week** of **Vorige week** te klikken. 
3. Als u in de juiste week bent beland kunt u de uren accorderen van uw collega's door in het veld **Akkoord** te gaan staan en de keuze op 'JA' te zetten. Indien niet akkoord, dan is de keuze 'NEE'.  
De uren staan nu gereed om door de controleur/manager goedgekeurd te worden. 

### Goedkeuren uren

De controleur/manager kan nu de ingevoerde uren in het overzicht **Accorderen uren** gaan accorderen.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst  **Accorderen uurtotalen**. U komt in het overzicht van de uren die gereed staan om geaccordeerd te worden.
2. Op tabblad **Algemeen** kunt u bij het veld **Toon uren** kiezen voor 'Alle'; dit zijn alle te boeken uren na akkoord. Als u kiest voor 'Alleen niet-geaccordeerd' zijn de uren zichtbaar die nog niet geboekt kunnen worden na akkoord! 
3. Klik op de knop **Accorderen**, waarna een pop-up verschijnt met de tekst: "Wilt u alle uren (binnen de selectie) accorderen?" Kies voor **JA**.  
De uren zijn nu geaccordeerd en gereed om geboekt te worden.

## Versturen herinnering

Het niet tijdig schrijven, accorderen en boeken van uren kan het afsluiten van boekhoudperiodes vertragen. Collega’s dienen daarom eraan herinnerd te worden dat ze nog uren moeten schrijven. Een dergelijke controle door het systeem kan alleen als niet met een zogenaamd NUL-urensjabloon wordt gewerkt. Als niet alle uren geschreven zijn moet er een herinnering verstuurd worden naar de medewerkers.

De betreffende controleur/manager van de medewerkers die uren moeten schrijven op projecten dient deze herinnering te versturen.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Accorderen uren**. 
2. Op tabblad **Beheren** kiest u voor **Alleen niet acc.**. Blader nu via de knoppen **Volgende week**/**Vorige week** naar de juiste week en kies vervolgens de optie **Herinnering**. De betreffende medewerker krijgt een mail met daarin het verzoek de uren te controleren en te accorderen.

## Uren boeken

Als alle uren geaccordeerd zijn kunnen deze worden geboekt.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Boeken uren (weekbon)**. 
2. In het overzicht staan alle te boeken uren. De controleur/manager kan hier eventueel nog een extra controle uitvoeren door de betreffende medewerker te selecteren en voor optie **Weekbon** te kiezen als hij ziet dat de uren in de kolom **Uren te boeken** niet overeenkomen met het aantal te werken urensjabloon(niet bij NUL-urensjabloon).
3. De controleur/manager kan via actie **Herinnering** de medewerker een bericht sturen dat het niet klopt.
4. Als alle uren geboekt kunnen worden selecteert u alle medewerkers. (Dit doet u door op de drie puntjes ('...') in één van de regels te klikken en dan **Meer selecteren** te kiezen; u kunt dan alle regels aanvinken waarvan de uren geboekt mogen worden.) 
5. Klik tot slot op **Boeken**, waarna de uren zijn geboekt.

## Zie ook

[Voorbereiden ontwikkelproject](../voorbereiden-ontwikkelproject/)  
[Voorbereiden projectfase](../voorbereiden-projectfase/)  
[Afronden projectfase](../afronden-projectfase/)  
