# Applied-Data-Science
Welkom bij de portfolio van Luke de keijzer, in dit portfolio zullen alle activiteiten beschreven worden waaraan ik heb meegewerkt / gedaan heb binnen de minor Applied Data science - KB74 ( in de periode van sep 2018 t/m jan 2019 ). 

In deze minor heb in een team van 3 medestudenten en één docent gewerkt aan een onderzoek voor het LUMC. 

Ons doel tijdens dit onderzoek was om te achterhalen of het 'flock-of-birds'-systeem dat momenteel door het LUMC enkel wordt gebruikt voor onderzoeksdoeleinden of dat het ook gebruikt kan worden voor de diagnostische doeleinden.

# Inhoudsopgave 
- [Jargon](#Jargon)
- [Onderzoek](#Onderzoek)
- [Pre-data](#Pre-data)
- [Extra activiteiten](#Extra-Activiteiten)

## Extra activiteiten
Omdat tijdens het project soms extra activiteiten uitgevoerd worden en deze niet terug te vinden zijn op het scrum board, is dit hoofdstuk gemaakt. In dit hoofdstuk zullen dus activiteiten te vinden zijn zoals uitleg geven, hulp bij persoonlijke projecten & het uitzoeken in eigen tijd.

# Jargon
Tijdens ons onderzoek hebben we met termen gebruikt die eigenlijk alleen maar begrepen kunnen worden door ons project team, maar deze zullen wel in dit portfolio terugkomen. Daarom zullen ze hieronder worden toegelicht.

jargon | Explenation 
--- | --- 
Raw data / Ruwe data | Ruwe sensor data met locatie en rotatie van de sensoren  
Cleaned data / Schone data | Cleaned data zijn de door LUMC verwerkte ruwe data, in deze data zijn alle locaties weg is alle data relatief van elkaar weergegeven d.m.v. hoeken 
Super cleaned data / Super schone data | De super cleaned data is de door ons schoon gemaakte cleaned data, dit proces is later beschreven

Naast ons project jargon zijn er ook termen die gebruikt worden om dit medisch gebied, deze zijn hieronder te zien. Dit plaatje is gemaakt door [Vincent](https://github.com/Vincentvdoord/Data-Science-KB-74)
<div style="text-align:center"><img src="https://i.imgur.com/9aViKwp.png" width="700" height="700"></div>

# Onderzoek
Het doel van het onderzoek is het volgende:
> achterhalen of het 'flock-of-birds'-systeem dat momenteel door het LUMC enkel wordt gebruikt voor onderzoeksdoeleinden of dat het ook gebruikt kan worden voor de diagnostische doeleinden

Tijdens het uitvoeren van dit onderzoek zouden we twee soorten data tot onze beschikbaarheid krijgen, ruwe data & gecleande data. Met de gecleande data hebben we de super cleaned data gemaakt, deze drie soorten data hebben ons onderzoek eigenlijk opgesplitst in 3 fases. Elk van deze drie fases had zijn eigen activiteiten die hieronder beschreven zijn

![Onderzoek fases](https://i.imgur.com/ODAt0De.png)

- [Ga naar: pre-data](#pre-data)
- [Ga naar: raw data](#Raw-data)
- [Ga naar: cleaned data](#Cleaned-data)
- [Ga naar: super cleaned data](#super-cleaned-data)

# Pre-data
In de fase voordat we data ontvingen ben ik vooral bezig geweest met drie onderwerpen, namelijk:
- [Opzetten project management](#Opzetten-project-management)
- [Zelf ontwikkeling](#Zelfontwikkeling)
- [Strategie](#Strategie)

## Opzetten project management
Als projectontwikkelingsmethode hebben we als groep gekozen om Scrum te gebruiken, dit hebben gedaan om iteratief aan het project te werken en sinds de project details pas duidelijk zouden worden tijdens het project was dit voor ons de juiste keuze.

Als scrumtool gebruiken wij de website: <img src="https://wac-cdn.atlassian.com/dam/jcr:d6a89d75-bad0-46f3-88aa-406542eb6cb5/trello-logo-blue-flat.png" alt="alt text" width="90" height="23">. Met deze ProjectManagement tool kunnen wij mensen aan projectentaken koppelen en exact extraheren hoeveel tijd er aan welke activiteiten besteed is.

Het onderzoek en het oprichten is vooral door mij en vincent gedaan aan het begin van dit project.

### Scrumboard
Het Scrumboard wat wij gebruiken bestaat uit 5 colummen die de layout van het board bepalen. Deze colommen zijn: Product Backlog; Sprint Backlog; In-Progress; Verify & Done. Om personen, datums, metadata & problemen aan te geven wordt er gebruikt gemaakt van tags en andere vormen van metadata. Een afbeelding van het ScrumBoard is te zien in de volgende afbeelding.
De orginele inrichting is door Vincent en mij samen gedaan.
![](https://i.imgur.com/QqA3vb1.jpg)

### Scrum by Vince
De plugin 'Scrum by Vince' maakt het mogelijk om tijd per activiteit in te plannen en een burndown chart te genereren. Het nadeel van deze burn down chart is dat er vanuit gegaan wordt dat alle beschikbare tijd volledig ingepland is. Dat is in Sprint 1 nog niet altijd het geval. Een afbeelding van een burndown chart via 'Scrum by Vince' is te zien in de volgende afbeelding.
Het onderzoek doen naar welke scrum tools het beste werken binnen Trello is alleen gedaan.
![](https://i.imgur.com/C8H2r1w.jpg)

## Zelfontwikkeling
In het begin van de course 'Applied Data Science' hebben we ons vooral gericht op zelfontwikkeling, met name zelfontwikkeling op het gebied van Python en machine learning. Onderaan zal de voortgang van de python courses (via DataCamp); en de voortvang van machine learning (via Coursera) staan.

### DataCamp Voortgang
<details><summary>Klik mij om de DataCamp voortgang te zien (foto) <img src="http://pngimg.com/uploads/exclamation_mark/exclamation_mark_PNG32.png" alt="Uitroepteken" width="16" height="16"></summary>
  <img src="https://i.imgur.com/BxXcGKm.png" alt="DataCamp Voortgang">
</details>

### Coursera Voortgang
<details><summary>Klik mij om de Coursera voortgang te zien (foto) <img src="http://pngimg.com/uploads/exclamation_mark/exclamation_mark_PNG32.png" alt="Uitroepteken" width="16" height="16"></summary>
  <img src="https://i.imgur.com/N9B9MnQ.png" alt="Coursera Voortgang">
</details>

## Strategie
Als team hebben we gezamelijk een strategie opgezet om het project te lijden. In deze strategie zouden we eerst onderzoek doen naar de ruwe data; daarna de cleaned data; en als laatste unsupervised learning.

# Raw data
Al vrij snel in het project, rond week 3, hebben we de eerste samples data ontvangen. Bij dit ontvangst kregen we één ruwe data meting en één door het LUMC gecleande data meting. Met deze twee bestanden konden we ons richten op het daadwerkelijk begrijpen van de data. Volgens de strategie zouden we ons eerst focussen op de ruwe data.

Omdat de ruwe data maar niet binnen kwam hebben we besloten hier niet mee verder te gaan, toch zijn er elke activiteiten die voor de ruwe data gemaakt zijn:
- [Visualisatie](#Visualisatie)
- [Ellebooghoek](#Ellebooghoek)

## Visualisatie
Om de data te begrijpen ben ik de data gaan visualiseren. Tony had een script geschreven om één frame van een oefening te visualiseren. Dit is gedaan door een skelet te tekenen met de locatie van de sensoren die in de ruwe data gemeten werden.

Met dit script ben ik rond week 4 verder gegaan, met eigen onderzoek heb ik een animatie van de frames kunnen maken die liet zien welke beweging de patient gemaakt zou moeten hebben bij het daadwerkelijk uitvoeren van de oefening.
![](https://i.imgur.com/LO7XOCw.gif)

Het script wat bovenstaande gif gemaakt heeft is [hier](1.%20Animaties/Animation%20Demo.ipynb) te zien. Later is dit script uitgebreid om de visualisatie van raw data & cleaned data naast elkaar te laten draaien.

## Ellebooghoek
In het onderzoek dat we uitgevoerd hebben was één van onze doelen achterhalen hoe het LUMC van de ruwe data naar de gecleande data zou transformeren. Een van de berekende colommen waren de elleboog hoeken. Sinds we alleen de positie hadden van de sensoren ben ik hierin onderzoek naar gaan doen. Orgineel zou ik dit samen met een team genoot doen, maar uiteindelijk ben ik hier zelf mee verder gegaan.

De oplossing die ik uiteindelijk gevonden heb is het gebruik maken van [SSS driehoken](https://www.mathsisfun.com/algebra/trig-solving-sss-triangles.html), een driehoek waar je alle lengtes weet, maar niet de hoeken. In onderstaande afbeelding is te zien hoe deze informatie daarna is getoond in python.

<img src="https://i.imgur.com/EpigWMn.png" alt="Elleboog hoek" width="700" height="250">

De geschreven functie voor het berekenen van de ellebooghoek is te vinden in cell 3 [dit](1.%20Animaties/Animation%20Demo.ipynb) van bestand.

# Cleaned data
Na het ontvangen van de cleaned data zijn we begonnen met het begrijpen en analyseren hiervan. Hier hebben we veel tijd van ons project voor gebruikt.

## Gecleande Visualisatie - beweged skelet
Bij de gecleande data hebben we ook een manier gezocht om de oefening visueel te maken. Orgineel was het de bedoeling om hetzelfde plaatje te maken als bij de ruwe data [gemaakt was](#Visualisatie). Dit was alleen lastiger om voor de gecleande data te doen sinds deze geen locatie data meer had, alleen maar relatieve hoeken. Om deze hoeken om te zetten in een soortgelijke afbeelding ben ik op onderzoek gegaan hoe ik deze reletieve hoeken moet behandelen. Het is niet gelukt om de data op dezelfde manier te interpreteren als bij de ruwe data, de beweging die getoont wordt in onderstaande afbeelding zou gelijk moeten zijn. Maar is dit niet.

Ik heb niet alleen zelf geprobeerd dit op te lossen, de wiskunde groepslid kon dit probleem ook niet oplossen. De hoeken konden door ons niet op de juiste manier geinterpreteerd worden, dit komt misschien mede door de moeilijke communicatie tussen ons en het LUMC.

!!! op oude laptop script zoeken !!!

## Gecleande Visualisatie - bovenarm
Na het niet kunnen visualiseren in een 3d bewgend plaatje zijn heb ik de data op een simpelere 2d manier gevisualiseerd.zoals hieronder te zien is.

![](https://i.imgur.com/loNFJBH.png)

## Classifiers - cleaned data
Tijdens het werken met classifiers binnen dit project heb ik aan veel classifiers mee gewerkt. In de [paper](paper_ortho_eyes.pdf) zijn de resultaten van deze classifiers te zien.

### Classifier 1, 2, 3, 4
De eerste classifier die ik heb gemaakt in dit project is de één tegen de 3 classifier, waar één categorie tegen de andere categorien vergeleken wordt. Dit was gedaan op sample niveau wat in de [paper](paper_ortho_eyes.pdf) wordt uitgelegd. Het maken van de classifier is gedaan met SKlearn. Het script wat gebruikt is voor deze classifier is omgebouwt tot een andere classifier, maar is te zien in cell 3 van [dit](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) script.

### Classifier 5 (5 classifiers combined)
Classifier 5 is een 5-in-1 classifier. Dit is het resultaat van classifier 1, 2, 3, 4 als input van een 5e classifier. Deze classifier is samen met kasper gemaakt, waar kasper en ik de eerste versie samen hebben gemaakt. Waarna ik zelf het script heb op geschoond tot een beutified versie. Dit script is [hier](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) te vinden. 

### Classifier 10 t/m 21 (Category 1 vs 2 (True vs False))
Classifier 11 tot en met 22 heeft ons geholpen de data beter te begrijpen, met de resultaten van deze classifier (te vinden in de [paper](paper_ortho_eyes.pdf)) hebben we gezien dat hoe groter het verschil tussen de categorien, hoe preciser we kunnen clasificeren. De classifier werkt door twee categorien met elkaar te vergelijken, bijvoorbeeld categorie 1 met 2 (True vs False). Deze sample niveau classifier is samen met vincent gemaakt en is [hier](3.%20Classifiers/Classifier%202%20vs%203%20v0.2.ipynb) te vinden.

### Classifier 25 t/m 48 (Category 1 vs 2 .MAX)
Classifier 26 tot en met 49 is de eerste poging tot een patient niveau classifier. Om van sample niveau classifiers af te stappen hadden we een manier nodig om parameters van een patient te maken. Als eerste patient classifier hebebn we daarom gekozen om de absolute maximale hoeken mee te nemen als waardes voor de classifier. Het idee hierachter was om de maximale beweging van de patient te meten, om te zien hoever hij zijn arm bijvoorbeeld omhoog kon bewegen.

Deze patient niveau classifier is samen met vincent gemaakt en is [hier](3.%20Classifiers/classifier%20patient%20niveau%20versie%200.2%20-%202%20classes.ipynb) te vinden.

### Classifier 49 (Multivariate classifier MAX.ABS)
De vorige classifier deed alle categorien apart tegenover elkaar zetten, in deze versie heb ik samen met vincent dezelfde data in een multivariate classifier geprobeerd.

Dit script is [hier](3.%20Classifiers/classifier%20patient%20niveau%20versie%200.3%20-%20less%20is%20more.ipynb) te vinden.

### Oefening Classifier
Één van de misluke pogingen was een classifier maken die de oefeningen zou identificeren, dit is een concept wat misschien wat meer inzicht zou geven over de oefeningen. Dit is een script gebasseerd op de [5-in-een](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) en is hernoemd naar de [40-in-een classifier](3.%20Classifiers/40%20in%201.ipynb)

## Energie berekenen
Om meer parameters voor een patient te berekenen, kregen we het advies van de lectoraat om de energie te berekenen. Dit is een meetwaarde, die volgens de lectoraat, vaak gebruikt wordt. De energie kunnen we berekenen door de afgeleide te nemen van een patient zijn oefening. Een voorbeeld van zo'n oefening is [hier](#Gecleande-Visualisatie---bovenarm) te zien.

De afgeleide van een oefening laat de versnelling zien, de oppervlakte van de versnelling is ook wel de energie genoemd. Om dit te berekenen in python hebben we de volgende methode gebruikt.

![](https://i.imgur.com/cpWTLew.png)

Om de oppervlakte van de afgeleide te berekenen hebben we eerst de oppervlakte van het vierkant(in de afbeelding ligt blauw) berekend, daarna de oppervlakte van het driehoek wat daarom ligt (in het plaatje oranje strepen). Omdat er met deze methode ook de witte onderkant onderkant meegenomen wordt berekenen we de onderkant op dezelfde manier, en trekken we deze van de totale oppervlakte af. Om te bepalen of boven of onder zitten hebben we gedaan door naar links gaan op te tellen en bij het naar rechts gaan af te trekken. Op deze manier krijgen we de oppervlakte van alleen de binnenkant. Ook wordt er op deze manier de energie juist berekend op dubbele gedeeltes, zoals de loop die links te zien is.

Het script voor de energie berekenen heb ik alleen gemaakt, de strategie hoe we dit berekenen hebben we als groep verzonnen met behulp van Tony. Het script komt in de [patient classifier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) voor en staat [hier](2.%20miscellaneous/Oppervlakte.ipynb) als los script.

### Classifier Energie
Met deze nieuwe data heb ik samen met Vincent een classifier gebouwd met alleen deze informatie. Uit deze classifier kwamen helaas geen zinnig resultaten. 

## Toppen berekenen
Om een andere paramter te maken die iets zegt over de oefening, en makkelijk te maken is. Heb ik een functie gemaakt die telt hoevaak een grafiek van richting veranderd. Dit zou het aantal pieken moeten optellen. Of dit getal ook iets toevoegd is niet getest, maar was in ieder geval een extra parameter waarme de classifier kon werken.

Het maken van deze toppen teller heb ik zelf gedaan, het verzinnen ook. De toppen teller is te vinden in [dit](2.%20miscellaneous/Turn%20punten%20berekenen.ipynb) notebook.

# Super cleaned data
Na onsuccesvol met de door het LUMC gecleande data onze categorieen te classificieren, zijn we de data gaan opschonen. De opgeschoonde data van de gecleande data hebben we de super cleaned data genoemd.

De reden dat opschonen nodig was is te zien in onderstaande afbeelding. 

![](https://i.imgur.com/1K5LXwz.png)

In deze afbeelding is te zien dat het eigenlijk twee oefeningen zijn, daarnaast is te zien dat de oefening pas begint bij frame ~100. Daarom hebben we alle oefeningen ~1500 nagelopen om de data meer eenduidiger te maken.

## Creëren data
Om de gecleande data op te schonen heb ik een script gemaakt die dit gebruiksvriendelijk doet. Door middel van gamification heb ik een soort spel gemaakt waarom de gebruiker drie keer om input gevraagd wordt:
- Welke frame de splitsing moet komen
- Wanneer de eerste oefening echt begint
- Wanneer de tweede oefening echt eindigd

In onderstaande afbeelding zie je de afbeelding die de gebruiker ziet na het invullen van de drie getallen.

![](https://i.imgur.com/tDLtOyX.png)

Het script wat de gebruikers gebruikte is [hier](5.%20Data%20Cleaning/Data%20Verdubbelaar%20V2.0.ipynb) te zien. In dit script worden de getallen opgeslagen in een metadata.csv bestand die later gebruikt is om de oefeningen daadwerkelijk te splitsen.

### Toepassen splitsing
Om het metadata.csv bestand toe te passen op de oefeningen ben ik samen met kasper alle oefeningen nagelopen om te kijken of er niks fout is gegaan. Zo hebben we handmatig alle oefeningen gesplitst die bijvoorbeeld uit drie oefeningen bestonden. Al deze wijzegingen hebben we opgeslagen in drie bestanden, te vinden in [deze](5.%20Data%20Cleaning/Corrections) map.

Het script wat gebruikt is om deze vier csv bestanden om te zetten naar nieuwe oefeningen is [hier](5.%20Data%20Cleaning/Clean%20Checker.ipynb) te vinden, onder het kopje 'step 2'.

## Oefening onderzoek
Om de data nog beter te kunnen vergelijken wouden we de oefeningen met elkaar vergelijken. Tijdens ons gesprek met de groot, onze opdracht gever, werd er verteld dat er altijd 5 oefeningen zijn die bij iedereen uitgevoerd worden. Als groep wisten we alleen niet welke 5 oefeningen dat waren binnen de patient categorien. Daarom wouden we hier onderzoek naar doen.

Orgineel zou een ander teamlid dit onderzoek doen, maar die kwam er niet achter hoe de oefeningen met elkaar verbonden waren. Daarom heb ik dit zelf op gepakt en ben ik met mijn papier aan de gang gegaan. Door van elke oefening per categorie een schets te maken kon ik de oefeningen over de categorieen vergelijken.

Uit eigen onderzoek bleek dat de alle oefeningen eigenlijk variaties waren op 5 oefeningen, op oefening 22 Cat4 na. Oefening 22 hebben we niet meegenomen. Onderstaand zijn de notities te zien.

![](https://i.imgur.com/oZ2HHRe.jpg)

Het script om deze oefeningen goed te zetten is [hier](5.%20Data%20Cleaning/Clean%20Checker.ipynb) te vinden onder het kopje 'step 3'.

# Classifier Super cleaned data
Met deze data wouden we een patient level classifier maken. Deze classifier konden we nu vullen met oefening informatie. Omdat we deze nu gelijk getrokken hadden over de verschillende categorien.

## Creeeren dataset
Om de patient classifier te maken wouden we deze vullen met 5 soorten informatie:
- Informatie over oefening Alpha
- Informatie over oefening Bravo
- Informatie over oefening Charlie
- Informatie over oefening Delta
- Informatie over oefening Echo

Voor elke oefening wouden ik deze informatie meenmen:
- Energie bovenarm X, Y, Z
- Toppen bovenarm X, Y, Z
- Alle paramters van frame 10% (24 colommen, excl ellebooghoek)
- Alle paramters van frame 25% (24 colommen, excl ellebooghoek)
- Alle paramters van frame 50% (24 colommen, excl ellebooghoek)
- Alle paramters van frame 75% (24 colommen, excl ellebooghoek)
- Alle paramters van frame 90% (24 colommen, excl ellebooghoek)

In totaal kwamen we rond de 630 colommen per regel.

Om nu de patient regels te maken, moesten we kiezen welke oefening we mee wouden nemen. Sinds we de data gesplist hadden kunnen sommige patienten één oefening twee of meer keer gedaan hebben. Omdat we geen data weg wouden gooien hebben ik besloten om een cross join te gebruiken om alle combinaties van oefeningen mee te nemen als regels.

```
Voorbeeld:
Als Patient 4018 de volgende oefeningen heeft gedaan
Alpha: 1 x
Bravo: 1 x
Charlie: 3 x
Delta: 1 x
Echo: 1 x

Dan zouden alle combinaties van oefeningen het volgende zijn:
Alpha 1 Bravo 1 Charlie 1 Delta 1 Echo 1
Alpha 1 Bravo 1 Charlie 2 Delta 1 Echo 1
Alpha 1 Bravo 1 Charlie 3 Delta 1 Echo 1
```
Op deze manier hebben we onze circa 100 patienten omgezet in 46000 regels data, dit is zonder de aparte testset.

Het script wat dit doet heb ik zelf in de vakantie gemaakt en is [hier](3.%20Classifiers/Patient%20level%20-%20Create%20dataset.ipynb) te vinden.

## Classifier 55 t/m 58 (Final Classifier) 
Dit is de laatste classifier die ik gemaakt heb binnen dit project. In deze classifier wordt de data die in het vorige hoofdstuk gemaakt is gebruikt. Als eerst is deze data ~80% / ~20% gesplitst om het succes van deze classifier te meten. Hier kwam een vrij hoog percentage uit. Ook [hier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) te vinden.

![](https://i.imgur.com/nxUNZ4u.png)

Met dit resultaat hebben we ook de aparte testset super cleaned, dit heeft Vincent gedaan in de laatste week van het project. Met deze super cleaned testset hebben we de huidige classifier opnieuw getest, en daar kwam het volgende resultaat uit.

![](https://i.imgur.com/EInWTmq.png)

Een nog hoger resultaat dan de eerste testset. Een succes voor ons als groep!
De classifier zelf is [hier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) te vinden.

## Classifier 51 t/m 54 (Final Classifier) 
Met dit resultaat moesten we ook deze classifier proberen zonder de data te super cleanen. Dit hebben ik ook gedaan, maar zonder groot succes. Uit deze classifier kwam niet zo'n  mooi resultaat


### Sprint 3
Sprint 3 die liep van 24-09-2018 tot 1-10-2018. In deze sprint ben ik vooral bezig geweest met het visueel maken van de geschone data die in de vorige sprint beschikbaar was gesteld. Om dit probleem op te lossen heb ik twee verschillende oplossingen geprobeerd. De eeste door de bewegingen in driehoeken te verdelen en de afstand uit te meten, te zien in onderstaande afbeelding. En als tweede oplossing is het gebruik van rotatie matrixen getest. Uiteindelijk is er gekozen voor rotatie matrixen sinds het werken met driehoeken niet precies genoeg was vanwege tussendoor afronden. Dit kwam op een verschil uit van 1 % per beweging.

<img src="https://i.imgur.com/CppW2sH.png" alt="Variable namen" width="250" height="250">
