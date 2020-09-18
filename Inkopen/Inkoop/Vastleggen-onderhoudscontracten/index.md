# Vastleggen onderhoudscontracten

In dit werkproces worden de uitgangspunten van een contract in Dynamics Empire vastgelegd en door een contractbeheerder gefiatteerd. De contractbeheerder heeft zodoende het totaalbudget beschikbaar voor de duur van de looptijd van het contract. Vervolgens kunnen ook onderhoudsprojecten op contract worden aangemaakt waarin de verplichtingenadministratie kan worden gevoerd.

## Opvoeren onderhoudscontract
 1. Navigeer via de zoekfunctionaliteit ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Contracten**.
 2. Kies voor **+Nieuw** om een nieuw contract op te voeren.
 3. Dynamics Empire maakt een nieuwe, lege **Contractkaart** aan. Ga naar veld **Omschrijving**, waarna automatisch een contractnummer wordt toegekend aan veld **Nr.**.
 4. Vul de gegevens op de kaart als volgt in:
	- **Omschrijving**: Bijvoorbeeld 'Contract CV-ketelonderhoud'.
	- **Soort**
	- **Leverancier**
	- **Status**: 'Initiatie' (de status wordt bij het in gebruik nemen van het contract hierna door het systeem gewijzigd).
	- **Geblokkeerd**: Alleen invullen als u het contract wilt blokkeren voor prolongeren.
	- **Startdatum**: De datum vanaf wanneer het contract in Dynamics Empire ingaat, dus niet de ingangsdatum van het contract zelf. Dynamics Empire heeft deze datum nodig om te bepalen vanaf welke datum geprolongeerd wordt.
	- **Looptijd**: Betreft de looptijd van het contract. Als u halverwege het contract gebruik gaat maken van de contractmodule, dan betreft dit de resterende looptijd van het contract. De veldinvoer gaat op basis van een datumformule. Voorbeeldwaarden: '1D', '1W', '1M', '1J'.
	- **Einddatum**: Wordt uitgerekend door Dynamics Empire en is daarna eventueel aan te passen.
	- **Reden beëindigen**
	- **Totaal budget**: Betreft het volledige budget, nadat het contract conform de looptijd is geprolongeerd, inclusief indexering. Wanneer door een prolongatie het budget wordt overschreden, dan wordt het prolongeren afgebroken met een foutmelding.
	- **Index percentage**: Betreft het percentage waarmee het contract moet worden geïndexeerd bij prolongatie.
	- **Gereedmelden orders**: Als alle orders na prolongatie status 'Gereedgemeld' moeten krijgen.  
	>Let op: Als match & boek wordt toegepast krijgt de inkoper geen facturen meer te zien ter goedkeuring, als er een match is tussen facturen en orders. Automatisch gereed melden is dan een risico.
	- **Fiatteur status**: Geeft aan dat het vastgelegde contract is goedgekeurd.
	- **Geprolongeerd t/m**: Geeft aan tot welke datum het contract is geprolongeerd.
	- **Opzegtermijn**: Is een datumformule en betreft de termijn waarbinnen beide partijen het contract kunnen opzeggen. Voorbeeldwaarden: '1D', '1W', '1M', '1J'.
	- **Stilzwijgende verlegging**

## Fiatteren onderhoudscontract

1. Navigeer via de zoekfunctionaliteit ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Contracten** en open het juiste contract.
2. Kies via menu-item **Proces** voor **Budgethouders**.
3. Vul de contractbeheerder in. Als u dit zelf bent, plaats dan een vinkje in kolom **Fiat**.
4. Als iemand anders de contractbeheerder is, kies dan voor de actie/functie **E-mail verzenden** om deze persoon te informeren dat het contract kan worden gefiatteerd.

## Zie ook

[Accorderen prestatie](../accorderen-prestatie/)  
[Beheren leveranciersinformatie](../beheren-leveranciersinformatie/)  
[Goedkeuren documenten](../goedkeuren-documenten/)  
[Inkopen PO/VGO](../inkopen-po-vgo/)  
[Registreren inkooporder](../registreren-inkooporder/)  
[Muteren/prolongeren onderhoudscontract](../muteren-prolongeren-onderhoudscontract/)
