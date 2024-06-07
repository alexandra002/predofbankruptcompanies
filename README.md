# Prédire la sortie d'une entreprise : probabilité et classification

Dans cette étude, notre objectif est de prédire la sortie d'une entreprise, c'est-à-dire si une entreprise va faire faillite ou se retirer du marché. Cette prédiction est cruciale pour diverses décisions commerciales, telles que le choix de fournisseurs, l'approbation de crédits par les banques, ou la location d'espaces de bureaux. Nous utilisons des données d'entreprises européennes sur la période 2005-2016 pour quelques industries manufacturières et de services.

Nous nous concentrons sur un échantillon représentatif d'entreprises en 2012 et analysons si elles sont restées en activité les années suivantes. Nous définissons la variable dépendante 'y' comme étant 1 si l'entreprise a cessé ses activités dans les 2 ans (jusqu'en 2014), et 0 sinon.

## Données

Notre ensemble de données, 'original_bisnode_data', couvre l'ensemble de la population des entreprises entre 2005 et 2016 pour certaines industries manufacturières et de services. Les grandes entreprises (plus de 100 millions d'euros de chiffre d'affaires annuel) sont exclues pour des raisons de protection des données. Nous nous concentrons sur les petites et moyennes entreprises (PME) avec un chiffre d'affaires annuel inférieur à 10 millions d'euros en 2012 et excluons les entreprises non opérationnelles avec des ventes inférieures à 1 000 euros. 

> Les données se trouvent dans un fichier zip en raison de son volume. 

## Analyse exploratoire

L'analyse exploratoire comprend la sélection, le nettoyage et la mise en forme des variables pour les modèles prédictifs. Nous traitons spécifiquement les variables financières qui ne devraient pas être négatives, telles que les stocks, les passifs courants et le capital souscrit.

## Modèles prédictifs

Notre première tâche est de construire un modèle pour prédire la probabilité de cessation d'activité d'une entreprise. Nous utilisons au moins trois classifieurs pour la classification et comparons les meilleurs classifieurs en termes de l'aire sous la courbe ROC (AUC).

## Auteurs

- Alexandra MILLOT
- Benjamin BAILLET



