# Publiceren eenheid

De beschikbare eenheid wordt gepubliceerd, zodat woningzoekenden kunnen reageren op de eenheid. Hierbij wordt ervan uitgegaan dat de eenheid via de standaard VERA-WRV-koppeling wordt gepubliceerd in een extern woonruimteverdeelsysteem, zoals WoningNet of ZIG.
Het publiceren gaat in twee stappen: voorbereiden van de publicatie in Dynamics Empire en daadwerkelijk publiceren van de eenheid in het woonruimteverdeelsysteem. Nadat de publicatie is gesloten, worden de reacties van de woningzoekenden verwerkt en wordt de rangorde van de kandidaten bepaald in het woonruimteverdeelsysteem.  

## Voorbereiden publicatie

In deze stap bereidt u de publicatie van de beschikbare eenheid voor. Deze voorbereidende stap vindt plaats in Dynamics Empire. Daarbij verzamelt u alle details over de eenheid, de publicatie en de huurprijs waarvoor de eenheid wordt gepubliceerd.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verhuurmutaties**.
2. Zoek de verhuurmutatie op waarvan de publicatie moet worden voorbereid en open de detailpagina van de verhuurmutatie door op het nummer te klikken.
3. Navigeer naar de **Beschikbare OG Eenheid**.  Een pagina verschijnt waarop alle details van de beschikbare OG Eenheid worden verzameld die naar het externe woonruimteverdeelsysteem worden verstuurd.  Mocht u in plaats daarvan een foutmelding krijgen, kies dan eerst voor **Verhuuraanbieding** en klik daarna op **Voorbereiden beschikbare OG Eenheid**.  Dan verschijnt de genoemde pagina alsnog.
4. Controleer de details op tabbladen **Adres** en **OG Eenheid-eigenschappen** van de beschikbare eenheid. Als deze details niet juist of volledig zijn, navigeer dan naar **OG Eenheid** of naar de **VERA-eigenschappen**. De onroerendgoedeenheidkaart resp. de pagina met meervoudige VERA-eigenschappen wordt geopend waarop u de onjuiste of ontbrekende details kunt aanpassen of aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de gegevens automatisch zijn bijgewerkt.
5. De details op het tabbladdeel getiteld **Vertrekken** zijn afkomstig uit de versie van de **Woningwaardering** die geldig is op de **Verhuurbaar-per-datum**. Elke regel onder **Vertrekken** komt overeen met een **Vertrek** of **Overige ruimte** die aanwezig is in de woningwaardering van de OG Eenheid en die is gerelateerd aan een **VERA-ruimtesoort**.
6. Als de details onder kopje **Vertrekken** niet juist of volledig zijn, navigeer dan naar de **Woningwaardering** van de OG Eenheid, maak een nieuwe versie aan van de woningwaardering waarin u de onjuiste of ontbrekende details kunt aanpassen resp. aanvullen. Klik op **Sluiten**. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt.
7. De details op het tabbladdeel getiteld **Elementen** zijn afkomstig uit het **Aanbiedingscontract** van de **Verhuuraanbieding**.  Als de verhuuraanbieding meerdere aanbiedingscontracten heeft, dan worden de details overgenomen uit het aanbiedingscontract met een ingevulde en gefiatteerde huurprijsmutatie.
8. Als de details onder kopje **Elementen** niet juist of volledig zijn, sluit dan de pagina, navigeer naar de **Verhuuraanbieding** met status 'Lopende aanbieding', selecteer het juiste **Aanbiedingscontract** en klik op **Aanbiedhuur**. Als een element een verkeerd bedrag bevat, pas dan de eenheidsprijs van dat element aan. Als een element ontbreekt, voeg dan het element toe aan het aanbiedingscontract. Sluit de pagina. U keert terug naar de pagina met details van de beschikbare OG Eenheid, waarop de details automatisch zijn bijgewerkt.
9. De details onder kopje **Prijscomponenten** zijn automatisch afgeleid van de details onder kopje **Elementen** op dit tabblad. 
10. Tabblad **OG Eenheidvoorwaarden** bevat een specificatie van de voorwaarden waaraan een kandidaat moet voldoen, wil hij in aanmerking komen voor het huren van de OG Eenheid. De standaardwaarden van deze gegevens zijn afkomstig uit de **WRV-eenheidvoorwaardenset** die betrekking heeft op de **VERA-doelgroep** van de OG Eenheid. Pas deze voorwaarden daar waar nodig aan.
11. Tabblad **Publicatie** bevat details over de publicatie van de eenheid in het woonruimteverdeelsystseem. Een deel van de details is afkomstig van de pagina **OG Eenheidkaart**, tabblad **WRB**, en alleen op die pagina wijzigbaar. De waarde van het detail **Opleverdatum** is gelijk aan de waarde van het detail **Verhuurbaar per datum** (zie tabblad **Algemeen**).
12. Tabblad **Vorige huurder** bevat details over de vorige huurder van de OG Eenheid. De **Vertrekdatum** is gelijk aan de einddatum van het opgezegde huurcontract, dat wil zeggen: het contract dat via de huuropzegging is gekoppeld aan de verhuuraanbieding. U kunt deze datum wijzigen. De overige details zijn afkomstig van de klant die is gekoppeld aan het opgezegde huurcontract. Als u deze velden leeg maakt op deze pagina, worden de gegevens over de vorige huurder niet naar het extern woonruimteverdeelsysteem gestuurd.
13. Zodra u constateert dat alle details juist en volledig zijn, klikt u op **Berichten versturen** | **Versturen beschikbaarheidsbericht**.  Zodoende stuurt u een bericht met alle getoonde details naar het woonruimteverdeelstysteem dat is vermeld op tabblad **Algemeen**.  

## Publiceren eenheid 

In deze stap publiceert u daadwerkelijk de eenheid, zodat woningzoekenden de eenheid kunnen vinden en kunnen reageren op de eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem.  

1. Login in het externe woonruimteverdeelsysteem.
2. Zoek de voorbereide eenheid op waarvan u de gegevens vanuit Dynamics Empire naar het woonruimteverdeelsysteem hebt gestuurd.
3. Controleer de gegevens op juistheid en volledigheid. Als blijkt dat er nog gegevens uit Dynamics Empire ontbreken, ga dan terug naar de vorige stap **[Voorbereiden publicatie](#voorbereiden-publicatie)**. Vul daar waar nodig de publicatie van de eenheid aan met extra gegevens, zoals foto's. Als alle gegevens juist en compleet zijn, publiceer dan de eenheid.  

## Verwerken reacties  

In deze stap verwerkt u de reacties van woningzoekenden op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem.

## Bepalen rangorde  

In deze stap bepaalt u de rangorde van de kandidaten die hebben gereageerd op de gepubliceerde eenheid. Deze stap vindt plaats in het externe woonruimteverdeelsysteem.

## Zie ook

[Beheren woningzoekende-informatie](../beheren-woningzoekende-informatie)  
[Selecteren kandidaten](../selecteren-kandidaten)  
[Toewijzen eenheid](../toewijzen-eenheid)  
