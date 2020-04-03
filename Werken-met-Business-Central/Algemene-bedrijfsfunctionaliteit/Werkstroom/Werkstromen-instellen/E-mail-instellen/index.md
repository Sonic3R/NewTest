# E-mail instellen

Als u e-mails wilt versturen en ontvangen in Business Central, moet u de velden op de pagina SMTP-mailinstellingen invullen.

In plaats van de SMTP-serverdetails handmatig in te voeren, kunt u de functie **Office 365 Server-instellingen toepassen** gebruiken om ze in te voeren met informatie uit uw Office 365-abonnement.

U kunt uw e-mail handmatig instellen, zoals hieronder beschreven, of u kunt hulp krijgen door de begeleide instelling **Instelling van e-mail** te gebruiken.

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **SMTP-e-mailinstellingen** in en kies de desbetreffende koppeling.
2. Vul de velden in. Wijs een veld aan om een korte omschrijving te lezen.

    > [!NOTE]
    > Als u een account gebruikt waarvoor tweefactorauthenticatie is vereist, moet het wachtwoord dat u invoert in het veld **Wachtwoord**, hetzelfde zijn als het wachtwoord dat u gebruikt voor uw Office 365-abonnement en moet het van het type **App-wachtwoord** zijn.
3. Of u kiest de actie **Office 365 Server-instellingen toepassen** om alle informatie in te voegen die al voor uw Office 365-abonnement is gedefinieerd.
4. Als alle velden correct zijn ingevuld, kiest u de actie **Instelling e-mail testen**.
5. Als de test is geslaagd, sluit u de pagina.

## Een vervangend afzenderadres gebruiken voor uitgaande e-mailberichten

Alle uitgaande e-mailberichten vanuit Business Central gebruiken het standaardadres voor het account dat u hebt opgegeven op de pagina SMTP-e-mailinstellingen, zoals hierboven beschreven. U kunt echter de mogelijkheden **Verzenden als** of **Verzenden namens** op uw Exchange-server gebruiken om het afzenderadres van uitgaande berichten te wijzigen. Business Central zal het standaardaccount gebruiken om te verifiëren bij Exchange, maar zal het afzenderadres vervangen door het adres dat u opgeeft, of het wijzigen met 'namens'.

Hierna volgen voorbeelden van hoe Verzenden als en Verzenden namens worden gebruikt in Business Central.

* Wanneer u documenten zoals inkoop- of verkooporders naar leveranciers en klanten verzendt, wilt u misschien dat ze afkomstig lijken te zijn van een _noreply@yourcompanyname.com_-adres.
* Wanneer uw werkstroom een goedkeuringsverzoek per e-mail verzendt met behulp van het e-mailadres van de aanvrager.

> [!Note]
> U kunt slechts één account gebruiken om afzenderadressen te vervangen. Dat wil zeggen, u kunt niet één vervangend adres hebben voor inkoopprocessen en een ander voor verkoopprocessen.

### Een vervangend afzenderadres instellen voor alle uitgaande e-mailberichten

1. Zoek in het **Exchange-beheercentrum** voor uw Office 365-account de postbus die u als vervangend adres wilt gebruiken en kopieer of noteer het adres. Als u een nieuw adres nodig hebt, gaat u naar uw Microsoft 365-beheercentrum om een nieuwe gebruiker te maken en hun mailbox in te stellen.
2. Kies in Business Central het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **SMTP-e-mailinstellingen** in en kies de desbetreffende koppeling.
3. Voer in het veld **Verzenden als** het vervangende adres in.
4. Kopieer of noteer het adres in het veld **Gebruikersnaam**.
5. Zoek in het **Exchange-beheercentrum** de postbus die u als vervangend adres wilt gebruiken en voer vervolgens het adres uit het veld **Gebruikersnaam** in het veld **Verzenden als** in.

### Het vervangende adres gebruiken in goedkeuringswerkstromen

1. Kies in Business Central het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **SMTP-e-mailinstellingen** in en kies de desbetreffende koppeling.
2. Kopieer of noteer het adres in het veld **Gebruikersnaam**.
3. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Gebruikersinstellingen voor goedkeuring** in en kies de gerelateerde koppeling.
4. Zoek in het **Exchange-beheercentrum** de postvakken voor elke gebruiker die wordt vermeld op de pagina **Gebruikersinstellingen voor goedkeuring** en voer in het veld **Verzenden als** het adres uit het veld **Gebruikersnaam** van de pagina **SMTP-e-mailinstellingen** in Business Central in.
5. Kies in Business Central het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **SMTP-e-mailinstellingen** in en kies de desbetreffende koppeling.
6. Als u vervanging wilt inschakelen, zet u de schakelaar **Vervanging van afzender toestaan** aan.

> [!Note]
> Business Central bepaalt welk adres wordt weergegeven in de volgende volgorde: <br><br> 1. Het adres dat is opgegeven in het veld **E-mail** op de pagina **Gebruikersinstellingen voor goedkeuring** voor berichten in een werkstroom. <br> 2. Het adres dat is opgegeven in het veld **Verzenden als** op de pagina **SMTP-e-mailinstellingen**. <br> 3. Het adres dat is opgegeven in het veld **Gebruikersnaam** op de pagina **SMTP-e-mailinstellingen**.
