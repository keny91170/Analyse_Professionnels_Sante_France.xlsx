# Analyse_Professionnels_Sante_France.xlsx

Analyse des Effectifs de Santé en France (Dashboard Excel)

 Présentation du Projet

Ce projet consiste en la création d'un outil de Business Intelligence interactif analysant les effectifs de santé à partir des données réelles de la Data AMELI. L'objectif est de piloter les indicateurs de densité et de démographie médicale.

Méthodologie (Data Cleaning)

Le jeu de données initial présentait des doublons et des agrégats complexes. J'ai réalisé les étapes suivantes :

Traitement des agrégats : Exclusion du code géographique "999" (Total National) pour ne garder que le détail départemental.

Filtre de structure : Retrait des lignes "Ensemble" et "Tout âge" pour garantir l'intégrité des sommes globales.

Calculs KPI : Création de mesures pour l'âge moyen et la part de féminisation.

Aperçu du Dashboard

<img width="1917" height="972" alt="image" src="https://github.com/user-attachments/assets/93afc718-f545-4289-a214-0412dcf5beb4" />


 Fonctionnalités

Filtres dynamiques : Segments par Profession, Année et Département.

Visualisations : Pyramide des âges empilée, évolution temporelle de la mixité, et classement géographique.
