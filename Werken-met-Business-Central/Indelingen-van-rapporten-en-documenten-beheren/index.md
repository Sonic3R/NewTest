# Lay-outs van rapporten en documenten beheren

Een rapportlay-out bepaalt de inhoud en de indeling van het rapport, inclusief welke gegevensvelden van een rapportgegevensset in het rapport worden weergegeven, hoe ze worden gerangschikt, welke tekststijl en afbeeldingen worden gebruikt, enzovoort. Vanuit Business Central kunt u bepalen welke lay-out wordt gebruikt in een rapport, een nieuwe lay-out maken of de huidige lay-outs wijzigen.

> [!NOTE]  
> In Business Central omvat de term 'rapport' ook documenten die extern worden verspreid, zoals verkoopfacturen en orderbevestigingen die u aan klanten als pdf-bestanden verzendt.

Met een rapportlay-out wordt met name het volgende ingesteld:

* De label- en gegevensvelden die moeten worden opgenomen uit de gegevensset van het Business Central-rapport.
* De tekstindeling, bijvoorbeeld lettertype, -grootte en -kleur.
* Het bedrijfslogo en de positie ervan.
* Algemene pagina-instellingen, zoals marges en achtergrondafbeeldingen.

Een rapport kan worden ingesteld met meerdere rapportlay-outs, waartussen u indien nodig kunt schakelen. U kunt een van de ingebouwde rapportlay-outs gebruiken of u kunt aangepaste rapportlay-outs maken en ze indien nodig aan uw rapporten toewijzen. Zie voor meer informatie [Een aangepaste lay-out voor een rapport of document maken](../Aangepaste-rapportlay-outs-maken-en-wijzigen/).

Er zijn twee soorten rapportlay-outs die u in rapporten kunt gebruiken: Word en RDLC.

## Overzicht van de Word-rapportlay-out

Een Word-rapportlay-out wordt gebaseerd op een Word-document (.docx-bestandstype). Met Word-rapportlay-outs kunt u rapportlay-outs ontwerpen door Microsoft Word 2013 of later te gebruiken. Een Word-rapportlay-out bepaalt de inhoud van het rapport: hoe de inhoudelementen worden gerangschikt en hoe ze eruit zien. Een Word-document met een rapportlay-out gebruikt meestal tabellen om inhoud te rangschikken. De cellen kunnen gegevensvelden, tekst of afbeeldingen bevatten.

## Overzicht van de RDLC-lay-out

RDLC-lay-outs zijn gebaseerd op clientrapportdefinitielay-outs (.rdlc- of .rdl-bestandstypen). Deze lay-outs worden gemaakt en gewijzigd vanuit SQL Server Report Builder. Het ontwerpconcept voor RDLC-lay-outs lijkt op Word-lay-outs, waarbij de lay-out de algemene indeling van het rapport definieert en bepaalt welke velden uit de database worden opgenomen. RDLC-lay-outs ontwerpen is geavanceerder dan Word-lay-outs ontwerpen.

## Ingebouwde en aangepaste rapportlay-outs

Business Central bevat verschillende geïntegreerde lay-outs. Ingebouwde lay-outs zijn vooraf gedefinieerde lay-outs die voor bepaalde rapporten zijn ontworpen. Rapporten in Business Central hebben een geïntegreerde lay-out zoals een RDLC-rapportlay-out, Word-rapportlay-outs of in bepaalde gevallen beide. U kunt een geïntegreerde rapportlay-out niet vanuit Business Central wijzigen, maar u gebruikt deze als uitgangspunt voor het maken van uw eigen aangepaste rapportlay-outs.

Aangepaste lay-outs zijn rapportlay-outs die u ontwerpt om de weergave van een rapport te wijzigen. U maakt meestal een aangepaste lay-out op basis van een ingebouwde lay-out, maar u kunt ze ook nieuw maken of op basis van een kopie van een bestaande aangepaste lay-out. Met aangepaste lay-outs kunt u meerdere lay-outs voor hetzelfde rapport hebben waartussen u indien nodig kunt schakelen. U kunt bijvoorbeeld verschillende lay-outs voor elk Business Central-bedrijf hebben of u kunt verschillende lay-outs voor hetzelfde bedrijf hebben voor bepaalde situaties of gebeurtenissen, zoals een speciale campagne of feestdagen.

## Besluiten of u een Word- of een RDLC-rapportlay-out wilt gebruiken

Een rapportlay-out kan worden gebaseerd op een Word-document of op een RDLC-bestand. Het besluit om een Word-rapportlay-out of een RDLC-rapportlay-out te gebruiken is afhankelijk van hoe u wilt dat het gegenereerde rapport eruitziet en van uw kennis van Word en SQL Server Report Builder.

De algemene ontwerpconcepten voor Word- en RDLC-lay-outs lijken erg op elkaar. Elk type heeft echter bepaalde ontwerpfuncties die bepalen hoe het gegenereerde rapport eruitziet in Business Central. Dit houdt in dat hetzelfde rapport er anders uit kan zien wanneer u de Word-rapportlay-out gebruikt dan wanneer u de RDLC-rapportlay-out gebruikt.

Het proces voor het instellen van Word-rapportlay-outs en RDLC-rapportlay-outs in rapporten is hetzelfde. Het belangrijkste verschil is de manier waarop u de lay-outs wijzigt. Word-rapportlay-outs zijn in het algemeen gemakkelijker te maken en te wijzigen dan RDLC-rapportlay-outs, omdat u Word kunt gebruiken. RDLC-rapportlay-outs worden gewijzigd met SQL Server Report Builder, dat voor geavanceerdere gebruikers is bedoeld.

Zie [De huidige rapportindeling wijzigen](../De-huidige-rapportindeling-wijzigen/) voor informatie over het wijzigen van de te gebruiken indeling.
