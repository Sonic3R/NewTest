# Afronden projectfase

*[Klik hier](https://cegeka-dsabestpracticeprocessen.mavimcloud.com//Portal/code?id=1a4&view=Chart&maximize=true) voor de flowchart van dit werkproces (Ctrl+link om een nieuw browservenster te openen).*

In dit werkproces wordt de projectfase afgerond. Er wordt een fasedocument opgesteld met daarin onder ander de gewijzigde investeringsbegroting, gewijzigde budgetten en een rapportage van reeds aangegane verplichtingen van de inkoop. Op basis van dit document wordt besloten om de investeringsbegroting aan te passen of eventueel het project te stoppen.

## Maken boekingsvoorstel

Als bij het boeken van een factuur kosten niet op de juiste grootboekrekening terecht zijn gekomen, kan dit gecorrigeerd worden met een projectdagboek. Let wel, alleen de projectpost en het grootboeksaldo worden gecorrigeerd. BTW-posten, leveranciersposten, etc. zijn immers correct.
1.	Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de taak **Projectdagboek**.
2.	Open het betreffende projectdagboek door op de naam te klikken.
3.	Selecteer in de regel het **Projectnr.** en **Budgetregelnr.** waarop de correctie moet plaatsvinden. 
4.	In de kolom **Kostenrekening** wordt de grootboekrekening weergegeven waar de kosten op terecht zijn gekomen. 
5.	Omdat we een correctie op grootboekrekening niveau gaan uitvoeren, kiezen we in de kolom **Soort** de optie 'Grootboekrekening'. 
6.	De kosten worden van de kostenrekening in de regel afgeboekt, met als tegenrekening de grootboekrekening die u selecteert in kolom **Nr.**
7.	Zodra de tegenrekening gevuld wordt, wordt het veld **Omschrijving** automatisch gevuld met de omschrijving van deze grootboekrekening. Pas deze aan, zodat deze correctieboeking later te herkennen is. 
8.	Vul bij **BTW-bedrijfsboekingsgroep** de waarde 'NL' in en bij **BTW-productboekingsgroep** 'GEEN'. 
9.	Vul vervolgens het bedrag in dat moet worden gecorrigeerd in kolom **Kostprijs** en pas het **Aantal** aan naar –1.  
 
>**Let op!** Als het project een zogenaamd gemengd project is, plaatst Dynamics Empire een vinkje in kolom Verdeelsleutel, om aan te geven dat er een verdeelsleutel van toepassing is op de budgetregel waarop de kosten zullen worden geboekt. In een dergelijk geval dien je de functie Verdeelsleutel toepassen uit te voeren via Acties| Functies en het verdeeld bedrag en omschrijvingen eventueel aan te passen.  
 
## Verwerken projectmemorialen

Nadat het boekingsvoorstel is aangemaakt, kunnen de projectmemorialen geboekt worden.
1. Klik in het menu op **Boeken**.
2. Dynamics Empire bevestigt dat alle dagboekregels zijn verwerkt. Klik op **OK** en sluit het projectdagboek.
 
## Afsluiten ontwikkelproject

Het afsluiten van een project is slechts het veranderen van de status van de fase van het project in 'Afgehandeld'. 
Onderstaande stappen worden uitgevoerd door een projectadministrateur op het moment dat er geen boekingen meer verwacht worden op het project. 
1. Navigeer via het zoekveld ![zoeken icon](/assets/images/zoeken.png "zoeken icon") naar de lijst **Projectoverzicht** en open de juiste projectkaart.
2. Pas de **Projectfase** op tabblad **Algemeen** aan naar 'Afgesloten'.
3. De status van alle budgetregels op het project zijn omgezet naar 'Afgehandeld'. Hierdoor is het niet meer mogelijk om offertes, orders, facturen, uren, etc. op het project vast te leggen. Dit is alleen mogelijk als de status op de betreffende budgetregel leeg is.

## Zie ook

[Voorbereiden ontwikkelproject](../voorbereiden-ontwikkelproject/)  
[Voorbereiden projectfase](../voorbereiden-projectfase/)  
[Registreren uren](../registreren-uren/)  
