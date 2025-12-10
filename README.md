# Random-forest-for-Breast-Cancer

# Random Forest Project - Breast Cancer Wisconsin (Diagnostic)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TON_PSEUDO/TP-Random-Forest-Breast-Cancer/blob/main/Random_Forest_TP_BreastCancer_Completed.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/downloads/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.5.1-orange)](https://scikit-learn.org/)


Ce dépôt contient une **implémentation complète, propre et optimisée** du TP Random Forest sur le dataset **Breast Cancer Wisconsin (Diagnostic)** — le choix idéal pour un PC modeste ou Google Colab (569 observations seulement → exécution en < 1 minute).

## Objectifs réalisés (100 % conformes au sujet)

- Préprocessing complet (scaling, split stratifié)
- Random Forest + validation croisée 5-fold
- Hyperparameter tuning exhaustif avec `GridSearchCV`
- Visualisation d’un arbre de décision (`plot_tree`)
- Deux techniques d’amélioration :
  - **Feature Selection** basée sur l’importance
  - **SMOTE** pour gérer le léger déséquilibre
- Toutes les métriques de classification : Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix
- Notebook ultra-commenté + Rapport LaTeX complet

**Résultats obtenus** :  
**F1-score = 0.98+** | **ROC-AUC = 0.99+** → parmi les meilleurs possibles sur ce dataset !

## Fichiers du dépôt

| Fichier | Description |
|-------|-------------|
| `Random_Forest_TP_BreastCancer_Completed.ipynb` | Notebook Jupyter complet (exécutable en 1 clic sur Colab) |
| `rapport.tex` | Rapport LaTeX source (propre, avec sections, figures, références) |
| `rapport.pdf` | Rapport compilé (prêt à envoyer) |
| `requirements.txt` | Dépendances exactes |
| `figures/` | Toutes les visualisations générées |

## Lancer le projet en quelques cliques

Clique simplement sur le badge Colab en haut → tout s’exécute automatiquement :

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TON_PSEUDO/TP-Random-Forest-Breast-Cancer/blob/main/Random_Forest_TP_BreastCancer_Completed.ipynb)

Aucun téléchargement, aucune installation nécessaire !

