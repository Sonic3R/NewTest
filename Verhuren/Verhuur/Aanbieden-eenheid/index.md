# Aanbieden eenheid

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=2d7&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces bezichtigt de kandidaat of een groep kandidaten de beschikbare eenheid. Daarnaast controleert  de huishoudgegevens van de kandidaat en bepaalt u op basis daarvan of de toewijzing van de eenheid aan die kandidaat al dan niet passend is.
Dit proces is beëindigd zodra beide partijen hebben geaccepteerd: een kandidaat heeft de eenheid en de aanbieding geaccepteerd, en  heeft de kandidaat geaccepteerd.

Welke stappen in welke volgorde en in welk systeem worden uitgevoerd, hangt af van de vraag of u kiest voor een individuele bezichtiging of groepsbezichtiging.
- In het geval van een individuele bezichtiging worden alle stappen uitgevoerd in het externe woonruimteverdeelsysteem. Pas nadat beide partijen hebben geaccepteerd wordt alleen die ene kandidaat vanuit het woonruimteverdeelsysteem doorgezet naar en verwerkt in Dynamics Empire.
- In het geval van een groepsbezichtiging worden alle stappen uitgevoerd vanuit Dynamics Empire (de ERP-module en de **VerhuurApp**). In dat geval worden alle kandidaten direct vanuit het woonruimteverdeelsysteem doorgezet naar en verwerkt in Dynamics Empire.

## Verwerken kandidaat of kandidaten

In deze stap wordt de geaccepteerde kandidaat of worden de kandidaten met de hoogste rangnummers geïmporteerd vanuit het externe woonruimteverdeelsysteem (WRV) en verwerkt in Dynamics Empire. Deze kandidaten zijn vanuit het woonruimteverdeelsysteem naar Dynamics Empire doorgezet. Een kandidaat bevat in ieder geval een hoofdaanvrager en mogelijk ook een mede-aanvrager. Hoofd- en mede-aanvragers uit het woonruimteverdeelsysteem corresponderen met personen in Dynamics Empire, kandidaten corresponderen met huishoudens in Dynamics Empire.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Zoek de OG Eenheid op waarvan de kandidaten moeten worden verwerkt en open de kaart door op het nummer te klikken.
3. Klik op **Gegadigden verwerken**. Een pagina verschijnt waarop de uit het woonruimteverdeelsysteem afkomstige kandidaten van de OG Eenheid worden getoond. Per kandidaat wordt één regel met de hoofdaanvrager en eventueel één regel voor de mede-aanvrager getoond.
4. Kies voor **Duplicaatcontrole**  **Alle regels**. Het systeem gaat voor elke aanvrager controleren of de uit het woonruimteverdeelsysteem afkomstige gegevens van de aanvrager corresponderen (op basis van de ingestelde duplicatencriteria) met de gegevens van een bestaand persoon in Dynamics Empire. Als het systeem voor een aanvrager een corresponderend persoon vindt, dan toont het  systeem het contactnummer van die persoon op de desbetreffende regel in kolom **Secndair Relatienr.**.  Als die persoon al tot een huishouden behoort, dan toont het systeem het contactnummer van dat huishouden op de desbetreffende regel in kolom **Primair Relatienr.**.
5. Controleer per aanvrager of deze inderdaad correspondeert met de gevonden persoon. Zo niet, wis dan het contactnummer in kolom **Secundair Relatienr.** als de aanvrager met geen enkele persoon in Dynamics Empire correspondeert. Of selecteer dan het juiste contactnummer in kolom **Secundair Relatienr.** als de aanvrager met een andere bestaande persoon in Dynamics Empire correspondeert.  
6. Controleer per kandidaat of deze inderdaad correspondeert met het gevonden huishouden. Zo niet, wis dan het contactnummer in kolom **Primair Relatienr.** op de regel van de hoofdaanvrager en - indien aanwezig -  de regel van de mede-aanvrager, als de kandidaat met geen enkel huishouden in Dynamics Empire correspondeert. Of selecteer dan het juiste contactnummer in kolom **Primair Relatienr.** op de betreffende regel(s) als de kandidaat met een ander huishouden in Dynamics Empire correspondeert.
7. Klik op **Verwerken**  **Alle gegadigden**. Als de kolom **Primair Relatienr.** leeg is maakt het systeem voor de betreffende kandidaat een nieuw huishouden aan in Dynamics Empire en koppelt dit nieuwe huishouden aan de kandidaat. Als de kolom **Primair Relatienr.** gevuld is koppelt het systeem de betreffende kandidaat aan het bestaande huishouden. Als de kolom **Secundair Relatienr.** leeg is maakt het systeem voor de betreffende aanvrager een nieuw persoon aan in Dynamics Empire en koppelt de nieuwe persoon aan de aanvrager. Als de kolom **Secundair Relatienr.** gevuld is koppelt het systeem de betreffende aanvrager aan de bestaande persoon.

## Uitnodigen voor bezichtiging

In deze stap nodigt u meerdere kandidaten uit voor de groepsbezichtiging.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutaties**.
2. Zoek de verhuurmutatie op waarvoor kandidaten moeten worden uitgenodigd voor de groepsbezichtiging.
3. Open de detailpagina door op het nummer te klikken.
4. Kies voor **Verhuuraanbieding**.
5. Klik op de actie **Worddocument**, selecteer het Word-sjabloon betreffende de uitnodiging en klik op **OK**.

In een bijlage bij de uitnodiging is een conceptversie van de huurovereenkomst opgenomen.

## Bezichtigen eenheid (groep)

In deze stap bezichtigt de groep met kandidaten de beschikbare eenheid. Bij deze groepsbezichtiging is een medewerker van de corporatie aanwezig. Deze medewerker kan de **Verhuuraanbieding**, inclusief alle kandidaten, raadplegen op de **VerhuurApp**.

## Selecteer kandidaat met hoogste rangnummer

De medewerker selecteert op de **VerhuurApp** de kandidaat met het hoogste rangnummer.

## Beoordelen passendheid

De kandidaat die de eenheid en aanbieding heeft geaccepteerd, verstrekt alle benodigde huishoudgegevens aan de medewerker van de corporatie. De medewerker controleert aan de hand van deze huishoudgegevens of de toewijzing van de eenheid aan deze kandidaat passend is. Daarbij controleert hij of de toewijzing voldoet aan de wettelijke criteria die door de Rijksoverheid worden gesteld binnen de passendheidstoets en staatssteunregeling. De medewerker voert deze controle uit met behulp van een externe tool, bijvoorbeeld van Finance Ideas.

Als blijkt dat de toewijzing passend is of niet getoetst hoeft te worden, dan accepteert u als corporatie de kandidaat. Als blijkt dat de toewijzing niet passend is, dan bepaalt u of de kandidaat desondanks toch wordt geaccepteerd. Het accepteren van niet-passende kandidaten is toegestaan, mits aan het eind van het kalenderjaar de wettelijke normen op dit gebied niet worden overschreden (zie proces **[Verantwoorden verhuring](../verantwoorden-verhuring/)**).  

## Registreren en terugkoppelen weigering

U selecteert op de **VerhuurApp** de reden waarom de kandidaat de eenheid en aanbieding heeft geweigerd resp. de reden waarom de corporatie de kandidaat heeft geweigerd.

## Opvragen huishoudgegevens

In deze stap vraagt u de huishoudgegevens van de kandidaat op. Deze stap wordt uitgevoerd vanuit het woonruimteverdeelsysteem.

## Verstrekken contactgegevens zittende huurder

Nadat u de huishoudgegevens van de kandidaat heeft gecontroleerd en op basis daarvan de kandidaat heeft geaccepteerd, verstrekt u de kandidaat de contactgegevens van de zittende huurder, zodat de kandidaat zelf een afspraak met de zittende huurder kan maken voor het bezichtigen van de eenheid.

## Bezichtigen eenheid (individueel)

De kandidaat bezichtigt zelf de eenheid in bewoonde staat. Hierbij is doorgaans geen medewerker van de corporatie aanwezig. Op basis van deze bezichtiging zal de kandidaat de eenheid en de aanbieding accepteren of weigeren.

## Vastleggen acceptatie of weigering door kandidaat

In deze stap legt u de acceptatie of weigering door de kandidaat vast in het woonruimteverdeelsysteem.

## Registreren weigering

In deze stap legt u de weigering van de kandidaat door de corporatie vast in het woonruimteverdeelsysteem.  

## Zie ook

[Beheren verhuurbare eenheidsinformatie](../beheren-verhuurbare-eenheidsinformatie/)  
[Bepalen aanbiedhuur](../bepalen-aanbiedhuur/)  
[Innemen eenheid](../innemen-eenheid/)  
[Ondertekenen huurovereenkomst](../ondertekenen-huurovereenkomst/)  
[Opleveren eenheid](../opleveren-eenheid/)  
[Opstellen eindafrekening](../opstellen-eindafrekening/)  
[Registreren huuropzegging](../registreren-huuropzegging/)  
[Verantwoorden verhuring](../verantwoorden-verhuring/)  
[Annuleren/wijzigen huuropzegging](../annuleren-wijzigen-huuropzegging/)
