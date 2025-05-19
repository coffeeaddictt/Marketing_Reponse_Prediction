# Marketing_Reponse_Prediction (Mini-Projet 2)

## Description

Ce dépôt contient le Mini-Projet 2 réalisé dans le cadre du cours de Machine Learning. L'objectif est de développer et comparer plusieurs modèles de machine learning pour prédire la probabilité qu'un client réponde positivement à une campagne marketing.

## Utilisation

### Cloner le dépôt

bash
git clone https://github.com/<votre-utilisateur>/mini-projet-2-marketing.git
cd mini-projet-2-marketing

### Lancer le notebook Jupyter

bash
jupyter notebook notebooks/MiniProjet_{2}_<OUARAZ Sanaa:Asmaa>.ipynb
### Suivre les cellules pour :

- Charger et explorer les données  
- Prétraiter et ingérer les variables  
- Entraîner et valider les modèles :
  - Régression logistique  
  - Arbres de décision  
  - Forêts aléatoires  
  - Gradient Boosting  
- Évaluer les performances sur le jeu de test :
  - AUC  
  - Précision  
  - Rappel

### Résultats principaux

- **Meilleur modèle : Gradient Boosting** (AUC = 0,82)  
- **Forêt aléatoire** : AUC = 0,79  
- Détails et visualisations disponibles dans le notebook et dans `outputs/reports`
