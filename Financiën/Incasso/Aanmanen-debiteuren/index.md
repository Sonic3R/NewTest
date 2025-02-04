# Aanmanen debiteuren

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=6h2&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces worden betalingsachterstanden gesignaleerd en wordt de debiteur op basis van de segmentatie en de duur van de achterstand gemaand om de achterstand te betalen.

## Voorstellen aanmaningen

In deze stap wordt een voorstel gemaakt voor welke klanten aangemaand worden.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Aanmaningen**.
2. Klik op de pagina **Aanmaningen** op de actie **Aanmaningen maken**. Vul op de zojuist geopende pagina de volgende velden met de aangegeven waarden:
	* **Boekingsdatum:** Alle posten die voor deze datum vervallen zijn worden meegenomen in het aanmangsvoorstel.
	* **Documentdatum:** Dit is de datum die op het aanmaningsdocument voor de debiteur getoond wordt.
	* **Alleen vervallen posten:** 'Aan'.
	* **Wachtende posten opnemen:** 'Uit'.
	* **Kopniveau gebruiken:** 'Uit'.
	* **Code:** Selecteer de transactiewijze voor automatisch uitbetalen van leveranciersposten.
	* Stel onder het **Klantfilter** een filter in op het veld **Aanmaningsconditiecode** (klik hiertoe op **+ Filteren...**) en selecteer de aanmaningsconditie die u aan wilt aanmanen.
3. Klik op **OK**. De aanmaningsvoorstellen worden aangemaakt.  U keert terug naar de pagina **Aanmaningen**.

## Opschonen voorstel

Nadat de voorstellen gegenereerd zijn kunt u deze opschonen en controleren.

1. U verstuurt de aanmaningen per aanmaningsniveau. De aanmaningsvoorstellen die niet van het niveau zijn dat u op dit moment wilt aanmanen, dient u te verwijderen. Stel op de pagina **Aanmaningen** een filter in (via ![filter icon](/assets/images/filter.png "filter icon") rechtsboven in het scherm, gevolgd door een klik op **+ Filteren...**)  op het veld **Aanmaningsniveau** en wel zodanig dat alle aanmaningen die niet van het niveau zijn dat u aan wilt manen, getoond worden binnen het filter. Wilt u bijvoorbeeld niveau 1 versturen, dan stelt u het filter in het veld **Aanmaningsniveau** als volgt in: '<>1' (ongelijk aan 1).
2. Selecteer alle aanmaningsvoorstellen; klik daartoe eerst op de drie verticaal geplaatste puntjes achter een willekeurig aanmaningsnummer (*Meer opties weergeven*), kies voor *Meer selecteren* en selecteer alle regels. Klik op **Verwijderen**. Er wordt nu een lege lijst getoond.
3. Verwijder het ingestelde filter (klik op kruisje), en de aanmaningen van het niveau dat u wilt versturen worden getoond.
4. Wanneer de overgebleven aanmaningen betrekking hebben op een aanmaningsconditie voor betalingsregelingen, en het aanmaningsniveau betekent dat de betalingsregeling vervalt, ga dan verder naar de processtap **[Verwerken aanmaningen beëindigde betalingsregeling](#verwerken-aanmaningen-beëindigde-betalingsregeling)**.
5. In alle andere gevallen gaat u door naar de processtap **[Controleren voorstellen en aanpassen individuele aanmaning](#controleren-voorstellen-en-aanpassen-individuele-aanmaning)**.

## Verwerken aanmaningen beëindigde betalingsregeling

U heeft een separate aanmaningsconditie voor betalingsregelingen ingesteld. Wanneer de debiteur zijn betalingsregeling niet voldoet vervalt de betalingsregeling en wordt de debiteur gemaand de gehele oorspronkelijke vordering te voldoen. Hiervoor dient de betalingsregeling beëindigd te worden en de aanmaning dient opnieuw gegenereerd te worden.

1. In de processtap **[Opschonen voorstel](#opschonen-voorstel)** heeft u een lijst gecreëerd met aanmaningen voor debiteuren waarvoor de betalingsregeling beëindigd dient te worden. Open de eerste aanmaning uit deze lijst waarna de pagina **Aanmaning** opent.
2. Selecteer in het feitenblok **Klantinformatie**, rechts in het scherm, de waarde achter het veld **Betalingsregeling actief**. De pagina **Betalingsregelingoverzicht** opent. Deze pagina toont de actieve betalingsregelingen voor de debiteur.
3. Klik op **Beëindigen**. U krijgt de vraag of u zeker weet of u de regeling wilt beëindigen. Klik op **Ja**. 
4. De pagina **Beëindigingscodes betalingsregeling** opent. Selecteer de beëindigingsreden die van toepassing is en klik op **OK**. De betalingsregeling is nu beëindigd.
5. U keert terug naar de pagina **Beëindigingscodes betalingsregeling**. Klik op **Sluiten**. U keert terug naar de pagina **Aanmaning**.
6. Herhaal stap 2 tot en met 5 voor alle aanmaningsvoorstellen. U navigeert eenvoudig naar de volgende aanmaning door op de pagina **Aanmaning** op het pijltje naar rechts te klikken.
7. Nadat u alle betalingsregelingen beëindigd hebt sluit u de pagina; u keert terug naar de pagina **Aanmaningen**. Selecteer alle aanmaningen in de lijst.
8. Klik op **Aanmaningsregels voorstellen**, waarna de gelijknamige pagina wordt geopend. Klik op **OK**. De oorspronkelijke vordering wordt nu opgenomen in de aanmaningsvoorstellen en u keert terug naar pagina **Aanmaningen**.
9. Selecteer opnieuw alle aanmaningen en klik op **Aanmaningstekst bijwerken**. Vul op de nu geopende pagina de volgende velden met de aangegeven waarden:
	* **Aanmaningsniveau:** Geef het aanmaningsniveau voor vervallen betalingsregelingen op.
	* **Aanvullende kosten aanpassen:** 'Aan'.
	* **Aanmaningsniveau bijwerken:** 'Aan'.
10. Klik op **OK**. De test van de aanmaning wordt nu bijgewerkt o.b.v. de bedragen uit de oorspronkelijke vorderingen. U keert terug naar de pagina **Aanmaningen**. De aanmaningsvoorstellen voor betalingsregelingen zijn klaar om verstuurd te worden. U kunt voor de zekerheid de voorstellen nog een keer controleren. Ga verder naar de processtap **[Controleren voorstellen en aanpassen individuele aanmaning](#controleren-voorstellen-en-aanpassen-individuele-aanmaning)**.

## Controleren voorstellen en aanpassen individuele aanmaning

Na het verwijderen van de overbodige voorstelregels of het bijwerken van de aanmaningen voor beëindigde betalingsregelingen kunt u de aanmaningsvoorstellen controleren en desgewenst aanpassen. Deze stap is niet verplicht. U kunt ook direct doorgaan naar de volgende processtap **[Definitief maken aanmaningen](#definitief-maken-aanmaningen)**.

1. Vanaf de pagina **Aanmaningen** kunt u een individuele aanmaning openen door op het nummer van de aanmaning te klikken. De pagina **Aanmaning** opent.
2. Wilt u de tekst van een individuele aanmaning aanpassen, dan kan dit door in de **Aanmaningsregels** de tekst aan te passen.
3. Wilt u dat de klant niet aangemaand wordt in deze ronde, dan kunt u een individuele aanmaning verwijderen door op **Verwijderen** te klikken (prullenbak-icoontje bovenop de pagina). U wordt gevraagd de verwijdering te bevestigen. U keert terug naar de pagina **Aanmaningen.**

## Definitief maken aanmaningen

Nadat u de aanmaningen al dan niet gecontroleerd en aangepast heeft kunt u de aanmaningsvoorstellen definitief maken.

1. Selecteer op de pagina **Aanmaningen** alle aanmaningsvoorstellen. (Klik daartoe eerst op de drie verticaal geplaatste puntjes achter een willekeurig aanmaningsnummer (*Meer opties weergeven*), kies voor *Meer selecteren* en selecteer alle regels.)
2. Klik op **Verzenden**. De pagina **Aanmaningen verzenden** opent. Klik op **OK**. De aanmaningsvoorstellen worden definitief gemaakt en worden verplaatst naar de pagina **Verzonden aanmaningen**.
3. Moeten de aanmaningen die u definitief gemaakt heeft verzonden worden, ga dan verder met processtap **[Versturen aanmaning](#versturen-aanmaning)**.
4. Waren de aanmaningen die u definitief gemaakt heeft van het niveau Deurwaarder, ga dan verder met het werkproces **[Uit-handen-geven-vorderingen](../uit-handen-geven-vorderingen/)**.

## Versturen aanmaning

Nadat de aanmaningsvoorstellen definitief gemaakt zijn kunt u de aanmaningen versturen via Postex.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verzonden aanmaningen**.
2. Stel een filter in voor de aanmaningen die u wilt verzenden (via ![filter icon](/assets/images/filter.png "filter icon") rechtsboven in het scherm, gevolgd door een klik op **+ Filteren...**):
	* **Aanmaningsconditiecode:** De aanmaningsconditie waarvoor u documenten wilt verzenden.
	* **Aanmaningsniveau:** Het aanmaningsniveau waarvoor u documenten wilt verzenden.
	* **Documentdatum:** De documentdatum van de documenten die u wilt verzenden.
3. Selecteer alle aanmaningen in de gefilterde lijst en klik op **Postex**. De pagina **Aanmaningen** opent. Selecteer **Afdrukken**. De aanmaningen worden via Postex verstuurd.

## Genereren overige communicatie

Naast dat u de aanmaningen kunt versturen kunt u het overzicht van aanmaningen ook filteren en openen in Excel om vervolgacties buiten Dynamics Empire uit te voeren, zoals het opstellen van bellijsten of het aanleveren van bestanden voor sms-acties.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verzonden aanmaningen**.
2. Stel een filter in (via ![filter icon](/assets/images/filter.png "filter icon") rechtsboven in het scherm, gevolgd door een klik op **+ Filteren...**) voor de aanmaningen die u wilt exporteren:
	* **Aanmaningsconditiecode:** De aanmaningsconditie waarvoor u documenten wilt verzenden.
	* **Aanmaningsniveau:** Het aanmaningsniveau waarvoor u documenten wilt verzenden.
	* **Documentdatum:** De documentdatum van de documenten die u wilt verzenden.
3. Klik op **Openen in Excel**. De tabel wordt geopend in Excel.

## Zie ook

[Afboeken vorderingen](../afboeken-vorderingen/)  
[Afsluiten betalingsregeling](../afsluiten-etalingsregeling/)  
[Beëindigen betalingsregeling](../beeindigen-betalingsregeling/)  
[Segmenteren debiteuren](../segmenteren-debiteuren/)  
[Terugboeken vorderingen](../terugboeken-vorderingen/)
[Uit handen geven vorderingen](../uit-handen-geven-vorderingen/)  
[Verwerken WSNP/minnelijk traject](../verwerken-wsnp-minnelijk-traject/)  
