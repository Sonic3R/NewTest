# Annuleren/wijzigen huuropzegging

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=2d3&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

Dit werkproces betreft het annuleren van een huuropzegging (in het geval de klant de eenheid bij nader inzien wil blijven huren) of het wijzigen van een huurcontracteinddatum van een huuropzegging (in het geval de klant de eenheid bij nader inzien korter of langer wil huren). 

## Beoordelen aanvraag

In deze stap bekijkt u hoever de eenheid is gevorderd in het verhuurmutatieproces en besluit u of u de aanvraag van de klant honoreert of afwijst. 

1. Klik op de bladwijzer **Verhuurmutaties** in het rolcentrum. De ljjst met openstaande verhuurmutaties wordt geopend. 
2. Zoek en open de verhuurmutatie waarop de aanvraag betrekking heeft. 
3. Open het sneltabblad **Nieuwe verhuring** en bekijk hoever het subproces van de nieuwe verhuring al is gevorderd. 
4. Besluit of u de aanvraag van de klant al dan niet honoreert. 

## Verwerken verschuiving

In deze stap verwerkt u de aanvraag van de klant voor het verschuiven van de huurcontracteinddatum. 

1. Klik op de bladwijzer **Verhuurmutaties** in het rolcentrum. De ljjst met openstaande verhuurmutaties wordt geopend. 
2. Zoek en open de verhuurmutatie waarop de aanvraag betrekking heeft. 
3. Klik op **Navigeren vertrekkende huurder** en kies voor **Huuropzegging**. De huuropzeggingskaart wordt geopend met details van de huuropzegging. 
4. Kik op **Proces** en kies voor **Huuropzegging verschuiven**. Een gelijknamige pagina wordt geopend. 
5. Open sneltabblad **Huuropzeggingsdetails**.  Het veld **Nieuwe huurcontracteinddatum** bevat standaard de huidige huurcontracteinddatum zoals die momenteel in Dynamics Empire is geregistreerd. 
6. Selecteer de juiste datum in het veld **Nieuwe huurcontracteinddatum**. De **Nieuwe verhuurbaar per datum** en de **Nieuwe contactgegevens wijzigdatum** verschuiven automatisch hetzelfde aantal werkdagen mee. 
7. Klik op **OK**. Het systeem past de door u gespecificeerde verschuiving door d.m.v. het aanpassen van de details van de huuropzegging en het aanmaken van één of meer nieuwe contractegels.   

## Verwerken annulering

In deze stap verwerkt u de aanvraag van de klant voor het annuleren van de huurcontracteinddatum. Hierbij wordt een onderscheid gemaakt tussen de situatie dat het leegstandscontract al is geprolongeerd en de situatie dat het nog niet is geprolongeerd. 

1. Klik op de bladwijzer **Verhuurmutaties** in het rolcentrum. De ljjst met openstaande verhuurmutaties wordt geopend. 
2. Zoek en open de verhuurmutatie waarop de aanvraag betrekking heeft. 
3. Klik op **Navigeren nieuwe verhuring** en kies voor **Verhuuraanbieding**. 
4. Klik op **Beheren** en kies voor **Verwijderen**. De gerelateerde verhuuraanbieding wordt verwijderd. 
5. Klik op **Navigeren vertrekkende huurder** en kies voor **Huuropzegging**. De huuropzeggingskaart wordt geopend met details van de huuropzegging. 
6. Open tabblad **Inspectie** en klik op de link in het veld **Onderhoudsverzoeknr.**. Een pagina met details het het gerelateerde onderhoudsverzoek wordt geopend. 
7. Klik op **Verwerken** en kies voor **Onderhoudsverzoek annuleren**. Het onderhoudsverzoek wordt geannuleerd. Sluit de pagina en keer terug naar de pagina met details van de verhuurmutatie. 
8. Klik op **Navigeren OG Eenheid** en kies voor **Contractoverzicht**. Een pagina met de contractregels van de OG Eenheid wordt geopend. 
9. Bekijk de **Exploitatietoestandstype** en **Status** van de eerste (bovenste) contractregel. 
10. Als u in stap 9 heeft geconstateerd dat de **Exploitatietoestandstype** gelijk is aan *Leegstand* en de **Status** gelijk is aan *Nieuw*, sluit dan de pagina **Contractoverzicht** en klik op **Navigeren vertrekkende huurder** en kies voor **Huuropzegging**. De huuropzeggingskaart wordt geopend met details van de huuropzegging. 
11. Klik op **Beheren** en kies voor **Verwijderen**. Het systeem verwijdert de huuropzegging en verwijdert ook de gerelateerde contractregel met **Exploitatietoestandstype**  *Leegstand*. Als gevolg daarvan wordt de einddatum van de laatste contractregel  **Exploitatietoestandstype**  *Verhuur* gewist, zodat het verhuurcontract van de klant niet meer is beëindigd. 
12. Als u in stap 9 heeft geconstateerd dat de **Exploitatietoestandstype** gelijk is aan *Leegstand* en de **Status** gelijk is aan *Nieuw*, klik dan op **+Nieuw**. Een nieuwe contractregel wordt aangemaakt. 
13. Vul de kolom **Ingangsdatum** met een datum die één dag vóór de ingangsdatum van de leegstandscontractregel ligt en de kolom **Klantnummer** met het nummer van de klant die de huuropzegging annuleert. 
14. Klik op een andere contractregel in het overzicht. Het systeem slaat de nieuwe verhuurcontractregel op. Als gevolg daarvan wordt de leegstandscontractregel logisch verwijderd. De nieuwe verhuurcontractregel heeft dezelfde eigenschappen (elementen, bedragen, aanbiedingsvorm, aanbiedingssoort, etc.) als de voorgaande verhuurcontractregel. 
15. Sluit de pagina **Contractoverzicht** en keer terug naar de pagina met details van de verhuurmutatie. 
16. Klik op **Navigeren vertrekkende huurder** en kies voor **Huuropzegging**. De huuropzeggingskaart wordt geopend met details van de huuropzegging. 
17. Activeer de indicatie **Eindafrekening verzonden**. Als gevolg hiervan wordt de indicatie **Huuropzegging afgehandeld** automatisch geactiveerd. 
  

## Zie ook

[Aanbieden eenheid](../aanbieden-eenheid/)  
[Beheren verhuurbare eenheidsinformatie](../beheren-verhuurbare-eenheidsinformatie/)  
[Bepalen aanbiedhuur](../bepalen-aanbiedhuur/)  
[Innemen eenheid](../innemen-eenheid/)  
[Ondertekenen huurovereenkomst](../ondertekenen-huurovereenkomst/)  
[Opleveren eenheid](../opleveren-eenheid/)  
[Opstellen eindafrekening](../opstellen-eindafrekening/)  
[Registreren huuropzegging](../registreren-huuropzegging/)  
[Verantwoorden verhuring](../verantwoorden-verhuring/)  
