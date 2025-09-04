#  Projet IA : Classification du risque de diabète

##  Énoncé du projet
Afin d’améliorer la détection du diabète, deux laboratoires ont mené des recherches avec des bases de données médicales.

### Objectifs :
1. Décrire la démarche :
   - Prétraitement des données  
   - Approche de modélisation choisie  
   - Justification du choix des architectures de réseaux de neurones  

2. Implémenter des modèles capables de :
   - Classer les patients en **3 groupes** (selon le 1er dataset)  
     - 0 = pas de diabète  
     - 1 = pré-diabète  
     - 2 = diabète confirmé  
   - Classer les patients en **2 groupes** (selon le 2e dataset)  

3. Évaluer les performances, optimiser, et proposer des pistes d’amélioration.  

---

##  Données utilisées
Les données proviennent de deux laboratoires avec des variables médicales et socio-démographiques.

### Variables principales :
- **HighBP** : Hypertension (1 = oui, 0 = non)  
- **HighChol** : Cholestérol élevé (1 = oui, 0 = non)  
- **CholCheck** : Cholestérol vérifié (1 = oui, 0 = non)  
- **BMI** : Indice de masse corporelle (valeur numérique)  
- **Smoker** : Fumeur (1 = oui, 0 = non)  
- **Stroke** : AVC (1 = oui, 0 = non)  
- **HeartDiseaseorAttack** : Maladie cardiaque / infarctus (1 = oui, 0 = non)  
- **PhysActivity** : Activité physique (1 = oui, 0 = non)  
- **Fruits** : Consommation régulière de fruits (1 = oui, 0 = non)  
- **AnyHealthcare** : Accès à un système de santé (1 = oui, 0 = non)  
- **NoDocbcCost** : A renoncé aux soins pour cause de coût (1 = oui, 0 = non)  
- **GenHlth** : Santé perçue (1 = excellente, …, 5/6 = mauvaise)  
- **MentHlth** : Jours de mauvaise santé mentale (numérique)  
- **PhysHlth** : Jours de mauvaise santé physique (numérique)  
- **DiffWalk** : Difficulté à marcher (1 = oui, 0 = non)  
- **Sex** : 0 = femme, 1 = homme  
- **Education** : Niveau d’éducation (1 = pas d’école … 6 = universitaire)  
- **Age** : Tranche d’âge (1 = 18-24 … 13 = 80+)  
- **Income** : Revenu par classe (1 = très faible … 8 = très élevé)  

---

## ⚙ Méthodologie
1. **Prétraitement** :  
   - Nettoyage des données  
   - Standardisation des variables numériques  
   - Encodage des variables catégorielles  
   - Gestion des valeurs manquantes  

2. **Modélisation** :  
   - Réseaux de neurones (multi-class et binaire)  
   - Comparaison avec d’autres modèles (Random Forest, XGBoost, etc.)  

3. **Évaluation** :  
   - Précision, rappel, F1-score  
   - Matrice de confusion  
   - Optimisation des hyperparamètres  

4. **Améliorations possibles** :  
   - Feature engineering  
   - Réseaux de neurones plus profonds  
   - Régularisation et dropout  

---

##  Résultats attendus
- Modèles robustes pour la classification binaire et multi-classes.  
- Comparaison des performances.  
- Recommandations pour améliorer la détection du diabète.  

---

##  Équipe
- Étudiants : Angele Blandine FEUSSI NGUEMKAM  
- Cours : **Introduction à l'intelligence artificielle**  
- Collège La Cité – Automne 2025  

---

##  Fichiers importants
- `ENONCE_PROJET.pdf` : Énoncé officiel du projet  
- `notebooks/` : Jupyter notebooks pour l’analyse  
- `data/` : Données utilisées (⚠️ anonymisées)  
- `results/` : Rapports et résultats  






