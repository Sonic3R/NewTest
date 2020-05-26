# Beheren financiering

In dit werkproces worden nieuwe leningen aangetrokken en bestaande leningen gemuteerd.

## Vastleggen basisgegevens
Wanneer u een nieuwe financiering aantrekt dient u als eerste de basisgegevens te registreren. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Financieringenoverzicht** en klik op **Nieuw**. 
2. Vul in het scherm dat opent de volgende velden:
	- **Nr.**: Het nummer van de financiering. 
	- **Extern nummer:** Het nummer dat wordt gehanteerd door de geldgever. 
	- **Omschrijving**
	- **Status**: Wanneer u de lening mee wilt nemen in de prolongatie zet u de status op **Akkoord**
	- **Fin. boekingsgroep**: Selecteer hier het type lening. 
	- **Geldgever ID**: Vul het contactnummer van de geldgever
	- **Code transactiewijze**: Selecteer de transactiewijze voor leningen
	- **Code bankrekening**: Selecteer het bankrekeningnummer waarop de rente en aflossingen van de lening betaald dienen te worden. 
3. Onder de sneltab **WSW** kunt u desgewenst extra informatie m.b.t. het WSW kwijt. De velden onder deze sneltab zijn niet verlicht. 
4. Klik in het feitenblok op het blauwe getal achter **Kasstromen (act.model)** en klik in het scherm wat opent op **Nieuw**. 
5. Vul in het veld **Ingangsdatum** de datum van de storting van de leningen in. 
6. Kies in het veld **Soort kasstroom** de kasstroom voor het storten van de hoofdsom. 
7. Vul in het veld **Bedrag** het bedrag wat gestort wordt op deze datum. 
8. Sluit het scherm voor kasstromen om terug te keren naar het scherm met de algemene gegevens van de financiering. 

## Opvoeren financieringsvorm
Nadat u de basisgegevens geregistreerd hebt kunt u de wijze van aflossing, rentebetaling en de rente percentages opgeven. 

1. Klik op de pagina met de algemene leninggegevens in het feitenblok op het blauwe getal achter **Fin.vormen (act.model)** en klik in het scherm wat opent op **Nieuw**. Vul de volgende velden in het scherm dat opent:
	- **Begindatum:** Stortingsdatum van de financiering. 
	- **Looptijd (jaren/maanden)**: De looptijd in jaren
	- **Aflossingswijze**
	- **Periode rentebetaling**: Geef aan om de hoeveel maanden rente betaald dient te worden
	- **Periode rentebepaling**: Zelfde waarde als veld **Periode rentebetaling**
	- **Periode aflossingen**: Geef aan om de hoeveel maanden de aflossing betaald wordt (indien van toepassing). 
	- **Rente prognose**
	- **Rente conventie**
	- **Verschuiving coupondatum**
2. Klik op **Rente percentages**. Vul het rente percentage voor de eerste periode in het veld **Percentage**. 
3. Geef in het veld **Rente vast tot** op tot wanneer het rente percentage geldig is. Wanneer deze datum voor de einddatum van de financieringsvorm ligt wordt er automatisch een regel met code **Renteconversie** aangemaakt. U kunt de velden in deze regel leeg laten. 
4. Sluit het scherm voor rente percentages en vervolgens het scherm financieringsvorm om terug te keren naar het scherm met de algemene gegevens van de financiering. 
5. Klik op **Bijwerken**. In de fasttab **Rente/aflossingsschema** wordt het vervalschema getoont. 

## Controleren en accorderen vervalschema
nadat u de basisgegevens en de financieringsvorm opgevoerd heeft kunt u het vervalschema controleren en accorderen. 

1. Op het scherm met de algemene financieringsgegevens wordt In de fasttab **Rente/aflossingsschema** wordt het vervalschema getoont. Vergelijk de datums en de kasstromen met het aflossingsschema dat u van de geldgever gekregen heeft. 
2. Wanneer de gegeven akkoord zijn kunt u de financieringsgegevens (laten) accorderen. Klik op **Accorderen**. 
3. Wanneer het veld **Status** nog niet op **AKKOORD** staat vul deze waarde nu dan in dit veld. 

## Controleren en accorderen vervalschema
Wanneer er een extra aflossing of extra storting voor de leningen plaats vindt kunt u deze registreren door middel van het opvoeren van een handmatige kasstroom. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Financieringenoverzicht** en open de lening waarvoor u de extra kasstroom op wilt voeren. 
2. Klik in het feitenblok op het blauwe getal achter **Kasstromen (act.model)** en klik in het scherm wat opent op **Nieuw**. 
3. Vul in het veld **Ingangsdatum** de datum van de extra aflossing/storing van de leningen in. 
4. Kies in het veld **Soort kasstroom** de soort kasstroom die van toepassing is. 
5. Vul in het veld **Bedrag** het bedrag wat gestort / afgelost wordt op deze datum. Aflossingen voert u op als negatief bedrag. 
6. Sluit het scherm voor kasstromen om terug te keren naar het scherm met de algemene gegevens van de financiering. 
7. Klik op **Bijwerken**. In de fasttab **Rente/aflossingsschema** wordt het opnieuw berekende vervalschema getoont. 
8. Wanneer het vervalschema correct is kunt u de kasstroom (laten) accorderen. Klik in het feitenblok op het blauwe getal achter **Kasstromen (act.model)** en open de kasstroom die u wilt accorderen. Klik vervolgens op **Accorderen**. 

## Wijzigen rentepercentage
Wanneer het rentepetenrage van een lening wijzigt voert u dit nieuwe percentage op bij de financieringsform. 

1. Navigeer via het zoekveld ![Lampje dat de functie Vertel me opent](https://docs.microsoft.com/nl-NL/dynamics365/business-central/media/ui-search/search_small.png "Vertel me wat u wilt doen") naar **Financieringenoverzicht** en open de lening waarvoor u het rente percentage wilt wijzigen. 
2. . Klik op de pagina met de algemene leninggegevens in het feitenblok op het blauwe getal achter **Fin.vormen (act.model)**.  Klik op **Rente percentages**. Vul het nieuwe rente percentage in op een nieuwe regel. 
3. Sluit het scherm voor rente percentages en vervolgens het scherm financieringsvorm om terug te keren naar het scherm met de algemene gegevens van de financiering. 
4. Klik op **Bijwerken**. In de fasttab **Rente/aflossingsschema** wordt het vervalschema getoont. 
5. Wanneer het vervalschema correct is kunt u het nieuwe rente percentage (laten) accorderen. 
6. Klik op de pagina met de algemene leninggegevens in het feitenblok op het blauwe getal achter **Fin.vormen (act.model)**.  Klik op **Rente percentages**. Selecteer het rente percentage wat u wilt accorderen. Klik vervolgens op **Accorderen**. 


## Zie ook

[Genereren overzicht gerealiseerde kasstromen](../genereren-overzicht-gerealiseerde-kasstromen/)  
[Prognosticeren kasstromen](../prognosticeren-kasstromen/)  
[Prolongeren financiering](../prolongeren-financiering/)
