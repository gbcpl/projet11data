# Projet 11 — Produire une étude de marché avec Python

## Présentation du projet

Ce projet consiste à réaliser une étude de marché à partir de données internationales afin d'identifier des pays présentant un potentiel de développement commercial pour l'exportation de viande de volaille.

L'objectif est de croiser des indicateurs économiques, démographiques et alimentaires pour comparer les marchés potentiels et fournir des éléments d'aide à la décision.

## Objectifs

- Préparer et nettoyer les données nécessaires à l'étude de marché.
- Explorer les indicateurs de disponibilité et de consommation alimentaire.
- Étudier les différences entre pays à partir de plusieurs variables économiques et démographiques.
- Réduire la dimension des données pour faciliter leur interprétation.
- Regrouper les pays présentant des caractéristiques similaires grâce à des méthodes de clustering.
- Identifier des marchés potentiels pour orienter la stratégie d'exportation.

## Méthodologie

1. **Préparation des données** : exploration, nettoyage et sélection des variables pertinentes pour l'étude.
2. **Analyse exploratoire** : étude des indicateurs alimentaires et économiques afin de comprendre les différences entre pays.
3. **Analyse en composantes principales (ACP)** : réduction de la dimension des données pour faciliter l'analyse des relations entre variables et la représentation des pays.
4. **Classification ascendante hiérarchique (CAH)** : exploration des regroupements de pays selon leurs caractéristiques.
5. **Clustering avec K-means** : constitution de groupes de pays présentant des profils similaires.
6. **Interprétation des groupes** : comparaison des profils obtenus pour identifier les marchés susceptibles de présenter un intérêt commercial.

## Résultats clés

L'analyse combine des indicateurs alimentaires et économiques avec des méthodes de classification non supervisée.

L'ACP permet de synthétiser une partie de l'information contenue dans les variables, tandis que la CAH et K-means permettent d'explorer des groupes de pays aux caractéristiques similaires.

Les groupes obtenus constituent une base de comparaison pour étudier les marchés potentiels. Leur interprétation doit toutefois tenir compte des besoins d'importation, de la capacité économique, des contraintes réglementaires et des conditions d'accès aux marchés.

## Outils et technologies

- **Python** : préparation et analyse des données.
- **Jupyter Notebook** : réalisation et documentation des analyses.
- **Pandas** : manipulation et préparation des jeux de données.
- **NumPy** : calculs numériques.
- **Scikit-learn** : standardisation des variables, ACP et clustering K-means.
- **SciPy** : classification ascendante hiérarchique.
- **Matplotlib et Seaborn** : visualisation des résultats et comparaison des groupes.

## Livrables

- [Notebook 1 — Préparation, nettoyage et analyse exploratoire](./Capell_Gabriel_1_preparation_nettoyage_analyse_exploratoire_082026.ipynb)
- [Notebook 2 — Clustering et visualisations](./Capell_Gabriel_2_clustering_visualisations_082026.ipynb)
- [Notebook 3 — Clustering et visualisations](./Capell_Gabriel_3_clustering_visualisations_082026.ipynb)
- [Support de présentation](./Capell_Gabriel_4_presentation_082026.pptx)

## Compétences développées

- Préparation et nettoyage de données avec Python.
- Analyse exploratoire de données.
- Manipulation de données avec Pandas et NumPy.
- Réduction de dimension avec l'ACP.
- Classification ascendante hiérarchique.
- Clustering avec K-means.
- Visualisation et interprétation de groupes de pays.
- Analyse de marché et aide à la décision.

## Conclusion

Ce projet m'a permis de mettre en pratique une démarche d'analyse de marché fondée sur l'exploitation de données internationales et l'utilisation de méthodes statistiques et de clustering.

La combinaison de l'analyse exploratoire, de l'ACP et des méthodes de classification permet de comparer les profils des pays et de structurer une première sélection de marchés potentiels pour l'exportation de viande de volaille.

---

**Domaine :** Data Analytics et étude de marché  
**Outils principaux :** Python, Pandas, Scikit-learn, SciPy  
**Type de projet :** Analyse exploratoire, ACP et clustering  
**Thématique :** Étude de marchés internationaux pour l'exportation de viande de volaille  
**Formation :** Data Analyst  
**Dépôt GitHub :** [projet11data](https://github.com/gbcpl/projet11data)
