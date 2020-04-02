# Werkstroomgebruikers instellen

Voordat u werkstromen kunt maken, moet u de gebruikers instellen die deelnemen aan werkstromen. Dit is nodig om bijvoorbeeld op te geven wie een bericht ontvangt als er moet worden gereageerd op een werkstroomstap.  

Op de pagina **Werkstroomgebruikersgroep** stelt u gebruikers in onder werkstroomgebruikersgroepen en geeft u het nummer van de gebruikers op in een procesvolgorde, zoals een fiatteringsketen.  

Werkstroomgebruikers die fungeren als goedkeuringgebruikers, zowel aanvragers als fiatteurs, moeten ook worden ingesteld op de pagina **Gebruikersinstellingen voor goedkeuring**. Zie voor meer informatie [Goedkeuringsgebruikers instellen](../Goedkeuringsgebruikers-instellen/).  

> [!NOTE]  
> Stel een hiërarchie voor fiatteurs op om aan te geven dat een goedkeuringsaanvraag niet wordt goedgekeurd totdat meerdere fiatteurs in een goedkeuringsketen deze hebben goedgekeurd. Voor het fiatteurstype **Fiatteur** stelt u fiatteurs op de pagina **Gebruikersinstellingen voor goedkeuring** in. Stel voor het fiatteurstype **Werkstroomgebruikersgroep** op de pagina **Werkstroomgebruikersgroepen** in en definieer de hiërarchie door incrementele nummers aan elke fiatteur in het veld **Volgnr.** toe te wijzen. Zie dit onderwerp en [Goedkeuringsgebruikers instellen](../Goedkeuringsgebruikers-instellen/) voor meer informatie.  
>
> U kunt definiëren dat een goedkeuringsaanvraag pas wordt goedgekeurd nadat meerdere gelijkwaardige fiatteurs deze hebben goedgekeurd, ongeacht het bestaan van een hiërarchie, door een werkstroomgebruikersgroep in een platte structuur in te stellen. Stel voor het fiatteurstype **Werkstroomgebruikersgroep** op de pagina **Werkstroomgebruikersgroepen** in en wijs hetzelfde nummer toe aan elke fiatteur in het **Volgnr.** te kiezen. Zie dit onderwerp voor meer informatie.  

### Een werkstroomgebruiker instellen

1. Kies het pictogram ![zoeken icon](/assets/images/zoeken.png "zoeken icon"), voer **Werkstroomgebruikersgroepen** in en kies de desbetreffende koppeling.  
2. Kies de actie **Nieuw**. De pagina **Werkstroomgebruikersgroep** wordt geopend.  
3. Voer in het veld **Code** maximaal 20 tekens in om de werkstroom te identificeren.  
4. Beschrijf de werkstroom in het veld **Omschrijving**.  
5. Vul in het sneltabblad **Werkstroomgebruikersgroepsleden** de velden op de eerste regel in, zoals in de volgende tabel is beschreven.  

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Gebruikersnaam**|Geef de gebruiker op die deelneemt aan werkstromen.<br /><br /> De gebruiker moet op de pagina **Gebruikersinstellingen** bestaan.|  
    |**Volgnr.**|Geef de volgorde waarin de werkstroomgebruiker deelneemt aan een werkstroom in verband met andere gebruikers. Dit veld kan bijvoorbeeld worden gebruikt om aan te geven wanneer de gebruiker in verhouding tot andere fiatteurs goedkeurt, als u de optie **Werkstroomgebruikersgroep** in het veld **Soort fiatteur** voor het gerelateerde werkstroomantwoord gebruikt. **TIP:** stel een vaste werkstroomgebruikersgroep in door hetzelfde volgordenummer aan de relevante fiatteurs toe te kennen om aan te geven dat een goedkeuringsaanvraag niet wordt goedgekeurd alvorens deze door meerdere gelijkwaardige fiatteurs is goedgekeurd, ongeacht of sprake is van een hiërarchie.|  
6. Herhaal stap 5 om meer werkstroomgebruikers aan de gebruikersgroep toe te voegen.  
7. Herhaal stap 2 tot en met 6 om werkstroomgebruikersgroepen toe te voegen.  
