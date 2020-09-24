# Distribueren materialen

## Bepalen behoefte

In deze processtap wordt beschreven hoe u bepaalt welke artikelen voor het magazijn besteld moeten worden. Zie hiervoor de instructie **[Bestellen materialen](../bestellen-materialen/)**.

## Picken materialen

Deze processtap betreft het verplaatsen van artikelen voor het magazijn (van hoofdmagazijn naar submagazijn(en)). Zie hiervoor de instructie **[Bestellen materialen](../bestellen-materialen/)**.

## Ontvangen materialen

Om artikelen naar het juiste magazijn te verplaatsen maken we gebruik van transferorders. Om per magazijn te bepalen wat de materiaalbehoefte is voeren we een Planningsvoorstel uit. 

1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Planningsvoorstellen**.  
2. Ga naar de actie/functie **Regeneratief plan berekenen**.  
3. De pagina **Plan berekenen - Planningsvoorstel** wordt geopend. Vul hier de volgende velden:
    - **MRP**: Dient altijd aangevinkt te zijn.  
    - **Begindatum**: Vul hier de datum van vandaag in.  
    - **Einddatum**: Kies hier een datum die twee weken vanaf de begindatum in de toekomst ligt.  
    - **Planningsparameters voor uitzonderingswaarschuwingen respecteren**: Dient aangevinkt te worden.
4. Klik op **OK**. Het planvoorstel wordt berekend. 
5. Nu gaan we de materialen via een transferorder naar het juiste magazijn verplaatsen. Klik hiertoe op **Proces | Planningsboodschap uitvoeren**.
6. De pagina **Planningsvoorstel uitvoeren - plan** wordt geopend. Kies in het veld **Transferorder** voor 'Transferorders maken'.
7. Klik op **OK**.
8. Open de betreffende transferorder en kies voor **Boeken**. 

### Deelontvangst? 

Wanneer niet alle artikelen zijn ontvangen dan kun je ook een deelontvangst registreren. Dit doet u als volgt: 

1. Ga naar het betreffende artikel op de regel.
2. Vul in het veld **Te ontvangen aantal** het aantal in. Doordat u hier een lager aantal invult, blijft het resterende aantal in backorder staan. 
3. Klik op **Boeken**.
4. Er verschijnt een popup die aangeeft dat er ontvangsten geboekt gaan worden. Klik op **OK**. Het veld **Ontvangen aantal** is nu gevuld. 

## Aanmaken inkooporders 
 
Het aanmaken van een inkoop- of transferorder doet u door de planningsboodschap uit te voeren. Dit rapport kan zowel geaccepteerde als niet-geaccepteerde regels geven. Niet-geaccepteerde regels moeten na controle verwijderd worden, of alsnog geaccepteerd worden. u gaat nu inkoop- en transferorders aanmaken.  

1. 
2. Vul de volgende velden op het scherm dat verschijnt:  

    - Inkooporder: Kies voor Inkooporders aanmaken, als je voor de leverancier een inkooporder wilt 
      aanmaken om materiaal te bestellen.  
    - Transferorder: Kies voor Inkooporders aanmaken, indien je de artikelen wilt verplaatsen van het 
       hoofdmagazijn naar de sub magazijnen.  
    - Transferorders combineren: Dit is een keuzeveld.   

3. Klik op OK. Er zullen nu nieuwe orders worden aangemaakt.   

## Zie ook

[Bestellen materialen](../bestellen-materialen/)  
[Inventariseren voorraad](../inventariseren-voorraad/)  
[Ontvangen materialen](../ontvangen-materialen/)  
[Beheren artikelinformatie](../beheren-artikelinformatie/)  
