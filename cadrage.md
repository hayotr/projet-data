# Cadrage du projet

## Sujet

Analyse des manifestations et mouvements de protestation recensés en France à partir des données GDELT.

## Objectif

Créer un dashboard permettant de visualiser :
- où les manifestations sont recensées en France ;
- à quelles périodes elles sont les plus nombreuses ;
- quels types de manifestations sont les plus présents ;
- quelles manifestations ont reçu le plus de couverture médiatique.

## Données

Les données utilisées proviennent de GDELT.

Les fichiers GDELT contiennent des événements recensés à partir de sources médiatiques.

Nous allons filtrer les événements localisés en France et appartenant à la catégorie PROTEST.

Les données seront récupérées automatiquement avec Python puis nettoyées avec Pandas.

## Répartition du travail

### Rani HAYOT

- création de l'arborescence du projet ;
- mise en place de Git et de l'environnement Python ;
- configuration générale du projet ;
- récupération d'une partie des données ;
- création de certains graphiques ;
- tests et vérification de la qualité du code.

### Alexis GUINLE

- documentation du projet et README ;
- récupération et étude des données ;
- nettoyage d'une partie des données ;
- création de certains composants du dashboard ;
- création de certains graphiques ;
- tests et vérification de la qualité du code.

## Organisation Git

Le projet sera réalisé progressivement avec des commits réguliers.

Chaque modification importante devra correspondre à un commit clair.

L'objectif est que Rani HAYOT et Alexis GUINLES aient une contribution équilibrée sur le dépôt Git.

## Étapes prévues

1. Création de l'arborescence
2. Mise en place de l'environnement Python
3. Récupération des données GDELT
4. Nettoyage des données avec Pandas
5. Stockage des données dans SQLite
6. Création du dashboard avec Dash
7. Création de la carte
8. Création des graphiques
9. Ajout des filtres et interactions
10. Tests et qualité du code
11. Finalisation du README
12. Analyse des résultats
13. Vidéo de démonstration