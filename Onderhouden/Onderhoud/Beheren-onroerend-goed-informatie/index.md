# Beheren onroerend-goed-informatie

Dit werkproces betreft het aanmaken van nieuwe onroerendgoed-eenheden en het beheren van algemene informatie over die eenheden, dat wil zeggen: informatie die nodig is voor andere doeleinden dan het verhuren van de eenheden. Dit betreft o.a.:

- adres van de eenheid, inclusief koppeling met CBS-buurt, CBS-wijk en gemeente;
- koppeling van een BAG-verblijfsobject aan de eenheid;
- toewijzen van dimensiewaarden aan de eenheden t.b.v. het boeken van eenheidsgebonden kosten en opbrengsten;
- gegevens voor het onderhouden van de eenheid, m.n. onderhoudsvormen en vraagboomsoort;
- WOZ-gegevens van de eenheid;
- cartotheekitems van de eenheid.

## Aanmaken nieuwe eenheid

In deze stap maakt u een nieuwe OG Eenheid aan, inclusief het unieke eenheidsnummer en de koppeling aan een eenheidstype en eenheidsdetailsoort.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Klik op **Nieuw** | **+ Nieuw**. Een pagina verschijnt waarop u de nieuwe eenheid kunt aanmaken met bijbehorende basisgegevens.
3. Het systeem genereert automatisch een uniek nummer en toont deze waarde in veld **Nr.**
4. Ga met de cursor in het veld **Straatnaam** staan en type in dit veld achter elkaar (zonder spaties) de postcode, het huisnummer en eventueel het toevoegsel van de nieuwe eenheid (bijvoorbeeld: '3904NJ4').
5. Verlaat het veld **Straatnaam**. Het systeem vult automatisch alle velden van het adres met de juiste waarden.
6. Het systeem koppelt aan de hand van de postcode/huisnummer-combinatie automatisch de juiste **CBS-buurt**, **CBS-wijk** en **Gemeente** aan de OG Eenheid.
7. De **Status** van de eenheid is standaard gelijk aan 'In ontwikkeling'.
8. Navigeer naar **Verhuurcontracten**. De pagina **Contractoverzicht** wordt geopend. Het systeem heeft standaard een contractregel aangemaakt met **Exploitatietoestandstype** gelijk aan 'In ontwikkeling'. Deze contractregel bevat per definitie geen **Elementen**, zodat prolongatie van deze regel niet leidt tot prolongatiefacturen, noch tot prolongatieposten (boekingen). Pas eventueel de **Ingangsdatum** of het **Exploitatietoestandstype** van deze contractregel aan. Sluit de pagina.
9. Selecteer de **Eenheidstype** waartoe de nieuwe eenheid behoort in veld **Type** op tabblad **Algemeen**.
10. Selecteer de **VERA-eenheiddetailsoort** waartoe de eenheid behoort in veld **Eenheiddetailsoort** op tabblad **VERA-eigenschappen**.

## Aanpassen adres

In deze stap past u het adres van een bestaande eenheid aan.
 
1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de OG Eenheid waarvan u het adres wilt aanpassen.
3. Ga met de cursor in het veld **Straatnaam** staan en vervang de huidige waarde door de combinatie van (achter elkaar, zonder spaties) de postcode, het huisnummer en eventueel het toevoegsel van de bestaande eenheid in (bijvoorbeeld: '3904NJ4').
4. Verlaat het veld **Straatnaam**. Het systeem vult automatisch alle velden van het adres met de juiste waarden.
5. Het systeem koppelt aan de hand van de postcode/huisnummer-combinatie automatisch de juiste **CBS-buurt**, **CBS-wijk** en **Gemeente** aan de OG Eenheid.

## Koppelen BAG-verblijfsobject

In deze stap koppelt u een BAG-verblijfsobject aan een OG Eenheid. Dit kunt u doen voor een individuele OG Eenheid of in bulk voor alle OG Eenheden. Voor een individuele eenheid gaat u als volgt te werk.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de OG Eenheid waaraan u een BAG-verblijfsobject wilt koppelen.
3. Klik op **Acties** en kies voor **BAG-verblijfsobject koppelen**.
4. Aan de eenheid wordt automatisch het **BAG-verblijfsobject** gekoppeld waartoe een **Nummeraanduiding** behoort met dezelfde combinatie van **Postcode**, **Huisnummer**, **Huisletter** en **Huisnummertoevoeging** als de OG Eenheid. Als er meerdere nummeraanduidingen zijn die matchen met deze combinatie, dan wordt het BAG-verblijfsobject gekoppeld waarvan de nummeraanduiding de meest recente ingangsdatum heeft.
5. Het adres van het gekoppelde BAG-verblijfsobject wordt getoond op tabblad **Adressen**. Het ID van het gekoppelde BAG-verblijfsobject wordt getoond op tabblad **Algemeen**.

Om BAG-verblijfsobjecten in bulk toe te wijzen aan alle eenheden gaat u als volgt te werk.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **BAG Import**.
2. Klik op **Eenheid bij BAG zoeken**. Het systeem gaat nu proberen BAG-verblijfsobjecten te koppelen aan *alle* OG Eenheden in *alle* bedrijven.

## Aanpassen exploitatievorm

In deze stap past u de exploitatievorm van de OG Eenheid aan. Via de exploitatievorm van de OG Eenheid bepaalt u of, en zo ja, op welke manier de OG Eenheid kan worden verhuurd of verkocht. U kunt een exploitatievorm toevoegen of juist verwijderen bij de OG Eenheid. Elke exploitatievorm is van een bepaald soort ('Verhuur', 'Verkoop' of 'Uit beheer') en bestaat uit een combinatie van **Aanbiedingssoort** en **Aanbiedingsvorm**.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken.
3. Navigeer naar de **Exploitatievormen**.  Een pagina wordt geopend met de exploitatievormen die momenteel zijn gekoppeld aan de OG Eenheid.
4. Om een extra exploitatievorm toe te voegen aan de OG Eenheid, klik op **Nieuw**, selecteer een **Soort**,  klik op de drie puntjes in de kolom **Aanbiedingssoort**, selecteer een regel en klik op **OK**.
5. Om een bestaande exploitatievorm te verwijderen van de OG Eenheid, selecteer een regel en klik op **Verwijderen**.

## Aanpassen bestemming 

In deze stap past u de bestemming van de OG Eenheid aan. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3. Selecteer een nieuwe waarde in veld **Bestemming** op tabblad **VERA-eigenschappen**. 
4. Selecteer een nieuwe waarde in veld **Huidig labelconditie** op tabblad **Exploitatie (Alg)**.

## Toewijzen dimensiewaarden

In deze stap wijst u dimensiewaarden toe aan een OG Eenheid. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2. Selecteer de OG Eenheid waaraan u een dimensiewaarde toe wilt voegen. Navigeer naar **Dimensies**. 
3. Geef in de kolom **Dimensiecode** aan welk type dimensiewaarde u toe wilt voegen. 
4. Geef in de kolom **Dimensiewaardecode** de dimensiewaarde op.

## Aanpassen gegevens t.b.v. onderhoud

In deze stap passen we de gegevens aan t.b.v. het onderhoudsproces op de Onr. Goed-Eenhedenpagina. Het betreft de volgende gegevens: 
- Onderhoudsvorm  
- Vraagboomsoort  
- Voorkeursleverancier(s)  
- Mutatietype  
- Inspectiegegevens  

### Onderhoudsvorm

Per woning kunnen verschillende afspraken gelden ten aanzien van het uit te voeren onderhoud. Denk hierbij bijvoorbeeld aan woningen die zijn verkocht, maar waar het casco-onderhoud nog wel door de corporatie wordt uitgevoerd. Ook veranderingen in beleid, zoals bijvoorbeeld sloop op termijn, kunnen een verandering in onderhoudsniveau met zich meebrengen. Om deze diversiteit aan mogelijkheden vast te leggen, beschikt Dynamics Empire over een *onderhoudsvorm*. Deze wordt gekoppeld aan de reparatiesjabloon en kan door middel van deze koppeling de eindgebruiker ondersteunen in het nemen van de juiste beslissing ten aanzien van uit te voeren werkzaamheden. 

1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2.	Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3.	Navigeer naar de onderhoudsvormen via menu-item **Onderhoudsvorm**. Een pagina wordt geopend met de onderhoudsvormen die momenteel zijn gekoppeld aan de OG Eenheid. 
4.	Klik op **+Nieuw** om een extra onderhoudsvorm toe te voegen aan de OG Eenheid.
5.	Geef in de kolom **Ingangsdatum** aan per wanneer de onderhoudsvorm actief moet zijn.
6.	Selecteer vervolgens een **Onderhoudsvorm**. 
7.	Om een bestaande onderhoudsvorm te verwijderen van de OG Eenheid, selecteert u een regel en klikt u op **Verwijderen**.

### Vraagboomsoort

De vraagboom voor onderhoudsverzoeken kan worden gebruikt om op eenvoudige wijze onderhoudsverzoeken vast te leggen. Door een specifieke reeks vragen te doorlopen komt de gebruiker (of op het Klantportaal: de klant/huurder) tot een volledig ingevuld onderhoudsverzoek. Een vraagboom kan worden ingericht per vraagboomsoort. Het geeft aan welke ruimte, welk bouwelement en mogelijk gebrek een relatie heeft met een reparatiesjabloon. U koppelt als volgt een vraagboomsoort aan de OG Eenheid.

1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2.	Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3.	Open tabblad **Type**. Het veld **Vraagboomsoort** is al gevuld met een defaultwaarde die meegegeven wordt vanuit het eenheidstype. 
4.	Als u de defaultwaarde wilt wijzigen, dan kan dat door hier via de lookup rechts in het veld een andere waarde te selecteren.

### Voorkeursleveranciers

Veelal zal voor werkzaamheden in bepaalde delen van het bezit dezelfde leverancier worden gekozen. Deze voorkeursleverancier kunt u door het systeem laten invullen in het onderhoudsverzoek. U dient hiervoor de leveranciers aan werkgebieden te koppelen.

1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Werkgebieden**. 
2.	Selecteer het werkgebied waaraan u leveranciers wilt koppelen en klik op **Bewerken**. 
3.	Kies in het menu voor de actie **Leveranciers**. De pagina met daarop de leveranciers per werkgebied wordt geopend. 
4.	Klik op **+Nieuw** om een nieuwe leverancier aan het werkgebied te koppelen.
5.	Zet een vinkje bij **Reparatie-onderhoud** en/of **Overig onderhoud** om aan te geven in welk proces de voorkeursleverancier toegepast moet worden. 

### Mutatietype

Als onderhoud voortkomt uit een huuropzegging, dan is er sprake van *mutatieonderhoud*. In dat geval krijgen we te maken met het **Mutatietype**. Op basis van dit mutatietype wordt een uiterste gereeddatum voor de mutatiewerkzaamheden op het onderhoudsverzoek gezet. Vooraf kan het mutatietype op de eenheidskaart worden vastgelegd. Indien leeg kan deze handmatig worden gevuld op het onderhoudsverzoek, of via de InspectieApp.  
Bij gebruik van mutatietypen wordt de standaard ingestelde urgentiecode overruled door de ingestelde urgentiecode behorend bij het mutatietype. Daarnaast wordt de ‘Verhuurbaar per’-datum op de Huurcontractopzeggingskaart ook aangepast naar aanleiding van de uiterste gereeddatum, die gebaseerd is op de einddatum plus urgentiecode. 
 
1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2.	Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3.	Ga naar tabblad **Inspectie**.
4.	Selecteer in het veld **Mutatietype** het gewenste mutatietype uit de lijst.

### Inspectiegegevens

Inspectiegegevens, zoals aantal in voor- en eindopname en duur in voor- en eindopname t.b.v. mutatieinspecties, worden default vastgelegd bij de eenheidtypen. Het is mogelijk om per eenheid hier van af te wijken. Dit verwerkt u als volgt:

1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2.	Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3.	Ga naar tabblad **Inspectie**. 
4.	Pas eventueel de volgende velden aan: 
      - Aantal vooropnames 
      - Aantal eindopnames 
      - Duur vooropname 
      - Duur eindopname 
      - Termijn eerste vooropname

## Importeren nieuwe WOZ-waarden

In deze stap importeert u nieuwe WOZ-waarden van OG Eenheden, zodat deze per OG Eenheid in de vorm van een nieuwe regel worden toegevoegd in de WOZ-gegevens van die OG Eenheid. U kunt WOZ-waarden in bulk importeren met behulp van een CSV-bestand dat per OG Eenheid één regel met de volgende velden (gescheiden door komma's) bevat: 

- Type = 'WOZ-gegevens'
- OG Eenheidnummer
- WOZ-objectnummer
- WOZ-peildatum
- WOZ-taxatiewaarde
- Jaar vanaf

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **OGE Exploitatie (Fin.)-import**.
2. Een pagina wordt geopend met meerdere tabbladen, waaronder tabblad **WOZ**. Dit tabblad is initieel leeg.
3. Kies voor de actie **Importeren**.
4. Selecteer het CSV-bestand en klik op **OK**.
5. De geïmporteerde gegevens worden vermeld op tabblad **WOZ**.
6. Klik op **Acties** en kies voor **Verwerken**. De geïmporteerde gegevens worden toegevoegd aan de **WOZ-gegevens** van de desbetreffende OG Eenheden.

Ook kunt u handmatig een nieuwe regel toevoegen of een bestaande regel aanpassen in of verwijderen uit de WOZ-gegevens van een individuele OG Eenheid.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de OG Eenheid waarvan u de WOZ-gegevens wilt wijzigen. 
3. Klik op **Navigeren** en kies voor **WOZ-gegevens**. Een pagina wordt geopend met een overzicht met WOZ-waarden van de OG Eenheid.
4. Om een bestaande regel te verwijderen selecteert u de regel en klikt u op **Verwijderen**.
5. Om een bestaande regel aan te passen selecteert u de regel en past u de waarde in de betreffende kolom aan.
6. Om een nieuwe regel toe te voegen selecteert u een lege regel en daarop een **WOZ-peildatum**, voert u de **WOZ-taxatiewaarde** in en voert u het **Jaar vanaf** in.
7. Sluit de pagina.

## Aanpassen cartotheekitems

Voor elke eenheid is het mogelijk om specifieke gegevens vast te leggen met betrekking tot voorzieningen (in bijvoorbeeld keuken en badkamer), de verwarming, het warme water en dergelijke. Deze gegevens worden ingesteld in de zogenoemde cartotheek.
Wanneer nu een onderhoudsverzoek wordt opgevoerd voor een eenheid waarvoor een item is opgenomen in de cartotheek, gaat het systeem een controle uitvoeren op plaatsingsdatum, invoerdatum onderhoudsverzoek, garantietermijn en klachtsoort, bouwelement en ZAV. 

U past als volgt een item aan in de cartotheek: 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**. 
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken. 
3. Navigeer naar de **Cartotheek** (te vinden onder **Onderhoud** in het menu). 
4. Als u een nieuw item wilt toevoegen klikt u op **Nieuw Cartotheek Item**. Klik op de asststedit (…) in het veld **Cartotheekitem**, kies het gewenste cartotheekitem en klik op **OK**.
5. Als u een bestaand item wilt aanpassen selecteert u de juiste regel en kiest u voor **Kaart**. 
6. Loop de tabbladen na en vul de gewenste velden in.

## Aanpassen administratief eigenaar

In deze stap past u een bestaande administratief eigenaar aan (of maakt u een nieuwe aan).

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken.
3. Navigeer naar de **Administratief eigenaar** (in het menu te vinden onder **Exploitatie**) en kies dan de actie **Administratief eigenaar wijzigen**.
4. Vul in het scherm het veld **Ingangsdatum wijziging**. Wanneer u voor het eerst een OG eenheid opvoert is het advies om hier de eerste van de huidige maand te kiezen. Wanneer u een huidige adminstatief eigenaar wijzigt dient de datum in te toekomst te liggen en na de 'geprolongeerd tot'-datum op het contract.
5. Vul in het veld **Nieuwe dimensiewaarde** de nieuwe administratief eigenaar in.
6. Voordat de wijziging doorgevoerd kan worden dient de wijziging goedgekeurd te worden. Dit doet u door op **Goedkeuren** te klikken. Bent u niet gemachtigd om dit te doen, dan dient u dit door een gemachtigd persoon binnen uw organisatie te laten doen. 

## Aanpassen beheerder

In deze stap voert u een nieuwe beheerder op of past u een bestaande aan. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **OG Eenheden**.
2. Selecteer de juiste OG Eenheid en open de kaart door op het nummer te klikken.
3. Navigeer naar de **Beheerder** (in het menu te vinden onder **Exploitatie**).
4. Vul in het scherm dat verschijnt het veld **Startdatum** in.
5. Kies in het veld **Beheerder** een contact dat gekenmerkt is als 'Beheerder'.  
6. Vul eventueel een einddatum in wanneer u een niet langer actieve beheerder wilt deactiveren. 

## Zie ook

[Beheren collectief-object-informatie](../beheren-collectief-object-informatie/)  
[Uitvoeren inspectie naar staat eenheid](../uitvoeren-inspectie-naar-staat-eenheid/)  
[Uitvoeren inspectie-opdracht](../uitvoeren-inspectie-opdracht/)  
[Registreren onderhoudsverzoek](../registreren-onderhoudsverzoek/)  
[Samenstellen onderhoudsorders](../samenstellen-onderhoudsorders/)  
[Bewaken uitvoering onderhoudsorder](../bewaken-uitvoering-onderhoudsorder/)  
[Beoordelen ZAV-aanvraag](../beoordelen-zav-aanvraag/)  
