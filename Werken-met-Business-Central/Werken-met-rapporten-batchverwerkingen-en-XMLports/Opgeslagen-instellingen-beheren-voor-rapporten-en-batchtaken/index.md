# Opgeslagen instellingen beheren voor rapporten en batchtaken

Wanneer gebruikers rapporten uitvoeren, zien ze meestal een pagina waarmee ze opties kunnen selecteren en filters kunnen instellen om de gegevens te wijzigen die in het gegenereerde rapport worden opgenomen. Deze pagina wordt de aanvraagpagina genoemd. Een rapport kan een of meer *opgeslagen instellingen* bevatten die gebruikers op het rapport kunnen toepassen vanaf de aanvraagpagina. *Opgeslagen instellingen* zijn in wezen vooraf gedefinieerde opties en filters. Met behulp van opgeslagen instellingen kunt u snel en betrouwbaar rapporten genereren die de juiste gegevens bevatten. Zie voor meer informatie [Opgeslagen instellingen gebruiken](../werken-met-rapporten-batchverwerkingen-en-XMLports/#Opgeslagen-instellingen-gebruiken).

> [!NOTE]
> Dit onderwerp verwijst hoofdzakelijk naar 'rapport', maar soortgelijke informatie geldt voor batchverwerkingen.

Als u de juiste machtigingen hebt, kunt u de opgeslagen instellingen voor alle gebruikers in een bedrijf weergeven, maken en wijzigen. U kunt opgeslagen instellingen voor een rapport toewijzen aan afzonderlijke gebruikers of aan alle gebruikers in het bedrijf.

## Opgeslagen instellingen maken en wijzigen voor alle gebruikers

U beheert opgeslagen instellingen op de pagina **Rapportinstellingen**. Er zijn twee manieren om deze pagina te openen:

- Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Rapportinstellingen** in en kies de gerelateerde koppeling.
- Open een rapport, kies de opzoekactie in het veld **Standaardwaarden gebruiken uit** en kies vervolgens de actie **Selecteren vanuit volledige lijst**.

De pagina bevat alle bestaande opgeslagen instellingsvermeldingen voor alle gebruikers. Als er een gebruikersnaam in het veld **Toegewezen aan** staat, kan alleen deze gebruiker de opgeslagen instellingen voor het corresponderende rapport gebruiken. Als er een vinkje in het veld **Gedeeld met alle gebruikers** staat, kunnen alle gebruikers de opgeslagen instellingen voor het rapport gebruiken.

Vanaf de pagina **Rapportinstellingen** kunt u het volgende doen:

- Kies de actie **Nieuw** om een nieuwe vermelding met opgeslagen instellingen te maken.
- Selecteer een vermelding met opgeslagen instellingen en kies de actie **Kopiëren** om een kopie te maken.
- Selecteer een vermelding met opgeslagen instellingen in de lijst en kies de actie **Bewerken** om een vermelding met opgeslagen instellingen te wijzigen.

> [!Important]
> Denk na over de naam die u een vermelding met opgeslagen instellingen geeft. Als u een vermelding met opgeslagen instellingen voor alle gebruikers maakt en deze dezelfde naam geeft als een bestaande vermelding met opgeslagen instellingen die aan één specifieke gebruiker is toegewezen, kan die gebruiker de vermelding met opgeslagen instellingen die aan iedereen is toegewezen, niet gebruiken.  In de sectie **Opgeslagen instellingen** op de aanvraagpagina ziet de gebruiker twee vermeldingen met opgeslagen instellingen met dezelfde naam. Ongeacht welke optie de gebruiker echter kiest, de gebruikersspecifieke vermelding met opgeslagen instellingen wordt gebruikt.

> [!NOTE]
> De functie voor opgeslagen instellingen is alleen beschikbaar voor rapporten waarvoor de eigenschap SaveValues van de rapportaanvraagpagina is ingesteld op **Ja**. De eigenschap **SaveValues** wordt ingesteld in de ontwikkelomgeving.  
