# Project 8: Conduct a study on access to drinking water using Tableau Desktop 2022.4
As a Data Analyst consultant on a mission for the NGO DWFA (Drinking Water For All); its ambition is to provide access to drinking water for everyone in the world.

## Objectives: 
Conduct a study on the global access to drinking water through data visualization using Tableau Desktop 2022.4
1. Analyse a client need to formulate analytical questions and select the indicators that seem most relevant to you.
2. Synthesize our requests via a document presenting the indicators you have chosen to visualize for each view and for each area of expertise.
3. Create a dashboard to identify countries that are experiencing difficulties accessing drinking water to target for funding. The dashboard will present a global view of access to drinking water in the world selecting indicators related to our 3 areas of expertise below:
- Creation of services for access to drinking water
- Modernization of existing water access services
- Consulting with administrations/governments on water access policies.
  
## Data source
- FAO data on population ("Population.csv" and "RegionCountry".csv), political insatbility 2000-2018 ("PoliticalStability.csv")
- WHO data on basic and safely managed drinking water services, 2000-2017 ("BasicAndSafelyManagedDrinkingWaterServices.csv") and mortality rate attributed to water in 2016 (MortalityRateAttributedToWater.csv)

## Data preparation
- Build data dictionary or metadata repository which is a centralized repository of information about all the datasets.
- Create blueprint for indicator definition and the type of graph required such as map, bar chart, stacked chart, scatter plot, group bar chart, line grapgh, and table.
- Design wireframes or mockups using Figma for the 3 dashboards pages: global, continental, and national
- Convert the 4 excel files to csv. file
  
## Data analysis
- Import the 5 csv. files on population, country, political stability, mortality rate, and basic water services into Jupyter Notebook using Python programming
<img width="1025" alt="aa" src="https://github.com/user-attachments/assets/fb979d44-86f0-4943-811c-b08948a88817" />

- Clean the data by checking for duplicates, missing values, and incoherences in datasets
<img width="970" alt="aaaa" src="https://github.com/user-attachments/assets/b99f5f5a-41ff-4556-9ae0-7d7a4559a179" />

- Merge
<img width="1283" alt="aaa" src="https://github.com/user-attachments/assets/b144b021-babc-44cd-ad78-49dc1718044a" />

- Export cleaned files to csv.file
- Import the csv. file into Tableau desktop to build connection and data visualisation.
- Plot the relevant graphs.

## Insights
- The continent with the highest percentage of deaths due to Water, Sanitation, and Hygiene (WASH) is Africa; with highest occurence in Chad
- Eastern Mediteterranean has the least percentage of population using safely managed drinking water services in rural area.
- Africa has the least perecentage of population using basic drinking water services in rural area.
- Yemen has the worst political instability in the world.
- Chad has approximately 46% of its population living in the rural area have access to basic drinking water services.

![Tableau Dashboard National](https://github.com/user-attachments/assets/b91eb980-a793-4abe-9943-71b7f47794ae)

![Tableau Dashboard Continental](https://github.com/user-attachments/assets/3934887c-5528-46c8-a005-9c94abc02883)

![Tableau Dashboard Global](https://github.com/user-attachments/assets/1aea9bb9-e21f-4823-b4e1-5b8231718a6c)


## Recommendations
-  Access to drinking water should be improved in Chad given that it has the highest WASH deaths on the continent of Africa.
-  The political instability is not too bad as compared to other African countries like South Sudan and Libya.
-  Feasility studies should be carried out to assess the existing water access services if there is need for modernisation and the level of insecurity.
-  Administrations/governments should be consulted on water access policies.

# Projet 8 (French) 
Vous êtes consultant Data Analyst en mission dans l’ONG DWFA (Drinking Water For All) ; elle a pour ambition de donner accès à l’eau potable à tout le monde.
DWFA présente 3 domaines d’expertises :

- Création de services d’accès à l’eau potable ;
- Modernisation de services d’accès à l’eau déjà existants ;
- Consulting auprès d’administrations/gouvernements à propos des politiques d’accès à l’eau.
- L’association a effectué une demande de financement auprès d’un bailleur de fonds en présentant ces 3 domaines d’expertise. 

Ces nouveaux financements, s’ils sont accordés par le bailleur, pourront permettre d’investir dans un des domaines d’expertise dans un pays qui n’est pas encore déterminé.

Dans ce cadre, vous êtes missionné pour réaliser un tableau de bord présentant une vue globale de l’accès à l’eau potable dans le monde. Celui-ci permettra de choisir le pays à cibler dès que le bailleur de fonds aura donné sa réponse sur le domaine d’expertise qu’il souhaite financer.
