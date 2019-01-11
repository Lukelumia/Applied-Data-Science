# Applied-Data-Science
Welkom bij het portfolio van Luke de Keijzer, in dit portfolio zullen alle activiteiten beschreven worden waaraan ik heb meegewerkt/ gedaan heb binnen de minor Applied Data science - KB74 (in de periode van sep 2018 t/m jan 2019). 

In deze minor heb in een team van 3 medestudenten en één docent gewerkt aan een onderzoek voor het LUMC. 

Ons doel tijdens dit onderzoek was om te achterhalen of het 'flock-of-birds'-systeem dat momenteel door het LUMC enkel wordt gebruikt voor onderzoeksdoeleinden of dat het ook gebruikt kan worden voor de diagnostische doeleinden.

# Inhoudsopgave 
- [1. Jargon](#1-jargon)
- [2. Onderzoek](#2-onderzoek)
- [3. Pre-data](#3-pre-data)
  - [3.1 Opzetten project management](#31-opzetten-projectmanagement)
     - [3.1.1 Scrumboard](#311-scrumboard)
     - [3.1.2 Scrum by Vince](#312-scrum-by-vince)
  - [3.2 Zelfontwikkeling](#32-zelfontwikkeling)
     - [3.2.1 DataCamp Voortgang](#321-datacamp-voortgang)
     - [3.2.1 Coursera Voortgang](#321-coursera-voortgang)
  - [3.3 Strategie](#33-strategie)
- [4. Raw data](#4-raw-data)
  - [4.1 Visualisatie](#41-visualisatie)
  - [4.2 Ellebooghoek](#42-ellebooghoek)
- [5. Cleaned data](#5-cleaned-data)
  - [5.1 Gecleande Visualisatie - bewegend skelet](#51-gecleande-visualisatie---bewegend-skelet)
  - [5.2 Gecleande Visualisatie - bovenarm](#52-gecleande-visualisatie---bovenarm)
  - [5.3 Classifiers - cleaned data](#53-classifiers---cleaned-data)
     - [5.4.1 Classifier 1, 2, 3, 4](#541-classifier-1-2-3-4)
     - [5.4.2 Classifier 5 (5 classifiers combined)](#542-classifier-5-5-classifiers-combined)
     - [5.4.3 Classifier 10 t/m 21 (Category 1 vs 2 (True vs False))](#543-classifier-10-tm-21-category-1-vs-2-true-vs-false)
     - [5.4.4 Classifier 25 t/m 48 (Category 1 vs 2 .MAX)](#544-classifier-25-tm-48-category-1-vs-2-max)
     - [5.4.5 Classifier 49 (Multivariate classifier MAX.ABS)](#545-classifier-49-multivariate-classifier-maxabs)
     - [5.4.6 Oefening Classifier](#546-oefening-classifier)
  - [5.5 Energie berekenen](#55-energie-berekenen)
     - [5.5.1 Classifier Energie](#551-classifier-energie)
  - [5.6 Toppen berekenen](#56-toppen-berekenen)
- [6. Super cleaned data](#6-super-cleaned-data)
  - [6.1 Creëren data](#61-creëren-data)
     - [6.1.1 Toepassen splitsing](#611-toepassen-splitsing)
  - [6.2 Oefening onderzoek](#62-oefening-onderzoek)
  - [6.3 Classifier Super cleaned data](#63-classifier-super-cleaned-data)
     - [6.3.1 creëren dataset](#631-creëren-dataset)
     - [6.3.2 Classifier 55 t/m 58 (Final Classifier)](#632-classifier-55-tm-58-final-classifier)
     - [6.3.3 Classifier 51 t/m 54 (Final Classifier)](#633-classifier-51-tm-54-final-classifier)
- [7. Extra activiteiten](#7-Extra-activiteiten)
  - [7.1 Uitleg](#71-Uitleg)
  - [7.2 CVB-borrel](#72-CVB-borrel)
  - [7.3 Presentaties](#73-Presentaties)

# 1. Jargon
Tijdens ons onderzoek hebben we met termen gebruikt die eigenlijk alleen maar begrepen kunnen worden door ons projectteam, maar deze zullen wel in dit portfolio terugkomen. Daarom zullen ze hieronder worden toegelicht.

jargon | Explenation 
--- | --- 
Raw data / Ruwe data | Ruwe sensor data met locatie en rotatie van de sensoren  
Cleaned data / Schone data | Cleaned data zijn de door LUMC verwerkte ruwe data, in deze data zijn alle locaties weg is alle data relatief van elkaar weergegeven d.m.v. hoeken 
Super cleaned data / Super schone data | De super cleaned data is de door ons schoon gemaakte cleaned data, dit proces is later beschreven

Naast ons project jargon zijn er ook termen die gebruikt worden om dit medisch gebied, deze zijn hieronder te zien. Dit plaatje is gemaakt door [Vincent](https://github.com/Vincentvdoord/Data-Science-KB-74)
<div style="text-align:center"><img src="https://i.imgur.com/9aViKwp.png" width="700" height="700"></div>

# 2. Onderzoek
Het doel van het onderzoek is het volgende:
> achterhalen of het 'flock-of-birds'-systeem dat momenteel door het LUMC enkel wordt gebruikt voor onderzoeksdoeleinden of dat het ook gebruikt kan worden voor de diagnostische doeleinden

Tijdens het uitvoeren van dit onderzoek zouden we twee soorten data tot onze beschikbaarheid krijgen, ruwe data & gecleande data. Met de gecleande data hebben we de super cleaned data gemaakt, deze drie soorten data hebben ons onderzoek eigenlijk opgesplitst in 3 fases. Elk van deze drie fases had zijn eigen activiteiten die hieronder beschreven zijn

![Onderzoek fases](https://i.imgur.com/ICHGDiO.png)

- [Ga naar: 3. pre-data](#3-pre-data)
- [Ga naar: 4. raw data](#4-Raw-data)
- [Ga naar: 5. cleaned data](#5-cleaned-data)
- [Ga naar: 6. super cleaned data](#6-super-cleaned-data)

# 3. Pre-data
In de fase voordat we data ontvingen ben ik vooral bezig geweest met drie onderwerpen, namelijk:
- [Opzetten projectmanagement](#31-opzetten-projectmanagement))
- [Zelfontwikkeling](#32-zelfontwikkeling)
- [Strategie](#33-strategie)

## 3.1 Opzetten projectmanagement
Als projectontwikkelingsmethode hebben we als groep gekozen om Scrum te gebruiken, dit hebben gedaan om iteratief aan het project te werken en sinds de project details pas duidelijk zouden worden tijdens het project was dit voor ons de juiste keuze.

Als scrumtool gebruiken wij de website: <img src="https://wac-cdn.atlassian.com/dam/jcr:d6a89d75-bad0-46f3-88aa-406542eb6cb5/trello-logo-blue-flat.png" alt="alt text" width="90" height="23">. Met deze Projectmanagement tool kunnen wij mensen aan projectentaken koppelen en exact extraheren hoeveel tijd er aan welke activiteiten besteed is.

Het onderzoek en het oprichten is vooral door mij en Vincent gedaan aan het begin van dit project.

### 3.1.1 Scrumboard
Het Scrumboard wat wij gebruiken bestaat uit 5 kolommen die de lay-out van het board bepalen. Deze kolommen zijn: Product Back log; Sprint Back log; In-Progress; Verify & Done. Om personen, datums, metadata & problemen aan te geven wordt er gebruikt gemaakt van tags en andere vormen van metadata. Een afbeelding van het Scrum Board is te zien in de volgende afbeelding.
De originele inrichting is door Vincent en mij samengedaan.
![](https://i.imgur.com/QqA3vb1.jpg)

### 3.1.2 Scrum by Vince
De plug-in 'Scrum by Vince' maakt het mogelijk om tijd per activiteit in te plannen en een burndown chart te genereren. Het nadeel van deze burn down chart is dat ervan uit gegaan wordt dat alle beschikbare tijd volledig ingepland is. Dat is in Sprint 1 nog niet altijd het geval. Een afbeelding van een burndown chart via 'Scrum by Vince' is te zien in de volgende afbeelding.
Het onderzoek doen naar welke scrum tools het beste werken binnen Trello is alleen gedaan.
![](https://i.imgur.com/C8H2r1w.jpg)

## 3.2 Zelfontwikkeling
In het begin van de course 'Applied Data Science' hebben we ons vooral gericht op zelfontwikkeling, met name zelfontwikkeling op het gebied van Python en machine learning. Onderaan zal de voortgang van de python courses (via DataCamp); en de voortgang van machine learning (via Coursera) staan.

### 3.2.1 DataCamp Voortgang
<details><summary>Klik mij om de DataCamp voortgang te zien (foto) <img src="http://pngimg.com/uploads/exclamation_mark/exclamation_mark_PNG32.png" alt="Uitroepteken" width="16" height="16"></summary>
  <img src="https://i.imgur.com/BxXcGKm.png" alt="DataCamp Voortgang">
</details>

### 3.2.1 Coursera Voortgang
<details><summary>Klik mij om de Coursera voortgang te zien (foto) <img src="http://pngimg.com/uploads/exclamation_mark/exclamation_mark_PNG32.png" alt="Uitroepteken" width="16" height="16"></summary>
  <img src="https://i.imgur.com/N9B9MnQ.png" alt="Coursera Voortgang">
</details>

## 3.3 Strategie
Als team hebben we gezamenlijk een strategie opgezet om het project te lijden. In deze strategie zouden we eerst onderzoek doen naar de ruwe data; daarna de cleaned data; en als laatste unsupervised learning.

# 4. Raw data
Al vrij snel in het project, rond week 3, hebben we de eerste samples data ontvangen. Bij dit ontvangst kregen we één ruwe data meting en één door het LUMC gecleande data meting. Met deze twee bestanden konden we ons richten op het daadwerkelijk begrijpen van de data. Volgens de strategie zouden we ons eerst focussen op de ruwe data.

Omdat de ruwe data maar niet binnen kwam hebben we besloten hier niet mee verder te gaan, toch zijn er elke activiteiten die voor de ruwe data gemaakt zijn:
- [Visualisatie](#Visualisatie)
- [Ellebooghoek](#Ellebooghoek)

## 4.1 Visualisatie
Om de data te begrijpen ben ik de data gaan visualiseren. Tony had een script geschreven om één frame van een oefening te visualiseren. Dit is gedaan door een skelet te tekenen met de locatie van de sensoren die in de ruwe data gemeten werden.

Met dit script ben ik rond week 4 verder gegaan, met eigen onderzoek heb ik een animatie van de frames kunnen maken die liet zien welke beweging de patiënt gemaakt zou moeten hebben bij het daadwerkelijk uitvoeren van de oefening.
![](https://i.imgur.com/LO7XOCw.gif)

Het script wat bovenstaand gif gemaakt heeft is [hier](1.%20Animaties/Animation%20Demo.ipynb) te zien. Later is dit script uitgebreid om de visualisatie van raw data & cleaned data naast elkaar te laten draaien.

## 4.2 Ellebooghoek
In het onderzoek dat we uitgevoerd hebben was een van onze doelen achterhalen hoe het LUMC van de ruwe data naar de gecleande data zou transformeren. Een van de berekende kolommen waren de elle boog hoeken. Sinds we alleen de positie hadden van de sensoren ben ik hierin onderzoek naar gaan doen. Origineel zou ik dit samen met een team genoot doen, maar uiteindelijk ben ik hier zelf mee verder gegaan.

De oplossing die ik uiteindelijk gevonden heb is het gebruik maken van [SSS driehoken](https://www.mathsisfun.com/algebra/trig-solving-sss-triangles.html), een driehoek waar je alle lengtes weet, maar niet de hoeken. In onderstaande afbeelding is te zien hoe deze informatie daarna is getoond in python.

<img src="https://i.imgur.com/EpigWMn.png" alt="Elleboog hoek" width="700" height="250">

De geschreven functie voor het berekenen van de ellebooghoek is te vinden in cell 3 [dit](1.%20Animaties/Animation%20Demo.ipynb) van bestand.

# 5. Cleaned data
Na het ontvangen van de cleaned data zijn we begonnen met het begrijpen en analyseren hiervan. Hier hebben we veel tijd van ons project voor gebruikt.

## 5.1 Gecleande Visualisatie - bewegend skelet
Bij de gecleande data hebben we ook een manier gezocht om de oefening visueel te maken. Origineel was het de bedoeling om hetzelfde plaatje te maken als bij de ruwe data [gemaakt was](#Visualisatie). Dit was alleen lastiger om voor de gecleande data te doen sinds deze geen locatie data meer had, alleen maar relatieve hoeken. Om deze hoeken om te zetten in een soortgelijke afbeelding ben ik op onderzoek gegaan hoe ik deze relatieve hoeken moet behandelen. Het is niet gelukt om de data op dezelfde manier te interpreteren als bij de ruwe data, de beweging die getoond wordt in onderstaande afbeelding zou gelijk moeten zijn. Maar is dit niet.

<img src="https://i.imgur.com/CppW2sH.png" alt="Variabel namen" width="250" height="250">

Ik heb niet alleen zelf geprobeerd dit op te lossen, de wiskunde groepslid kon dit probleem ook niet oplossen. De hoeken konden door ons niet op de juiste manier geïnterpreteerd worden, dit komt misschien mede door de moeilijke communicatie tussen ons en het LUMC.

## 5.2 Gecleande Visualisatie - bovenarm
Na het niet kunnen visualiseren in een 3d bewegend plaatje zijn heb ik de data op een simpelere 2d manier gevisualiseerd. Zoals hieronder te zien is.

![](https://i.imgur.com/loNFJBH.png)

## 5.3 Classifiers - cleaned data
Tijdens het werken met classifiers binnen dit project heb ik aan veel classifiers mee gewerkt. In de [paper](paper_ortho_eyes.pdf) zijn de resultaten van deze classifiers te zien.

### 5.4.1 Classifier 1, 2, 3, 4
De eerste classifier die ik heb gemaakt in dit project is de een tegen de 3 classifier, waar één categorie tegen de andere categorieën vergeleken wordt. Dit was gedaan op sample niveau wat in de [paper](paper_ortho_eyes.pdf) wordt uitgelegd. Het maken van de classifier is gedaan met SKlearn. Het script wat gebruikt is voor deze classifier is omgebouwd tot een andere classifier, maar is te zien in cell 3 van [dit](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) script.

### 5.4.2 Classifier 5 (5 classifiers combined)
Classifier 5 is een 5-in-1 classifier. Dit is het resultaat van classifier 1, 2, 3, 4 als input van een 5e classifier. Deze classifier is samen met Kasper gemaakt, waar Kasper en ik de eerste versie samen hebben gemaakt. Waarna ik zelf het script heb op geschoond tot een beautified versie. Dit script is [hier](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) te vinden. 

### 5.4.3 Classifier 10 t/m 21 (Category 1 vs 2 (True vs False))
Classifier 11 tot en met 22 heeft ons geholpen de data beter te begrijpen, met de resultaten van deze classifier (te vinden in de [paper](paper_ortho_eyes.pdf)) hebben we gezien dat hoe groter het verschil tussen de categorieën, hoe preciezer we kunnen classificeren. De classifier werkt door twee categorieën met elkaar te vergelijken, bijvoorbeeld categorie 1 met 2 (True vs False). Deze sample niveau classifier is samen met Vincent gemaakt en is [hier](3.%20Classifiers/Classifier%202%20vs%203%20v0.2.ipynb) te vinden.

### 5.4.4 Classifier 25 t/m 48 (Category 1 vs 2 .MAX)
Classifier 26 tot en met 49 is de eerste poging tot een patiënt niveau classifier. Om van sample niveau classifiers af te stappen hadden we een manier nodig om parameters van een patiënt te maken. Als eerste patiënt classifier hebben we daarom gekozen om de absolute maximale hoeken mee te nemen als waardes voor de classifier. Het idee hierachter was om de maximale beweging van de patiënt te meten, om te zien hoever hij zijn arm bijvoorbeeld omhoog kon bewegen.

Deze patiënt niveau classifier is samen met Vincent gemaakt en is [hier](3.%20Classifiers/classifier%20patient%20niveau%20versie%200.2%20-%202%20classes.ipynb) te vinden.

### 5.4.5 Classifier 49 (Multivariate classifier MAX.ABS)
De vorige classifier deed alle categorieën apart tegenover elkaar zetten, in deze versie heb ik samen met Vincent dezelfde data in een multivariate classifier geprobeerd.

Dit script is [hier](3.%20Classifiers/classifier%20patient%20niveau%20versie%200.3%20-%20less%20is%20more.ipynb) te vinden.

### 5.4.6 Oefening Classifier
Één van de mislukte pogingen was een classifier maken die de oefeningen zou identificeren, dit is een concept wat misschien wat meer inzicht zou geven over de oefeningen. Dit is een script gebaseerd op de [5-in-een](3.%20Classifiers/5in1_v3.2%20-%20beautified%20split.ipynb) en is hernoemd naar de [40-in-een classifier](3.%20Classifiers/40%20in%201.ipynb)

## 5.5 Energie berekenen
Om meer parameters voor een patiënt te berekenen, kregen we het advies van de lectoraat om de energie te berekenen. Dit is een meetwaarde, die volgens de lectoraat, vaak gebruikt wordt. De energie kunnen we berekenen door de afgeleide te nemen van een patiënt zijn oefening. Een voorbeeld van zo'n oefening is [hier](#Gecleande-Visualisatie---bovenarm) te zien.

De afgeleide van een oefening laat de versnelling zien, de oppervlakte van de versnelling is ook wel de energie genoemd. Om dit te berekenen in python hebben we de volgende methode gebruikt.

![](https://i.imgur.com/cpWTLew.png)

Om de oppervlakte van de afgeleide te berekenen hebben we eerst de oppervlakte van het vierkant(in de afbeelding ligt blauw) berekend, daarna de oppervlakte van de driehoek wat daarom ligt (in het plaatje oranje strepen). Omdat er met deze methode ook de witte onderkant meegenomen wordt berekenen we de onderkant op dezelfde manier, en trekken we deze van de totale oppervlakte af. Om te bepalen of boven of onder zitten hebben we gedaan door naar links gaan op te tellen en bij het naar rechts gaan af te trekken. Op deze manier krijgen we de oppervlakte van alleen de binnenkant. Ook wordt er op deze manier de energie juist berekend op dubbele gedeeltes, zoals de loop die links te zien is.

Het script voor de energie berekenen heb ik alleen gemaakt, de strategie hoe we dit berekenen hebben we als groep verzonnen met behulp van Tony. Het script komt in de [patiënt classifier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) voor en staat [hier](2.%20miscellaneous/Oppervlakte.ipynb) als los script.

### 5.5.1 Classifier Energie
Met deze nieuwe data heb ik samen met Vincent een classifier gebouwd met alleen deze informatie. Uit deze classifier kwamen helaas geen zinnig resultaten. 

## 5.6 Toppen berekenen
Om een andere parameter te maken die iets zegt over de oefening, en makkelijk te maken is. Heb ik een functie gemaakt die telt hoe vaak een grafiek van richting veranderd. Dit zou het aantal pieken moeten optellen. Of dit getal ook iets toevoegt is niet getest, maar was in ieder geval een extra parameter waarmee de classifier kon werken.

Het maken van deze toppen teller heb ik zelf gedaan, het verzinnen ook. De toppen teller is te vinden in [dit](2.%20miscellaneous/Turn%20punten%20berekenen.ipynb) notebook.

# 6. Super cleaned data
Na onsuccesvol met de door het LUMC gecleande data onze categorieën te classificeren, zijn we de data gaan opschonen. De opgeschoonde data van de gecleande data hebben we de super cleaned data genoemd.

De reden dat opschonen nodig was is te zien in onderstaande afbeelding. 

![](https://i.imgur.com/1K5LXwz.png)

In deze afbeelding is te zien dat het eigenlijk twee oefeningen zijn, daarnaast is te zien dat de oefening pas begint bij frame ~100. Daarom hebben we alle oefeningen ~1500 nagelopen om de data meer eenduidiger te maken.

## 6.1 Creëren data
Om de gecleande data op te schonen heb ik een script gemaakt die dit gebruiksvriendelijk doet. Door middel van gamificatie heb ik een soort spel gemaakt waarom de gebruiker drie keer om input gevraagd wordt:
- Welke frame de splitsing moet komen
- Wanneer de eerste oefening echt begint
- Wanneer de tweede oefening echt eindigt

In onderstaande afbeelding zie je de afbeelding die de gebruiker ziet na het invullen van de drie getallen.

![](https://i.imgur.com/tDLtOyX.png)

Het script wat de gebruikers gebruikte is [hier](5.%20Data%20Cleaning/Data%20Verdubbelaar%20V2.0.ipynb) te zien. In dit script worden de getallen opgeslagen in een metadata.csv bestand die later gebruikt is om de oefeningen daadwerkelijk te splitsen.

### 6.1.1 Toepassen splitsing
Om het metadata.csv bestand toe te passen op de oefeningen ben ik samen met Kasper alle oefeningen nagelopen om te kijken of er niks fout is gegaan. Zo hebben we handmatig alle oefeningen gesplitst die bijvoorbeeld uit drie oefeningen bestonden. Al deze wijzigingen hebben we opgeslagen in drie bestanden, te vinden in [deze](5.%20Data%20Cleaning/Corrections) map.

Het script wat gebruikt is om deze vier CSV bestanden om te zetten naar nieuwe oefeningen is [hier](5.%20Data%20Cleaning/Clean%20Checker.ipynb) te vinden, onder het kopje 'step 2'.

## 6.2 Oefening onderzoek
Om de data nog beter te kunnen vergelijken wouden we de oefeningen met elkaar vergelijken. Tijdens ons gesprek met de groot, onze opdracht gever, werd er verteld dat er altijd 5 oefeningen zijn die bij iedereen uitgevoerd worden. Als groep wisten we alleen niet welke 5 oefeningen dat waren binnen de patiënt categorieën. Daarom wouden we hier onderzoek naar doen.

Origineel zou een ander teamlid dit onderzoek doen, maar die kwam er niet achter hoe de oefeningen met elkaar verbonden waren. Daarom heb ik dit zelf op gepakt en ben ik met mijn papier aan de gang gegaan. Door van elke oefening per categorie een schets te maken kon ik de oefeningen over de categorieën vergelijken.

Uit eigen onderzoek bleek dat de alle oefeningen eigenlijk variaties waren op 5 oefeningen, op oefening 22 Cat4 na. Oefening 22 hebben we niet meegenomen. Onderstaand zijn de notities te zien.

![](https://i.imgur.com/oZ2HHRe.jpg)

Het script om deze oefeningen goed te zetten is [hier](5.%20Data%20Cleaning/Clean%20Checker.ipynb) te vinden onder het kopje 'step 3'.

## 6.3 Classifier Super cleaned data
Met deze data wouden we een patiënt level classifier maken. Deze classifier konden we nu vullen met oefening informatie. Omdat we deze nu gelijk getrokken hadden over de verschillende categorieën.

### 6.3.1 Creëren dataset
Om de patiënt classifier te maken wouden we deze vullen met 5 soorten informatie:
- Informatie over oefening Alpha
- Informatie over oefening Bravo
- Informatie over oefening Charlie
- Informatie over oefening Delta
- Informatie over oefening Echo

Voor elke oefening wouden ik deze informatie meenemen:
- Energie bovenarm X, Y, Z
- Toppen bovenarm X, Y, Z
- Alle parameters van frame 10% (24 kolommen, excl. ellebooghoek)
- Alle parameters van frame 25% (24 kolommen, excl. ellebooghoek)
- Alle parameters van frame 50% (24 kolommen, excl. ellebooghoek)
- Alle parameters van frame 75% (24 kolommen, excl. ellebooghoek)
- Alle parameters van frame 90% (24 kolommen, excl. ellebooghoek)

In totaal kwamen we rond de 630 kolommen per regel.

Ook in afbeelding te zien:

![](https://i.imgur.com/IA8xrxh.jpg)

Om nu de patiënt regels te maken, moesten we kiezen welke oefening we mee wouden nemen. Sinds we de data gesplist hadden kunnen sommige patiënten één oefening twee of meer keer gedaan hebben. Omdat we geen data weg wouden gooien hebben ik besloten om een cross-join te gebruiken om alle combinaties van oefeningen mee te nemen als regels.

```
Voorbeeld:
Als Patiënt 4018 de volgende oefeningen heeft gedaan
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
Op deze manier hebben we onze circa 100 patiënten omgezet in 46000 regels data, dit is zonder de aparte testset.

Het script wat dit doet heb ik zelf in de vakantie gemaakt en is [hier](3.%20Classifiers/Patient%20level%20-%20Create%20dataset.ipynb) te vinden.

### 6.3.2 Classifier 55 t/m 58 (Final Classifier) 
Dit is de laatste classifier die ik gemaakt heb binnen dit project. In deze classifier wordt de data die in het vorige hoofdstuk gemaakt is gebruikt. Als eerst is deze data ~80% / ~20% gesplitst om het succes van deze classifier te meten. Hier kwam een vrij hoog percentage uit. Ook [hier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) te vinden.

![](https://i.imgur.com/nxUNZ4u.png)

Met dit resultaat hebben we ook de aparte testset super cleaned, dit heeft Vincent gedaan in de laatste week van het project. Met deze super cleaned testset hebben we de huidige classifier opnieuw getest, en daar kwam het volgende resultaat uit.

![](https://i.imgur.com/EInWTmq.png)

Een nog hoger resultaat dan de eerste testset. Een succes voor ons als groep!
De classifier zelf is [hier](3.%20Classifiers/Patient%20level%20-%20Classifier.ipynb) te vinden.

### 6.3.3 Classifier 51 t/m 54 (Final Classifier) 
Met dit resultaat moesten we ook deze classifier proberen zonder de data te super cleanen. Dit hebben ik ook gedaan, maar zonder groot succes. Uit deze classifier kwam niet zo'n  mooi resultaat

# 7. Extra activiteiten
Omdat tijdens het project soms extra activiteiten uitgevoerd zijn niet per se onder deze hiervoor beschreven fases vallen, staan hier andere activiteiten die eerder geen plaatst konden krijgen.

## 7.1 Uitleg
Tijdens deze minor begon ik met een voorsprong vergeleken met mijn groepsgenoten. Als enige had ik al ervaring met programmeren in Python. Daarom heb ik mijn ervaring proberen over te brengen, en de andere te helpen op dit gebied. Enkele foto's en tekst hiervan staan in het volgende document:

[Leraar Luke.md](Leraar%20Luke.md)

Naast het onderzoek doen zijn we ook bezig geweest met me paper. Aan de paper zelf heb ik niet veel geschreven, maar wel veel samengevat om Kasper en Rogier te helpen bij het schrijven. Zo is een van de voorbeelden deze foto, waarin ik alles samenvat wat we gedaan hebben om zo een logische structuur in de paper te brengen.

![](https://i.imgur.com/chl8JCl.jpg)

## 7.2 CVB-borrel
In oktober was er een CVB-borrel van de faculteit IT&D op de Haagse Hogeschool. Op verzoek van Tony hebben we hier een poster gepresenteerd om de minor Applied Data Science toe te lichten. Hieronder is een foto te zien hoe wij daar stonden.

![](https://i.imgur.com/qOHxcGD.jpg)

## 7.3 Presentaties
Tijdens elke sprint hebben we als groep twee presentaties gegeven, elke week één. Zelf heb ik de volgende vier presentaties gedaan:
- [Presentatie Week 2](Presentaties/Ortho%20Eyes%20presentatie%20week%202.pdf)
- [Presentatie Week 6](Presentaties/Ortho%20Eyes%20presentatie%20week%206.pdf)
- [Presentatie Week 15](Presentaties/Ortho%20Eyes%20presentatie%20week%2015.pdf)
- [Presentatie Week 16](Presentaties/Ortho%20Eyes%20presentatie%20week%2016.pdf)
