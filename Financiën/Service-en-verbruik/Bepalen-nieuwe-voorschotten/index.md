# Bepalen nieuwe voorschotten

In dit werkproces worden de nieuwe voorschotten voor service- en verbruikcomponenten bepaald en verwerkt.

## Voorbereiden nieuwe voorschotten

De nieuwe voorschotten bij service en verbruik worden geïmporteerd via een .csv bestand. De eerste stap is het opstellen van de .csv bestand met de juiste waardes hiervoor dienen eerst gegeven geëxporteerd te worden . Vervolgens wordt het bestand opgesteld worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar het rapport **Exporteer de huurverhogingsgegevens naar Excel**.
2. Vul de volgende velden:
	 - **Referentiedatum:** De referentiedatum voor de te exporteren gegevens. Denk hier bijvoorbeeld aan de op die datum geldige servicekosten.	
	 - **Cluster:** Het cluster/de clusters waarvoor u de gegevens wilt exporteren. 
3. Klik op **OK** om de gegevens naar Excel te exporteren. Open het Excel-bestand. Hierin vindt u de gegevens per element per contractregel. Deze gegevens kunt u gebruiken voor het opstellen van het te importeren .csv-bestand. 
4. Open een nieuw Excel-bestand om het .csv-bestand op te stellen. Dit bestand dient altijd de volgende 8 kolommen te bevatten:
	- **Kolom A:** OG Eenheid-nummer - Dit kunt u uit het geëxporteerde bestand halen. 
	- **Kolom B:** Klantnummer - Dit kunt u uit het geëxporteerde bestand halen. 
	- **Kolom C:** Contractregelnummer - Dit is het nummer van de huidige contractregel op basis waarvan u de verhoging door wilt voeren, dit kunt u uit het geëxporteerde bestand halen. 
	- **Kolom D:** Elementnummer - Dit betreft het element waarvoor u een aanpassing door wilt voeren, dit kunt u uit het geëxporteerde bestand halen. 
	- **Kolom E:** Type aanpassing - U dient een getal van 0 tot 5 op te geven:
		- 0 = Niet
		- 1 = Percentage
		- 2 = Bedrag (bedrag waarmee verhoogd wordt)
		- 3 = Vervalt
		- 4 = Toevoegen
		- 5 = Was/Wordt
	 -  **Kolom F:** Verhoging:
		 - Wanneer in kolom E waarde = 0, vul hier 0 in.
		 - Wanneer in kolom E waarde = 1, vul hier het percentage in.
		 - Wanneer in kolom E waarde = 2, vul hier het verhogingsbedrag in. 
		 - Wanneer in kolom E waarde = 3, vul hier 0 in.
		 - Wanneer in kolom E waarde = 4, vul hier 0 in.
		 - Wanneer in kolom E waarde = 5, vul hier 0 in.
	 -  **Kolom G:** Was
		 - Wanneer in kolom E waarde = 0, vul hier 0 in.
		 - Wanneer in kolom E waarde = 1, vul hier 0 in.
		 - Wanneer in kolom E waarde = 2, vul hier 0 in.
		 - Wanneer in kolom E waarde = 3, vul hier 0 in.
		 - Wanneer in kolom E waarde = 4, vul hier 0 in.
		 - Wanneer in kolom E waarde = 5, vul hier het huidige bedrag in.
	 -  **Kolom H:** Wordt
		 - Wanneer in kolom E waarde = 0, vul hier 0 in.
		 - Wanneer in kolom E waarde = 1, vul hier 0 in.
		 - Wanneer in kolom E waarde = 2, vul hier 0 in.
		 - Wanneer in kolom E waarde = 3, vul hier 0 in.
		 - Wanneer in kolom E waarde = 4, vul hier het nieuwe bedrag in.
		 - Wanneer in kolom E waarde = 5, vul hier het nieuwe bedrag in.
 - Sla het Excel-bestand zonder kolomkoppen op als .csv-bestand. 
 
## Verwerken nieuwe voorschotten

Wanneer de huurder gelijktijdig met de jaarlijkse huurverhoging geïnformeerd wordt over de nieuwe voorschotten voor service en verbruik, dient u de nieuwe voorschotten te importeren en te verwerken op de nieuwe contractregel. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Huurverhogingsbestand importeren**. Selecteer het opgeslagen .csv-bestand en klik op **OK**.
2. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Huurverhoging-import**. Hier vindt u de geïmporteerde regels. U kunt deze regels nog controleren. 
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Verwerken huurverhoging-import**. 
4. Selecteer de batch voor het verhogen van service- en verbruikskosten en geef de huurverhogingsdatum op. Zet de opties **Huurdernr.** en **Contractnr.** aan. Klik op **OK** om de huurprijsaanpassing klaar te zetten op de huidige contractregel.

## Zie ook

[Genereren afrekenresultaat](../genereren-afrekenresultaat/)  
[Vaststellen kosten en opbrengsten](../vaststellen-kosten-en-opbrengsten/)  
