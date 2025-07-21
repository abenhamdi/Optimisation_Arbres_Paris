# 🌳 Optimisation de la Plantation d’Arbres à Paris

Projet d'analyse de données géospatiales visant à optimiser l’implantation de nouveaux arbres dans la ville de Paris, en se basant sur des critères environnementaux, sociaux et urbains. Ce projet explore l’utilisation de données ouvertes et de techniques de data science pour améliorer la qualité de vie urbaine.

---

## 🎯 Objectifs

* Analyser les données existantes sur la végétation urbaine à Paris.
* Identifier les zones carencées en couverture végétale.
* Proposer des emplacements optimaux pour de futures plantations.
* Utiliser des critères comme la densité de population, l’îlot de chaleur urbain, ou la pollution pour guider les choix.

---

## 📦 Contenu du projet

```
Optimisation_Arbres_Paris/
│
├── arbres.ipynb                  # Notebook principal d’analyse et de visualisation
├── data/                         # Répertoire contenant les fichiers de données
│   ├── arbres.csv                # Données géolocalisées des arbres existants
│   └── autres_datasets.csv       # Données urbaines complémentaires (pollution, population...)
├── cartes/                       # Cartes générées (heatmaps, zones prioritaires)
└── README.md
```

---

## 🛠️ Technologies utilisées

* Python 3.x
* Jupyter Notebook
* `pandas`, `numpy` – traitement de données
* `matplotlib`, `seaborn` – visualisation
* `folium`, `geopandas` – cartographie interactive et géodonnées
* `scikit-learn` – clustering (ex : KMeans)
* `shapely` – géométrie spatiale

---

## 📊 Étapes principales

1. **Exploration des données**

   * Répartition des arbres actuels
   * Types d’essences plantées
   * Données de pollution / population par quartier

2. **Analyse spatiale**

   * Cartes de chaleur (heatmaps)
   * Croisement avec données INSEE / Airparif / Mairie de Paris

3. **Optimisation**

   * Détection des zones sous-végétalisées
   * Suggestions de lieux d’implantation (clustering / scoring)

4. **Visualisation**

   * Cartes interactives (`folium`)
   * Résultats illustrés par arrondissements

---

## 💡 Exemples d’utilisation

* Identifier les zones de Paris avec peu d’arbres par habitant.
* Prioriser les quartiers combinant forte densité + forte pollution.
* Générer des cartes interactives avec des propositions de plantation.

---

## 📁 Données sources

Les jeux de données utilisés proviennent :

* de [Data.gouv.fr](https://www.data.gouv.fr)
* de [l’Open Data de la Ville de Paris](https://opendata.paris.fr)

---

## 🔍 Pistes d’amélioration

* Intégration d’un modèle multicritères pondéré (ex : AHP)
* Calcul d’indicateurs de justice environnementale
* Prise en compte de la biodiversité ou de la canopée
* Déploiement sur une interface Web (Streamlit, Dash)

---

## 👤 Auteur

* **abenhamdi** – [@abenhamdi](https://github.com/abenhamdi)

