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

  - **Qualitatives :** 6
  - **Quantitatives :** 4
    - `object` : 3
    - `int64` : 1

- ## **Analyse des valeurs manquantes :**
  - Pas de valeur manquante

---

### 🔹 Analyse de Fond

#### 🎯 Visualisation de la variable cible

- Prix du diamon (variable)

#### 📌 Compréhension des variables

- ## **Variables continues :**
  - La majorité ne suit pas une distribution normale
  - Depth suit une distribution normale
- **Variables qualitatives :**

  - cut : 'Ideal', 'Premium', 'Good', 'Very Good' , 'Fair'
    - Ideal : Excellente coupe, maximise la brillance
    - Premium : Presque aussi brillante qu’Ideal
    - Very Good : Très bon éclat, mais légèrement moins bien taillé
    - Good : Bon équilibre entre qualité et prix, éclat correct
    - Fair : Moins de brillance, coupe plus profonde ou peu équilibrée
  - color : 'E', 'I', 'J', 'H' , 'F', 'G', 'D'
    - D : Incolore (qualité maximale)
    - E, F : Presque incolore
    - G, H : Légèrement teinté (presque invisible à l’œil nu)
    - I, J : Teinte plus visible mais encore acceptable
  - clarity : 'SI2' ,'SI1' ,'VS1' ,'VS2' ,'VVS2' ,'VVS1' ,'I1' ,'IF'
    - FL/IF (Flawless/Internally Flawless) : Aucune inclusion visible
    - VVS1, VVS2 : Très très petites inclusions (difficilement visibles même à la loupe)
    - VS1, VS2 : Très petites inclusions (légèrement visibles à la loupe)
    - SI1, SI2 : Inclusions visibles à la loupe, parfois à l’œil nu
    - I1 : Inclusions visibles à l’œil nu (qualité inférieure)

---

### 🔍 Relations entre Variables et la Cible (`target`)

- **Target vs. T :**

- **Target vs. Âge :**

---

## 🧠 Remarques Générales

- ***

## 🔍 Analyse Plus Détaillée

### 🔄 Relations entre Variables
