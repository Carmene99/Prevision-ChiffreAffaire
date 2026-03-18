## Prévision du Chiffre d'Affaires à 3 ans (Modèle Prophet)

## Contexte du Projet

Réalisé dans le cadre d'un Stage de Fin d'Année (PFA), ce projet visait à fournir une visibilité stratégique à long terme pour l'entreprise. L'objectif était de transformer les données historiques de ventes en prévisions exploitables pour anticiper la croissance et optimiser la gestion des ressources sur un horizon de 36 mois.

## Approche Technique : Pourquoi Prophet ?

Pour mon projet, j'ai choisi la bibliothèque Prophet de Meta en raison de sa capacité à :

    Gérer automatiquement les saisonalités (annuelles, mensuelles, hebdomadaires).

    Prendre en compte les effets de vacances et les événements exceptionnels.

    Traiter les données manquantes et les valeurs aberrantes (outliers) sans dégrader la précision.

## Étapes de Réalisation

    Préparation des données (Data Prep) : Nettoyage des historiques et formatage spécifique requis par le modèle (colonnes ds pour les dates et y pour le chiffre d'affaires).

    Analyse de la Tendance : Identification des cycles de croissance et des périodes de forte activité.

    Entraînement du Modèle : Ajustement des hyperparamètres (changepoint_prior_scale) pour capturer les changements de tendance sans sur-apprentissage.

    Prédiction & Visualisation : Génération du "forecast" sur 3 ans avec intervalles de confiance.

## Résultats & Impact

    Fiabilité : Obtention d'un modèle robuste permettant de quantifier la croissance prévisionnelle.

    Visualisation des composants : Décomposition de la série temporelle pour isoler la tendance de fond des variations saisonnières.

    Aide à la décision : Présentation des résultats à la direction pour soutenir la planification budgétaire.
