# Visualisation Géographique avec Python

Ce projet permet de créer des visualisations géographiques interactives en utilisant Python. Il inclut des exemples de visualisation de données géographiques avec différentes bibliothèques comme Folium et Plotly.

## Prérequis

Avant de commencer, assurez-vous d'avoir Python installé sur votre machine. Vous pouvez télécharger Python depuis [python.org](https://www.python.org/downloads/).

## Installation

1. Clonez ce dépôt sur votre machine locale :
```bash
git clone https://github.com/EnzoTurpin/GeographicVisualiser.git
cd GeographicVisualiser
```

2. Installez les dépendances requises qui sont mises à l'étape 1 de [netflix_geo_visualization.ipynb](netflix_geo_visualization.ipynb):
```bash
pip install folium geopandas matplotlib plotly pandas
```

## Structure du Projet

- `geographic_visualization.ipynb` : Notebook principal contenant les exemples de visualisation
- `netflix_geo_visualization.ipynb` : Notebook spécifique pour la visualisation des données Netflix
- `archive/` : Dossier contenant le dataset utilisé pour le projet.

## Utilisation

1. Ouvrez Jupyter Notebook ou Jupyter Lab :
```bash
jupyter notebook
```

2. Ouvrez le fichier `geographic_visualization.ipynb`

3. Exécutez les cellules dans l'ordre pour voir les différentes visualisations :
   - Visualisation de base avec Folium
   - Visualisation avec clusters
   - Visualisation avec cercles proportionnels
   - Visualisation interactive avec Plotly

## Fonctionnalités

Le projet inclut plusieurs types de visualisations :

1. **Cartes interactives avec Folium**
   - Marqueurs personnalisés
   - Clusters de marqueurs
   - Cercles proportionnels

2. **Visualisations interactives avec Plotly**
   - Cartes
   - Graphiques interactifs

## Attention

```
Afin que le projet fonctionne correctement, véillez à ne pas sauter de cellule.
```

## Projet réalisé par : Dorian LE BLEIS et Enzo TURPIN.