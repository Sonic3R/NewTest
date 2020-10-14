# Afhandelen contactmoment

In dit werkproces wordt een contactmoment afgehandeld dat de corporatie heeft met een klant of een ander soort contact. Het contactmoment kan betrekking hebben op een vraag of een klacht.

De term 'vraag' is in dit verband een ruim begrip. Het kan een vraag zijn die wordt afgehandeld door het verstrekken van het juiste antwoord (informatieverstrekking). Het kan ook een verzoek zijn dat kan worden afgehandeld door het uitvoeren van een bepaalde transactie, zoals het afsluiten van een betalingsregeling. Overigens behoort het uitvoeren van de transactie niet tot dit werkproces, maar het geven van terugkoppeling daarover aan de indiener va het verzoek, behoort hier wel toe. Waar in deze werkinstructie wordt gesproken over 'vraag' en 'vraag beantwoorden' wordt de ruime betekenis ervan bedoeld.

Als de vraag direct kan worden beantwoord op het moment dat de vraag wordt gesteld, wordt er slechts één contactmoment vastgelegd waarin zowel de vraag als de terugkoppeling worden vastgelegd.

Als aan de hand van de vraag eerst een vervolgactie moet worden uitgevoerd voordat de vraag kan worden beantwoord, wordt er eerst een contactmoment voor het registreren van de vraag vastgelegd en een taak toegewezen aan het team dat de vervolgactie moet uitvoeren. Vervolgens wordt de taak afgehandeld en een tweede contactmoment vastgelegd voor het terugkoppelen van het antwoord.

Als het contactmoment een klant over de dienstverlening van de corporatie betreft, wordt een contactmoment voor het registreren van de klacht vastgelegd en een taak toegewezen aan het team dat de klacht moet afhandelen. De afhandeling van de klacht vindt plaats in een ander werkproces: **[Afhandelen klacht](../afhandelen-klacht/)**.

In deze werkinstructie wordt ervan uitgegaan dat een contactmoment wordt vastgelegd met behulp van een **Interactiesjabloon**.

## Aanmaken contact

In deze stap maakt u een nieuw contact aan. Dit is alleen nodig als degene die de vraag of klacht heeft gesteld resp. heeft ingediend, nog niet bekend is in Dynamics Empire. Als de vraag of klacht afkomstig is van een rechtspersoon maakt u alleen een contact van het soort Huishouden/bedrijf aan; als het een natuurlijk persoon betreft maakt u daarnaast een bijbehorend contact van het soort Persoon aan.

1. Navigeer via de zoekfunctionaliteit ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Contacten**. Klik op **Nieuw | + Nieuw**, waarna de contactkaart verschijnt. Druk op Tab, waarna het systeem een nieuw contactnummer aanmaakt.
2. Vul de **Initialen**, **Tussenvoegsels** en **Achternaam** van het nieuwe contact in. Het systeem bepaalt aan de hand daarvan automatisch de waarde van het veld **Naam**.
3. Selecteer in veld **Soort** de waarde 'Huishouden / Bedrijf'.
4. Voer op tabblad **Communicatie** het adres van het contact in. Doe dit door in veld **Straat** de postcode en het huisnummer en eventueel het toevoegsel in te voeren (zonder spaties) en vervolgens het veld te verlaten. Het systeem bepaalt automatisch de juiste waarden van de verschillende velden waaruit het adres is opgebouwd.
5. Voer op hetzelfde tabblad de telefoonnummers en het e-mailadres van het contact in.
6. Maak eventueel een persoon aan binnen dit huishouden. Kies hiervoor de actie **Nieuw persoon voor huishouden/bedrijf** in het menu. Selecteer in het scherm **Rollen** de juiste rol (regel) en klik op **OK**. U komt dan op de contactkaart van die persoon, waar u de **Initialen**, **Tussenvoegsels** en **Achternaam** van de persoon in. Het systeem bepaalt aan de hand daarvan automatisch de waarde van het veld Naam. Ga via **Navigeren | Contact | Persoon** naar de **Persoonlijke gegevens** van de persoon en vul de **Geboortedatum** en **Aanhefcode** in.
7. Als u geen persoon aanmaakt, vul dan de bedrijfsnaam in het veld **Achternaam** van het huishouden in. Navigeer naar de bedrijfsgegevens van het huishouden (via **Navigeren | Contact | Bedrijf | Huishouden- / bedrijfsgegevens**) en selecteer de **Aanhefcode** 'BLANCO'.
8. Sluit de pagina('s).

## Vastleggen contactmoment

In deze stap maakt u een contactmoment aan voor het registreren van de vraag of klacht of voor het registreren van de terugkoppeling n.a.v. een vraag. Als de vraag is gesteld door een klant, dan legt u het contactmoment bij de betreffende klant vast. Het systeem koppelt het contactmoment aan het gerelateerde huishouden en toont het bij de *klant*. Alleen als de vraag is gesteld door een andersoortig contact (bijvoorbeeld een woningzoekende of en leverancier), legt u het contactmoment rechtstreeks bij het betreffende *contact* (van het soort **Huishouden/Bedrijf**) vast.

1. Navigeer via de zoekfunctionaliteit ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Klanten** of **Contacten**. Een pagina genaamd **Klanten** resp. **Contacten** verschijnt.
2. Zoek en selecteer de klant resp. het contact van het soort Huishouden/Bedrijf voor wie u het contactmoment wilt vastleggen.
3. Klik op het **Nr.** van de klant of het contact. Een pagina genaamd **Klantkaart** resp. **Contactkaart** wordt geopend met alle details van de geselecteerde klant resp. het geselecteerde contact.
4. Klik op **+ Nieuw** en kies voor **Interactie via sjabloon**. Een popuppagina genaamd **Interactie aanmaken** verschijnt.
5. Selecteer het juiste sjabloon in veld **Sjabloon standaardwaarden** en klik op de Tab-toets.
6. Geef in veld **Toon in klantportaal** aan of u wilt dat het contactmoment al dan niet moeten worden getoond op het klantportaal.
7. Geef in veld **Taak aanmaken** aan of er een vervolgactie moet worden uitgevoerd om de vraag te kunnen beantwoorden.
8. Selecteer in veld **Teamcode** de code van het team waaraan de taak moet worden toegewezen.
9. Leg bij **Notitie** de formulering van de vraag of de formulering van de terugkoppeling vast.
10. Klik op **Voltooien**. Het systeem maakt een *interactielogpost* aan met de gegevens die u heeft ingevoerd en met de eigenschappen die zijn ingesteld in het geselecteerde sjabloon. Als u heeft aangegeven dat er een taak moet worden aangemaakt, dan maakt het systeem bovendien een **taak** aan met de eigenschappen die zijn ingesteld in het geselecteerde sjabloon. Deze taak wordt toegewezen aan alle medewerkers die tot het geselecteerde team behoren.

## Aanmaken en toewijzen taak

Deze stap is automatisch uitgevoerd als u in de vorige stap een contactmoment hebt aangemaakt waarbij u heeft aangegeven dat er ook een taak moet worden toegewezen aan een team. Dit betekent in feite dat alle medewerkers die deel uitmaken van dat team, de taak krijgen toegewezen.

## Afhandelen taak

In deze stap handelt u een taak af die is toegewezen aan een team waarvan u deel uitmaakt. Het afhandelen van een taak verloopt in twee stappen. Ten eerste neemt u de taak in uitvoering, waardoor de taak niet meer zichtbaar is voor de overige medewerkers uit uw team, Vervolgens voert u de benodigde vervolgactie uit en formuleert u de uitkomsten van die vervolgactie in de notitie van de taak.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Teams**. Een pagina verschijnt met een overzicht van alle teams.
2. Selecteer het team waarvan u de taken wilt zien.
3. Navigeer naar de **Taken**. Een pagina verschijnt met een overzicht van alle taken die zijn toegewezen aan het geselecteerde team en die nog niet in behandeling zijn genomen door één van de medewerkers van dat team.
4. Selecteer een taak en kies voor **Bewerken**. Een pagina met de details van de geselecteerde taak wordt geopend.
5. Wijzig de **Status** van de taak in 'In uitvoering'.
6. Wijs de taak aan uzelf toe in het veld **Medewerker**. Hierdoor verdwijnt de taak uit het overzicht van de andere medewerkers die behoren tot het desbetreffende team.
7. Het systeem toont een mededeling en vraagt of u wilt doorgaan. Klik op **Ja**. U heeft de taak nu in behandeling genomen en de taak is nu alleen aan u toegewezen, niet meer aan uw team of aan de andere medewerkers van uw team.
8. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Verkopers/inkopers**. Een pagina verschijnt met een overzicht van alle verkopers en inkopers.
9. Zoek en selecteer uzelf in de lijst.
10. Navigeer naar de **Taken**. Een pagina verschijnt met de details van de geselecteerde taak.  
11. Voer de benodigde vervolgactie uit en formuleer de uitkomst van die acties in de **Notities** van de taak.
12. Zodra de vervolgacties volledig zijn uitgevoerd, past u de **Status** van de taak aan in 'Afgerond'.
13. Het systeem vraagt of u een interactie wilt aanmaken. Klik op **Nee**.

## Zie ook

[Afhandelen klacht](../afhandelen-klacht/)  
[Behandelen zaak](../behandelen-zaak/)  
[Beheren klantinformatie](../beheren-klantinformatie/)  
[Beoordelen verzoek geriefsverbetering/WMO](../beoordelen-verzoek-geriefsverbetering-WMO/)  
[Meten klanttevredenheid](../meten-klanttevredenheid/)
