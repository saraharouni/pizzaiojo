# pizzaiojo

Ce nouveau projet consiste à réaliser une analyse de données pour Jo le Pizzaiojo.  
Nous avons à notre disposition un jeu de données qui représente les ventes effectuées en 2015. 

Lors de ma première analyse, j'ai remarqué que notre jeu de données présentés des informations sur des commandes passées sur tous les jours de la semaine.  
Or dans notre consigne, il est écrit que Jo ne travaille que du lundi au vendredi.  
C'est la raison pour laquelle je propose deux notebooks d'analyse, l'un contenant que les jours compris entre lundi et vendredi et l'autres avec l'ensemble des jours
de la semaine.  

## Qu'est-ce que la Data Analyse ?  

Cela consiste à explorer, transformer et analyser les données afin d'identifier les tendances et les schémas qui révèlent des informations exploitables pertinentes afin d'optimiser la prise de décision.  

## Les étapes de data analyse  

**La préparation des données**  

Le but de la préparation des données est la production d'informations exploitables grâce à l'analyse de données. Cela inclut le nettoyage et la consolidation des données brutes en données bien structurées, prêtes pour l'analyse.   

**Exploration des données**  

L'exploration des données, ou l'analyse exploratoire des données, consiste à inspecter et examiner un vaste ensemble de données à travers l'échantillonnage, l'analyse statistique, l'identification des schémas (ou patterns), le profilage visuel, et plus encore. Les méthodes ne sont pas nécessairement scientifiques ou concluantes ; elles servent plutôt à comprendre, ce qui mène à une transformation plus judicieuse des données.  

**Enrichissement des données**  

Cette opération consiste à enrichir et augmenter les données avec des entrées et des jeux de données supplémentaires pour fournir plus d'éléments à l'analyse. Cette étape du processus de data analytics est cruciale pour révéler de nouvelles informations exploitables, ou insights, en observant les données sous un autre angle.

**Reporting**  

Les résultats du processus de data analytics doivent être partagés efficacement afin de préserver les informations obtenues. Le reporting consiste à organiser ces informations et les résultats d'une façon claire et facile à comprendre.

# Librairie Pandas  

Pour réaliser cette analyse exploratoire, j'ai utilisé la librairie Pandas de Python.  
Elle nous permette de représenter les données avec le format souhaité (individus/variables), de manipuler différents types de données, et de lire les données provenant de différentes sources.  

Pandas utilise les objets data frame et des series.
* Le data frame est un objet Python permettant de représenter les données sous forme de tableau, où chaque colonne est explicitement nommée. Il reprend les mêmes paradigmes que l’array NumPy : chaque colonne peut naturellement être d’un type différent, mais une colonne ne peut contenir qu’un seul type ! Cette organisation simplifie l’accès aux variables, et permet de nombreuses manipulations de données plus ou moins complexes.  
* Une Series ne peut contenir qu’un seul type, alors qu’un data frame, qui est finalement une collection de Series, peut contenir des colonnes de types différents : une colonne d’entiers, une colonne de nombres décimaux, etc.






