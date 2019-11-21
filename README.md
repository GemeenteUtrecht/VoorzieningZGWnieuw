# VoorzieningZGWnieuw

Dit is de backlog van de Voorziening Zaakgerichtwerken - team nieuw

### Epics  

### Principes	
- we ontwikkelen adhv kaders en richtlijnen en willen bij het uitblijven daarvan helder hebben wat de consequenties zijn	
  - Worden documenten per zaak opgeslagen, dwz replica's igv hetzelfde document bij meerdere zaken? Of eenmalige opslag
  -	We onderbouwen per component of proces welke taal zich het beste leent voor ontwikkeling (bijv. angular of react of python), maar zijn niet gebonden aan specifieke talen
  -	Hoe kijken we aan tegen misbruik van Zaaktypes als verzamelbak
  -	we zetten een process engine in in geval van meerwaarde
  -	Hoe wegen we af of  we in een keten af kunnen wijken van generieke componenten? Of van een landelijk beschikbare component
  -	Inkoopprincipes/inkoopstrategie (Leveranciersmanagement, contractbeheer) https://github.com/18F/technology-budgeting/blob/master/handbook.md
  -	Migratiestrategie is duidelijk
  -	Relatie Haalcentraal en common ground is duidelijk in de context van utrecht
  -	UI's gevoed door procesengine en ZTC

### Recordmanagement 	
- Het is duidelijk welke mogelijkheden voor recordmanagement we in kunnen zetten binnen ketens	
  - nodig zijn kaders (NEN certificering) en technisch beleid en de component(en) zelf? 	
  -	baseline 
  -	import export (als generieke tool of bijv uvo specifiek), datadistributie (navragen lazo)
  -	bpmn in rma module van alfresco -  meer over weten
  -	rma module zelf moet af zijn en gedocumenteerd
  -	hoe kijken we aan tegen rma op documenten zonder zaak? 
  -	er zijn record managers die in de context van ketens kunnen vernietigen
  
### Process engine	
- Het is duidelijk welke process engine(s) we gebruiken en kunnen onderbouwen waarom dat al dan niet relevant is 	
  -	we hebben kennis van de beperkingen en mogelijkheden van het inzetten van een process engine
  -	de afhankelijkheid van goede modellen is duidelijk
  -	we hebben een goede code bibliotheek nodig met herbruikbare bijv listeners en scripts 
  -	we houden in de gaten welke andere process engines er zijn er of er een landelijke beschikbaar komt
  -	Procescatalogus/procestypecomponent onderzoeken (komt bij conduction vandaan via huwelijksplanner)

### Postverwerking
- We weten wat er met postverwerking mogelijk is; we kunnen slim gescande documenten afhankelijk van de metadat koppelen aan bestaande of nieuwe zaken. Of dossiers? 

### BMPN modellen en modellering
- er zijn afspraken over het eigenaarschap van modellen en over het beheer van modellen 
- er zijn afspraken over modellen die aan een process engine gekoppeld zijn
- er zijn afspraken over hoe we modelleren (symbolen, naamgevingsconventies) 

### Autorisatiebeheer (op applicatie, api en gebruikersniveau)
- Organisatisch is duidelijk hoe autorisatie van personen en applicaties wordt uitgevoerd (wie is eigenaar, wie regelt rechten…)
  - Het is duidelijk hoe geautoriseerd wordt en hoe dat gebeurt op het niveau van gebruikers/rollen en applicaties en apis
  - relatie met single sign on, IAM
  
### Inrichten van ketens			
- We willen de inrichting van ketens gestructureerd oppakken (bijv uitgaan van generieke stukken, stukken die veel businesswaarde opleveren)			
  -	wanneer vragen we een bestaande leverancier of een nieuwe? 		
  -	wanneer maken we een nieuw component? 		
  -	oo neemt actief aan scrumteam		
  -	we hebben opleidingsmateriaal om te kunnen starten met een keten		
  -	we hebben een teststraat en geautomatiseerde tests om aanpassingen naar productie te kunnen brengen		

### Organisatorisch inrichten beheer en support		
- Voordat we een keten in productie nemen, zijn er afspraken over beheer en support (wijzigingenbeheer, incidenten en calamiteiten)  (zie functionaliteitenbeer Bisl)  		
  -	Er is duidelijk uit welke componenenten een keten bestaat, en wat waar draait en beheert wordt en door wie(adhv architectuur plaat.	
  -	soms volledige applicaties, soms alleen configuratie, soms centraal soms decentraal 	
  -	het is duidelijk waar een gebruiker problemen kan melden (als medewerker of namens een burger)	
  -	functioneel beheer kan overzien welke componenten functioneren en welke niet, zodat er proactief beheer gevoerd kan worden (zowel technische onderlaag als functionele bovenlaag) 	
  -	idem voor de connectivieteit	
  -	invullen eigen opleidingsbehoefte adhv nieuwe componenten 	
  -	onderhoud demoscript 	

### Landelijke samenwerking	
- We streven ernaar om compentenen te delen, te hergebruiken of daar waar relevant landelijke standaarden aan te passen	
  - hoe leveren we bruikbare componenten aan andere gemeenten? 
  - hoe kaarten we zaken aan die in standaarden moeten worden opgenomen? 
  -	hoe hergebruiken we compenten? 
  -	HaalCentraal
  
### Architectuur	
- De architectuur is per keten en generiek beschreven. Het is duidelijk wie de architectuurplaten up to date houdt	
  -	Voor functioneel beheer is ook duidelijk wie waarvoor verantwoordelijk is en wie waarop ondersteuning biedt. 
  -	er worden twee versies van de architectuur bijgehouden: 1 technisch en 1 met als insteek common ground
  -	Doelarchitectuur

### huwelijksplanner
- het is duidelijk wat de relatie tussen ons traject en dat van de huwelijksplanner is
- we willen graag hergebruiken (code, organisatie van beheer) 

### securtiy, logging en auditing	
- Het is duidelijk wat er op dit gebied geregeld moet zijn voordat een keten kan worden ingericht	
  -	moeten er PIA's worden uitgevoerd? 
  -	hoe wordt duidelijk wat er gelogd moet worden en hoe de audittrail eruit moet zien? 
  -	autorisatie van gebruikers, api en applicatie
  -	security van cloudoplossing 
  -	digid audit
  
### backlog
- we werken vanuit een backlog per keten, en een backlog generiek






