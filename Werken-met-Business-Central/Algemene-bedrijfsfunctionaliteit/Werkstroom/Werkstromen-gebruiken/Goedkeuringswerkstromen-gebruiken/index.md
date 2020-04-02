# Goedkeuringswerkstromen gebruiken

Wanneer een record, zoals een inkoopdocument of klantenkaart, door iemand in uw organisatie moet worden goedgekeurd, stuurt u een goedkeuringsaanvraag als onderdeel van een werkstroom. Op basis van de instellingen van de werkstroom krijgt de betreffende fiatteur vervolgens het bericht dat hij of zij de record moet goedkeuren.

U stelt goedkeuringswerkstromen op de pagina **Werkstroom** in. Zie voor meer informatie [Werkstromen instellen](../Werkstromen-instellen/).

Naast werkstromen voor goedkeuring die in dit onderwerp worden beschreven kunt u verschillende andere werkstroomtaken uitvoeren. Zie voor meer informatie [Werkstromen gebruiken](../Werkstromen-gebruiken/).

## Goedkeuring van een record aanvragen

De volgende taak wordt uitgevoerd door een fiatteurgebruiker.

1. op de pagina met de record de actie **Goedkeuringsaanvraag verzenden** kiezen.
2. Als u al uw goedkeuringsaanvragen wilt zien, kiest u het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Posten met goedkeuringsaanvraag** in en kies vervolgens de gerelateerde koppeling.  

De status van de goedkeuringsvermelding wordt bijgewerkt van **Gemaakt** naar **Open**. De status van de record, bijvoorbeeld een inkoopfactuur, wordt bijgewerkt van **Open** naar **Wacht op goedkeuring** en blijft voor verwerking vergrendeld totdat alle fiatteurs de record hebben goedgekeurd.

Als de fiatteur de record heeft goedgekeurd, wordt de status gewijzigd in **Vrijgegeven**. U kunt dan uw taken met de record voortzetten.

## Aanvragen voor goedkeuring annuleren

De volgende taak wordt uitgevoerd door een fiatteurgebruiker met fiatteursrechten.

Het kan voorkomen dat een klant wijzigingen wil aanbrengen in een order nadat deze is ingediend ter goedkeuring. In dit geval kunt u het goedkeuringsproces annuleren en de noodzakelijke wijzigingen aanbrengen aan de order voordat u opnieuw goedkeuring aanvraagt.

- op de pagina met de record de actie **Goedkeuringsaanvraag annuleren** kiezen.

Als de goedkeuringsaanvraag is geannuleerd, wordt de status voor de gerelateerde goedkeuringspost veranderd in **Geannuleerd**. De status van de record wordt bijgewerkt van **Wacht op goedkeuring** naar **Open**. Het goedkeuringsproces kan vervolgens opnieuw beginnen.

## Aanvragen voor goedkeuring goedkeuren of afwijzen

De volgende taak wordt uitgevoerd door een fiatteurgebruiker met fiatteursrechten.

U kunt goedkeuringsaanvragen verwerken op de pagina **Aanvragen ter goedkeuring**, bijvoorbeeld om meerdere aanvragen tegelijk goed te keuren. U kunt ook elke aanvraag voor de gerelateerde record verwerken zoals de pagina **Inkoopfactuur**, door de koppeling te kiezen in het bericht dat u ontvangt.

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Aanvragen ter goedkeuring** in en kies vervolgens de gerelateerde koppeling.
2. Selecteer een of meer regels voor de record of records die u wilt goedkeuren of afwijzen.
3. Kies de actie **Goedkeuren**, **Weigeren** of **Delegeren**.

Wanneer een record is goedgekeurd of afgewezen, wordt de goedkeuringsstatus in het veld **Status** gewijzigd in **Goedgekeurd** of **Afgewezen**.

Als er een fiatteurhiërarchie is ingesteld, is de recordstatus **Wacht op goedkeuring** totdat alle fiatteurs de record hebben goedgekeurd. Vervolgens wordt de recordstatus gewijzigd in **Vrijgegeven**.

Tegelijkertijd wordt de goedkeuringsstatus gewijzigd van **Gemaakt** in **Open** zodra een goedkeuringsaanvraag voor de record is gemaakt. Als het verzoek wordt afgewezen, wordt de goedkeuringsstatus gewijzigd in **Afgewezen**. De status blijft **Open** of **Afgewezen** totdat alle fiatteurs het verzoek hebben goedgekeurd.

## Aanvragen voor goedkeuring delegeren

De volgende taak wordt uitgevoerd door een fiatteurgebruiker met fiatteursrechten.

De aanvrager en de goedkeuringsbeheerder kunnen een goedkeuringsaanvraag delegeren aan de vervangende fiatteur om te voorkomen dat documenten zich ophopen of anderszins de werkstroom blokkeren. De vervanger kan een aangewezen vervanger, de directe fiatteur of de goedkeuringsbeheerder zijn, in die volgorde van prioriteit. Deze functie wordt doorgaans gebruikt wanneer een fiatteur niet op kantoor is en aanvragen niet kan goedkeuren voor de vervaldatum.

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Aanvragen ter goedkeuring** in en kies vervolgens de gerelateerde koppeling.
2. Selecteer een of meer regels voor de goedkeuringsaanvragen die u wilt delegeren aan een vervangende fiatteur, en kies vervolgens de actie **Delegeren**.

Er wordt een bericht met het verzoek om de aanvraag goed te keuren, verstuurd naar de vervangende fiatteur.

## Vervallen goedkeuringsaanvragen beheren

De volgende taak wordt uitgevoerd door een fiatteurgebruiker met fiatteursrechten.

Met regelmatige intervallen moet u gebruikers van goedkeuringswerkstromen herinneren aan vervallen goedkeuringsaanvragen waarop ze moeten reageren. Hiervoor gebruikt u de functie **Berichten over achterstallige goedkeuringen verzenden**.

Met de functie **Berichten over achterstallige goedkeuringen verzenden** controleert u op alle openstaande goedkeuringsaanvragen die op dat moment achterstallig zijn. Elke fiatteur waarvoor ten minste één goedkeuringspost achterstallig is, ontvangt een bericht met een overzicht van alle achterstallige goedkeuringsaanvragen. Het bericht wordt ook verzonden naar hun fiatteurs en alle aanvragers die de achterstallige goedkeuringen hebben ingediend. Dit komt van pas wanneer de achterstallige goedkeuringspost moet worden overgedragen aan een vervanger.

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Vervallen goedkeuringsaanvragen** in en kies vervolgens de gerelateerde koppeling.
2. Kies op de pagina **Vervallen goedkeuringsaanvragen** de actie **Berichten over vervallen goedkeuringen verzenden**.
