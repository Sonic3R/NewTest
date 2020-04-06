# Gebruik van taakwachtrijen om taken te plannen

Met taakwachtrijen in Business Central kunnen gebruikers specifieke rapporten en codeunits plannen en uitvoeren. U kunt taken éénmalig of herhaaldelijk uitvoeren. U kunt bijvoorbeeld het statistiekrapport **Verkoper - Statistiek** wekelijks uitvoeren om de verkopen per verkoper wekelijks bij te houden of u kunt de codeunit **E-mailwachtrij service verwerken** dagelijks uitvoeren om ervoor te zorgen dat niet-verzonden e-mailberichten aan klanten met betrekking tot hun serviceorders tijdig worden verzonden.

Op de pagina **Taakwachtrijposten** worden alle bestaande posten weergegeven. Als u een nieuwe taakwachtrijpost toevoegt die u wilt plannen, moet u informatie opgeven over het objecttype dat u wilt uitvoeren, zoals een rapport of codeunit, en de naam en id van het object opgeven dat u wilt uitvoeren. U kunt ook parameters toevoegen om het gedrag van de taakwachtrijpost te specificeren. Zo kunt u een parameter toevoegen om alleen geboekte verkooporders te verzenden. U moet zijn gemachtigd om het betreffende rapport of de betreffende code-unit uit te voeren, want anders wordt een fout geretourneerd wanneer de verwerkingswachtrij wordt uitgevoerd.  

Een taakwachtrij kan veel posten bevatten, die de taken vormen die door de wachtrij worden beheerd en uitgevoerd. Informatie in de post geeft aan welke code-unit of welk rapport wordt uitgevoerd, wanneer en hoe vaak de post wordt uitgevoerd, in welke categorie de taak wordt uitgevoerd en hoe deze wordt uitgevoerd.  

## Boeking op de achtergrond instellen met taakwachtrijen

Taakwachtrijen zijn een effectief hulpmiddel om de uitvoering van bedrijfsprocessen op de achtergrond te plannen, zoals wanneer meerdere gebruikers proberen verkooporders te boeken, maar er slechts één order tegelijk kan worden verwerkt. U wilt mogelijk ook boekingen plannen voor tijden die geschikt zijn voor uw organisatie. Het kan bijvoorbeeld zinvol zijn in uw bedrijf bepaalde routines uit te voeren wanneer de meeste van de gegevensinvoer voor de dag is afgesloten.

U kunt dat bereiken door de taakwachtrij in te stellen om diverse batchboekingsrapporten uit te voeren, zoals **Batchboeken verkooporders**, **Batchboeken verkoopfacturen**, **Batchboeken verk.-retourorders** en **Batchboeken verk.-creditnota**. Zie voor meer informatie [Een taakwachtrijpost maken voor boeking van verkooporders op de achtergrond](#Een-taakwachtrijpost-maken-voort-batchboeking-van-verkooporders).  

Business Central ondersteunt boeken op de achtergrond voor alle verkoop-, inkoop- en servicedocumenten.

> [!NOTE]
> Sommige taken wijzigen dezelfde gegevens en moeten niet tegelijkertijd worden uitgevoerd omdat dat conflicten kan veroorzaken. Met achtergrondtaken voor verkoopdocumenten wordt bijvoorbeeld geprobeerd dezelfde gegevens tegelijkertijd te wijzigen. Taakwachtrijcategorieën helpen dit soort conflicten voorkomen door ervoor te zorgen dat wanneer een taak wordt uitgevoerd, een andere taak die tot dezelfde taakwachtrijcategorie behoort, pas wordt uitgevoerd als de eerste is voltooid. Een taak die bijvoorbeeld behoort tot een taakwachtrijcategorie Verkooptaak wacht tot alle andere verkoopgerelateerde taken zijn voltooid. U geeft een taakwachtrijcategorie op met het sneltabblad **Boeken op achtergrond** op de pagina **Verkoopinstellingen**.
>
> Business Central biedt taakwachtrijcategorieën voor verkoop-, inkoop- en grootboekboeking. We raden aan dat een van deze, of een die u maakt, altijd wordt opgegeven. Als u problemen ondervindt als gevolg van conflicten, kunt u overwegen een categorie in te stellen voor alle verkoop-, inkoop- en grootboekboeking.

In de volgende procedure wordt uitgelegd hoe u achtergrondboeking van verkooporders instelt. De stappen zijn vergelijkbaar voor inkoop en service.  

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Verkoopinstellingen** in en kies de desbetreffende koppeling.
2. Kies op de pagina **Verkoopinstellingen** het selectievakje **Boeken via taakwachtrij**.
3. Als u wilt filteren op taakwachtrijposten voor boeking van verkooporders, kiest u het veld **Taakwachtrijcategoriecode** en selecteert u vervolgens de categorie **Vrkboeking**.

    Er wordt een taakwachtrijobject, codeunit 88 **Verkoopboeking via taakwachtrij** gemaakt. Schakel het in op de pagina **Taakwachtrijposten**.
4. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Taakwachtrijposten** in en kies de desbetreffende koppeling.
5. Kies op de pagina **Taakwachtrijposten** de actie **Nieuw**.
6. Selecteer in het veld **Uit te voeren objecttype** **Codeunit**.  
7. Selecteer in het veld **Uit te voeren object-id** **88**. De velden Beschrijving en Uit te voeren objectbijschrift bevatten Verkoopboeking via taakwachtrij.

    Er zijn geen andere velden van toepassing op dit scenario.
8. Kies de actie **Status instellen op Gereed**.
9. Om te controleren dat de taakwachtrij werkt zoals verwacht, boekt u een verkooporder.
10. Kijk op de pagina **Logposten taakwachtrij** of de verkooporder met succes is geboekt. Zie voor meer informatie [Status of fouten in de projectwachtrij weergeven](#Status-of-fouten-in-de-taakwachtrij-weergeven).

Als u ook wilt dat verkoopdocumenten worden afgedrukt wanneer deze worden geboekt, schakelt u het selectievakje **Boeken en afdrukken via taakwachtrij** in op de pagina **Verkoopinstellingen**.  

> [!IMPORTANT]  
> Wanneer u een taak voor het boeken en afdrukken van documenten instelt en er op de printer een dialoogvenster wordt weergegeven, zoals een verzoek om aanmeldingsgegevens of een waarschuwing over een laag printerinktniveau, dan wordt het document geboekt, maar niet afgedrukt. De overeenkomstige invoer van de taakwachtrij krijgt uiteindelijk een time-out en het veld **Status** wordt ingesteld op **Fout**. Dienovereenkomstig is het raadzaam dat u geen printerinstellingen gebruikt waarvoor interactie met de weergave van printerdialoogvensters nodig is in combinatie met boeken op de achtergrond.

## Een taakwachtrijpost maken voort batchboeking van verkooporders

In de volgende procedure wordt aangegeven hoe u het rapport **Batchboeken verkooporders** instelt om automatisch vrijgegeven verkooporders te boeken om 16:00 uur op werkdagen.  

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Taakwachtrijposten** in en kies de desbetreffende koppeling.  
2. Kies de actie **Nieuw**.  
3. Selecteer in het veld **Uit te voeren objecttype** **Rapport**.  
4. Selecteer in het veld **Uit te voeren object-id** 296, **Batchboeken verkooporders**.
5. Selecteer het selectievakje **Rapportaanvraagpagina**.
6. Definieer op de aanvraagpagina **Batchboeken verkooporders** wat er wordt opgenomen tijdens automatische boeking van verkooporders en kies vervolgens de knop **OK**.
7. Selecteer alle selectievakjes van **Uitvoeren op maandagen** tot en met **Uitvoeren op vrijdagen**.
8. Voer in het veld **Begintijd** 4 PM in.
9. Kies de actie **Status instellen op Gereed**.

Verkooporders die gereed zijn om te boeken worden nu elke werkdag om 16:00 uur geboekt.

> [!NOTE]
> Als de taakwachtrij de verkooporder niet kan boeken, wordt de status gewijzigd in **Fout** en wordt de verkooporder toegevoegd aan de lijst met verkooporders die de gebruiker handmatig moet afhandelen. Zie voor meer informatie [Status of fouten in de projectwachtrij weergeven](#Status-of-fouten-in-de-taakwachtrij-weergeven).

Nadat taakwachtrijen zijn ingesteld en werken, kan de status als volgt veranderen in elke doorlopende periode:

* **Afwachten**  
* **Gereed**  
* **In verwerking**  
* **Fout**  
* **Gereedgemeld**  

Nadat een taak is voltooid, wordt deze verwijderd uit de lijst met taakwachtrijposten, tenzij het een terugkerende taak is. Als het een terugkerende taak is, wordt het veld **Vroegste begintijd** aangepast, zodat het de volgende keer weergeeft dat de taak naar verwachting wordt uitgevoerd.  

## Status of fouten in de taakwachtrij weergeven

Gegevens die worden gegenereerd wanneer een taakwachtrij wordt uitgevoerd, worden opgeslagen in de database, zodat u taakwachtrijfouten kunt oplossen.

### De status voor een taak weergeven

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Taakwachtrijposten** in en kies de desbetreffende koppeling.
2. Selecteer op de pagina **Taakwachtrijposten** een taakwachtrijpost en kies vervolgens de actie **Logboekvermeldingen**.  

### Een status vanuit een verkoop- of inkoopdocument weergeven

1. Kies vanuit het document dat u hebt geprobeerd te boeken met de taakwachtrij, het veld **Status taakwachtrij**, dat **Fout** bevat.
2. Bekijk de foutmelding en los het probleem op.

## Het onderdeel Mijn taakwachtrij

In het onderdeel **Mijn taakwachtrij** in uw rolcentrum worden de taakwachtrijposten weergegeven die u hebt gestart, maar die nog niet zijn voltooid. Standaard is het onderdeel niet zichtbaar, zodat u het moet toevoegen aan uw rolcentrum. Zie voor meer informatie [Basisinstellingen wijzigen](../Basisinstellingen-wijzigen/).  

Dit onderdeel toont welke documenten met uw id in het veld **Toegewezen gebruikers-id** worden verwerkt of in de wachtrij staan, inclusief posten die verband houden met boeking op de achtergrond. Het onderdeel kan u in één oogopslag laten zien of er een fout is opgetreden bij het boeken van een document en of er fouten zijn opgetreden in een taakwachtrijpost. Met het onderdeel kunt u een documentboeking annuleren als deze niet wordt uitgevoerd.

### Een fout in het gedeelte Mijn taakwachtrij weergeven

1. Kies in een post met de status **Fout** de actie **Fout weergeven**.
2. Bekijk de foutmelding en los het probleem op.

## Beveiliging

Taakwachtrijposten worden uitgevoerd op basis van machtigingen. Die machtigingen moeten de uitvoering van de lijst of codeunit toestaan.  

Wanneer een taakwachtrij handmatig is geactiveerd, wordt deze uitgevoerd met de referenties van de gebruiker. Wanneer een taakwachtrij is geactiveerd als een geplande taak, wordt deze uitgevoerd met de referenties van de serverinstantie. Wanneer een taak wordt uitgevoerd, wordt deze uitgevoerd met de referenties van de taakwachtrij die deze activeert. De gebruiker die de taakwachtrijpost maakte, moet echter ook machtigingen hebben. Wanneer een taak wordt uitgevoerd in de gebruikerssessie (bijvoorbeeld bij het boeken op de achtergrond), wordt deze uitgevoerd met de referenties van de gebruiker die deze taak heeft gemaakt.  

> [!IMPORTANT]  
> Als u de machtigingenset SUPER gebruikt die wordt geleverd met [!INCLUDE[d365Business Central, hebben u en uw gebruikers de machtiging om alle objecten uit te voeren. In dit geval wordt de toegang voor elke gebruiker alleen beperkt door machtigingen voor gegevens.  

## Taakwachtrijen efficiënt gebruiken

De record van de taakwachtrijpost heeft veel velden om de parameters in een codeunit te plaatsen die u hebt opgegeven voor het uitvoeren met een taakwachtrij. Dit betekent ook dat codeunits die moeten worden uitgevoerd via de taakwachtrij, moeten worden gespecificeerd met de taakwachtrijrecord als een parameter in de **OnRun** trigger. Dit biedt een extra beveiligingsniveau aangezien het voorkomt dat gebruikers willekeurige codeunits uitvoeren via de taakwachtrij. Als de gebruiker parameters aan een rapport moet doorgeven, kan dit enkel door de lijstuitvoering in een codeunit te plaatsen die vervolgens de invoerparameters parseert en deze in de lijst plaatst voordat deze wordt uitgevoerd.  
