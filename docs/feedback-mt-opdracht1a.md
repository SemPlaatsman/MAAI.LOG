# M&T Opdracht 1a feedback per criterium

## A2: Je stelt voor een AI-oplossing juridische, ethische, organisatorische, functionele en technische requirements op

**Beoordeling:** Op niveau

### Positieve punten (+)
* Vanuit de opdracht en data en met de juiste verantwoording een volledige lijst gemaakt waar de modellen aan horen te voldoen
* Vanuit de opdracht en data bepaalt wanneer het model 'voldoende genoeg' is

### Verbeterpunten (-)
* Niet alle eisen uit de eisenlijst waar het model aan hoort te voldoen volgen uit de opdracht of jouw data-analyse

---

## B1: Je verkent en prepareert een dataset voor het trainen en testen van een AI-model en kan de voor- en nadelen van het gebruik van een bestaande dataset onderbouwen, rekening houdend met technische en ethische randvoorwaarden

**Beoordeling:** Hier is nog werk voor nodig

### Positieve punten (+)
* Data is correct gesplitst
* Correcte verantwoording van stratified split
* Stratified split correct gebruikt
* Testdata correct gebruikt

### Kritieke verbeterpunten (--)
* Je doet een dataverkenning op de gehele dataset (zonder splitsing). Dit is niet volgens de conventies en kan leiden tot data-leakage

---

## B2: Je stelt op basis van requirements en data een geschikte architectuur voor een AI-oplossing op en selecteert daarvoor passende AI-technieken gebruik makend van bijvoorbeeld machine learning, deep learning, kennisrepresentatie, computer vision en natural language processing

**Beoordeling:** Hier is nog werk voor nodig

### Positieve punten (+)
* Correcte verantwoording van prestatiemaat
* Correcte verantwoording van nulmodel

### Gemengde punten (+-)
* Correcte verantwoording van model door gebruik te maken van informatie over de opdracht en de data. Je bespreekt de voordelen van het model. Bespreek voortaan ook de nadelen
* Je geeft een verantwoording voor het model door gebruik te maken van informatie over de opdracht en de data. Zijn er andere modellen met dezelfde eigenschappen?

### Verbeterpunten (-)
* Het is onduidelijk uit welke modellen je gekozen hebt
* Data getransformeerd zonder correcte verantwoording. Ja, je zou hoog-correlerende variabelen kunnen verwijderen, maar er zijn wel meer variabelenselectiemethodes. Waarom zou je deze gebruiken? Je merkt terecht op dat dit niet zo noodzakelijk is voor een RF. Waarom dan toch doen? Het argument dat het interpreteerbaarheid betrouwbaarder zou zijn, is niet gefundeerd. Bovendien noem je interpreteerbaarheid hier voor het eerst (stond niet in de eisenlijst)
* Data getransformeerd zonder correcte verantwoording. Waarom zou het nodig zijn om Winsorizing te gebruiken? Welk probleem los je hiermee op en waarom los je dat probleem op deze manier op? Met deze methode verwijder je informatie uit de data. Er moeten wel heel goede redenen zijn om dat te doen. Bovendien weet ik niet zeker of uitschieters werkelijk zoveel invloed hebben op de beslisbomen

---

## B3: Je ontwikkelt een nieuw of voorgetraind AI-model volgens een iteratief en systematisch proces

**Beoordeling:** Hier is nog werk voor nodig

### Verbeterpunten (-)
* Het is niet duidelijk waarom enkele hyperparameters wel en andere niet worden getuned. Je zegt: "zijn de volgende parameters het belangrijkst om te tunen: " Waar is dit op gebaseerd?
* De keuze voor de waardes van de (grid-search van de) hyperparameters zijn niet altijd correct verantwoord
* Waarom zou je het aantal bomen tunen? Je kent het antwoord al
* Wat laat je eigen in die learning curve zien? Waarom staat "training set size" op de x-as? Wat betekent dit?

---

## C2: Je evalueert en beoordeelt de kwaliteit van een AI-model aan de hand van kwaliteitscriteria die in het vakgebied erkend worden zoals robustness, performance, scalability, explainability, model complexity en resource demand

**Beoordeling:** Hier is nog werk voor nodig

### Positieve punten (+)
* Testresultaten van de modellen worden gegeven
* Fouten van het model worden besproken
* Model wordt vergeleken met nulmodel

### Verbeterpunten (-)
* Geen confusion matrix. Je lijkt dit wel te willen presenteren, maar doe je uiteindelijk niet. Waarom is niet helemaal duidelijk