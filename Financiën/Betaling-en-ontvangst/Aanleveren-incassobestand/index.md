# Aanleveren incassobestand

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=6c1&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces wordt een incassobestand gegenereerd op basis van te incasseren klantposten.

## Ophalen voorstel klantposten

Als u een incassobestand voor klantposten aan wilt maken, dient u aan te geven welke posten daarin meegenomen moeten worden.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Telebankieren - bankoverzicht**.
2. Klik op **Voorstelposten ophalen**, waarna de gelijknamige pagina opent.
3. Vul de volgende velden met de aangegeven waarden:
	* **Transactiedatum:** Datum waarop de incasso moet plaatsvinden.
	* **Valutadatum:** Posten met een vervaldatum op of voor deze datum worden meegenomen in het betaalvoorstel. Bij een incasso op de eerste van de maand vult u hier bijvoorbeeld 01-03-2020 in.
	* **Onze bank:** Bank vanaf waar de incasso uitgevoerd wordt.
	* **Rekeningsoort:** 'Klant'.
	* **Code:** Selecteer de transactiewijze voor automatische incasso voor klantposten.
	* **Onder het kopje Klantenpost** (als bepaalde velden niet zichtbaar zijn kunt u die toevoegen via de optie **+ Filteren...**):
		* **Broncode:** Vul de broncode in. Voor prolongatieposten is dit 'PROLON', voor service- en verbruiksposten is dit 'SENV'.
		* **Documenttype:** 'Factuur'.
		* **Boekingsdatum:** Wanneer u posten vanuit de prolongatie wilt incasseren vult u hier de boekingsdatum van de prolongatie in.
4. Klik op **OK**. Het voorstel wordt aangemaakt en er zal een popup verschijnen met het resultaat.

## Controleren en oplossen

Als bij de vorige stap bleek dat er foutmeldingen of waarschuwingen zijn ontstaan bij het aanmaken van het betaalvoorstel, dan dient u deze te controleren en eventueel op te lossen.

1. Klik op **Voorstel**, waarna de pagina **Telebankiervoorstel** opent.
2. In de kolom **Foutmelding** ziet u meldingen die u moet oplossen voordat de voorstelregel meegenomen kan worden in het betaalvoorstel.
3. In de kolom **Waarschuwing** ziet u meldingen die niet blokkerend zijn voor het meenemen van de voorstelregel. Lees deze waarschuwingen door en bepaal of u iets met deze waarschuwing wilt doen of niet.
4. Wanneer u foutmeldingen en/of waarschuwingen heeft opgelost selecteert u in het telebankierenvoorstel de functie **Controleren**. Het systeem controleert het voorstel opnieuw op fouten en waarschuwingen.

## Verwerken voorstel

Wanneer er geen foutmeldingen (meer) in het betaalvoorstel staan kunt u het betaalvoorstel omzetten naar een betaalrun.

1. Klik op **Voorstel**, waarna de pagina **Telebankiervoorstel** opent.
2. Klik op **Verwerken**, waarna de betaalrun wordt aangemaakt. Er verschijnt een popup met het resultaat.

## Controleren betaalrun

Nadat u de betaalrun aangemaakt heeft kunt u deze controleren.

 1. Klik op de pagina **Telebankieren - bankoverzicht** op **Betaalrun**. De pagina **Betaalrunlijst** opent. 
 2. Klik op **Weergeven** om de regels in de betaalrun te tonen. 

## Annuleren betaalrunregels

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat één of meerdere regels niet meegenomen moeten worden in de betaalrun, kunt u individuele regels annuleren zonder de hele betaalrun te hoeven annuleren.

1. Selecteer in de lijst **Betaalrunlijst** (zie **[Controleren betaalrun](#controleren-betaalrun)**) de betaalrun waaruit u regels wilt annuleren en klik op **Bewerken.**
2. In het scherm **Betaalrunkaart** kunt u de regelnummers vinden van de regels die u wilt annuleren. Noteer hiervan de betreffende nummers.
3. Klik op **Status wijzigen**, waarna het scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
    * **Nieuwe status:** 'Geannuleerd'.
    * **Onze bank:** (laat ongewijzigd)
    * **Runnummer:** (laat ongewijzigd)
    * **Regelnr.:** Vul hier de regelnummers in van de regels die u wilt annuleren.
4. Klik op **OK**. De regels krijgen de status 'Geannuleerd' en worden niet meegenomen wanneer u de betaalrun exporteert.

## Annuleren betaalrun

Wanneer naar aanleiding van het controleren van de betaalrun blijkt dat de betaalrun opnieuw gegenereerd moet worden, dient u de betaalrun in zijn geheel te annuleren.

1. Selecteer in de lijst **Betaalrunlijst** (zie **[Controleren betaalrun](#controleren-betaalrun)**) de betaalrun waaruit u regels wilt annuleren en klik op **Bewerken**.
2. Klik op **Status wijzigen**. Het scherm **Betaalrun - status wijzigen** opent. Vul hier de volgende velden:
    * **Nieuwe status:** 'Geannuleerd'.
    * **Onze bank:** (laat ongewijzigd)
    * **Runnummer:** (laat ongewijzigd)
3. Klik op **OK**. De status van de betaalrunregels wordt aangepast naar **Geannuleerd**.  

## Exporteren betaalrun

Wanneer de betaalrun gecontroleerd en goed bevonden is, kan deze geëxporteerd worden om vervolgens in de applicatie van de bank ingelezen te worden.

1. Selecteer in de lijst **Betaalrunlijst** (zie **[Controleren betaalrun](#controleren-betaalrun)**) de betaalrun die u wilt exporteren.
2. Klik op **Exporteren**. Het scherm **Exporteren PAIN** opent.
3. Klik op **OK**. Het PAIN-bestand word opgeslagen op de in de exportprotocollen gedefinieerde locatie.

## Zie ook

[Aanleveren betaalbestand](../aanleveren-betaalbestand/)  
[Verwerken bankmutaties](../verwerken-bankmutaties/)  
[Verwerken overige betaalverzoeken](../verwerken-overige-betaalverzoeken/)  
[Verwerken pintransacties](../verwerken-pintransacties/)  
