# Gebruik van een record beperken en toestaan

Als u wilt voorkomen dat een record wordt gebruikt bij bepaalde activiteiten, bijvoorbeeld totdat de record is goedgekeurd, kunt u twee werkstroomantwoorden opnemen in een werkstroom die het gebruik van de record bestuurt. Eén werkstroomantwoord beperkt het gebruik van de record zoals gedefinieerd door de werkstroomgebeurtenis en -voorwaarden. Een andere werkstroomantwoord staat het gebruik van de record toe zoals gedefinieerd door de werkstroomgebeurtenis en -voorwaarden. Er bestaan twee responsen in de generieke versie van Business Central voor dit doel: **Gebruik van een record beperken** en **Gebruik van een record toestaan**.

> [!NOTE]  
> De algemene versie van Business Central helpt verhinderen dat een record wordt geboekt, als betaling wordt geëxporteerd en als cheque wordt afgedrukt. Als een Microsoft-partner andere beperkingen wil ondersteunen, moet deze de toepassingscode aanpassen.  

> [!NOTE]  
> De werkstroomfunctionaliteit om te verhinderen en toe te staan dat records worden gebruikt houdt geen verband met de functionaliteit om het boeken van artikel-, klant- en leveranciersrecords te blokkeren.

In de volgende procedure wordt beschreven hoe u het boeken van inkooporders kunt verhinderen totdat deze zijn goedgekeurd. De nieuwe werkstroom wordt gebaseerd op de bestaande werkstroomsjabloon Goedkeuringswerkstroom inkoopfactuur.  

## Een werkstroomstap maken die voorkomt dat niet-goedgekeurde inkooporders worden geboekt

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Werkstromen** in en kies de gerelateerde koppeling.  
2. Maak op de pagina **Werkstromen** een nieuwe werkstroom genaamd Goedkeuringswerkstroom inkooporder. Zie voor meer informatie [Werkstromen maken](../Werkstromen-instellen/Werkstromen-maken/).  
3. Kies de actie **Kopiëren van werkstroomsjabloon**.  
4. Kies het veld **Bronwerkstroomcode** en kies vervolgens op de pagina **Werkstroomsjablonen** de werkstroomsjabloon Goedkeuringswerkstroom inkooporder.  

     Zoals u ziet, draait het bij de eerste twee werkstroomstappen om het verhinderen en vervolgens het toestaan van het gebruik van inkoopfacturen. Ga door met het wijzigen van de gebeurtenisvoorwaarde in de eerste stap van de werkstroom om op te geven dat deze van toepassing is op inkooporders.  
5. Kies op het sneltabblad **Werkstroomstappen** het veld **Gebeurtenisvoorwaarden** en selecteer vervolgens voor het filter **Documentsoort** de optie **Order**.  
6. Ga door om andere werkstroomstappen te bewerken, te verwijderen of toe te voegen in een bedrijfsproces dat begint door het boeken van niet-goedgekeurde inkooporders te verhinderen.  
