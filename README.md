# Prédiction du Cancer du Sein - Wisconsin Dataset

## 1. Description
Application de Machine Learning pour prédire le diagnostic du cancer du sein (bénin ou malin) à partir de données médicales réelles du Wisconsin Breast Cancer Dataset.

## 2. Objectif
Comparer différentes techniques d'apprentissage automatique pour identifier le meilleur modèle de classification, avec suivi des expériences via MLflow.

## 3. Technologies Utilisées
- **Python 3**
- **Bibliothèques principales :**
  - Pandas, NumPy (manipulation de données)
  - Scikit-learn (modèles ML)
  - Matplotlib, Seaborn (visualisation)
  - MLflow (tracking des expériences)

## 4. Modèles Implémentés

### Apprentissage Supervisé
- Régression Logistique
- SVM (Support Vector Machine)
- Arbre de Décision
- Random Forest
- K-Nearest Neighbors (KNN)
- Réseau de Neurones (MLP)

### Apprentissage Non Supervisé
- K-Means
- DBSCAN
- PCA (Analyse en Composantes Principales)

## 5. Résultats

Les meilleures performances (AUC ROC) :

| Modèle | AUC ROC | Accuracy |
|--------|---------|----------|
| **Random Forest** | 0.9940 | 96.5% |
| **MLP (Neural Network)** | 0.9917 | 94.7% |
| **SVM** | 0.9914 | 96.5% |

## 6. Utilisation

1. **Installer les dépendances :**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn mlflow
```

2. **Exécuter le notebook :**
```bash
jupyter notebook Breast_Cancer_Wisconsin.ipynb
```

3. **Visualiser les résultats MLflow :**
```bash
mlflow ui
```

## 📂 Structure du Projet
```
├── Breast_Cancer_Wisconsin.ipynb  # Notebook principal
├── mlruns/                         # Expériences MLflow
└── README.md                       # Documentation
```

## ✅ Fonctionnalités
- ✓ Exploration des données (EDA)
- ✓ Prétraitement et normalisation
- ✓ Entraînement de multiples modèles
- ✓ Évaluation comparative
- ✓ Tracking MLflow
- ✓ Visualisations des performances

## 📝 Notes
Ce projet a été développé dans le cadre d'un cours de Machine Learning, mettant en pratique les concepts d'apprentissage supervisé, non supervisé et de réseaux de neurones.

---
**Dataset :** Wisconsin Breast Cancer Dataset (scikit-learn)