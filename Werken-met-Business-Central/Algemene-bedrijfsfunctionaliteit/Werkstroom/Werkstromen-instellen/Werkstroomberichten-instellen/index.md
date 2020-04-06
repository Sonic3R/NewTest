# Werkstroomberichten instellen

In veel werkstroomantwoorden wordt aan een gebruiker gemeld dat er een gebeurtenis is opgetreden waarop deze moet reageren. De gebeurtenis in een werkstroomstap kan bijvoorbeeld zijn dat Gebruiker 1 de goedkeuring van een nieuwe record aanvraagt, en het antwoord is dat er een bericht wordt verzonden naar Gebruiker 2, de fiatteur. In de volgende werkstroomstap kan de gebeurtenis zijn dat Gebruiker 2 de record goedkeurt, en het antwoord is dat er een bericht wordt verzonden naar Gebruiker 3, die een gerelateerde bewerking van de goedgekeurde record start. Voor werkstroomstappen die betrekking hebben op goedkeuring, is elk bericht gekoppeld aan een goedkeuringspost. Zie [Werkstroom](../werkstroom/) voor meer informatie.  

> [!NOTE]  
> De algemene versie van Business Central ondersteunt berichten als e-mail en als interne opmerking.  

> [!IMPORTANT]  
> Alle werkstroomberichten worden verzonden via een taakwachtrij. Zorg dat de taakwachtrij in uw installatie is ingesteld om werkstroomberichten te verwerken en dat het selectievakje **Automatisch starten van server** is ingeschakeld. Zie voor meer informatie [Gebruik van taakwachtrijen om taken te plannen](../gebruik-van-taakwachtrijen/).

U stelt verschillende aspecten van werkstroomberichten op de volgende plaatsen in:  

1. Voor goedkeuringswerkstromen kunt u de ontvangers van werkstroomberichten instellen door op de pagina **Gebruikersinstellingen voor goedkeuring** een regel in te vullen voor elke gebruiker die deelneemt aan de werkstroom. Als bijvoorbeeld Gebruiker 2 wordt opgegeven in het veld **Fiatteur-id** op de regel voor Gebruiker 1, wordt het bericht over de goedkeuringsaanvraag verzonden naar Gebruiker 1. Zie voor meer informatie [Goedkeuringsgebruikers instellen](../goedkeuringsgebruikers-instellen/).  
2. U stelt in wanneer en hoe gebruikers werkstroomberichten ontvangen door de pagina **Berichtplanning** in te vullen voor elke werkstroomgebruiker. Zie voor meer informatie [Vastleggen wanneer en hoe gebruikers berichten ontvangen](../opgeven-wanneer-en-hoe-gebruikers-berichten-ontvangen/).  
3. Als u wilt, kunt u de inhoud van het e-mailbericht wijzigen door rapport 1320, Berichte-mail te wijzigen. Zie voor meer informatie [Aangepaste rapportlay-outs maken en wijzigen](../aangepaste-rapportlay-outs-maken-en-wijzigen/).  
4. U stelt specifieke inhoud en regels van een werkstroombericht in als u de betreffende werkstroom maakt. U doet dit door opties te selecteren op de pagina **Opties werkstroomreactie** voor het werkstroomantwoord dat het bericht representeert. Zie voor meer informatie stap 9 in [Werkstromen maken](../werkstromen-maken/).  
