# Verwerken periodieke mutaties vaste activa

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=6e3&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces worden mutaties binnen de vaste activa verwerkt als onderdeel van een periode-afsluiting.

## Opvoeren nieuwe activakaarten

Wanneer de administratief eigenaar van een eenheid muteert dient de waarde van de eenheid overgeboekt te worden naar een nieuwe activum. Hiervoor dient u eerst nieuwe activa kaarten aan te maken. Het aanmaken van de nieuwe kaarten kan o.b.v. de al bestaande activa kaarten. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Vaste activa** en selecteer de hoofdkaart van het activum dat van administratief eigenaar wisselt. 
2. Kies voor de actie **Vast activum kopiëren**. Vul in het veld **Eerste VA-nr.** het nummer van het nieuwe activum in. Advies is om het oorspronkelijke nummer te gebruiken met een toevoeging, bijvoorbeeld D voor DAEB of ND voor niet-DAEB.
3. Herhaal stap 1 en 2 voor de subactivakaarten.
4. Open de oude/oorspronkelijke activakaarten en maak het veld **Eenheidnr.** leeg. Hiermee zorgt u ervoor dat alleen de nieuwe activakaarten gekoppeld zijn aan de OG Eenheid. 
5. Open de nieuwe hoofdactivakaart en pas op de afschrijvingsregels de **VA-boekingsgroep** op alle regels aan naar de nieuwe VA-boekingsgroep. Herhaal dit voor de subactivakaarten. 
6.  Nadat u de VA-boekingsgroep aangepast heeft kunt u de nieuwe subactivakaarten koppelen aan de nieuwe hoofdactivakaart. Open de hoofdactivakaart en klik op **Onderdelen van hoofdactivum**. Koppel de subactivakaarten door per subactivum een regel op te voeren en in het veld **Nr.** het nummer van de subactivakaart in te geven.

## Overboeken waarden DAEB/niet-DAEB

Nadat u de kaarten ten behoeve van de overboeking aangemaakt heeft kunt u de waarden overboeken. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofdactivakaart.
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofdactivakaart.
	-	**Afschrijvingsboek**: Kies het afschrijvingsboek voor marktwaarde. 
	-	**Herind, aanschafk.-%**: '100'.
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
2. Klik op **Herindelen**.
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **VA fin. dagboeken**. en kies voor **Boeken** om de waarden over te boeken. 
4. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke subactivakaart.
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe subactivakaart.
	-	**Afschrijvingsboek**: Kies het afschrijvingsboek voor historische kostprijs.
	-	**Herind. aanschafk.-%**: '100'.
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Afschr.**
5. Voeg een regel toe voor elke subactivakaart en klik op **Herindelen**.
6. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **VA-dagboeken** en kies voor **Boeken** om de waarden over te boeken.
7. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofdactivakaart.
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofdactivakaart .
	-	**Afschrijvingsboek**: Kies het afschrijvingsboek voor beleidswaarde.
	-	**Herind, aanschafk.-%**: '100'.
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
8. Klik op **Herindelen**.
9. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **VA-dagboeken** en kies voor **Boeken** om de waarden over te boeken.
10. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofdactivakaart.
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofdactivakaart.
	-	**Afschrijvingsboek**: Kies het afschrijvingsboek voor fiscaal.
	-	**Herind, aanschafk.-%**: '100'.
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Afschr.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
		-	**Herind. vrij 1**
		-	**Herind. vrij 2**
		-	**Herind. restwaarde**
2. Klik op **Herindelen**.
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **VA-dagboeken** en kies voor **Boeken** om de waarden over te boeken.
 
## Boeken waardemutaties

Aan het eind van ieder boekjaar dienen de waardemutaties van de marktwaarde van de vaste activa te worden geboekt.

1. De eerste stap in dit proces is het exporteren van de marktwaarde per activum uit Dynamics Empire. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **VA-posten** en stel het volgende filter in:
	- **VA-boekingsdatum**: Tot en met 31-12 van rapportagejaar, bijvoorbeeld '..31-12-2020'.
	- **Afschrijvingsboek**: Kies het afschrijvingsboek voor marktwaarden.
	- **VA-boekingssoort**: Aanschafkosten|Waarderverminderingen|Waardervermeerderingen.
2. Exporteer de gefilterde posten naar Excel en bepaal via een draaitabel de marktwaarde per vast activum. U heeft nu de marktwaarde per vast activum voor de waardemutaties. Vanuit uw taxatiemanagementapplicatie heeft u de marktwaarde per activum na waardemutaties beschikbaar. Bepaal in Excel per activum het verschil tussen de waarde in Dynamics Empire en de waarde uit u taxatiemanagementapplicatie. Dit verschil gaat u inlezen in Dynamics Empire. 
3. Open een Excel-bestand. Het bestand dat u importeert dient altijd 17 kolommen te bevatten. Hieronder wordt beschreven welke waarde u per kolom in dient te vullen als u de waardemutaties van vaste activa wilt doorvoeren.
	- **VA-nummer** (Kolom A ): Het nummer van het **hoofd-activum** waarvoor u de waardemutaties wilt doorvoeren. 
	- **Omschrijving** (Kolom B): Laat deze kolom leeg.
	- **Serienummer** (Kolom C): Laat deze kolom leeg.
	- **Onderdeel van** (Kolom D): Laat deze kolom leeg.
	- **OGE-nummer** (Kolom E): Laat deze kolom leeg.
	- **VA-categorie** (Kolom F): Laat deze kolom leeg.
	- **VA-subcategorie** (Kolom G): Laat deze kolom leeg.
	- **Globale dimensie 1** (Kolom H): Laat deze kolom leeg.
	- **Globale dimensie 2** (Kolom I): Laat deze kolom leeg.
	- **Afschrijvingsboek** (Kolom J): Vul het afschrijvingsboek voor **Marktwaarde**.
	- **VA-boekingsgroep** (Kolom K): Vul de VA-boekingsgroep voor sociaal (DAEB) of commercieel (niet-DAEB).
	- **Afschrijvingsmethode** (Kolom L): Laat deze kolom leeg.
	- **Begindatum afschrijving** (Kolom M): Laat deze kolom leeg.
	- **Aantal afschr. jaren** (Kolom N): Laat deze kolom leeg.
	- **VA-boekingssoort** (Kolom O): Vul de waarde 3 of 4 in. 3 staat gelijk aan **Waardevermindering**, 4 staat gelijk aan **Waardevermeerdering**. 
	- **Boekingsdatum** (Kolom P) : Vul de datum in waarop u de waardemutatie wilt boeken. 
	- **Bedrag** (Kolom Q): Vul de waardemutatie in. Waardeverminderingen zijn altijd negatief, waardevermeerderingen zijn altijd positief.  
 2. Wanneer u voor alle vaste activa de gegevens gevuld hebt kunt u het Excel-bestand opslaan als .csv-bestand. U dient het Excel-bestand op te slaan zonder kopregels; het bestand mag alleen regels met in te lezen waarden bevatten. 
 3.  Open Dynamics Empire en navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Vaste Activa (fin. dagboekregels) maken**. Selecteer de regel waarbij **Soort** gelijk is aan 'VA-fin. dagboek' en klik op **OK**. 
 4. Klik op de drie puntjes naast het veld **Bestandsnaam** en selecteer het .csv-bestand dat u wilt inlezen. 
 5. Vul in het veld **Tegenrekeningnr.** het nummer van de resultatenrekening waarop de waardemutaties geboekt dienen te worden. 
 6. Klik op **OK** om de waarde klaar te zetten in het VA-fin. dagboek. 
 7. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **VA fin. dagboeken**. In het dagboek staan de geïmporteerde regels klaar. Kies voor **Boeken** om de dagboekregels te boeken. 

## Afschrijven MVA t.d.v.exploitatie

Periodiek dienen de afschrijvingen op de MVA ten dienste van de exploitatie berekend en geboekt te worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Afschrijving berekenen**. Vul de volgende velden:
- **Afschrijvingsboek**: Kies het afschrijvingsboek voor historische kostprijs.
- **Boekingsdatum**: De datum tot en met wanneer afgeschreven dient te worden. 
- **Boekingsomschrijving**
- **Direct boeken**: 'Nee'.
2. Klik op **OK**. De afschrijvingsregels worden klaargezet in het VA-fin. dagboek. 
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **VA-fin. dagboeken**, controleer eventueel de regels en kies voor **Boeken**. 

## Afschrijven fiscale waarden

Periodiek dienen de afschrijvingen op de fiscale waarde berekend en geboekt te worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Afschrijving berekenen**. Vul de volgende velden:
- **Afschrijvingsboek**: Kies het afschrijvingsboek voor fiscale waarde.
- **Boekingsdatum**: De datum tot en met wanneer afgeschreven dient te worden. 
- **Boekingsomschrijving**
- **Direct boeken**: 'Nee'.
2. Klik op **OK**. De afschrijvingsregels worden klaargezet in het VA dagboek. 
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **VA-dagboeken**, controleer eventueel de regels en kies voor **Boeken**. 


## Zie ook

[Beheren vaste activa ten dienste van exploitatie](../beheren-vaste-activa-ten-dienste-van-exploitatie/)  
[Beheren vaste activa in exploitatie](../beheren-vaste-activa-in-exploitatie/)  
