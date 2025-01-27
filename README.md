Dans le cadre d’un projet de fin de formation suivi lors d’un bootcamp Data Analyst, j’ai travaillé sur une étude de marché et d’opportunité visant à établir une stratégie de déploiement pour une nouvelle plateforme de livraison de la société Bolt. Les données disponibles provenaient principalement des transactions et commandes de Deliveroo, Uber Eats, et Just Eat, sur une période allant de janvier 2017 à juin 2020.  

L’objectif du projet était d’analyser les données disponibles pour :
1.	Explorer les données pour en comprendre la structure et détecter les anomalies ou tendances.
2.	Nettoyer et préparer les données pour les rendre utilisables dans Power BI.
3.	Identifier le profil type des clients des plateformes concurrentes.
4.	Élaborer une stratégie permettant à Bolt de se différencier et capter de nouvelles parts de marché.
5.	Visualiser les insights clés sous forme de tableaux de bord clairs et interactifs.

Pour atteindre ces objectifs, j’ai mené plusieurs étapes :
1.	Nettoyage et préparation des données (Python)
  o	J’ai procédé à une revue complète des données :
    •	Revue des différentes données présentes dans les fichiers.
    •	Transformation des colonnes (comme la création de plage horaire pour la commande, de catégorie et de sous catégories de cuisine, du jour de la semaine de la commande) pour faciliter l’analyse.
    •	Non prise en compte des données de Just Eat, jugées peu fiables vu le nombre de données manquantes ou erronées excepté pour l’analyse macro.
    •	Suppression des anomalies financières (montants aberrants tels que des commandes dépassant 900 euros ou des montants à zéro sans promotion) pour les analyses financières.
2.	Analyse des données (Power BI)
  o	Création d’une table de date qui permet de filtrer les données selon la hiérarchie de la date qui a été définie.
  o	Création de visualisations interactives pour explorer les tendances et comportements des clients.
  o	Mise en place de filtres dynamiques permettant aux utilisateurs d'explorer les données par sexe, région, plateforme, catégorie d’âge, etc.
  o	Identification du profil type des clients concurrents :
    •	Homme, appartenant à la génération Y/Z, consommant majoritairement des cuisines fast food.
  o	Proposition pour Bolt : se différencier en ciblant des segments de clients ayant un panier moyen plus élevé :
    •	Femmes, appartenant à la génération X, préférant la cuisine asiatique.
3.	Gestion des limites des données
  o	Reconnaissance des contraintes, telles que l’absence d’informations précises sur les clients et la marge réalisée par commande, pour ajuster l’analyse.

Grâce à mon travail :
•	J’ai fourni une analyse approfondie des profils clients des plateformes concurrentes.
•	Une stratégie différenciée a été proposée pour Bolt, en se concentrant sur des segments de marché ayant un panier moyen plus élevé.
•	La qualité et l’interactivité des tableaux de bord Power BI ont permis de visualiser clairement les insights, facilitant la prise de décision stratégique.
•	Ce projet démontre mes compétences en Python pour le nettoyage de données et en Power BI pour la visualisation et l’analyse, tout en mettant en avant ma capacité à travailler avec des données imparfaites.
