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

- **R version** : 4.5.0  
- **Packages essentiels** :  
  - `refund 0.1-37` : analyse en composantes principales fonctionnelles (FPCA).  
  - `ranger 0.17.0` : forêts aléatoires rapides avec estimation d’importance des variables.  
  - `caret 7.0-1` : sélection de variables via RFE et validation croisée.  
  - `ale 0.5.1` : visualisation et interprétation des effets ALE (Accumulated Local Effects).  


# Objectif

L’objectif global est de **comprendre les facteurs influençant la propagation de FocTR4**, de **sélectionner les variables les plus pertinentes** pour la modélisation, et de fournir des **interprétations robustes des effets prédictifs** dans un contexte spatio-temporel.
