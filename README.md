# Prediction prix diamon

# 📊 Analyse Exploratoire des Données (Exploratory Data Analysis)

## 🎯 Objectif

- Mieux comprendre la structure et le contenu de notre jeu de données.\_
- Élaborer une première stratégie de modélisation.

---

## ✅ Checklist Initiale

### 🔹 Analyse de Forme

- **Variable cible :** `price`
- **Dimensions du jeu de données :** 53940 lignes × 10 colonnes
- **Types de variables :**

  - **Qualitatives :**
  - **Quantitatives :**
    - `object` :
    - `int64` :

- **Analyse des valeurs manquantes :**
  -
  -

---

### 🔹 Analyse de Fond

#### 🎯 Visualisation de la variable cible

-

#### 📌 Compréhension des variables

- **Variables continues :**
  -
- **Variables qualitatives :**
  - Principalement \*\* \*\*
  - Exemple notable : **Rhinovirus** semble très fréquent

---

### 🔍 Relations entre Variables et la Cible (`target`)

- **Target vs. T :**

- **Target vs. Âge :**

---

## 🧠 Remarques Générales

-

---

## 🔍 Analyse Plus Détaillée

### 🔄 Relations entre Variables

- **Tests sanguins vs. Tests sanguins :**

  - Certaines variables présentent une **forte corrélation** entre elles (> +0.9)  
    → À surveiller, car cela peut indiquer de la redondance dans les données

- **Tests sanguins vs. Âge :**

  - **Corrélation très faible** entre l’âge (quantiles) et les taux sanguins

- **Tests viraux vs. Tests viraux :**

  - Le **test rapide pour la grippe (Influenza Rapid Test)** semble peu fiable  
    → À envisager de l’exclure lors des prochaines étapes

- **Maladie vs. Tests sanguins :**

  - Les patients atteints de maladies présentent des **profils sanguins différents** des non-malades  
    → Différences à approfondir

- **Hospitalisation vs. Maladie :**

  - Relation à analyser davantage (non encore détaillée)

- **Hospitalisation vs. Taux sanguins :**
  - Relation à explorer (non encore détaillée)

---

### 📉 Analyse des Valeurs Manquantes (NaN)

| Groupe de variables | Nombre d’observations disponibles | Pourcentage NaN (%)  |
| ------------------- | --------------------------------- | -------------------- |
| **Viral**           | ~1350                             | ~76 %                |
| **Sanguin**         | ~600                              | ~89 %                |
| **Les deux**        | ~90                               | Très faible présence |

---

### 🧪 Hypothèses Nulle (H₀)

1. Les individus atteints du **COVID-19** ont des taux de **Leucocytes** et de **Plaquettes** **significativement différents** des non-infectés.
2. Les individus atteints **d’une quelconque maladie** présentent des **taux sanguins significativement différents** de ceux en bonne santé.

> Ces hypothèses devront être testées statistiquement (ex. : test t de Student, ANOVA, etc.) dans les prochaines étapes.

---
