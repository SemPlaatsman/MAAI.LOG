# Persoonlijk Logboek - Master Applied AI
## Blok 1: Beeldverwerking - Competentie Evaluaties

### Projectreferenties
| Project | Beschrijving | Link |
|---------|-------------|------|
| Churn Prediction Pipeline | Afstudeerstage - Geautomatiseerde pipeline met 6 ML modellen | [Research Article (Preprint)](https://www.preprints.org/manuscript/202507.0712/v1) |
| TNO Speaker Recognition | CNN-gebaseerd speaker recognition model | [Portfolio Details](https://semplaatsman.nl/projects/who-has-been-calling) |

---

## A. CONTEXTUALISEREN EN ONTWERPEN

### A1: Onderzoek en herformulering van vraagstukken

**S - Situatie:**
Tijdens mijn afstudeerstage heb ik deze competentie ontwikkeld door vanuit de vraag "wat kunnen we met onze huidige data doen" een concrete oplossing voor te stellen: een geautomatiseerde churn prediction pipeline. Dit proces vereiste het herformuleren van een vaag vraagstuk naar een technisch haalbare oplossing, waarbij ik de belangen van verschillende stakeholders (CTO, CEO, eindgebruikers) heb afgewogen. De stage resulteerde in een pipeline met 6 verschillende machine learning modellen, 3 temporal validation strategies, en 3 resampling techniques. Door het proces heen heb ik regelmatig meetings gehad met management om bevindingen en experimenten te koppelen aan business concerns en praktische relevantie te behouden. Mijn sterke punten liggen in oplossingsgericht, praktisch, en pragmatisch denken. Mijn grootste uitdaging binnen deze competentie is het hele project vanaf het begin duidelijker in kaart brengen, zodat fouten en onduidelijkheden eerder in het proces voorkomen kunnen worden.

**T - Taak:**
Voor het leeftijdscontrole project van blok 1 ga ik helpen om het project duidelijk in kaart te brengen.

**A - Actie:**
De volgende deliverables helpen met het in kaart brengen van het project:
* Empathy maps
* Value proposition
* Juridische en Ethische aspecten
* Gebruikersinterviews plannen
* Haalbaarheid onderzoeken

### A2: Requirements opstellen

**S - Situatie:**
Voor het churn prediction project heb ik juridische, organisatorische en technische vereisten gedocumenteerd in mijn research article. Tijdens mijn bachelor heb ik uitgebreide ervaring opgedaan met functionele en technische eisen via MoSCoW-analyses in verschillende projecten. Daarnaast heb ik een ethisch en juridisch verslag geschreven over Deep Fake & AI technologieën, wat mij een basis heeft gegeven in de ethische en juridische aspecten van AI. Mijn sterke punten liggen in het systematisch documenteren van technische en organisatorische requirements. Het gebied waar ik minder ervaring heb is de ethische kant van requirements opstelling.

**T - Taak:**
Requirements opstellen voor het leeftijdscontrole project, inclusief o.a. juridische (AVG, AI Act), ethische (bias), organisatorische (workflow), functionele en technische vereisten.

**A - Actie:**
De volgende deliverables zijn onderdeel van het in opstellen van requirements:
- AVG-wetgeving en AI Act analyseren voor juridische vereisten
- Ethische requirements definiëren via filosofie & ethiek lessen
- Functionele requirements afleiden uit gebruikersinterviews
- Technische requirements bepalen
- Requirements documenteren

### A3: AI-specifieke ontwerprichtlijnen

**S - Situatie:**
Bij mijn afstudeerproject heb ik het CRISP-DM framework toegepast om de hele lifecycle van het project te bewaken en te structureren. Aspecten zoals veiligheid, privacy en error handling heb ik in verschillende projecten aangepakt als vanzelfsprekende onderdelen van de ontwikkeling. Echter, specifieke richtlijnen zoals vertrouwen, feedback mechanismen en controlemechanismen heb ik nog niet expliciet geïmplementeerd of gedocumenteerd.

**T - Taak:**
AI-specifieke ontwerprichtlijnen toepassen voor vertrouwen, veiligheid, privacy, elegante foutafhandeling, feedback en controlemechanismen in het leeftijdscontrole project.

**A - Actie:**
- AI design patterns bestuderen (via bijv. Google's People + AI Guidebook)
- Happy en Error flows ontwerpen
- Privacy-by-design principes toepassen tijdens ontwerp
- Edge cases identificeren

### A4: Geschiktheid van AI onderbouwen

**S - Situatie:**
Deze afweging heb ik gemaakt bij het voorstellen van mijn afstudeerproject, waar ik samen met de CEO en CTO onderzoek deed naar haalbaarheid en een MVP opzette. Het proces omvatte technische analyses en haalbaarheidsonderzoek, maar lag voornamelijk gefocust op technische aspecten. De maatschappelijke en ethische overwegingen bij het inzetten van AI waren niet expliciet gedocumenteerd of uitgebreid besproken. Dit is een competentie waar ik graag een meer holistische benadering wil ontwikkelen die technische, maatschappelijke en ethische aspecten gelijkwaardig behandelt.

**T - Taak:**
De geschiktheid/haalbaarheeid van AI voor leeftijdscontrole onderbouwen vanuit technische en ethische aspecten, en de gewenste mate van automatisering bepalen.

**A - Actie:**
- Human-in-the-loop niveau bepalen
- Maatschappelijke/Ethische impact analyseren via filosofie & ethiek lessen
- Technische haalbaarheid onderzoeken
- Alternatieve oplossingen vergelijken
- Stakeholder feedback verzamelen over automatiseringsvoorkeuren

---

## B. ONTWIKKELEN EN MODELLEREN

### B1: Dataset exploratie en preparatie

**S - Situatie:**
Ik heb bij verschillende projecten datasets van scratch geanalyseerd, getransformeerd en ingezet voor machine learning modellen. Dit varieert van het preprocessen van volledig nieuwe datasets tot het fine-tunen van bestaande modellen op gespecialiseerde datasets, zoals bij het TNO Speaker Recognition project. Voor dat project ontwikkelden we een CNN-architectuur waarbij we een eigen dataset moesten prepareren en optimaliseren voor speaker recognition doeleinden. Mijn ervaring bestaat uit zowel traditionele machine learning datasets als meer complexe auditory en visual data preprocessing. Ik ben comfortabel met de technische aspecten van data preparation/preprocessing, maar wil graag meer diepgang ontwikkelen in o.a. de implicaties van data bias.

**T - Taak:**
Geschikte datasets voor leeftijdsschatting verkennen en prepareren, rekening houdend met technische en ethische randvoorwaarden zoals bias en representativiteit/diversiteit.

**A - Actie:**
- Face age estimation datasets evalueren (UTKFace, IMDB-WIKI, Fair Face)
- Data bias analyse uitvoeren op verschillende demografische groepen
- Ethische overwegingen documenteren voor dataset gebruik
- Data augmentation technieken verkennen/toepassen
- Verkennende data-analyse (Exploratory Data Analysis) uitvoeren en documenteren
- Dataset preprocessing pipeline implementeren in repository

### B2: Architectuur en AI-technieken selecteren

**S - Situatie:**
Deze competentie heb ik in verschillende contexten toegepast. Voor machine learning is mijn afstudeerproject een voorbeeld waar ik 6 verschillende algoritmes vergeleek en selecteerde. Voor deep learning ontwikkelden we een CNN-architectuur voor het TNO Speaker Recognition project. Daarnaast heb ik ervaring met computer vision via een movie poster classification model en natural language processing via een RAG-pipeline chatbot voor Inholland studiehandleidingen. Het gebied waar ik nog geen ervaring mee heb is kennisrepresentatie. Mijn sterke punt ligt in het praktisch vergelijken en implementeren van verschillende technieken.

**T - Taak:**
Geschikte architectuur selecteren voor leeftijdsschatting gebaseerd op computer vision technieken, requirements, en beschikbare data.

**A - Actie:**
- Veelgebruikte architecturen vergelijken (ResNet-50, VGG16, MiVOLO)
- Pre-trained modellen evalueren voor face age estimation
- Model performance evalueren
- Architectuurkeuzes documenteren (inclusief onderbouwing)
- (Prototype) Implementatie starten in teamrepository

### B3: Systematische modelontwikkeling

**S - Situatie:**
Tijdens mijn afstudeerproject heb ik het CRISP-DM framework gebruikt als leidraad voor systematische en iteratieve modelontwikkeling. Dit proces bevatte regelmatige stakeholder feedback momenten en aanpassingen gebaseerd op business requirements en technische bevindingen. De structuur was cruciaal omdat het een significant project was met verschillende combinaties van modellen, validatiestrategieën en resampling technieken die allemaal getest moesten worden om de beste configuratie per bedrijf/uitgever te vinden. Ik ben sterk in het volgen van gestructureerde methodologieën en het documenteren van het ontwikkelproces.

**T - Taak:**
Een iteratief en systematisch proces volgen voor het ontwikkelen van het leeftijdsschatting model, met continue evaluatie en verbetering.

**A - Actie:**
- CRISP-DM framework toepassen tijdens het leeftijdscontrole project
- Model training pipeline opzetten met versioning
- Validation strategies implementeren (cross-validation, holdout)

---

## C. EVALUEREN EN MONITOREN

### C1: Maatschappelijke impact evalueren

**S - Situatie:**
Dit is een competentie waar ik nog weinig concrete ervaring mee heb in AI-projecten. Het dichtstbijzijnde voorbeeld was tijdens het TNO Speaker Recognition project, waar ik opmerkte dat ons model stiltes tussen zinnen koppelde aan specifieke sprekers, waardoor gesprekken met veel stiltes altijd aan dezelfde spreker werden toegewezen. We behandelden dit voornamelijk als een technische kwestie en zijn niet diepgaand ingegaan op de bredere implicaties voor individu en maatschappij. Dit is een gebied waar ik graag meer systematische ervaring in wil ontwikkelen, vooral het proces van het identificeren en bespreken van mogelijke ongewenste consequenties van AI-oplossingen.

**T - Taak:**
De maatschappelijke impact van leeftijdscontrole AI evalueren, ongewenste consequenties identificeren, en hierover in gesprek gaan met vakgenoten.

**A - Actie:**
- Impact assessment uitvoeren tijdens filosofie & ethiek lessen
- Scenario's analyseren voor verkeerde classificaties (Error flow)
- Bias testing uitvoeren op verschillende demografische groepen
- Bevindingen presenteren tijdens mini-symposium

### C2: Kwaliteitscriteria toepassen

**S - Situatie:**
Ik heb ervaring met standaard evaluatiemetrieken zoals accuracy, precision, en recall in praktisch elk AI-project. Mijn afstudeerproject ging verder door ook resource demand, explainability, en scalability te analyseren als onderdeel van het totaalplaatje. Echter, aspecten zoals robustness en model complexity zijn weinig tot niet geanalyseerd in mijn eerdere projecten. Over deze kwaliteitscriteria wil ik graag meer leren en toepassen, vooral in de context van production AI-systems waar deze factoren belangrijk kunnen zijn.

**T - Taak:**
Het leeftijdsschatting model evalueren aan de hand van erkende kwaliteitscriteria zoals robustness, performance, scalability, explainability, model complexity, en resource demand.

**A - Actie:**
- Set van evaluatiemetrics samenstelleen
- Robustness testing uitvoeren
- Model explainability technieken toepassen (e.g. SHAP, indien relevant)
- Performance benchmarks opstellen
- Resource demand meten (inference tijd, memory gebruik)

### C3: Prototype testing met stakeholders

**S - Situatie:**
Deze competentie heb ik meerdere keren toegepast tijdens mijn afstudeerproject, waar we iteratief de churn prediction modellen op ongeziene data hebben getest en de resultaten analyseerden met stakeholders. Het proces omvatte het presenteren van bevindingen aan CTO en CEO, het toepassen van hun feedback, en het aanpassen van de aanpak gebaseerd op business requirements. Deze cyclus van testen, evalueren, en aanpassen was belangrijk voor het ontwikkelen van een praktisch bruikbare oplossing. Ik ben sterk in het vertalen van technische resultaten naar business impact en het faciliteren van feedback loops met stakeholders.

**T - Taak:**
Samen met stakeholders het prototype voor het leeftijdscontrole project analyseren met behulp van prototypes en inzichten.feedback meenemen in het proces.

**A - Actie:**
- Prototype ontwikkelen
- Demo opstelling creëren voor stakeholder feedback
- Test scenario's opstellen voor verschillende gebruikssituaties
- Feedback systematisch verzamelen en documenteren
- Verbeteringen implementeren in repository

---

## D. ZELFSTURING

### D1: Feedback verzamelen en verwerken

**S - Situatie:**
Dit is een competentie waar ik nog geen concrete voorbeelden van heb binnen specifiek AI-projecten. Hoewel ik wel ervaring heb met het ontvangen en verwerken van feedback in algemene projectcontext (zoals tijdens mijn afstudeerstage), heb ik dit nog niet systematisch gedocumenteerd of gestructureerd toegepast in de context van mijn eigen ontwikkeling binnen AI. Dit is een belangrijke competentie die ik graag wil ontwikkelen door een meer bewuste en gedocumenteerde aanpak van feedbackverwerking in mijn leerproces.

**T - Taak:**
Actief feedback verzamelen over eigen kennis, vaardigheden, en ontwikkeling, en deze feedback gebruiken om werk te verbeteren door blok 1 heen.

**A - Actie:**
- Persoonlijk logboek bijhouden met feedbackverwerking
- STARRT reflecties maken voor voortgangsgesprek
- Peer feedback vragen tijdens teamwerk
- Feedback van docenten documenteren en actiepunten formuleren

### D2: Onderzoek opzetten en rapporteren

**S - Situatie:**
Deze competentie heb ik sterk ontwikkeld tijdens mijn afstudeerstage door het schrijven van een research article over mijn churn prediction systeem. Het onderzoek volgde academische standaarden en ik communiceerde de resultaten zowel schriftelijk (via het artikel) als mondeling met mijn CTO en stagebegeleider. Het artikel is momenteel in preprint fase, wat aantoont dat de kwaliteit op academisch niveau is. Ik ben comfortabel met het opzetten van onderzoek, het volgen van methodologieën, en het rapporteren volgens academische standaarden. Mijn sterke punt ligt in het maken van de vertaalslag tussen technische bevindingen en praktische implicaties.

**T - Taak:**
Onderzoek opzetten, uitvoeren, en rapporteren voor artikel binnen het leeftijdscontrole project volgens academische standaarden.

**A - Actie:**
- Onderzoeksvraag formuleren voor artikel
- Plan van aanpak ontwikkelen tijdens mini-symposium workshops
- IEEE template gebruiken voor academische structuur
- Literatuuronderzoek uitvoeren voor verwante werkstukken
- Methodologie documenteren volgens wetenschappelijke standaarden
- Artikel presenteren tijdens mini-symposium voor peer feedback

### D3: Robuuste onderzoeksmethoden kiezen

**S - Situatie:**
Dit heb ik toegepast tijdens mijn afstudeerstage via het gebruik van het CRISP-DM framework, uitgebreid literatuuronderzoek, en het naleven van MDPI publicatiestandaarden voor mijn research article. Het onderzoek bevatte systematische vergelijking van verschillende machine learning technieken, temporal validation strategies, en evaluatiemethodologieën. Ik heb ervaring met het selecteren van passende methodologieën gebaseerd op onderzoeksvragen en het onderbouwen van methodologische keuzes met literatuur. Mijn aanpak is systematisch en evidence-based, wat heeft geresulteerd in een bijdrage aan de kennis in het vakgebied van churn prediction voor subscription-based businesses.

**T - Taak:**
Robuuste en valide onderzoeksmethoden kiezen voor het beeldverwerking project en bijdragen aan ontwikkeling van nieuwe kennis in AI-vakgebied.

**A - Actie:**
- CRISP-DM methodologie toepassen op computer vision project
- Statistische significance testing implementeren
- Literatuuronderzoek uitvoeren naar moderne methodiek
- Methodologische keuzes onderbouwen met academische bronnen
