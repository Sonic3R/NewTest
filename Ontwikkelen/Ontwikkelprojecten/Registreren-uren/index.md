# Registreren uren

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

### Invoeren te accorderen urenTOTHIERRRRRRRRRRRRRR

Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Accorderen uren**. 
Je komt in een overzicht met de lijst van de uren die klaar staan om geaccordeerd te worden. Je ziet eerst alleen je eigen uren maar die kan je "niet" accorderen. Het overzicht toont de week die op dat moment geldt!
Ga naar het tabblad **Beheren** en kies in het lint **Toon alle** en vervolgens zoek je de week die je wilt gaan accorderen door in het lint de knop **Volgende week** of **Vorige week** te kiezen. 
Indien je in de juiste week bent beland kan je de uren accorderen van je collega's door in het veld **Akkoord** te gaan staan en de keuze op "JA" te zetten. Indien niet akkoord dan de keuze "NEE".
De uren staan nu gereed om door de controleur/manager goed gekeurd te worden. 

### Goedkeuren uren

De controleur/manager kan nu de ingevoerde uren in het overzicht "accorderen uren" gaan accorderen.
Navigeer via de zoekfunctionaliteit ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  naar de lijst **Accorderen uurtotalen**. 
Je komt in het overzicht van te uren die gereed staan om geaccordeerd te worden. In het tabblad **Algemeen** kan je bij het veld **Toon uren** kiezen voor "Alle", dit zij alle te boeken uren na akkoord. Indien je kiest voor "Alleen niet geaccordeerd" zijn de uren zichtbaar die nog niet geboekt kunnen worden na akkoord! 
In het lint klik je op de knop **Accorderen** en vervolgens verschijnt er een pop-up met de tekst: "Wilt u de alle uren (binnen de selectie) accorderen? **JA** kiezen.  De uren zijn geaccordeerd en gereed om geboekt te gaan worden.

## Versturen herinnering

Het niet tijdig schrijven, accorderen en boeken van uren kan het afsluiten van boekhoudperiodes vertragen. Collega’s dienen daarom eraan herinnerd te worden dat ze nog uren moeten schrijven. Een dergelijke controle door het systeem kan alleen als niet met een zogenaamd NUL-urensjabloon wordt gewerkt. Als niet alle uren geschreven zijn moet er een herinnering verstuurd worden naar de medewerkers.

De betreffende controleur/manager van de medewerkers die uren moeten schrijven op projecten een herinnering te versturen. 
Navigeer via de zoekfunctionaliteit ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon") naar de lijst **Accorderen uren**. 
In het tabblad **Beheren** kies je in het lint voor **Alleen niet acc.** vervolgens blader via de knop **Volgende week** of **Vorige week** naar de juiste week en kies vervolgens in het lint **Herinnering**. 
De betreffende medewerker krijgt een mail met daarin het verzoek de uren te controleren en te accorderen.

## Uren boeken

Indien alle uren geaccordeerd zijn kunnen deze worden geboekt.

Navigeer via de zoekfunctionaliteit ![zoeken icon](https://docs.cegeka-dsa.nl/assets/images/zoeken.png "zoeken icon")  naar de lijst **Boeken uren (weekbon)**. 
In het overzicht staan alle te boeken uren. De controleur/manager kan hier eventueel nog een extra controle uitvoeren door de betreffende medewerker te selecteren en in het lint de knop **Weekbon** aan te klikken als hij ziet dat de uren in de kolom "Uren te boeken" niet overeenkomen met het aantal te werken urensjabloon(niet bij NUL urensjabloon). De controleur/manager kan via de knop **Herinnering** in het lint de medewerker een bericht sturen dat het niet klopt.
Indien alle uren geboekt kunnen worden dan selecteer je alle medewerkers. Dit doe je door middel van de eerste regel van de medewerker te selecteren en vervolgens bij **Resourcenr.** de **"drie" puntjes** te klikken en dan **Meer selecteren** te klikken. Je hebt nu de mogelijkheid om de medewerkers te selecteren waarvan de uren geboekt mogen worden. 
Vervolgens ga je naar het lint en klik je op **Boeken** en de uren zijn geboekt. 

## Zie ook

[Voorbereiden ontwikkelproject](../voorbereiden-ontwikkelproject/)  
[Voorbereiden projectfase](../voorbereiden-projectfase/)  
[Afronden projectfase](../afronden-projectfase/)  
