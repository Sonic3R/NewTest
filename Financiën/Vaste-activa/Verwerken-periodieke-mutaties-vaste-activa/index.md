# Verwerken periodieke mutaties vaste activa

In dit werkproces worden mutaties binnen de vaste activa verwerkt als onderdeel van een periode-afsluiting.

## Opvoeren nieuwe activakaarten

Wanneer de administratief eigenaar van een eenheid muteert dient de waarde van de eenheid overgeboekt te worden naar een nieuwe activum. Hiervoor dient u eerst nieuwe activa kaarten aan te maken. Het aanmaken van de nieuwe kaarten kan o.b.v. de al bestaande activa kaarten. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Vaste Activa** en Selecteer de hoofdkaart van het activum wat van administratief eigenaar wisselt. 
2. Klik op **Vast activum kopiëren**. Vul in het veld **Eerste VA-nr.** het nummer van het nieuwe activum in. Advies is om het oorspronkelijke nummer te gebruiken met een toevoeging. Bijvoorbeeld D voor DAEB of ND voon niet-DAEB. 
3. Herhaal stap 1 en 2 voor de sub-activa kaarten. 
4. Open de oude/oorspronkelijke activa kaarten en maak het veld **Eenheidnr.** leeg. Hiermee zorgt u er voor dat alleen de nieuwe activa kaarten gekoppeld zijn aan de Onroerend goed eenheid. 
5. Open de nieuwe hoofd activa kaart en pas op de afschrijvingsregels de **VA-boekingsgroep** op alle regels aan naar de nieuwe VA-boekingsgroep. Herhaal dit voor de sub-activa kaarten. 
6.  Nadat u de VA-boekingsgroep aangepast heeft kunt u de nieuwe sub activa kaarten koppelen aan de nieuwe hoofd activa kaart. Open de hoofd activa kaart en klik op **Onderdelen van hoofdactivum**. Koppel de sub-activa kaarten door per sub-activum een regel op te voeren en in het veld **Nr.** het nummer van de sub-activa kaart in te geven.

## Overboeken waarden DAEB/niet DAEB

Nadat u de kaarten ten behoeven van de overboeking aangemaakt heeft kunt u de waarden overboeken. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofd activa kaart
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofd activa kaart 
	-	**Afschrijvingsboek**: Afschrijvingsboek marktwaarde. 
	-	**Herind, aanschafk.-%**: 100
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
2. Klik op **Herindelen. **
3. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA fin. dagboeken**. en klik op **Boeken** om de waarden over te boeken. 
4. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke bub-activa kaart
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe sub-activa kaart 
	-	**Afschrijvingsboek**: Afschrijvingsboek historische kostprijs
	-	**Herind, aanschafk.-%**: 100
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Afschr.**
5. Voeg een regel toe voor elke sub-activa kaart en klik op **Herindelen. **
6. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA-dagboeken**. en klik op **Boeken** om de waarden over te boeken
7. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofd activa kaart
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofd activa kaart 
	-	**Afschrijvingsboek**: Afschrijvingsboek beleidswaarde
	-	**Herind, aanschafk.-%**: 100
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
8. Klik op **Herindelen. **
9. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")naar **VA-dagboeken**. en klik op **Boeken** om de waarden over te boeken
10. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Herindelingsdagboeken van vaste activa**. Vul de volgende velden:
	-	**VA-boekingsdatum**
	-	**VA-nr.**: Het nummer van de oorspronkelijke hoofd activa kaart
	-	**Nieuwe VA-nr.**: Het nummer van de nieuwe hoofd activa kaart 
	-	**Afschrijvingsboek**: Afschrijvingsboek fiscaal
	-	**Herind, aanschafk.-%**: 100
	-	Zet de volgende vinkjes op **Ja**:
		-	**Herind. Aanschfk.**
		-	**Herind. Afschr.**
		-	**Herind. Waardevermindering**
		-	**Herind. Waardevermeerdering** 
		-	**Herind. vrij 1**
		-	**Herind. vrij 2**
		-	**Herind. restwaarde**
2. Klik op **Herindelen. **
3. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen")naar **VA-dagboeken**. en klik op **Boeken** om de waarden over te boeken
 
## Boeken waardemutaties

Aan het eind van ieder boekjaar dienen de waardemutaties van de marktwaarde van de vaste activa te boeken. Dit doet u doodmiddel van het inlezen van het verschil tussen de marktwaarde aan het eind van het jaar uit Dynamics Empire te halen. De marktwaard uit u taxatie management applicatie te exporteren, en het verschil tussen deze nieuwe waarden opnieuw in te lezen. 

1. De eerste stap in dit proces is het Exporteren van de marktwaarde per activum uit Dynamics Empire. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA-posten**. en stel het volgende filter in:
	- **VA-boekingsdatum**: tot en met 31-12 van rapportage jaar. Bijvoorbeeld ..31-12-2020
	- **Afschrijvingsboek**: Afschrijvingsboek voor marktwaarden
	- **VA-boekingssoort**: Aanschafkosten|Waarderverminderingen|Waardervermeerderingen
2. Exporteer de gefilterde posten naar Excel en bepaal via een draaitabel de marktwaarde per vast activum. U heeft nu de marktwaarde per vast activum voor de waardemutaties. Vanuit u taxatiemanagement applicatie heeft u de marktwaarde per activum na waarde mutaties beschikbaar. Bepaal in Excel per activum het verschil tussen de waarde in Dynamics Empire en de waarde uit u taxatie management applicatie. Dit verschil gaat u inlezen in Dynamics Empire. 
1. Open een Excel bestand. Het bestand wat u importeert dient altijd 17 kolommen te bevatten. Hieronder wordt beschreven welke waarde u per kolom in dient te vullen indien u de waardemutaties van vaste activa wilt doorvoeren.
	- **Va-nummer** (Kolom A ): Het nummer van het **hoofd-activum** waarvoor u de de waardemutaties wilt doorvoeren. 
	- **Omschrijving** (Kolom B): Laat deze kolom leeg.
	- **Serienummer** (Kolom C): Laat deze kolom leeg.
	- **Onderdeel van** (Kolom D): Laat deze kolom leeg.
	- **OGE-nummer** (Kolom E): Laat deze kolom leeg.
	- **VA-categorie** (Kolom F): Laat deze kolom leeg.
	- **VA-subcategorie** (Kolom G): Laat deze kolom leeg.
	- **Globale dimensie 1** (Kolom H): Laat deze kolom leeg.
	- **Globale dimensie 2** (Kolom I): Laat deze kolom leeg.
	- **Afschrijvingsboek** (Kolom J): Vul het afschrijvingsboek voor **Marktwaarde.**
	- **VA-boekingsgroep** (Kolom K): Vul de VA-boekingsgroep voor sociaal (DAEB) of commercieel (niet_DAEB)
	- **Afschrijvingsmethode** (Kolom L): Laat deze kolom leeg.
	- **Begindatum afschrijving** (Kolom M): Laat deze kolom leeg.
	- **Aantal afschr. jaren** (Kolom N): Laat deze kolom leeg.
	- **VA-boekingssoort** (Kolom O): Vul de waarde 3 of 4 in. 3 Staat gelijk aan **Waardevermindering**, 4 staat gelijk aan waarde vermeerdering 
	- **Boekingsdatum** (Kolom P) : Vul de datum waarop u de waardemutatie wilt boeken. 
	- **Bedrag** (Kolom Q): Vul waarde waarde mutatie in. Waardeverminderingen zijn altijd negatief. Waardevermeerderingen zijn altijd positief.  
 2. Wanneer u voor alle vaste activa de gegevens gevuld hebt kunt u het Excel Bestand opslaan als .csv bestand. U dient het Excel bestand op te slaan zonder kop regels. Het bestand mag alleen regels met in te lezen waarden bevatten. 
 3.  Open Dynamics empire en Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Vaste Activa (fin. dagboekregels) maken**. Selecteer regel waarbij soort gelijk is aan VA-fin. dagboek en klik op **OK**. 
 4. Klik op de drie puntjes naast het veld **Bestandsnaam** en selecteer het . csv bestand dat u in wilt lezen. 
 5. Vul in het veld **Tegenrekningnr.** het nummer van de resultatenrekening waarop de waardemutaties geboekt dienen te worden. 
 6. Klik op **OK** om de waarde klaar te zetten in het VA-fin. dagboek. 
 7. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA fin. dagboeken**. In het dagboek staan de geïmporteerde regels klaar. Klik op **Boeken** om de dagboekregels te boeken. 

## Afschrijven MVA t.d.v.exploitatie

Periodiek dienen de afschrijvingen op de MVA ten dienste van de exploitatie berekend en geboekt worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Afschrijving berekenen**. Vul de volgende velden:
- **Afschrijvingsboek**: Afschrijvingsboek voor historische kostprijs
- **Boekingsdatum**: De datum tot en met wanneer afgeschreven dient te worden. 
- **Boekingsomschrijving**
- **Direct boeken**: Nee
2. Klik op **OK**. De afschrijvingsregels worden klaargezet in het VA-fin. dagboek. 
3. Navigeer u via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA-fin. dagboeken**, controleer eventueel de regels en klik op **Boeken**. 

## Afschrijven fiscale waarden

Periodiek dienen de afschrijvingen op de fiscale waarde berekend en geboekt worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Afschrijving berekenen**. Vul de volgende velden:
- **Afschrijvingsboek**: Afschrijvingsboek voor fiscale waarde
- **Boekingsdatum**: De datum tot en met wanneer afgeschreven dient te worden. 
- **Boekingsomschrijving**
- **Direct boeken**: Nee
2. Klik op **OK**. De afschrijvingsregels worden klaargezet in het VA dagboek. 
3. Navigeer u via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **VA-dagboeken**, controleer eventueel de regels en klik op **Boeken**. 


## Zie ook

[Beheren vaste activa ten dienste van exploitatie](../beheren-vaste-activa-ten-dienste-van-exploitatie/)  
[Beheren vaste activa in exploitatie](../beheren-vaste-activa-in-exploitatie/)  
