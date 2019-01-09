# Applied-Data-Science
Welkom bij de portfolio van Luke de keijzer, in dit portfolio zullen alle activiteiten beschreven worden waaraan ik heb meegewerkt / gedaan heb binnen de minor Applied Data science - KB74 ( in de periode van sep 2018 t/m jan 2019 ). 

In deze minor heb in een team van 3 medestudenten en één docent gewerkt aan een onderzoek voor het LUMC. 

Ons doel tijdens dit onderzoek was om te achterhalen of het 'flock-of-birds'-systeem dat momenteel door het LUMC enkel wordt gebruikt voor onderzoeksdoeleinden of dat het ook gebruikt kan worden voor de diagnostische doeleinden.

# Inhoudsopgave 
- [Zelfontwikkeling](#Zelfontwikkeling)
- [Project management](#Project-management)
- [Jargon](#Jargon)
- [Onderzoek](#Onderzoek)
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

Omdat de ruwe data na

## Visualisatie
Om de data te begrijpen ben ik de data gaan visualiseren. Tony had een script geschreven om één frame van een oefening te visualiseren. Dit is gedaan door een skelet te tekenen met de locatie van de sensoren die in de ruwe data gemeten werden.

Met dit script ben ik rond week 4 verder gegaan, met eigen onderzoek heb ik een animatie van de frames kunnen maken die liet zien welke beweging de patient gemaakt zou moeten hebben bij het daadwerkelijk uitvoeren van de oefening.
![](https://i.imgur.com/LO7XOCw.gifv)

Het script wat bovenstaande gif gemaakt heeft is [hier](./1.\ Animaties/Animation\ Demo.ipynb) te zien. Later is dit script uitgebreid om de visualisatie van raw data & cleaned data naast elkaar te laten draaien.

## Ellebooghoek
In het onderzoek dat we uitgevoerd hebben was één van onze doelen achterhalen hoe het LUMC van de ruwe data naar de gecleande data zou transformeren. Een van de berekende colommen waren de elleboog hoeken. Sinds we alleen de positie hadden van de sensoren ben ik hierin onderzoek naar gaan doen. Orgineel zou ik dit samen met een team genoot doen, maar uiteindelijk ben ik hier zelf mee verder gegaan.

De oplossing die ik uiteindelijk gevonden heb is het gebruik maken van [SSS driehoken](https://www.mathsisfun.com/algebra/trig-solving-sss-triangles.html), een driehoek waar je alle lengtes weet, maar niet de hoeken. In onderstaande afbeelding is te zien hoe deze informatie daarna is getoond in python.

<img src="https://i.imgur.com/EpigWMn.png" alt="Elleboog hoek" width="700" height="250">

#


### Sprint 1
In sprint 1, die liep van 27-08-2018 tot 07-09-2018, zijn we vooral bezig geweest met Python leren en de omgevingen opzetten. De scrum omgeving opzetten en onderzoeken heb ik voornamelijk zelf gedaan. Als minor werd de omgeving scrumwise aangeraden, na zelf onderzoek gedaan te hebben naar alternatieve omgevingen heb ik Trello gevonden en deze aangeraden aan de groep. De reden dat Trello als beter uit dit onderzoek is gekomen komt door de modernere layout en het gebruiksvriendelijk drag & drop functionaliteiten. Daarnaast waren er plugins mogelijk die het scrumboard meer customizable maakte.

Naast het scrumboard ben ik ook bezig geweest met het uitleggen van Python. Sinds ik hier zelf al ervaring in had voordat de minor begon kon in de basics van Python (proberen) uit te leggen. Dit heb ik gedaan in 1 en 1 sessies en 2 op 1 sessies.

### Sprint 2
Sprint 2 die liep van 10-09-2018 tot 21-09-2018. In deze sprint heb ik mij vooral gefocust op het begrijpen van de rauwe data en het berekenen van nieuwe informatie uit de data. Zo is er in de geschoonde data een column berekent genaamd de elleboog hoek. Deze week wou ik deze willen kunnen berekenen door middel van de coordinaten van de rauwe data. Dit is uiteindelijk gelukt door gebruik te maken van een SSS-driehoek, dit is een driekhoek waar alleen de drie zijdes bekend zijn en niet de hoeken. Door berekeningen kunnen alle hoeken berkend worden, en dus ook de ellebooghoek. Na deze functie gemaakt te hebben kan deze ook gebruikt worden voor hoeken tussen andere assen, dat is ook te zien in onderstaande afbeelding.

<img src="https://i.imgur.com/EpigWMn.png" alt="Elleboog hoek" width="700" height="250">

### Sprint 3
Sprint 3 die liep van 24-09-2018 tot 1-10-2018. In deze sprint ben ik vooral bezig geweest met het visueel maken van de geschone data die in de vorige sprint beschikbaar was gesteld. Om dit probleem op te lossen heb ik twee verschillende oplossingen geprobeerd. De eeste door de bewegingen in driehoeken te verdelen en de afstand uit te meten, te zien in onderstaande afbeelding. En als tweede oplossing is het gebruik van rotatie matrixen getest. Uiteindelijk is er gekozen voor rotatie matrixen sinds het werken met driehoeken niet precies genoeg was vanwege tussendoor afronden. Dit kwam op een verschil uit van 1 % per beweging.

<img src="https://i.imgur.com/CppW2sH.png" alt="Variable namen" width="250" height="250">
