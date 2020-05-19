# Vaststellen kosten en opbrengsten

In dit werkproces worden kosten en opbrengsten van service en verbruik bepaald en verrekend. De hieronder beschreven stappen worden per cluster uitgevoerd. 

## Vaststellen voorschotten

De eerste stap in het afrekenproces is het vaststellen van de voorschotten. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie/functie **Aanmaken voorschotten**. 
2. Selecteer in het scherm dat opent de batch die u wilt afrekenen in het veld **Batchnaam**. 
3. Wanneer u met clustergroepen werk selecteert u in het veld **Clustegroepfilter** de clustergroep waarvoor u de voorschotten aan wilt maken. 
4. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusterfilter** het cluster waarvoor u de voorschotten aan wilt maken. 
5. Laat de optie **Voorschotten met bedrag nul niet opnemen** uit staan.
6. Zet de optie **Voorschotten inclusief Btw-bedrag opnemen in afrekening** aan. 
7. Zet de optie **Foutenlog aanmaken** aan.
8. Klik op **OK**. Er wordt een melding gegeven hoeveel nieuwe voorschotten aangemaakt zijn. Dit aantal toont *niet* het aantal eenheden in het cluster, maar het aantal contracten waarvoor een afrekening opgesteld zal worden. 
9. U kunt een overzicht van de aangemaakte voorschotten opvragen door het rapport **Voorschotten - lijst** op te starten. 
	- Selecteer op de pagina die opent de **AfrekBatchnaam** die van toepassing is.  
	- Zet de optie **Details tonen** aan. 
	- Stel, afhankelijk van of u afrekent o.b.v. clustergroepen of niet, een filter in op  **Clustergroep** of **Clusternr.**
	- Klik op **Verzenden naar**, kies het bestandstype dat u wilt gebruiken en klik op **OK**. 

## Exporteren voorschotten t.b.v. servicebureau

Wanneer u elementen afrekent via een servicebureau, bijvoorbeeld ISTA of TECHEM, dient u de gegevens van de huurders en aangemaakte voorschotten te exporteren. Om de voorschotten t.b.v. servicebureaus te kunnen exporteren dient op het cluster aangegeven te zijn dat er afgerekend wordt door middel van een servicebureau (zie werkinstructie **[Beheren clusterinformatie](../financiën/grootboek/beheren-clusterinformatie/)**).

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie/functie **Aanmaken bestand ISTA Nederland** (dit bestand heeft weliswaar de naam ISTA in zich, maar kan ook gebruikt worden voor servicebureau TECHEM).  
2. Selecteer in het scherm dat opent in het veld **Batchnaam** de batch waarvoor u gegevens wilt exporteren.
3. Selecteer in het veld **Servicebureau** het servicebureau waarvoor u gegevens wilt exporteren.
4. Vul in het veld **Pijldatum voorschotbedrag** de datum van vandaag in. 
5. Laat de optie **SV-afrekeningen voor verkochte OGE"s uitsluiten** uit staan. 
6. Stel, afhankelijk van of u afrekent o.b.v. clustergroepen of niet, een filter in op **Clustergroep** of **Nr.** en klik op **OK**. 
7. Het bestandje wordt geëxporteerd en kan aangeleverd worden bij het servicebureau. 

## Doorgeven en markeren kosten t.b.v. servicebureau

Wanneer u elementen afrekent via een servicebureau, bijvoorbeeld ISTA of TECHEM, dient u naast de gegevens van de huurders en de in rekening gebrachte voorschotten ook de gemaakte kosten aan te leveren bij het servicebureau. Wanneer u deze kosten op kostencode en cluster geboekt heeft, kunt u via het overzicht **SV-kostenselectie** een overzicht maken van deze kosten. Daarnaast dient u in dit overzicht aan te geven dat deze kosten niet meelopen met regulier af te rekenen kosten. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-kostenselectie**. Dit overzicht toont alle nog niet verdeelde kosten. 
2. Stel een filter in op de **Afrekenbatchnaam** waarvoor u kosten wilt doorgeven. 
3. Stel een filter in op  **Clusternr.** voor het cluster waarvoor u kosten wilt doorgeven. De pagina toont alle kosten die voor deze afrekenbatch voor dit cluster nog afgerekend moeten worden. Mist u kosten of staan kosten onterecht in dit overzicht, dan kunt u in de processtap **[Beoordelen kosten](#beoordelen-kosten)** zien hoe u kosten corrigeert of toekent aan andere afrekenbatches.
4. Voor alle kosten die verdeeld worden door een servicebureau dient u aan te geven dat deze niet meegenomen dienen te worden in de reguliere kostentoerekening. Dit doet u door veld **Niet verder verdelen** op de desbetreffende regel aan te vinken. Het veld **Afrekenbatchnaam** wordt automatisch leeggemaakt.
5. U kunt het overzicht met kosten exporteren naar Excel (via opties **Openen/Bewerken in Excel**) en daar bewerken, zodat u het op kunt sturen naar het servicebureau. 
6. U kunt ook een overzicht van de benodigde kostennota's genereren door te klikken op **Overzicht kostennota's**. Vul op de pagina die verschijnt de volgende velden:
	- **Details verdeling**: 'Aan'.
	- **Nieuwe pagina per cluster**: 'Aan'.
	- **Clusternummer**
	- **Kostencode**: Vul hier in voor welke kostencodes u de kosten wilt rapporteren. 
	- Klik op **Verzenden naar**, kies het bestandstype dat u wilt gebruiken en klik op **OK**. 
7. U heeft nu een overzicht dat u kunt gebruiken als basis voor het aanleveren van de door het servicebureau te verdelen kosten.

## Importeren kostenverdeling servicebureau

Nadat het servicebureau de door u aangeleverde kosten heeft verdeeld kunt u deze kosten inlezen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie/functie **Inlezen bestand ISTA Nederland**. 
2. Selecteer in het scherm dat opent in het veld **Batchnaam** de batch waarvoor u gegevens wilt inlezen.
3. Selecteer in het veld **Servicebureau** het servicebureau waarvoor u gegevens wilt inlezen.
4. Laat de opties **Nieuw voorschot overnemen** en **Test bestand** uit staan. 
5. Klik op **OK** en klik op **Kiezen**. 
6. Selecteer het bestand dat u in wilt lezen en klik op **Openen**. 
7. Het programma toont het aantal records dat verwerkt is. De kostenverdeling voor de kosten verdeeld door het servicebureau zijn nu ingelezen. 

## Beheren verdeelsleutels

Voordat u kosten gaat verdelen dienen de verdeelsleutels voor de kosten goed ingesteld te worden. De verdeelsleutels stelt u in op de elementen die gekoppeld zijn aan de kostencode. In de werkinstructie **[Beheren clusterinformatie](../financiën/grootboek/beheren-clusterinformatie/)** vindt u hoe u deze elementen beheert.

## Beoordelen kosten

Voordat u de kosten voor de afrekening kunt verdelen dient u de te verdelen kosten te beoordelen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-kostenselectie**. Dit overzicht toont alle nog niet verdeelde kosten. 
2. Stel een filter in op **Clusternr.** voor het cluster waarvoor u kosten wilt verdelen. De pagina toont alle kosten die voor deze afrekenbatch voor dit cluster nog afgerekend moeten worden. 
3. De kolom **Afrekenbatchnaam** geeft aan aan welke afrekenperiode kosten toegerekend zullen worden. Wanneer er kosten toegekend zijn aan een verkeerde afrekenbatch kunt u de waarde in deze kolom aanpassen. 

> **Let op!** Voor kosten die afgerekend worden via een servicebureau (ISTA/TECHEM) geldt dat het veld **Afrekenbatchnaam** altijd leeg moet zijn. 

4. Wanneer kosten in geen enkele afrekening meegenomen dienen te worden kunt u dit aangeven. Dit doet u door veld **Niet verder verdelen** op de desbetreffende regel aan te vinken. Het veld **Afrekenbatchnaam** wordt automatisch leeg gemaakt.
5. Klik op **Kostencodeposten** om te zien welke kosten in voorgaande periode afgerekend zijn. Dit kan helpen bij het beoordelen van de kosten van de nog af te rekenen perioden.
6. Wanneer er kosten ontbreken of op een verkeerd cluster geboekt zijn kunt u kosten corrigeren met behulp van memoriaalboekingen **[Boeken memoriaal](../boeken-memoriaal/)**. 
7. U kunt een overzicht van  kostennota's genereren door te kiezen voor optie **Overzicht kostennota's**. Vul op de pagina die opent de volgende velden:
	- **Details verdeling**: 'Aan'.
	- **Nieuwe pagina per cluster**: 'Aan'.
	- **Clusternummer**
	- **Afrekenbatchnaam**
	- Klik op **Verzenden naar**, kies het bestandstype dat u wilt gebruiken en klik op **OK**. 

## Boeken memoriaal

Wanneer u service- en verbruikskosten wilt corrigeren kunt u dit doen via het reguliere memoriaal (zie **[Boeken memoriaal](../boeken-memoriaal/)**). 

## Verdelen kosten

Nadat alle kosten in het overzicht **SV-kostenselectie** toegewezen zijn aan de juiste afrekenbatch kunnen de kosten verdeeld worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie/functie **Verdelen kostencodes**. 
2. Selecteer in het scherm dat opent in het veld **Batchnaam** de batch waarvoor u de kosten wilt verdelen. 
3. Wanneer u met clustergroepen werkt selecteert u in het veld **Clustergroepfilter** de clustergroep waarvoor u de kosten wilt verdelen. 
4. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusterfilter** het cluster waarvoor u de kosten wilt verdelen. 
5. Kies in het veld **Verdelen over** voor 'Afrekenperiode'.
6. Laat de optie **Verkochte OGE's uitsluiten** uit staan.
7. Zet de optie **Foutenlog aanmaken** aan.
8. Klik op **OK** om de kosten te verdelen. 

## Beoordelen kostenverdeling

Voordat u de afrekening definitief boekt kunt u de kostenverdeling (laten) beoordelen. Dat kan het best gedaan worden via het rapport **SV saldi lijst**.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor het rapport **SV Saldilijst**. 
2. Selecteer in het scherm dat opent in het veld **Afrekeningsbatchnaam** de batch waarvoor u de kostenverdeling wilt beoordelen. 
3. Zet de optie **Details tonen** aan. 
4. Wanneer u met clustergroepen werkt selecteert u in het veld **Clustergroep** de clustergroep waarvoor u de kostenverdeling wilt beoordelen. 
5. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusternr.** het cluster waarvoor u de kostenverdeling wilt beoordelen. 
6. Klik op **Verzenden naar**, kies het bestandstype dat u wilt gebruiken en klik op **OK**. 
7. Het rapport toont per OGE, per klant, per element de volgende gegevens:
	- Voorschotten
	- Toegerekende kosten
	- Eventuele voorschotten vanuit leegstand
	- Nog te betalen bedrag
	- Nog te ontvangen bedrag
	- Toe te rekenen derving
8. Onderaan het rapport wordt een samenvatting van deze gegevens weergegeven, gegroepeerd per cluster.

## Verwijderen afrekening

Wanneer u in één van de voorgaande stappen erachter bent gekomen dat er ergens iets verkeerd is gegaan, kunt u nog niet geboekte afrekeningen eenvoudig verwijderen en opnieuw opbouwen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Verwijderen SV-afrekeningen**. 
2. Selecteer in het scherm dat opent in het veld **Afrekenbatchnaam** de batch waarvoor u de afrekeningen wilt verwijderen. 
3. Wanneer u met clustergroepen werkt selecteert u in het veld **Clustergroepfilter** de clustergroep waarvoor u de afrekeningen wilt verwijderen. 
4. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusterfilter** het cluster waarvoor u de afrekeningen wilt verwijderen.
5. Laat de optie **Geboekte afrekeningen verwijderen** uit staan. 
6. Klik op **OK**.
7. U kunt de afrekening nu opnieuw opbouwen vanaf processtap **[Vaststellen voorschotten](#vaststellen-voorschotten)**. 

## Accorderen afrekening

Wanneer de kostenverdeling juist is en u heeft ingesteld dat afrekeningen gefiatteerd dienen te worden voordat ze geboekt kunnen worden, kunt u de beoordeelde afrekeningen accorderen. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie/functie **Instellen status en fiatteren**. 
2. Laat het veld **Status** leeg. 
3. Zet de optie **Fiat** aan. 
4. Wanneer u met clustergroepen werkt selecteert u in het veld **Clustergroep** de clustergroep waarvoor u de afrekeningen wilt fiatteren.
5. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusternr.** het cluster waarvoor u de afrekeningen wilt fiatteren.
6. Klik op **OK**.

## Boeken afrekening

Nadat de verdeling van de kosten beoordeeld en goed bevonden is en wanneer de afrekening (wanneer nodig) geaccordeerd is kunnen de afrekeningen geboekt worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **SV-afrekeningoverzicht**. Kies voor de actie **Boeken**. 
2. Selecteer in het scherm dat opent in het veld **Batchnaam** de batch waarvoor u de afrekeningen wilt boeken. 
3. Vul in het veld **Boekingsdatum** de boekingsdatum waarop u de afrekening wilt boeken.
4. Vul in het veld **Documentdatum** de boekingsdatum waarop u de afrekening wilt boeken.
5. Zet de optie **Direct boeken** aan. 
6. Wanneer u met clustergroepen werkt selecteert u in het veld **Clustegroep** de clustergroep waarvoor u de afrekeningen wilt boeken.
7. Wanneer u niet met clustergroepen werkt selecteert u in het veld **Clusternr.** het cluster waarvoor u de afrekeningen wilt boeken.
8. Pas de overige velden niet aan.
9. Klik op **OK**. U krijgt een aantal vragen die u dient te beantwoorden, hierna worden de afrekeningen geboekt. 

## Zie ook

[Bepalen nieuwe voorschotten](../bepalen-nieuwe-voorschotten/)  
[Genereren afrekenresultaat](../genereren-afrekenresultaat/)
