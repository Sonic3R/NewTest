# Voorbereiden onderhoudsproject

Alle uitvoeringsactiviteiten van de jaarbegroting zijn ingelezen in Dynamics Empire en moeten worden samengevoegd tot een gecombineerde uitvoering. De projecten worden in Dynamics Empire aangemaakt.

## Informeren huurders

De goedgekeurde plannen moeten worden gecommuniceerd met de huurders. Dit kan door de plannen in één overzicht te presenteren op de website en/of het **Klantportaal** (achter de inlog, door middel van Nieuwsberichten).

## Samenstellen projecten

### Het verwerken van de begrotingsregels

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar het **Kladblokimportoverzicht**. Selecteer de juiste regel en klik op **Bewerken**.
2. Uitgangspunt is hier dat de begrotingsregels compleet zijn (zie **Kladblokimportregels**). Dat wil zeggen: in de begrotingsregels is de samenstelling van de projecten al bepaald (**Sjablooncode**). Daarnaast is bepaald wie de projecten zal uitvoeren (projectleider, toezichthouder, woonconsulent, contractbeheerder). Tevens in de initiële planning bepaald (start en opleverdatum).
2. Om de regels te verwerken kiest u voor de actie/functie **Samenvoegen alle regels op basis van Sjablooncode**. Dynamics Empire zal alle **Kladblokimportregels** samenvoegen of kopiëren naar het deel **Voorlopige projectregels** op de kaart, waarbij onderstaand beschreven bewerking wordt uitgevoerd.

### Samenvoegen

Het samenvoegen van begrotingsregels is nodig om de vele regels terug te brengen naar een ingedikte vorm ten behoeve van de budgetbewaking. De stelregel is dat u de begroting zo gedetailleerd mogelijk overzet naar Dynamics Empire, zodat u in Dynamics Empire kunt terugzien hoe een project begroot is. Dit is nodig om budgetoverschrijdingen te kunnen verklaren. Echter, op dit detailniveau is het niet wenselijk om budgetten te bewaken.
Aan het samenvoegen zijn voorwaarden verbonden. De begrotingsregels dienen te zijn opgebouwd uit dezelfde waarden voor **Cluster**, **Bouwblok**, **Werksoort**, **Werksoortboekingsgroep**, **Sjablooncode** en **Vrije code budget**. Alle regels die dezelfde sjablooncode hebben moeten in één keer worden aanbesteed. De samengevoegde regel is terug te vinden op kaartdeel **Voorlopige projectregels**.
Overigens kunnen begrotingsregels voor contractonderhoud en serviceonderhoud zelden worden samengevoegd, omdat hier meestal één regel per cluster wordt begroot.

Alle regels die niet kunnen worden samengevoegd, worden gekopieerd van tabblad **Kladblokimportregels** naar **Voorlopige projectregels**.

De sjablooncode wordt bij de bewerking **Samenvoegen alle regels op basis van Sjablooncode** gekopieerd naar kolom **Voorlopig projectnummer** op tabblad **Voorlopige projectregels**. Alle regels met hetzelfde voorlopige projectnummer zullen bij het aanmaken van onderhoudsprojecten gekoppeld worden onder één project. De sjablooncode in deze kolom is indien nodig aan te passen.

### Het oplossen van samenvoegingsconflicten

Wanneer regels voldoen aan de criteria om te worden samengevoegd, maar de **Projectomschrijving**, **Contactpersonen**, **Plaats** of vrije tekstvelden van die regels verschillen, dan treedt er een samenvoegingsconflict op. Dit is te zien aan een 'Ja' in kolom **Samenvoegingsconflict** op tabblad **Voorlopige projectregels**.

1. Klik op 'Ja' in kolom **Samenvoegingsconflict** om de oorspronkelijke regels te tonen.
2. Los het conflict op door de veroorzakende waarde in het betreffende veld aan te passen.
3. Doorloop op deze wijze alle samenvoegingsconflicten en los ze één voor één op.

>**Tip!** Plaats een filter op alle regels met een samenvoegingsconflict voordat u gaat werken aan het oplossen van conflicten.

### Functie instellen voor contactpersonen

1. Op tabblad **Functies** bvan de Kladblokbudgetimportkaart kunt u instellen welke rolcode toegekend moet worden aan de contactpersonen bij het aanmaken van projecten.

### Aanmaken van onderhoudsprojecten

1. Controleer voor het aanmaken van onderhoudsprojecten of alle regels op tabblad **Kladblokimportregels** zijn verwerkt. Dit is het geval als het clusternummer groen kleurt. Met de optie **Gekopieerde regels verbergen** (bovenin het tabblad, onder **Beheren**) kunt u snel controleren of alle regels zijn verwerkt. Met de optie **Gekopieerde regels tonen** brengt u ze weer in beeld.
>**Tip!** Als regels niet zijn verwerkt, dient u deze handmatig te kopiëren of samen te voegen. Selecteer hiervoor de niet-verwerkte regels en kies voor **Kopiëren** of **Samenvoegen**. Is hierbij een foutje gemaakt, verwijder dan de gekopieerde/samengevoegde regel van
tabblad **Voorlopige projectregels**.
2. Plaats nu een vinkje in veld **Definitieve versie** op tabblad **Algemeen**.
3. Maak nu *een nieuwe taak* aan voor de persoon die een en ander dient goed te keuren.
      1. Ga via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Gebruikerstaken**.
      2. Klik op **+ Nieuw** en vul de verschillende velden in, waaronder in ieder geval **Onderwerp**, **Toegewezen aan gebruiker**, **Taak koppelen aan** en **Rapport**.
      3. Specificeer in het veld **Taakbeschrijving** wat er van de persoon wordt verwacht (bijvoorbeeld "Ik ben klaar met de voorbereiding, graag controleren en projecten aanmaken.") en licht zonodig de exacte locatie in Dynamics Empire toe.
      4. De betreffende gebruiker krijgt hiervan een notificatie op zijn startpagina in het mapje **Mijn gebruikerstaken**.
4. De controle waar in de vorige stap om gevraagd wordt houdt in dat gecheckt wordt of het totaalbedrag in dit scherm overeenkomst met het bedrag dat door de bestuurder is goedgekeurd voor Planmatig onderhoud (velden **Regelbedrag excl. BTW** en **Regelbedrag incl. BTW**). Voer indien gewenst een detailcontrole uit.
5. Kies nu voor de functie **Aanmaken onderhoudsprojecten**.
6. Na het voltooien van deze actie geeft Dynamics Empire aan dat er een X aantal projecten is aangemaakt. Klik op **OK** om de melding te sluiten.
Er kunnen vanaf dit moment geen wijzigingen meer worden aangebracht op de **Kladblokbudgetimportkaart**. Alle correcties van fouten in de voorbereiding dienen in de projectadministratie te worden gecorrigeerd.
7. Maak een taak aan (zie stap 3), gericht aan uw collega die de Projectvoorbereiding heeft uitgevoerd, en geef de stand van zaken door (bijvoorbeeld "Er zijn 5 onderhoudsprojecten aangemaakt.").
8. Sluit de Kladblokbudgetimportkaart.

### Verbeteren projectnaam en omschrijving

Het verbeteren van projectnaam en -omschrijving is een actie die de projectleider moet uitvoeren, direct na het aanmaken van onderhoudsprojecten. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projectoverzicht**.
2. Open een projectkaart door de juiste regel te selecteren en op **Bewerken** te klikken.
3. Op de **Projectkaart** is op tabblad **Algemeen** een **Naam** en **Omschrijving** te zien. Deze worden door het systeem bepaald op basis van de bovenste voorlopige projectregel op de Kladblokbudgetimportkaart en dekken mogelijk niet de lading voor alle regels die aan het project zijn gekoppeld. Deze regels zijn terug te zien op tabblad **Budgetregels**. Doorloop alle projecten en pas waar nodig de **Naam** en **Omschrijving** aan. U kunt hiervoor gebruik maken van de pijlknoppen links en rechts in het scherm, aan weerszijden van de projectkaart.

## Plannen projecten

De projecten worden gepland (uitvoeringsjaar) en voor ieder afzonderlijk project wordt de projectorganisatie vastgesteld. Zowel de planning (start- en einddatum) als de projectorganisatie worden in de projectadministratie vastgelegd.

### Projecten plannen (MS-Project)

Wanneer voor het plannen van activiteiten gebruik gemaakt wordt van **MS-Project**, dienen projecten te worden doorgezet naar MS-Project (integratie Dynamics Empire en MS-Project). Vanaf dat moment vindt synchronisatie plaats van start- en einddatum tussen MS-Project en de projectadministratie.

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar **Projectoverzicht** en open het juiste project door de regel te selecteren en op **Bewerken** te klikken.
2. Vul op tabblad **Algemeen** de **Startdatum** en **Opleverdatum** in.
3. Kies voor de actie **Openen in MS Project**. Hiermee wordt het betreffende project in MS Project geopend. Als er nog geen project in MS Project bestond, moet dit eerst worden aangemaakt (geëxporteerd). Als er al eerder een export vanuit Dynamics Empire naar MS Project heeft plaatsgevonden, dan wordt het bestaande projectplan geopend en getoond.
>Afhankelijk van de instelling worden óf de werksoorten en resources óf de projectfases vanuit Dynamics Empire naar MS-Project geëxporteerd. 
4. Kies voor de actie **Vanuit MS Project importeren**. Hiermee worden de data van het betreffende project van MS Project in Dynamics Empire geïmporteerd. Bij de import worden alleen de datumvelden van in Dynamics Empire bestaande regels (fasen of werksoorten) geactualiseerd. Er worden geen nieuwe regels (in MS Project: taken) aangemaakt of verwijderd in Dynamics Empire. Bij het importeren wordt ook de in MS Project ingestelde voorgaande planningsactiviteit (predecessor) geïmporteerd, zodat deze bij een nieuwe export weer wordt aangemaakt. Deze voorganger is onder Microsoft Dynamics NAV niet muteerbaar en er wordt geen rekening mee gehouden met de start- en einddatumcontrole.
5. Kies voor de actie **Naar MS Project exporteren**. Hiermee worden de data van het betreffende project vanuit Dynamics Empire naar MS Project geëxporteerd. Het project wordt direct in MS Project geopend.

### Toevoegen contactpersonen aan project

1. Het toevoegen van een contactpersoon binnen een project kan op het tabblad **Contactpersonen**. Klik daartoe onder **Beheren** (bovenin tabblad) op **Nieuwe regel**, of klik in een lege regel in het veld **Contactnr.**.
2. Klik op het dropdown-pijltje en selecteer de juiste contactpersoon.
3. Voer vervolgens (indien van toepassing) de **Functiecode**, **Bedrijfsnaam**, **Telefoon** en **E-mail** in.
4. De contactpersoon staat nu gekoppeld aan het project. Dit is ook terug te vinden op het tablad Algemeen; de drie contactpersonen met de hoogste prioriteit worden daar getoond.

## Uitwerken plan


