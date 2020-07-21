# Verwerken terugkoopfactuur onroerend goed

In dit werkproces wordt de factuur van teruggekochte eenheden verwerkt en de waarde geregistreerd.

## Opvoeren vast activum

Voordat de terugkoopfactuur aangemaakt kan worden dient er eerst een vast activum aangemaakt te worden waarop de waarder van de teruggekochte woning geactiveerd kan worden. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Vaste activa** en klik op **+Nieuw**. 
2. Vul in het scherm dat opent de volgende velden:
	- **Nr.**: Het nummer van het vaste activum. Er wordt automatisch een nummer toegekend. Het advies is om het eenheidsnummer waarvoor het activum aangemaakt wordt te verwerken in het nummer van het vaste activum. 
	- **Omschrijving**
	- **VA-klassecode**: Selecteer de klassecode voor vaste activa in exploitatie.
	- **Eenheidsnummer**: Selecteer het eenheidsnummer dat van toepassing is. 
3. Klik op tabblad **Afschrijvingsboeken** op **Meer afschrijvingboeken toevoegen**. Maak een regel aan en vul de volgende velden per regel:
	- **Afschrijvingsboek**: Kies het afschrijvingsboek voor marktwaarde.
	- **VA-boekingsgroep**: Kies de boekingsgroep die gebruikt wordt voor verkoop onder voorwaarden.
	- **Afschrijvingsmethode**: Kies voor **Geen afschrijving**.
	- **Begindatum afschr.**: Dit veld kunt u leeg laten.
	- **Aantal afschr.-jaren**: Dit veld kunt u leeg laten.

## Genereren terugkoopfactuur

Nadat het vaste activum aangemaakt is kan de terugkoopfactuur gegenereerd worden. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Onr. Goed-Eenhedenoverzicht**. 
2. Selecteer de eenheid waarvoor u de terugkoopfactuur aan wilt maken en klik op **Terugkoopaanbiedingen**. 
3. Open de aanbieding waarvoor u de terugkoopfactuur aan wilt maken. 
4. Klik op **Terugkoopfactuur maken** om de verkoopfactuur aan te maken. De Terugkoopfactuur is aangemaakt. 

## Aanvullen factuur 

Nadat de factuur aangemaakt is kunt u de factuur controleren en aanvullen. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") Naar **Onr. Goed-Eenhedenoverzicht**. 
2. Selecteer de eenheid waarvoor u de verkoopfactuur wilt aanvullen en klik op **Terugkoopaanbiedingen**. 
3. Open de aanbieding waarvoor u de factuur wilt aanvullen 
4. Klik op **Terugkoopfactuur** De terugfactuur wordt geopend. 
5. Vul de volgende gegevens op de factuur kop aan:
	- **Omschrijving**
	- **Boekingsdatum**
	- **Documentdatum**
	- **Factuurnummer leverancier**
	- **Factuurberdag**
6. Vul de factuurregels aan met bijvoorbeeld de verkoop- of makelaarskosten. Selecteer een nieuwe regel en vul de volgende velden. 
	- **Soort**: Grootboekrekening
	- **Nr.**: De rekening waarop de kosten of opbrengsten geboekt moeten worden
	- **Omschrijving**
	- **Btw-productboekingsgroep**
	- **Aantal**: Wanneer het kosten betreft vul hier dan -1 in. Betreft het opbrengsten vul dan 1 in.
	- **Eenheidsprijs Exc. btw**
	- **Dimensie waarden velden**: Velden die eindigen met de het woord code zijn velden waar dimensies zoals afdelingsdimensie of clusterdimensie gevuld kunnen worden. Afhankelijk van op welke grootboekrekening de kosten geboekt worden zijn deze velden verplicht om in te vullen.  
7. Wanneer alle gegevens gecontroleerd en aangevuld zijn kunt u de factuur ter goedkeuring aanbieden. Klik op **Boeken verplichting** en vervolgens op **Goedkeuringsaanvraag verzenden**. De goedkeuringsaanvraag wordt verzonden. 

## Boeken en versturen factuur 

De inkoopfactuur wordt na goedkeuring via het reguliere inkoopfactuurproces geboekt. 

## Zie ook

[Ontvangen inkoopfacturen](../ontvangen-inkoopfacturen/)  
[Verwerken inkoopcreditnotas](../verwerken-inkoopcreditnotas/)  
[Verwerken inkoopfacturen](../verwerken-inkoopfacturen/)  
[Beheren rekening-courant-crediteuren](../beheren-rekening-courant-crediteuren/)  

