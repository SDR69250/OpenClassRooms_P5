# OC Data Scientist - Projet 5 : Segmentez des clients d'un site e-commerce


## Contexte

Je suis consultant pour Olist, une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne.

Olist souhaite que fournir à ses équipes d'e-commerce une segmentation des clients utilisable au quotidien pour leurs campagnes de communication.
L'objectif est de différencier les utilisateurs selon leur comportement d'achat et leurs données personnelles.

Il s'agit de fournir une description actionnable de la segmentation et de sa logique, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

Pour cette mission, Olist fournit une base de données anonymisée comportant des informations sur l’historique de commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.


## Données

https://www.kaggle.com/olistbr/brazilian-ecommerce

## Missions

J'utiliserai des méthodes non supervisées pour regrouper des clients de profils similaires. Ces catégories pourront être utilisées par l’équipe Marketing pour mieux communiquer.

Orientations spécifiques :

- seuls 3 % des clients du fichier de données ont réalisé plusieurs commandes
- la segmentation différenciera les bons et les moins bons clients en termes de commandes et de satisfaction
- la segmentation couvrira l’ensemble des clients
- une recommandation de fréquence de mise à jour de la segmentation sera fournie pour un contrat de maintenance
- respecter la convention PEP8 pour le code
- Ces orientations mènent à explorer tout d'abord une segmentation RFM pour établir à tire de comparaison des segments de clients homogènes selon l'approche classique, avant de poursuivre avec des méthodes de clusterisation non supervisées.

Approche RFM :

- Récence (date de la dernière commande),
- Fréquence des commandes
- Montant (de la dernière commande ou sur une période donnée)


## Livrables

1. Un notebook de l'analyse exploratoire (non cleané, pour comprendre ma démarche)
-  DeRosa_Sebastien_1_notebook_exploration_062022.ipynb

2. Un notebook (ou code commenté au choix) d’essais des différentes approches de modélisation (non cleané)
-  DeRosa_Sebastien_2_notebook_essais_062022.ipynb

3. Un notebook de simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation.
- DeRosa_Sebastien_3_notebook_simulation_062022.ipynb

4. Documentation du projet
-  DeRosa_Sebastien_4_presentation_062022.pdf : support de présentation qui présente la démarche et les résultats de la modélisation
