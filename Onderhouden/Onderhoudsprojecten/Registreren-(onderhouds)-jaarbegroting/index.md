# Registreren (onderhouds)jaarbegroting

In dit proces worden alle uitvoeringsactiviteiten van de jaarbegroting ingelezen in Dynamics Empire.

## Registreren begroting

### Importeren begrotingsregels

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar het **Kladblokimportoverzicht**. Hierin zijn alle in het verleden geïmporteerde begrotingen te zien.  

> Begrotingsregels uit Vastware worden automatisch overgezet naar Dynamics Empire. Hiervoor hoeft u niets te doen, anders dan in Vastware budgetten vrij te geven. Deze regels zijn te herkennen aan omschrijving DE MJO Jaarbegroting + jaartal, een RUN-nummer en een zogenaamde servicegebruiker.  

2. Klik op **+ Nieuw** in het lint. Dynamics Empire maakt een zogenaamde **Kladblokbudgetimportkaart** aan met een volgnummer.  

> **Let op!** De kaart die zojuist is aangemaakt dient een volgnummer te hebben, niet zijnde 0. Mocht de kaart die u zojuist heeft aangemaakt volgnummer 0 hebben, druk dan op Enter. Dynamics Empire zal dan een volgnummer toekennen.  

3. Een Kladblokbudgetimportkaart is een scherm waarin begrotingsregels kunnen worden geïmporteerd en verwerkt tot projecten. Deze kaart bestaat uit vier onderdelen:
	* **Algemeen**: Op dit tabblad vindt u algemene gegevens terug, zoals een volgnummer, een omschrijving voor de geïmporteerde begrotingsregels, en pad naar het geïmporteerde bestand, een begrotingsjaar en uiteraard het totaal bedrag excl. En incl. BTW van alle geïmporteerde regels ter controle.
	* **Kladblokimportregels**: Op dit tabblad staan de geïmporteerde begrotingsregels.
	* **Voorlopige projectregels**: Op dit tabblad vindt u de begrotingsregels na verwerking.
	* **Functies**: Op dit tabblad kunt u functies toekennen aan de contactpersonen (projectteam) van geïmporteerde begrotingsregels.
4. Kies voor de actie/functie **Budget importeren** om een bestand met begrotingsregels te importeren. Dynamics Empire opent een venster genaamd **Import budget planmatig onderhoud**. Vul de velden in dit venster in als volgt:
    * **Importsjablooncode**: Dit is de code van het te gebruiken importsjabloon.
    * **Omschrijving**: Hier staat de omschrijving van het importsjabloon; deze is aan te passen naar een omschrijving voor het geïmporteerde bestaand (bijvoorbeeld begroting PO 2017).
    * **Bestandsnaam**: Selecteer met behulp van de assistedit (…) het te importeren bestand.
    * **Projecttype**: Dit betreft het projecttype van de begrotingsregels die u wilt importeren (PO-CO-SO).
    * **Begrotingsjaar**: Dit betreft een boekjaar van de begrotingsregels.
5. Klik op **Import**. Wanneer de import slaagt, krijgt u hiervan een melding: 'De import is succesvol verlopen.' Sluit de melding.
6. Het resultaat is te zien op de bovenste twee onderdelen van de Kladblokbudgetimportkaart. Sluit de kaart.
7. Terug op het Kladblokimportoverzicht ziet u nu een nieuw record waarin handmatige begrotingsregels zijn geïmporteerd.
Wanneer u een foutief bestand heeft geïmporteerd, selecteer dan de betreffende regel en klik op **Verwijderen**. De Kladblokbudgetimportkaart wordt dan in zijn geheel verwijderd.
8. Voor het eventueel verder verwerken van de begrotingsregels selecteert u het nieuwe record en kiest u voor **Bewerken**, waarmee de kaart in een bewerkbare vorm wordt geopend.

## Zie ook

[Aanpassen onderhoudsbudget](../aanpassen-onderhoudsbudget/)  
[Voorbereiden onderhoudsproject](../voorbereiden-onderhoudsproject/)  
[Bewaken project](../bewaken-project/)  
[Aanmaken contractonderhoudsproject](../aanmaken-contractonderhoudsproject/)  
[Uitvoeren contractonderhoud](../uitvoeren-contractonderhoud/)  
