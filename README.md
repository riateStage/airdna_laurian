# Mise en oeuvre d'une chaîne de traitement de données AirDNA : Étudier l'activité de la plateforme Airbnb dans 3 communes franciliennes. 

* Louis Laurian, février-juillet 2021
* Direction de stage : Marianne Guérois (UMR Géographie-Cités, UMS RIATE), Malika Madelin (UMR PRODIG)
* Encadrement : Ronan Ysebaert (UMS RIATE)

## Objet du stage

Ce rapport de stage s’inscrit dans le cadre du projet de l’ANR WIsDHoM (coord. Renaud Le Goix), et a été effectué au sein de l’UMS2414 RIATE
 du 15/02/2021 au 30/07/2021. L’objectif est d’analyser les inégalités liées aux marché du logement via l’angle des locations saisonnières, 
et plus particulièrement Airbnb, dans des communes situées en espace périurbain des grandes métropoles. Cet angle a été abordé car 
il s’agit d’un phénomène récent, qui a pris de l’ampleur au cours des années 2010, à tel point que les politiques publiques ont émis
 des restrictions pour réguler le phénomène. En effet, un des processus accentuant la crise du logement au sein des grandes métropoles 
est la reconversion d’un logement vers le locatif à court terme, réduisant le parc de résidences principales d’une ville et augmentant les 
prix du logement.

Ce travail a pour vocation de construire un socle méthodologique afin dans un premier temps d’étudier l’activité d’Airbnb dans une communes 
francilienne, en l’occurence Issy-les-Moulineaux. Plusieurs pistes seront abordées, à savoir la dynamique du marché en terme de fréquentation
 et de revenus engendrés, ainsi que l’évolution temporelle du développement de la location saisonnières dans cette commune, pour finir sur une 
analyse infra-communale de la répartition des logements. Dans un second temps, ce travail a pour vocation d’être reproductible, et extensible
 à d’autres terrain d’études, afin de s’inscrire dans le champ de la recherche reproductible.

Pour cela, nous utilisons une base de données encore peu utilisée à ses fins, AirDNA. Le premier objectif est de produire une chaîne de traitement 
visant à consolider les tableaux de données fournis par cette entreprise, avant d’effectuer des traitements statistiques et spatiaux.
 Le travail a été entièrement mené à l’aide du logiciel libre R, permettant de diffuser les résultats en assurant une transparence 
de la méthode ainsi qu’une réplicabilité du code, répondant ainsi à des standards élevés de reproductibilité.


## Mémoire accessible [ici](https://github.com/riateStage/airdna_laurian/blob/main/Memoire/memoire_laurian.pdf)

## Site Web accessible [ici](https://riatestage.github.io/airdna_laurian/)

Ce site Web restitue les étapes de préparation des données (sélection et création de variables, traitement des données manquantes), puis présente les résultats
principaux (synthèse communale et comparaison inter-communale) issus de ce stage. Les traitements commentés (RMarkdown) sont réalisés avec le langage R 
et sont en ce sens reproductibles à partir du moment où l'on dispose de l'autorisation d'accéder aux données AirDNA (accès limité négocié dans le cadre de l'ANR WIsDHoM). 
