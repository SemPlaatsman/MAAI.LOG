Feedback for Tech Review Blok 2
Note: The activities evaluation will be applied to all members of this group.
Rubric Name: Rubric Technische Review

A2: Je stelt voor een AI-oplossing juridische, ethische, organisatorische, functionele en technische requirements op.
Je hebt ten minste een lijst van ondubbelzinnige juridische, ethische, organisatorische en
functionele en technische vereisten van de AI-oplossing. Deze zijn nader gedefinieerd aan de hand
van de bestaande literatuur, experts of vereisten van belangrijke stakeholders. Deze zijn
meegenomen in de ontwikkeling van de eindoplossing.

Criterion Feedback: Op verwachting
Jullie hebben de meeste requirements voorzien van bronvermeldingen, oftewel uit de literatuur of vanuit gebruikersonderzoek.
Sommige requirements zijn nog wat ambigue, zoals ER04, TR01. Deze zijn niet direct meetbaar gedefinieerd, probeer dat wel te doen.
Sommige requirements lijken helemaal niet voort te komen uit wat er is gezegd door jullie stakeholders. TR04, TR06, TR10. Klopt dat? Probeer deze altijd te herleiden naar onderzoek.
Testmethode = test of code is niet concreet en onduidelijk voor zowel een lezer als iemand die jullie onderzoek wil produceren. Probeer dit te verduidelijken.
B1: Je verkent en prepareert een dataset voor het trainen en testen van een AI-model en kan de voor- en nadelen van het gebruik van een bestaande dataset onderbouwen, rekening houdend met technische en ethische randvoorwaarden.
Je maakt een opsomming van de datasets die worden gebruikt voor het trainen, fine-tunen en
testen van je modellen. Je beschrijft de relevante kenmerken van de gekozen datasets voor de
oplossing en onderbouwt je keuzes hierin. Gebruik bijvoorbeeld wetenschappelijke bronnen en voer
een verkennende data-analyse uit, waarin de dataverdeling en mogelijke problemen zoals
ontbrekende data en onevenwichtigheden worden onthuld. Deze data-analyse is op een technisch
correcte manier toegepast. Dit komt terug in zowel het rapport als in code.

Criterion Feedback: Boven verwachting
EDA uitgevoerd. Komen duidelijke knelpunten naar voren. Duidelijk beschreven en meegenomen in jet vaststellen van de methodiek, waaronder datasetkeuze. Zeer goed!
Jullie datapreparatie regex en methodiek moet transparanter om het direct reproduceerbaar te maken, maar het resultaat wordt duidelijk beschreven en daaruit is te begrijpen wat jullie hebben gedaan. Probeer dit echter toch nog transparanter op te schrijven. Gelukkig is dit terug te vinden in de repo.
Duidelijke voor en nadelen besproken van de dataset. Boven verwachting zeker verdiend.
B2: Je stelt op basis van requirements en data een geschikte architectuur voor een AI-oplossing op en selecteert daarvoor passende AI-technieken gebruik makend van bijvoorbeeld machine learning, deep learning, kennisrepresentatie, computer vision en natural language processing.
Je beschrijft de gebouwde of geselecteerde (model)architecturen voor de gekozen oplossingsrichting. Hierbij beschrijf je welke metriek(en) je gebruikt om modellen te vergelijken en selecteren, evenals de onderbouwing van je keuzes. De toepassing is op een technisch correcte en methodologisch geaccepteerde wijze gedaan en dit kan het projectteam aantonen in de review

Criterion Feedback: Hier is nog werk nodig
Jullie gekozen methodiek staat niet duidleijk beschreven in het rapport, en in het assessment kwam naar voren dat jullie hier nog mee worstelden. RAG- en finetuningtechnieken worden door elkaar heen besproken en schept onduidelijkheid voor de lezer. 
De wel duidelijk gemaakte keuzes missen verantwoording. Zo is er een keuze gemaakt voor BLEU, maar lijkt deze niet echt onderbouwd. In het hoofdstuk komen vaak zinnen voor als (we gebruiken metrieken zoals SBERT). Het woordje zoals betekent dat het een voorbeeld is en niet direct toe te passen hoeft te zijn. Dit schept onduidelijkheid.
Later wordt er ook iets genoemd over het genereren van een dataset middels generative AI, wat vervolgens de ground-truth moet zijn voor jullie metingen. Hier lijkt niet goed over nagedacht te zijn en verantwoording ontbreekt. Wees heel voorzichtig met het genereren van synthetische data en dit vervolgens gebruiken als waarheid. Het is synthetisch, dus niet echt. Dit stelt geen directe representatie van de werkelijkheid voor. Mochten jullie dit alsnog willen doen, wees heel duidelijk over hoe en waarom.
B3: Je ontwikkelt een nieuw of voorgetraind AI-model volgens een iteratief en systematisch proces.
Je dient een systematische aanpak te hanteren, waarin je duidelijk vermeldt hoe je je model
traint of fine-tunet, valideert, optimaliseert, test en de resultaten communiceert. Voorlopige
resultaten zijn op dit punt verplicht.

Criterion Feedback: Hier is nog werk nodig
Over de toepassing van de gekozen methode is weinig over terug te vinden. Het vaststellen van je methodiek en de uitvoer hiervan zijn echt twee verschillende dingen. Het duidelijk beschrijven van de toepassing van je methodiek maakt jullie onderzoek reproduceerbaar. Dit is nu nog niet het geval. Werk hier de komende paar weken nog aan.

C2: Je evalueert en beoordeelt de kwaliteit van een AI-model aan de hand van kwaliteitscriteria die in het vakgebied erkend worden zoals robustness, performance, scalability, explainability, model complexity en resource demand.
Voor het evalueren van de kwaliteit van het AI-oplossing dien je ook andere door het veld
erkende kwaliteitsmaten zoals robustness, scalability, explainability, model complexity en resource
demand (en wellicht fairness metrics) in acht te nemen en te verantwoorden. Dit is op een technisch
correcte wijze uitgevoerd en kan aangetoond worden in de review.

Criterion Feedback: Hier is nog werk nodig
Goed om te zien dat jullie duurzaamheid meenemen als belangrijk punt als het gaat om het toepassen van Generatieve AI. Verder zijn er geen technische resultaten te vinden, waarschijnlijk omdat het fine-tuning niet helemaal gelukt bleek te zijn aan het eind van de iteratie. Het beschikken over voorlopige resultaten was een vereiste voor de technische review. Ik heb er echte volle vertrouwen in dat jullie straks mooie resultaten hebben om te bespreken. 