# Afhandelen huurverhogingsbezwaren

Dit werkproces betreft het afhandelen van een bezwaar dat een klant heeft ingediend tegen de jaarlijkse huurverhoging. Een klant kan met diverse argumenten bezwaar maken, zoals: 
- Onjuiste woningwaardering en als gevolg daarvan verkeerde maximale huurprijs 
- Ten onrechte toegepaste inkomensafhankelijke huurverhoging 
- Achterstallig onderhoud aan de eenheid 
 
Dynamics Empire biedt standaard functionaliteit voor het registreren van een bezwaar en bijbehorend weigeringsbedrag en voor het op hoofdlijnen bijhouden van de status en vastleggen en verwerken van de uitkomst van een bezwaar. Deze werkinstructie beschrijft m.n. de toepassing van deze standaard functionaliteit. 

Als u de procedure voor het afhandelen van een bezwaar meer in detail wilt monitoren en alle contactmomenten en documenten binnen die procedure bij elkaar wilt houden (bijvoorbeeld voor de communicatie met de huurcommissie), dan kunt u dat doen door per bezwaar een leefbaarheidsdossier van het type 'BEZWAAR' aan te maken. Dit wordt niet verder beschreven in deze werkinstructie. Voor een beschrijving daarvan kunt u terecht in de werkinstructie voor **[Afhandelen overlast](../../sociaal-beheer/afhandelen-overlast/)**.  

## Registreren bezwaar 

In deze stap registreert u het bezwaar in de contractregel waarin de huurverhoging is verwerkt. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2. Zoek en selecteer de OG Eenheid waarvoor u het bezwaar wilt registreren. 
3. Navigeer via het menu naar de **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de huurverhoging is verwerkt waartegen bezwaar wordt gemaakt. 
5. Klik op **Bewerken**. 
6. Activeer de indicatie **Bezwaar huurverhoging** op tabblad **Huurverhoging**. Het systeem vult automatisch het **Weigeringsbedrag** met het bedrag waarmee de nettohuur is verhoogd als gevolg van de jaarlijkse huurverhoging. 
7. Vul de **Ingangsdatum weigering** in. 
8. Geef aan of de huurder al dan niet **Betalingsbereid** is. Activeer deze indicatie als de huurder, ondanks het bezwaar en in afwachting van de uitkomst van het bezwaar, toch bereid is de verhoogde nettohuur te betalen. In dat geval wordt de huurder wel aangemaand als hij de verhuurfacturen niet op tijd betaalt; anders wordt de huurder niet aangemaand. 
9. Wijzig de **Bezwaarstatus** naar 'In afwachting'. 

## Beoordelen en bepalen vervolgacties 

In deze stap beoordeelt u de argumentatie van het bezwaar en bepaalt u de bijbehorende vervolgacties. 
- Als de huurder bezwaar maakt met als argument dat de woningwaardering onjuist is en als gevolg daarvan met een verkeerde maximale huurprijs is gerekend, dan moet de woningwaardering van de OG Eenheid worden gecontroleerd. 
- Als de huurder bezwaar maakt met als argument dat de inkomensverklaring onjuist is en als gevolg daarvan de inkomensafhankelijke huurverhoging ten onrechte is toegepast, dan moet een bewijs daartoe worden opgevraagd bij de huurder of een vervolgverklaring worden aangevraagd bij de Belastingdienst. 
- Als de huurder bezwaar maakt met als argument dat er sprake is van achterstallig onderhoud aan de gehuurde eenheid, dan moet die eenheid worden geïnspecteerd.  

U kunt er vanzelfsprekend ook voor kiezen om het bezwaar te honoreren zonder nadere controles uit te voeren.  

## Check woningwaardering 

In deze stap controleert u de woningwaardering van de eenheid. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2. Zoek en selecteer de OG Eenheid waarvoor u de woningwaardering wil controleren. 
3. Navigeer naar de **Woningwaardering**. 
4. Navigeer m.b.v. **Pagina - Volgende** naar de versie van de woningwaardering met ingangsdatum gelijk aan de ingangsdatum van het huurverhogingstijdvak (doorgaans 1 juli van het lopende kalenderjaar). 
5. Mocht de OG Eenheid geen versie van de woningwaardering hebben met de genoemde ingangsdatum, dan moet deze versie alsnog worden aangemaakt in de volgende stap. 
6. Controleer of in de gevonden versie van de woningwaardering de juiste WOZ-waarde van de OG Eenheid is gebruikt. 
7. Controleer of andere aspecten van de woningwaardering juist zijn geregistreerd. Houd hierbij rekening met de inhoudelijke argumenten die de huurder eventueel heeft gebruikt in het bezwaar. 

## Aanpassen woningwaardering 

Als in de vorige stap is gebleken dat de woningwaardering onjuist was, dan past u in deze stap de woningwaardering van de OG Eenheid aan. Dit doet u door een nieuwe versie van de woningwaardering aan te maken waarin u de correcties doorvoert. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarvoor u de woningwaardering wil aanpassen. 
3. Klik op **Navigeren** en kies voor **Woningwaardering**. 
4. Klik op **Nieuw+**. 
5. Vul de **Ingangsdatum** van de nieuwe woningwaardering met de de ingangsdatum van het huurverhogingstijdvak (doorgaans 1 juli van het lopende kalenderjaar) en klik op een ander deel van de pagina. Het systeem kopieert de vorige versie van de woningwaardering, haalt de juiste **WOZ-waarde** op uit de WOZ-gegevens van de OG Eenheid en berekent het aantal punten conform de wet- en regelgeving en de ingestelde **Woningwaarderingparameterset**.  Het systeem berekent op basis van het totaal aantal punten bovendien de maximale huurprijs en slaat deze op in de nieuwe versie van de woningwaardering. 
6. Pas daar waar nodig één of meer aspecten van de nieuwe versie van de woningwaardering aan. Elke keer als u een aspect van de woningwaardering aanpast, berekent het systeem automatisch het aantal punten en de maximale huurprijs. 
7. Sluit de pagina. 

## Simuleren nieuwe nettohuur 

In deze stap bepaalt u of de aangepaste woningwaardering al dan niet zou leiden tot een lagere nieuwe nettohuur dan de nieuwe nettohuur die was berekend tijdens de originele jaarlijkse huurverhoging van deze OG Eenheid. Dit is zeker niet het geval als de aangepaste woningwaardering leidt tot ongewijzigde of zelfs hogere maximale huurprijs. In het geval de aangepaste woningwaardering leidt tot een lagere maximale huurprijs, dan moet de nieuwe nettohuur worden berekend op basis van de lagere maximale huurprijs en de andere, ongewijzigde huurverhogingsparameters. Aangezien de originele jaarlijkse huurverhoging i deze fase van de bezwaarprocedure nog niet wordt teruggedraaid, moet u de berekening buiten het systeem uitvoeren. 

## Opvragen bewijs klant 

In deze stap vraagt u de huurder informatie aan te leveren waarmee kan worden aangetoond dat de inkomensafhankelijke huurverhoging ten onrechte is toegepast. 

## Beoordelen bewijs 

In deze stap beoordeelt u het door de huurder aangeleverde informatie waarmee de huurder probeert te bewijzen dat de inkomensafhankelijke huurverhoging ten onrechte is toegepast. Op basis van deze beoordeling besluit u of het bezwaar gegrond of ongegrond is. Als het bezwaar gegrond is, dan registreert u dat bij het bewaar. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Navigeren** en kies voor **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de huurverhoging is verwerkt waartegen bezwaar wordt gemaakt. 
5. Klik op **Bewerken**. 
6. Pas de **Bezwaarstatus** aan in *Ingetrokken verhuurder*. 

## Opvragen vervolgverklaring 

In deze stap vraagt u een vervolgverklaring op bij de Belastingdienst. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Kopieer het OG Eenheidsnummer. 
4. Zoek en open de taak **Aanvraaggegevens huishoudverklaringen exporteren**. 
5. Selecteer het juiste **Huurverhogingstijdvak**. 
6. Selecteer de **Huurverhogingsdatum**. 
7. Plak het gekopieerde OG Eenheidsnummer in het filter **Eenheidsnr.**. 
8. Klik op **OK**. Het systeem maakt een csv-bestand aan met de gegevens van de geselecteerde OG Eenheid. 
9. Upload dit csv-bestand naar de Belastingdienst. 

## Verwerken vervolgverklaring 

In deze stap verwerkt u de vervolgverklaring die u heeft ontvangen van de Belastingdienst. Als de vervolgverklaring dezelfde huishoudverklaringscode **J** bevat als de oorspronkelijke huishoudverklaring, dan verklaart u het bezwaar ongegrond. Als de vervolgverklaring een andere huishoudverklaringscode bevat, dan is het bezwaar gegrond en registreert u dat bij het bezwaar.  

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Navigeren** en kies voor **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de huurverhoging is verwerkt waartegen bezwaar wordt gemaakt. 
5. Klik op **Bewerken**. 
6. Pas de **Bezwaarstatus** aan in *Ingetrokken verhuurder*. 

## Inplannen inspectie 

In deze stap plant u een inspectie om de staat van onderhoud van de eenheid te laten controleren. Daartoe maakt u eerst een onderhoudsverzoek aan voor de betreffende OG Eenheid en plant vervolgens een inspectie binnen dat onderhoudsverzoek. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Nieuw** en kies voor **Onderhoudsverzoek**. De pagina **Onderhoudsverzoekkaart** wordt geopend. 
4. Selecteer de waarde *Reparatieverzoek* in het veld **Onderhoudstype**. 
5. Geef aan in het veld **Omschrijving** dat het gaat om een controle van de staat van onderhoud van de eenheid i.v.m. een bezwaar tegen de jaarlijkse huurverhoging. 
6. Navigeer naar de pagina met inspectieafspraken. Deze pagina is te bereiken via de knop **Inspectieafspraken** in het menu of via de link in het gelijknamige veld in feitenblok **Onderhoudsverzoekgegevens**.  
7. Klik op **Nieuw**. 
8. Klik op **Verwerken** en kies voor **Inspectieafspraak plannen**. 
9. Selecteer de **Datum** waarop de inspectie wordt uitgevoerd. 
10. Selecteer een tijdsblok op de regel van de inspecteur die de inspectie gaat uitvoeren. 
11. Klik op **OK**. De inspectieafspraak is aangemaakt. 

## Uitvoeren inspectie 

In deze stap wordt de inspectie uitgevoerd ter controle van de staat van onderhoud van de OG Eenheid. Deze stap vindt plaats binnen het werkproces *Uitvoeren inspectie naar staat eenheid*. 

## Verwerken resultaat inspectie 

In deze stap verwerkt u het resultaat van de inspectie. Als uit de inspectie blijkt dat er inderdaad sprake is van achterstallig onderhoud waardoor huurverhoging niet redelijk is, dan is het bezwaar gegrond en registreert u dat bij het bezwaar.  

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Navigeren** en kies voor **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de huurverhoging is verwerkt waartegen bezwaar wordt gemaakt. 
5. Klik op **Bewerken**. 
6. Pas de **Bezwaarstatus** aan in *Ingetrokken verhuurder*. 

## Verzoek intrekken bezwaar 

In deze stap vraagt u de huurder zijn bezwaar in te trekken, met de argumenten waarom u het bezwaar ongegrond acht.  

## Berekenen nieuwe nettohuur 

In deze stap berekent u de nieuwe nettohuur op basis van de aangepaste huurverhogingsparameters. Voordat u deze berekening kunt uitvoeren in het systeem, moet u eerst de originele jaarlijkse huurverhoging terugdraaien. Terugdraaien is mogelijk zolang de nieuwe contractregel nog niet is geprolongeerd. Terugdraaien heeft tot gevolg dat de originele jaarlijkse huurverhoging wordt overschreven en de nieuwe contractregel met ingangsdatum gelijk aan de huurverhogingsdatum wordt verwijderd. Als u de jaarlijkse huurverhoging niet kan of wil terugdraaien, dan moet u de berekening buiten het systeem uitvoeren. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarvoor u de woningwaardering wil aanpassen. 
3. Klik op **Navigeren** en kies voor **Jaarlijkse huurverhoging**. 
4. Selecteer de huurverhoging waartegen bezwaar wordt gemaakt. 
5. Klik op **Proces** en kies voor **Huurverhoging terugdraaien**. Het systeem verwijdert de nieuwe contractregel en wijzigt de status van de jaarlijkse huurverhoging in *Ongeldig*.  
6. Klik op **Proces** en kies voor **Parameters aanmaken**. Het systeem maakt de parameters aan op basis van de gewijzigde woningwaardering en maximale huurprijs en wijzigt de status van de jaarlijkse huurverhoging in *Aangemaakt*. 
7. Klik op **Proces** en kies voor **Berekenen (simulatie)**. Het systeem berekent de nieuwe nettohuur en wijzigt de status van de jaarlijkse huurverhoging in *Simulatie*. 
8. Klik op **Weergeven** en controleer de uitkomst van de berekening. Mocht de uitkomst niet akkoord zijn, pas dan het de uitgangspunten en/of het huurbeleid aan, en herhaal de voorgaande twee stappen (parameters aanmaken en berekenen (simulatie). 
9. Klik op **Proces** en kies voor **Berekenen (definitief)**. Het systeem berekent de nieuwe nettohuur en wijzigt de status van de jaarlijkse huurverhoging in *Definitief*. 

## Effecturen huurprijsaanpassing 

In deze stap effectueert u de huurprijsaanpassing. Als u de originele jaarlijkse huurverhoging heeft teruggedraaid, kunt u de huurprijsaanpassing effectueren door de zojuist berekende huurverhoging van de betreffende eenheid te verwerken. 

1. Zoek en open de taak **Huurverhoging verwerken**. 
2. Vul de **Huurverhogingsdatum** in. 
3. Selecteer de **Huurprijsmutatiereden**. 
4. Selecteer in het filter **Eenheidnr.** de OG Eenheid waarvan u de huurprijsaanpassing wil effectueren. 
5. Klik op **OK**. 

Als u de originele jaarlijkse huurverhoging *niet* heeft teruggedraaid,  moet u handmatig een nieuwe contractregel aanmaken met als ingangsdatum de huurverhogingsdatum en met de juiste bedragen voor de nettohuurelementen. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Navigeren** en kies voor **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de originele huurverhoging is verwerkt waartegen bezwaar wordt gemaakt.  
5. Klik op **+Nieuw**. Een nieuwe regel wordt toegevoegd aan het overzicht. 
6. Vul de **Ingangsdatum** van de nieuwe regel met de huurverhogingsdatum. 
7. Selecteer een andere contractregel. Het systeem kopieert kopieert alle elementen en overige eigenschappen van de originele contractregel naar de nieuwe contractregel. De originele contractregel is nu logisch verwijderd. 
8. Selecteer weer de nieuwe contractregel en klik op **Navigeren** en kies voor **Elementen**. 
9. Selecteer het nettohuurelement, d.w.z. het element met **Elementsoort** gelijk aan *Kale huur*.  
10. Wijzig de waarde van kolom **Eenheidprijs** in de nieuwe nettohuur die u heeft berekend op basis van de aangepaste huurverhogingsparameters. 
11. Sluit de pagina. 

## Informeren klant 

Hiertoe verstuurt u een brief met een omschrijving van de uitkomst van de bezwaarprocedure. Als u de originele jaarlijkse huurverhoging heeft teruggedraaid, kunt u de klant informeren door een nieuwe versie van het huurverhogingsdocument te genereren waarin het bezwaar is verwerkt.  

1. Zoek en open rapport **Huurverhoging - Document**. 
2. Selecteer de juiste **Huurverhogingsbatchnaam**. 
3. Selecteer de juiste **Huurverhogingsdatum**. 
4. Selecteer in het filter **Eenheidsnr.** de OG Eenheid waarvan het bezwaar is gegrond verklaard. 
5. Klik op **OK**. 

Als u de originele jaarlijkse huurverhoging niet heeft teruggedraaid, kunt u de klant informeren door het aanmaken van een Word-document. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft.  
3. Klik op het **Klantnr.** in het feitenblok **Klantinformatie**. De klantenkaart wordt geopend van de klant een actief huurcontract heeft op de OG Eenheid. 
4. Klik op **+Nieuw** en kies voor **Word-document**. 
5. Selecteer het juiste Word-sjabloon. 
6. Het systeem vraagt of u het samengevoegde document wil downloaden en bewerken. Klik op **Ja**. 
7. Sla het Word-document op en open het document in MS Word. 
8. Pas de inhoud van het document zodanig aan dat de uitkomst van de bezwaarprocedure duidelijk is omschreven, en sla het aangepaste document op. 
9. Klik op **Document bewerken** en kies voor **Document uploaden**. 
10. Klik op **Kiezen**, selecteer het zojuist opgeslagen Word-document en klik op **Open**. 

## Opsturen bezwaar naar huurcommissie 

In deze stap stuurt u het bezwaar naar de huurcommissie. Deze stap vindt buiten Dynamics Empire plaats. U wordt geadviseerd om in dit geval een leefbaarheidsdossier van het type *BEZWAAR* aan te maken, zodat u de afhandeling van het bezwaar meer in detail kan monitoren en alle contactmomenten en documenten bij elkaar kan houden. 

## Vastleggen uitspraak huurcommissie 

In deze stap legt u de uitspraak van de huurcommissie vast. 

1. Maak vanuit het leefbaarheidsdossier van het bezwaar een interactielogpost aan. 
2. Kopieer de uitspraak van de huurcommissie en plak deze in een notitie bij de interactielogpost en/of koppel het document waarin de uitspraak wordt verwoord aan die interactielogpost. 

## Verwerken uitspraak huurcommissie 

In deze stap verwerkt u de uitspraak van de huurcommissie, zodat de nieuwe nettohuur conform die uitspraak is. 

Als de huurcommissie de verhuurder volledig in het gelijk heeft gesteld, dan hoeft u in deze stap niets te doen, omdat in dat geval de originele huurverhoging in stand blijft of de door de verhuurder voorgestelde en reeds doorgevoerde aanpassing van de nettohuur wordt geaccepteerd door de huurcommissie. 

Als de huurcommissie de huurder in het gelijk heeft gesteld, dan moet u de nettohuur van de OG Eenheid (opnieuw) aanpassen. Dit doet u door handmatig een nieuwe contractregel aan te maken met als ingangsdatum de huurverhogingsdatum en met de juiste bedragen voor de nettohuurelementen. Zie de instructie bij stap *Effectueren huurprijsaanpassing*. 

## Registreren uitkomst 

In deze stap registreert u de uitkomst van de procedure bij het bezwaar en rondt u de behandeling van het bezwaar af. 

1. Open de **OG Eenheden** lijst door te klikken op de gelijknamige bladwijzer in het **Rolcentrum** 
2. Zoek en selecteer de OG Eenheid waarop het bezwaar betrekking heeft. 
3. Klik op **Navigeren** en kies voor **Verhuurcontracten**. De lijst **Contracten** wordt geopend. 
4. Selecteer de contractregel waarin de huurverhoging is verwerkt waartegen bezwaar wordt gemaakt. 
5. Klik op **Bewerken**. 
6. Als de huurder het bezwaar heeft ingetrokken, pas dan de **Bezwaarstatus** aan in *Ingetrokken huurder*. 
7. Als de verhuurder het bezwaar gerond heeft verklaard en de huurder is akkoord gegaan met de door de verhuurder voorgestelde aanpassing van de nettohuur, pas dan de **Bezwaarstatus** aan in *Ingetrokken verhuurder*.
8. Als de huurcommissie de huurder gelijk heeft gegeven, pas dan de **Bezwaarstatus** aan in *Toegewezen*.  
9. Als de huurcommissie de verhuurder gelijk heeft gegeven, pas dan de **Bezwaarstatus** aan in *Afgewezen*.

## Zie ook

[Bepalen huurverhogingsbeleid](../bepalen-huurverhogingsbeleid/)  
[Rappelleren klant](../rappelleren-klant/)  
[Uitvoeren jaarlijkse huurverhoging](../uitvoeren-jaarlijkse-huurverhoging/)  
[Uitvoeren tussentijdse huuraanpassing](../uitvoeren-tussentijdse-huuraanpassing/)  
[Voorbereiden jaarlijkse huurverhoging](../voorbereiden-jaarlijkse-huurverhoging/)  
