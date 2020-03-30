# Afsluiten jaar

In dit werkproces worden alle balansmutaties verwerkt en wordt de winst- en verliesrekening afgesloten.

## Jaar afsluiten

De boekingsperiode van het afgelopen jaar wordt afgesloten, zodat boekingen die hierna nog worden gemaakt in het afgelopen jaar worden gekenmerkt.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Boekingsperioden**. Kies voor de actie **Jaar afsluiten**.
2. Maak indien nodig alvast een nieuw boekjaar aan door op **Nieuw jaar** te klikken. Vul de volgende velden op de pagina die opent:
	- **Begindatum**
	- **Aantal perioden**: 12
	- **Periode lengte**: 1M
3. Klik op **OK**.

## Instellen grootboek t.b.v. afsluitboekingen

Voordat de eindejaarsboekingen gemaakt kunnen worden dient eerst het grootboek ingesteld te worden voor deze boekingen. Advies is om deze handelingen uit te voeren na reguliere kantooruren. In deze processtap worden namelijk de dimensieverplichtingen van het grootboek afgehaald en worden de vinkjes m.b.t. direct boeken op grootboekrekeningen aangepast.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Configuratiepakketten** en selecteer het pakket dat betrekking heeft op de jaarafsluiting. Open dit pakket. Dit pakket bevat twee tabellen:
	- Tabel Nr. 15: Grootboekrekeningen
	- Tabel Nr. 352: Standaard dimensies
2. Kies voor de actie **Pakket exporteren** en sla het pakket op. Dit pakket bevat de inrichting van de twee tabellen op dit moment. Dit pakket kunt u later gebruiken om de inrichting terug te zetten.
3. Kies voor **Naar Excel exporteren** en sla het geëxporteerde bestand op.
4. Open het geëxporteerde Excel bestand:
	- Zet op het tabblad **Grootboekrekening** de kolom **Direct boeken** op **Waar**.
	- Maak op het tabblad **Standaard dimensie** de kolommen **Dimensiewaarde code**, **Waardeboeking** en **Meervoudige-selectie actie** leeg.
	- Sla het Excel-bestand op.
5. Ga terug naar het RapidStart-pakket en klik op **Vanuit Excel importeren**. Klik in het scherm dat opent op **Import**.
6. Klik vervolgens op **Pakket toepassen** om de geïmporteerde inrichting toe te passen.

## Boeken naar beginbalansrekeningen

De eerste stap in het boeken van de jaarafsluiting is het boeken naar de beginbalansrekeningen t.b.v. het RGS. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Periodieke daboeken**. Selecteer in het scherm dat opent in het veld **Batchnaam** de batch voor het boeken van de beginbalans.
2. Controleer de **Boekingsdatum** van de regels; deze zou op 31-12 van het af te sluiten jaar moeten staan. Pas dit indien nodig aan.
3. Klik op **Boeken** om de boekingen uit te voeren.

## Afsluiten winst- en verliesrekening

Nadat de beginbalansboekingen gemaakt zijn kan de Winst- en Verliesrekening afgesloten worden.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Afsluiten WenV-rekening**. Vul in de pagina die opent de volgende velden:
	- **Einddatum boekjaar**
	- **Fin. dagboeksjabloon** (het dagboek dat u wilt gebruiken voor deze boeking)
	- **Fin. dagboekbatch** (de dagboekbatch die u wilt gebruiken voor deze boeking)
	- **Documentnummer**
	- **Resultaat lopend boekjaar** (de rekening waarop u het resultaat wilt boeken)
	- **Boekingsomschrijving**
2. Klik op **OK**. De regels worden klaargezet in het dagboek dat u opgegeven hebt.
3. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Diversendagboek** en selecteer het dagboek waarin u de regels klaargezet heeft. Selecteer indien nodig de juiste batch in het veld **Batchnaam**.
4. Klik op **Boeken** om de winst- en verliesrekening te boeken.

## Terugzetten grootboekinstellingen

Nadat u de boekingen t.b.v. de jaarafsluiting verwerkt heeft dient u de instellingen die u in de eerste stap aangepast heeft, terug te zetten.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Configuratiepakketten** en klik op  **Pakket importeren**.
2. Open het pakket en klik op **Pakket toepassen**. De instellingen worden teruggezet.

## Zie ook

[Beheren dimensies](../beheren-dimensies/)  
[Boeken memoriaal](../boeken-memoriaal/)  
[Boeken periodiek memoriaal](../boeken-periodiek-memoriaal/)  
[Verdelen posten naar eenheidsniveau](../verdelen-posten-naar-eenheidsniveau/)  
[Overboeken categoriaal naar functioneel](../overboeken-categoriaal-naar-functioneel/)  
[Verwerken DAEB/niet-DAEB-verdeling](../verwerken-daeb-niet-daeb-verdeling/)  
[Beheren clusterinformatie](../beheren-clusterinformatie/)  
[Vereffenen grootboekposten](../vereffenen-grootboekposten/)  
[Dichtzetten periode](../dichtzetten-periode/)
