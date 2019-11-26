# VoorzieningZGWnieuw

Dit is de backlog van de Voorziening Zaakgerichtwerken - team nieuw

Eventueel onderverdelen in inhoud / randvoorwaardelijk, eerst even kijken of dit zinvol is 


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
  -	Relatie Haalcentraal en common ground is duidelijk in de context van utrecht (Wie doet wat? Relatie met Wouter Bruining?)
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
  - wat is het DMS+ waar UVO het over heeft? 
  - kwaliteitsbeheer? 

  
### Process engine	
- Het is duidelijk welke process engine(s) we gebruiken en kunnen onderbouwen waarom dat al dan niet relevant is 	
  -	we hebben kennis van de beperkingen en mogelijkheden van het inzetten van een process engine
  -	de afhankelijkheid van goede modellen is duidelijk
  -	we hebben een goede code bibliotheek nodig met herbruikbare bijv listeners en scripts 
  -	we houden in de gaten welke andere process engines er zijn er of er een landelijke beschikbaar komt
  -	Procescatalogus/procestypecomponent onderzoeken (komt bij conduction vandaan via huwelijksplanner)

### Postverwerking
- We weten wat er met postverwerking mogelijk is; we kunnen slim gescande documenten afhankelijk van de metadata koppelen aan bestaande of nieuwe zaken. Of dossiers? 

### BMPN modellen en modellering
- er zijn afspraken over het eigenaarschap van modellen en over het beheer van modellen 
- er zijn afspraken over modellen die aan een process engine gekoppeld zijn
- er zijn afspraken over hoe we modelleren (symbolen, naamgevingsconventies) 

### Autorisatiebeheer (op applicatie, api en gebruikersniveau)
- Organisatisch is duidelijk hoe autorisatie van personen en applicaties wordt uitgevoerd (wie is eigenaar, wie regelt rechten…)
  - Het is duidelijk hoe geautoriseerd wordt en hoe dat gebeurt op het niveau van gebruikers/rollen en applicaties en apis
  - relatie met single sign on, IAM
  
### Inrichten van ketens			
- Voor we met een "keten" starten weten alle betrokkenen wat de reikwijdte is.
- We willen de inrichting van ketens gestructureerd oppakken (bijv uitgaan van generieke stukken, stukken die veel businesswaarde opleveren)			
  -	wanneer vragen we een bestaande leverancier of een nieuwe? 		
  -	wanneer maken we een nieuw component? 		
  -	oo neemt actief deel aan scrumteam		
  -	we hebben opleidingsmateriaal om te kunnen starten met een keten		
  -	we hebben een teststraat en geautomatiseerde tests om aanpassingen naar productie te kunnen brengen		

### Organisatorisch inrichten beheer en support		
- Voordat we een keten in productie nemen, zijn er afspraken over beheer en support (wijzigingenbeheer, incidenten en calamiteiten)  (zie functionaliteitenbeer Bisl)  	
  - hoe worden afspraken vastgelegd en wie beheert deze afspraken? 
  -	Er is duidelijk uit welke componenten een keten bestaat, en wat waar draait en beheert wordt en door wie(adhv architectuur plaat.	
  -	soms volledige applicaties, soms alleen configuratie, soms centraal soms decentraal 	
  -	het is duidelijk waar een gebruiker problemen kan melden (als medewerker of namens een burger)	
  -	functioneel beheer kan overzien welke componenten functioneren en welke niet, zodat er proactief beheer gevoerd kan worden (zowel technische onderlaag als functionele bovenlaag) 	
  -	idem voor de connectiviteit	
  -	invullen eigen opleidingsbehoefte adhv nieuwe componenten 	
  -	onderhoud demoscript 	
  - terugmelding
  - backup en recovery? 
  - Hosting


### Landelijke samenwerking	
- We streven ernaar om compentenen te delen, te hergebruiken of daar waar relevant landelijke standaarden aan te passen	
  - hoe leveren we bruikbare componenten aan andere gemeenten? 
  - hoe kaarten we zaken aan die in standaarden moeten worden opgenomen? 
  -	hoe hergebruiken we componenten? 
  -	HaalCentraal
  
### Architectuur	
- De architectuur is per keten en generiek beschreven. Het is duidelijk wie de architectuurplaten up to date houdt	
  -	Voor functioneel beheer is ook duidelijk wie waarvoor verantwoordelijk is en wie waarop ondersteuning biedt. 
  -	er worden twee versies van de architectuur bijgehouden: 1 technisch en 1 met als insteek common ground
  -	Doelarchitectuur

### huwelijksplanner
- het is duidelijk wat de relatie tussen ons traject en dat van de huwelijksplanner is
- we willen graag hergebruiken (code, organisatie van beheer) 

### securtiy / privacy / logging / auditing	
- Het is duidelijk wat er op dit gebied geregeld moet zijn voordat een keten kan worden ingericht	
  -	moeten er PIA's worden uitgevoerd? 
  -	hoe wordt duidelijk wat er gelogd moet worden en hoe de audittrail eruit moet zien? 
  -	autorisatie van gebruikers, api en applicatie
  -	security van cloudoplossing 
  -	digid audit
  - AGV, Landelijke kaders/wetten.
  - Toetsen rechtmatigheid en vaststellen autorisatie
  
### backlog
- we werken vanuit een backlog per keten, en een backlog generiek

### Organisatie
- het is duidelijk wat de rol van supplymanager, productowner(s) en scrummaster bij inrichten van de ketens
  - Hebben we nog met andere partijen te maken? (bijv portfolio manager) 
  - leveranciersmanagement verdient extra aandacht door het aantal verschillende partijen wat deelneemt aan de inrichting van ketens

### Generieke Keten Inzage en Afhandel Component	
- het is duidelijk hoe generiek de generieke component is. 	
  -	Wanneer we iedereen gebruik willen laten maken van hetzelfde wordt autorisatiebeheer ondoenlijk; 
  -	het werken met applicaties biedt juist mogelijkheden om de KIC als verschillende applicaties in te zetten
  -	Er is nog niet nagedacht over autorisatie van gebruikers, rollen of het beheer daarvan
 
### Migratiestrategie	
- We weten hoe we de overgangsfase zien van werken met het zaaksyteem van exxellence richting werken met gemeentezaak	

### Tooling 	
- we weten welke oplossingen we in de proeftuin neerzetten en kunnen gebruiken richting productie	
- we weten of bestaande oplossingen in aanmerking komen als component in een keten (denk aan typo3) 	
- er is duidelijkheid over de tooling die we gebruiken en waar we deze gebruiken (camunda, postman, valtimo, camunda modeler, slack, github als samenwerkingsomgeving)  	
- We willen vanuit onze werkplek kunnen werken 	
- Het is duidelijk wat de status van tooling (denk aan gratis software zonder onderhoud, software die op enig moment betaald wordt) en het al dan niet draaien binnen onze werkplek voor risico's met zich meebrengt	
- 

### Centraal beheerportaal (of inzageportaal) (of MOM)  
- 1. vanuit dit centrale dashboard hebben we zicht op de componenten en hun configuratie in een keten. 
- 2. oude, huidige en toekomstige versies van het systematisch overzicht zijn in te zien en in geval van toekomstig aan te passen. We zien ook de relatie met daarwerkelijke inrichting (pushen we bijv. configuratie vanuit een conceptversie naar huidige versie en daadwerkelijke inrichting) 

### Identificatie van herbruikbare modules
- Analyse van het geheel van ketens en generiek bedrijfsprocessen 

### Huisstijl
- UI library met huisstijl (voor verschillende ontwikkeltalen)

### Developerstrategy

### Ketenbeheerorganisatie
- We willen een overzicht van raken, rollen en verantwoordelijkheden binnen ketens. 
  - opstellen checklist adhv parallellen met stelsenbeheer organisatie https://digiplaza.utrecht.nl/share/page/site/2-ket-tea-stelsel-van-basisregistraties/document-details?nodeRef=workspace://SpacesStore/66bb20fb-e2fc-4a28-98d3-475f255afc63 
  - kijken naar hergebruik van opzet ketenbeheer in sbs  https://digiplaza.utrecht.nl/share/page/site/2-ket-tea-stelsel-van-basisregistraties/documentlibrary?file=Presentatie%20ketenbeheeroverleg%205%20september.pptx#filter=path%7C%2F01.%20Organisatie%20stelsel%2FAfspraken%20(convenanten%2C%20GLO's%20en%20SLA's)%2FStandaarden 




