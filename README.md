# Résumé des travaux

Ce projet analyse la dynamique spatio-temporelle de la maladie FocTR4 dans une plantation de bananiers au Mozambique.  
L’approche combine :  

- Une **analyse de données fonctionnelles** pour étudier l’évolution temporelle des contaminations.  
- Une **sélection de variables** via la procédure **RFE** (Recursive Feature Elimination) pour identifier les facteurs les plus importants.  
- Une **interprétation des modèles** à l’aide des effets **ALE (Accumulated Local Effects)** appliqués à des forêts aléatoires.  
- La mise en place d’une **procédure de validation sur les prédictions** pour évaluer la robustesse des modèles prédictifs.  

# Structures des fichiers et des données

Le schéma ci-dessous illustre la structure des fichiers et des données utilisées dans l’analyse :  

<img width="880" height="542" alt="schema" src="https://github.com/user-attachments/assets/2cce340a-d118-4a9f-99fd-bcbc2d087185" />

# Version de R et packages principaux

- **R version** : indiquer la version utilisée (ex. `R 4.3.1`)  
- **Packages essentiels** :  
  - `refund` : pour l’analyse en composantes principales fonctionnelles (FPCA).  
  - `ranger` : forêts aléatoires rapides avec estimation d’importance de variables.  
  - `caret` : pour la sélection de variables via RFE et la validation croisée.  


# Objectif

L’objectif global est de **comprendre les facteurs influençant la propagation de FocTR4**, de **sélectionner les variables les plus pertinentes** pour la modélisation, et de fournir des **interprétations robustes des effets prédictifs** dans un contexte spatio-temporel.
