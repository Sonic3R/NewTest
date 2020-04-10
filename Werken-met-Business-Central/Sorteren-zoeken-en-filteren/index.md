# Sorteren, zoeken en filteren

Er zijn verschillende manieren in Dynamics Empire om een reeks met records in te perken tot exact die gegevens die voor u van belang zijn. Dit geldt zowel voor lijstpagina’s als voor rapporten en XMLports. U kunt de records bijvoorbeeld (door)zoeken, sorteren en filteren, of u kunt een combinatie van deze methoden toepassen.

Voor rapporten en XMLports kunt u filters instellen zoals in lijsten om af te bakenen welke gegevens in het rapport of XMLport moeten worden opgenomen, maar u kunt niet sorteren en zoeken.

> [!TIP]
> Wanneer u uw gegevens weergeeft als tegels, kunt u zoeken en elementaire filtering gebruiken. Als u de volledige set functies wilt gebruiken voor sorteren, zoeken en filteren, kiest u het pictogram ![lijst icon](/assets/images/lijst.png "lijst icon") om de records als lijst weer te geven.

## Sorteren

Met de sorteerfunctie krijgt u snel een overzicht van de gegevens op het scherm. U kunt er bijvoorbeeld voor kiezen om in het **Onr. Goed-Eenhedenoverzicht** alle eenheden te sorteren op **Straatnaam**, **Status**, **Type** of **Clustercode**.

Als u een lijst wilt sorteren, kunt u op de kolomkoptekst klikken om te schakelen tussen op- en aflopend, of de pijl-omlaag in de kolomkop kiezen en vervolgens de actie **Oplopend** of **Aflopend** kiezen.  

> [!NOTE]  
> Sorteren wordt niet ondersteund bij afbeeldingen, BLOB-velden, FlowFilters en velden die niet deel van een tabel zijn.  

## Zoeken

Boven aan elke lijstpagina staat een actie ![lijst zoeken icon](/assets/images/lijst-zoeken.png "lijst zoeken icon") **Zoeken** waarmee u snel en makkelijk de records in een lijst kunt beperken tot de gegevens die u wilt zien.

Als u wilt zoeken, kiest u de actie Zoeken en typt u in het zoekveld de tekst die u zoekt. U kunt letters, cijfers en andere symbolen invoeren. Zodra u begint met typen geeft Dynamics Empire vanzelf, op basis van herkenning, resultaten weer die aan de getypte tekst voldoen. Hoe meer letters u opgeeft, hoe specifieker het zoekresultaat zal zijn. Over het algemeen wordt geprobeerd in alle velden tekst overeen te laten komen. Er wordt geen onderscheid gemaakt tussen hoofdletters en kleine letters (hoofdletterongevoelig), en er wordt gezocht naar overeenkomst met tekst die ergens in het veld, aan het begin, aan het einde of in het midden wordt geplaatst. Een belangrijk kenmerk is dat gezocht wordt in álle velden op de pagina, en daarmee in álle kolommen.

### De zoekactie verfijnen

U kunt de zoekactie echter sturen, en daarmee de lijst met getoonde resultaten beperken, door speciale tekens te gebruiken.

- Als u alleen veldwaarden wilt zoeken die exact overeenkomen met de volledige tekst en de hoofdletters/kleine letters, plaatst u de zoektekst tussen enkele aanhalingstekens (bijvoorbeeld `'man'`).

- Als u veldwaarden wilt zoeken die beginnen met een bepaalde tekst en overeenkomen met de hoofdletters/kleine letters, plaatst u een `*` achter de tekst (bijvoorbeeld `man*`).

- Als u veldwaarden wilt zoeken die eindigen met een bepaalde tekst en overeenkomen met de hoofdletters/kleine letters, plaatst u een `*` vóór de tekst (bijvoorbeeld `*man`).

- Wanneer u `''` of `*` gebruikt, wordt onderscheid gemaakt tussen hoofdletters en kleine letters. Als u hoofdletterongevoelig wilt zoeken, plaatst u een `@` vóór de zoektekst (bijvoorbeeld `@man*`).

In de volgende tabel vindt u enkele voorbeelden om aan te geven hoe u de zoekactie kunt gebruiken.

|Zoekcriteria|Zoekt…|
|---------------|----------|
|`man`<br />of <br />`Man`|Alle records met velden die de tekst **man** bevatten, ongeacht hoofdletters. Bijvoorbeeld **Manderveen**, **mannelijk** of **Brinkman**. |
|`'Man'`|Alle records met velden die alleen **Man** bevatten, ongeacht hoofdletters.|
|`Man*`|Alle records met velden die beginnen met de tekst <b>Man</b>, met identieke hoofdletters/kleine letters. Bijvoorbeeld **Manderveen**, maar niet **mannelijk** of **Brinkman**.|
|`@Man*`|Alle records met velden die beginnen met **man**, ongeacht hoofdletters. Bijvoorbeeld **Manderveen** en **mannelijk**, maar niet **Brinkman**.|
|`@*man`|Alle records met velden die eindigen met **man**, ongeacht hoofdletters. Bijvoorbeeld **Brinkman**, maar niet **Manderveen** of **mannelijk**.|

> [!TIP]
> U kunt op **F3** drukken om het zoekvak te activeren en te deactiveren. Zie voor meer informatie [Toetsenbordsneltoetsen](../Toegankelijkheid-en-sneltoetsen/Toetsenbordsneltoetsen/).

## Filteren

Filteren biedt een geavanceerde en flexibele manier om te bepalen welke records in een lijst worden weergegeven, of in een rapport of XMLport. Er zijn twee belangrijke verschillen tussen zoeken en filteren, zoals wordt beschreven in de volgende tabel.

|| **Zoeken** | **Filteren** |
|--|----------|------------|
| **Toepasselijke velden** | Zoekt in alle velden die zichtbaar zijn op de pagina. | Filtert een of meer velden afzonderlijk, selecterend vanuit een veld in de tabel, inclusief velden die niet zichtbaar zijn op de pagina. |
| **Afstemmen** | Geeft records weer met velden die voldoen aan de zoektekst, ongeacht hoofdletters/kleine letters of plaatsing van de tekst. | Geeft records weer waar het veld exact overeenkomt met het filter en is hoofdlettergevoelig, tenzij speciale filtersymbolen worden ingevoerd.

Filteren stelt u in staat records weer te geven voor bepaalde rekeningen of klanten, datums, bedragen en andere informatie door filtercriteria op te geven. Alleen records die voldoen aan de criteria, worden weergegeven in de lijst of opgenomen in het rapport, de batchtaak of de XMLport. Als u criteria opgeeft voor meerdere velden, worden alleen de records weergegeven die overeenkomen met alle criteria.

Voor lijsten worden de filters weergegeven in een filtervenster dat links van de lijst verschijnt wanneer u deze activeert. Voor rapporten, batchtaken en XMLports zijn de filters direct zichtbaar op de aanvraagpagina.

### Filteren met optievelden

Voor 'gewone' velden die gegevens, instellingsdatum of bedrijfsgegevens bevatten, kunt u filters instellen door gegevens te selecteren en filterwaarden te typen, en u kunt symbolen gebruiken om geavanceerde filtercriteria te definiëren. Zie voor meer informatie **[Filtercriteria invoeren](#filtercriteria-invoeren)**.

Voor velden van het type **Optie** kunt u echter alleen een filter instellen door een of meer opties te selecteren uit de vervolgkeuzelijst met beschikbare opties. Een voorbeeld van een optieveld is het veld **Status** op de lijstpagina **Inkooporders**. Dit veld kunt u filteren op de waarden 'Open', 'Vrijgegeven', 'Wacht op goedkeuring' en 'Wacht op vooruitbetaling'. Hierbij geldt dat wanneer u meerdere opties als filterwaarde selecteert, de relatie tussen die opties vervolgens wordt gedefinieerd als *OF*. Als u bijvoorbeeld zowel het selectievakje 'Open' als 'Vrijgegeven' selecteert in het filterveld **Status** op de lijstpagina **Inkooporders**, betekent dit dat de inkooporders worden weergegeven waarvoor geldt dat ze óf open óf vrijgegeven zijn.

### Filters instellen voor lijsten

In lijsten stelt u filters in met behulp van het **filterdeelvenster**. Als u dit venster voor een lijst wilt weergeven, kiest u het filtericoon ![filter icon](/assets/images/filter.png "filter icon") **Filterdeelvenster weergeven**, rechtsboven op de pagina. U kunt ook drukken op **Shift+F3**.

Als u het filtervenster voor een kolom in een lijst wilt weergeven, met een filter dat alleen records weergeeft met dezelfde waarde als in de geselecteerde cel, kiest u de keuzepijl naast de kolomnaam en selecteert u de actie **Filteren op deze waarde**. Het filterdeelvenster verschijnt links op de pagina, met in het veld **Filter lijst op:** de waarde uit de betreffende cel ingevuld. U kunt ook drukken op **Alt+F3**.

U kunt dit voor meerdere kolommen doen, waarvoor dan in het filterdeelvenster de verschillende waarden worden vermeld. Bedenk goed dat al deze gefilterde waarden dan uiteraard hun invloed hebben op de uitkomst in de lijst. Wilt u de filtering voor een specifieke kolom verwijderen, dan klikt u op het kruisje naast de kolomnaam onder **Filter lijst op:**, of u kiest de keuzepijl naast de kolomnaam en selecteert de actie **Filter wissen**.

Het filterdeelvenster bevat de huidige filters voor een lijst en biedt u de mogelijkheid uw eigen filters in te stellen op een of meer velden door de actie **+ Filteren** te kiezen.

Een filterdeelvenster is verdeeld in drie gedeelten: **Weergaven**, **Filter lijst op** en **Filter totalen op**:

- **Weergaven**

  Sommige lijsten bevatten het gedeelte **Weergaven**. Weergaven zijn variaties van de lijst die vooraf zijn ingesteld met filters. U kunt per lijst zoveel weergaven definiëren en opslaan als u wilt, en de weergaven zijn voor u beschikbaar op elk apparaat waarop u zich aanmeldt. Zie voor meer informatie [Lijstweergaven opslaan en personaliseren](../Uw-werkruimte-personaliseren/Lijstweergaven-opslaan-en-personaliseren/).

- **Filter lijst op**

  Hier voegt u filters toe aan specifieke velden om het aantal weergegeven records te reduceren. Als u een filter wilt toevoegen, kiest u de actie **+ Filteren**, typt u de naam van het veld waarop u de lijst wilt filteren of kiest u een veld in de vervolgkeuzelijst. 
  
  >Note: Zodra een filter is ingesteld en de focus wordt verlegd naar een ander deel in het filterdeelvenster, dan wordt de optie **+ Filteren** vervangen door **Bewerken**. Klik hierop om de focus weer te verleggen.

- **Filter totalen op**

  Sommige lijsten met berekende velden, zoals bedragen en aantallen, bevatten het gedeelte **Filter totalen op**, waarin u verschillende dimensies kunt aanpassen die van invloed zijn op berekeningen. Als u een filter wilt toevoegen, kiest u de actie **+ Filteren** (indien nodig: eerst **Bewerken**) en typt u de naam van het veld waarop u de lijst wilt filteren of kiest u een veld in de vervolgkeuzelijst.

### Filters instellen in rapporten, batchtaken en XMLports

Voor rapporten, batchtaken en XMLports zijn de filters direct zichtbaar op de aanvraagpagina. De aanvraagpagina toont de laatst gebruikte filters volgens uw selectie in het veld **Standaardwaarden gebruiken uit**. Zie voor meer informatie [Opgeslagen instellingen gebruiken](../Werken-met-rapporten-batchverwerkingen-en-XMLports/#opgeslagen-instellingen-gebruiken/).

De hoofdsectie **Filter** toont de standaardfiltervelden die u gebruikt om af te bakenen welke records in het rapport of de XMLport moeten worden opgenomen. Als u een filter wilt toevoegen, kiest u de actie **+ Filter**, typt u de naam van het veld waarop u de lijst wilt filteren of kiest u een veld in de vervolgkeuzelijst.

In de sectie **Filter totalen op** kunt u verschillende dimensies aanpassen die van invloed zijn op berekeningen in het rapport of de XMLport. Als u een filter wilt toevoegen, kiest u de actie **+ Filteren**, typt u de naam van het veld waarop u de lijst wilt filteren of kiest u een veld in de vervolgkeuzelijst.

## Filtercriteria invoeren

Zowel in het filtervenster als op een aanvraagpagina voert u uw filtercriteria in het vak onder het filterveld in.

Het type filterveld bepaalt welke criteria u kunt invoeren. Als u bijvoorbeeld filtert op een veld dat vaste waarden heeft, kunt u alleen kiezen uit die waarden. Voor meer informatie over speciale filtersymbolen raadpleegt u [Filtercriteria](#Filtercriteria-en-symbolen) en [Filtertokens](#FilterTokens)

Kolommen die al filters bevatten, worden aangegeven door het pictogram ![filter icon](/assets/images/filter.png "filter icon") in de kolomkop. Als u een filter wilt verwijderen, kiest u de vervolgkeuzepijl en kiest u vervolgens de actie **Filter wissen**.

> [!TIP]
> Versnel het zoeken en analyseren van uw gegevens met combinaties van toetsenbordsneltoetsen. Selecteer bijvoorbeeld een veld, gebruik **Shift+Alt+F3** om dat veld aan het filterdeelvenster toe te voegen, typ het filtercriterium, gebruik **Ctrl+Enter** om terug te keren naar de rijen, selecteer een ander veld en gebruik **Alt+F3** om op die waarde te filteren. Zie voor meer informatie [Toetsenbordsneltoetsen](../Toegankelijkheid-en-sneltoetsen/Toetsenbordsneltoetsen/).

### Filtercriteria en -symbolen

U kunt bij de invoer van criteria alle cijfers en letters gebruiken die u normaal ook kunt gebruiken. Daarnaast kunt u speciale symbolen (of operatoren) gebruiken om de resultaten verder te filteren. De volgende tabellen bevatten de symbolen die in filters kunnen worden gebruikt. Voor datums en tijden kunt u ook [Werken met kalenderdatums en -tijden](../Werken-met-agendadatums-en-tijden/) raadplegen voor meer gedetailleerde informatie.

> [!IMPORTANT]  
> Het kan voorkomen dat veldwaarden deze symbolen bevatten en u hierop wilt filteren. Hiervoor moet u de filterexpressie opnemen die het symbool tussen aanhalingstekens (“) bevat. Als u wilt filteren op records die beginnen met de tekst *S&R*, is de filterexpressie bijvoorbeeld `'S&R*'`.

In de volgende secties wordt beschreven hoe u de verschillende operatoren kunt gebruiken.

> [!NOTE]
> Als er meer dan 200 operatoren in één filter zijn, groepeert het systeem automatisch enkele uitdrukkingen tussen haakjes `()` met het oog op verwerking. Dit heeft geen effect op het filter of de resultaten.  

#### (..) Interval

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`1100..2100`|Nummers 1100 t/m 2100|  
|`..2500`|Tot en met 2500|  
|`..12 31 00`|Datums tot en met 31.12.00|  
|`P8..`|Gegevens voor boekhoudperiode 8 en verder|  
|`..23`|Van begindatum tot 23 lopende maand, lopend jaar 23:59:59|  
|`23..`|Van 23 lopende maand, lopend jaar 00:00:00 tot eindtijd|  
|`22..23`|Van 22 lopende maand, lopend jaar 0:00:00 tot 23 lopende maand, lopend jaar 23:59:59|  

#### (&#124;) Of/of

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`1200|1300`|Nummers met 1200 of 1300|  

#### (<>) Niet gelijk aan  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`<>0`|Alle nummers behalve 0<br /><br /> Met de SQL Server-optie kunt u dit teken combineren met jokertekens. <>A* betekent bijvoorbeeld 'Niet gelijk aan tekst die begint met A'.|  

#### (>) Groter dan  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`>1200`|Nummers groter dan 1200|  

#### (>=) Groter dan of gelijk aan  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`>=1200`|Nummers groter dan of gelijk aan 1200|  

#### (<) Kleiner dan  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`<1200`|Nummers kleiner dan 1200|  

#### (<=) Kleiner dan of gelijk aan  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`<=1200`|Nummers kleiner dan of gelijk aan 1200|  

#### (&) En  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`>200&<1200`|Getallen groter dan 200 en kleiner dan 1200|  

#### ('') Een exacte tekenovereenkomst  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`'man'`|Tekst die exact overeenkomt met man en hoofdlettergevoelig is.|  

#### (@) Niet hoofdlettergevoelig  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`@man*`|Tekst die begint met man en niet hoofdlettergevoelig is.|  

#### (*) Een onbeperkt aantal onbekende tekens

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`*Co*`|Tekst die “Co“ bevat en hoofdlettergevoelig is.|  
|`*Co`|Tekst die eindigt met “Co“ en hoofdlettergevoelig is.|  
|`Co*`|Tekst die begint met “Co“ en hoofdlettergevoelig is.|  

#### (?) Een onbekend teken  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`Hans?n`|Tekst zoals Jansen of Jansma|  

#### Gecombineerde notatiesoorten  

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`5999|8100..8490`|Alle records met het nummer 5999 of een nummer uit het interval 8100 tot en met 8490.|  
|`..1299|1400..`|Records met een nummer kleiner dan of gelijk aan 1299 of gelijk aan 1400 en hoger. Met andere woorden: alle nummers behalve 1300 tot en met 1399.|  
|`>50&<100`|Records met een nummer groter dan 50 en kleiner dan 100, ofwel nummer 51 tot en met 99.|  

### Filtertokens

Wanneer u filtercriteria invoert, kunt u ook woorden typen die een speciale betekenis hebben, filtertokens genaamd. Na het invoeren van het tokenwoord wordt het woord vervangen door de waarde of waarden die het woord vertegenwoordigt. Dit maakt filtering eenvoudiger doordat u niet naar andere pagina's hoeft te navigeren om waarden op te zoeken die u aan uw filter wilt toevoegen. In de onderstaande tabellen worden enkele van de tokens beschreven die u als filtercriteria kunt gebruiken.

> [!TIP]
> Uw organisatie kan aangepaste tokens gebruiken. Als u informatie wilt over de volledige set tokens die voor u beschikbaar zijn of als u aangepaste tokens wilt toevoegen, overlegt u met uw beheerder.

#### (%me of %userid) Records die aan u zijn toegewezen

Gebruik `%me` of `%userid` wanneer u velden filtert die de gebruikers-id bevatten, zoals het veld **Toegewezen aan gebruikers-id**, om alle records weer te geven die aan u zijn toegewezen.

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`%me`<br />of<br />`%userid`|Records die aan uw gebruikersaccount zijn toegewezen. |  

#### (%mycustomers) Klanten in Mijn klanten

Gebruik `%mycustomers` in het veld klant**nr.** om alle records weer te geven voor klanten die deel uitmaken van de lijst **Mijn klanten** in uw rolcentrum.

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`%mycustomers`|Klanten in **Mijn klanten** in uw rolcentrum. |  

#### (%myitems) Artikelen in Mijn artikelen

Gebruik `%myitems` in het veld artikel**nr.** om alle records weer te geven voor artikelen die deel uitmaken van de lijst **Mijn artikelen** in uw rolcentrum.

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`%myitems`|Artikelen in **Mijn artikelen** in uw rolcentrum. |  

#### (%myvendors) Leveranciers in Mijn leveranciers

Gebruik `%myvendors` in het veld leveranciers**nr.** om alle records weer te geven voor leveranciers die deel uitmaken van de lijst **Mijn leveranciers** in uw rolcentrum.

|Voorbeeld|Weergegeven records|  
|-----------------------|-----------------------|  
|`%myvendors`|Leveranciers in **Mijn leveranciers** in uw rolcentrum. |  
