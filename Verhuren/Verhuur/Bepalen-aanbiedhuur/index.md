# Bepalen aanbiedhuur

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=2d6&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

De aanbiedhuur van de beschikbare verhuurbare eenheid wordt automatisch bepaald op basis van het voor die eenheid geldende huurbeleid. Indien nodig wordt de aanbiedhuur handmatig aangepast. Daarnaast wordt de huurprijsmutatie ingevuld en indien nodig gefiatteerd.

## Berekenen nieuwe nettohuur conform huurbeleid

In deze stap zorgt u ervoor dat het systeem automatisch de nieuwe nettohuur voor de beschikbare verhuurbare eenheid berekent op basis van het bij die eenheid ingestelde huurbeleid en de bij de doelgroep van de eenheid ingestelde doelgroeplimiet.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutaties**.
2. Zoek de verhuurmutatie op waarvoor de aanbiedhuur moet worden bepaald.
3. Open de detailpagina van de verhuurmutatie.
4. Klik op **Nieuw** en kies voor **Verhuuraanbieding**. Het contractoverzicht van de OG Eenheid verschijnt met het leegstandscontract en het meest recente verhuurcontract van de vorige huurder. Selecteer de contractregel op basis waarvan  u de nieuwe verhuuraanbieding wilt aanmaken en klik op **OK**.
5. De verhuuraanbieding wordt aangemaakt met één of meer **Aanbiedingscontracten** (zie onder het gelijknamige kopje op de aanbiedingskaart): één aanbiedingscontract voor elke exploitatievorm van het soort 'Verhuur' dat is ingesteld bij de OG Eenheid. De nettohuur van elk aanbiedingscontract wordt automatisch berekend door toepassing van het huurbeleid dat is ingesteld bij de OG Eenheid en de aftopping op het effectieve limietbedrag van de doelgroep die is toegewezen aan de OG Eenheid. De andere soorten elementen van elk aanbiedingscontract zijn overgenomen van de contractregel die u in stap 4 heeft geselecteerd, aangevuld met elementen uit het huurmutatiesjabloon van de eenheid.
6. Bepaal op basis van welk aanbiedingscontract u de OG Eenheid wilt publiceren en opnieuw verhuren. Verwijder eventueel de overige aanbiedingscontracten van de verhuuraanbieding.

## Aanpassen aanbiedhuur

In deze stap past u - indien nodig - handmatig de door het systeem berekende aanbiedhuur aan. Dit doet u door het bedrag van bestaande elementen aan te passen en/of of door het toevoegen van extra elementen aan het aanbiedingscontract en/of verwijderen van bestaande elementen uit het aanbiedingscontract.
>**Let op:** Als u nettohuur-elementen toevoegt, wijzigt of verwijdert, dan heeft dat tot gevolg dat de nieuwe nettohuur afwijkt van de referentie-nettohuur die is berekend op moment van aanmaken van de verhuuraanbieding. 

1. Selecteer op de aanbiedingskaart op tabblad **Aanbiedingscontracten** het aanbiedingscontract en kies voor **Aanbiedhuur** (u vindt deze actie in hetzelfde deel als waar de contracten vermeld staan). Een nieuwe pagina wordt geopend waarop alle elementen van het aanbiedingscontract worden getoond. Elk element van het soort 'Element' heeft een bedrag dat gelijk is aan **Eenheidprijs** vermenigvuldigd met **Aantal**. Bedragen kunnen niet direct worden gewijzigd, wel indirect via het wijzigen van het aantal en/of de eenheidprijs.
2. Als u het bedrag van een bestaand element wilt aanpassen, selecteer dan dat element en pas de waarde in kolom **Eenheidprijs** aan.
3. Herhaal dit voor alle elementen waarvan u het bedrag wil aanpassen.
4. Als u een bestaand element wilt verwijderen uit het aanbiedingscontract, selecteer dan dat element, klik op de drie verticale puntjes in de regel en klik op **Regel verwijderen**.
5. Herhaal  dit voor alle elementen die u wilt verwijderen.
6. Als u een extra element wilt toevoegen aan het aanbiedingscontract, klik dan in kolom **Soort** op een lege regel onderaan het overzicht met elementen. Selecteer een element uit het elementoverzicht en klik op **OK**. Vul een waarde in in kolom **Eenheidprijs**.
7. Herhaal dit voor alle elementen die u wilt toevoegen.

De referentie-nettohuur bevat een waarde die is berekend op het moment dat het huurbeleid de laatste keer was toegepast. Deze huidige waarde kan inmiddels achterhaald zijn, bijvoorbeeld doordat: 
 - bij de OG Eenheid een ander huurbeleid of andere doelgroep is ingesteld;
 - de doelgroeplimiet is gewijzigd;  
 - de ingangsdatum of het subsidiabel servicebedrag van het aanbiedingscontract is gewijzigd. 
 
In dat geval kunt u de waarde van de referentie-nettohuur van het aanbiedingscontract opnieuw laten berekenen door het huurbeleid opnieuw toe te laten passen op basis van de actuele situatie.  
1. Selecteer op de aanbiedingskaart op tabblad **Aanbiedingscontracten** het aanbiedingscontract.
2. Kies voor menu-item **Huurbeleidverschillen**. Een pagina verschijnt waarop de huurbeleidsparameters worden getoond met hun huidige waarde (berekend en opgeslagen de laatste keer dat het huurbeleid was toegepast) en hun nieuwe waarde (conform de actuele situatie). 
3. Kies voor de actie **Huurbeleid opnieuw toepassen**. Het systeem voert de volgende acties uit: 
	- de nieuwe waarden van de huurbeleidsparameters (inclusief referentie-nettohuur) worden opgeslagen bij het geselecteerde aanbiedingscontract; 
	- de nettohuur van het geselecteerde aanbiedingscontract wordt gelijk gemaakt aan de nieuwe waarde van de referentie-nettohuur; 
	- de huurprijsmutatie van het aanbiedingscontract wordt verwijderd.

## Invullen huurprijsmutatie

In deze stap vult u de huurprijsmutatie in. Hiermee specificeert u wat de reden is waarom de huurprijs van de verhuurbare eenheid wijzigt. Mocht de nieuwe nettohuur ongelijk zijn aan de referentie-nettohuur van de verhuurbare eenheid, specificeert u daarnaast dan ook wat de reden van die afwijking is.

1. Selecteer op de aanbiedingskaart het aanbiedingscontract en klik op **Huurprijsmutatie** (u vindt deze actie in hetzelfde deel waar de contracten vermeld staan, voorheen genoemd **Verhuurmutatie**). Een nieuwe pagina genaamd **Huurprijsmutatie** wordt geopend. Op deze pagina wordt o.a. de referentie-nettohuur van de OG Eenheid vermeld, plus alle uitgangspunten op basis waarvan het systeem de referentie-nettohuur heeft berekend.
2. Selecteer een reden in veld **Reden wijziging**.
3. Als de nieuwe nettohuur afwijkt van de referentie-nettohuur, selecteer dan  een **Reden afwijking** onder het kopje **Afwijkingsreden voor verschil tussen referentie-nettohuur en nieuwe nettohuur**.
4. Klik op **Sluiten**.

## Fiatteren nettohuur 

In deze stap fiatteert u de nieuwe nettohuur. Hierbij wordt ervan uitgegaan dat de verhuuraanbieding al is gemaakt en de huurprijsmutatie al is ingevuld. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutaties**.
2. Zoek de verhuurmutatie op waarvoor de nieuwe nettohuur moet worden gefiatteerd.
3. Open de detailpagina van de verhuurmutatie.
4. Stel vast dat de mijlpaal **Aanbiedhuur is gefiatteerd** nog niet is bereikt, d.w.z. de waarde *Nee* heeft. De waarde van deze mijlpaal heeft de vorm van een link. 
5. Klik op deze link. De pagina met details van de huurprijsmutatie wordt geopend. 
6. Zet het schuifje van het veld **Fiat** naar rechts. 
7. Klik op **Sluiten**. U keert terug op de detailpagina van de verhuurmutatie. Stel vast dat de mijlpaal **Aanbiedhuur is gefiatteerd** nu wel is bereikt.
8. Sluit de pagina. 

## Zie ook

[Aanbieden eenheid](../aanbieden-eenheid/)  
[Beheren verhuurbare eenheidsinformatie](../beheren-verhuurbare-eenheidsinformatie/)  
[Innemen eenheid](../innemen-eenheid/)  
[Ondertekenen huurovereenkomst](../ondertekenen-huurovereenkomst/)  
[Opleveren eenheid](../opleveren-eenheid/)  
[Opstellen eindafrekening](../opstellen-eindafrekening/)  
[Registreren huuropzegging](../registreren-huuropzegging/)  
[Verantwoorden verhuring](../verantwoorden-verhuring/)  
[Annuleren/wijzigen huuropzegging](../annuleren-wijzigen-huuropzegging/)
