# Analyse de Sentiments avec Machine Learning

##  Description
Ce projet implémente un pipeline complet de **classification de sentiments** en utilisant des techniques de **Traitement du Langage Naturel (NLP)** et de **Machine Learning**.

L’objectif est de transformer des données textuelles en variables numériques pertinentes afin de prédire automatiquement le sentiment associé (positif, négatif, neutre).

---

##  Technologies utilisées

- **Langage** : Python  
- **Data manipulation** : pandas, numpy  
- **Visualisation** : matplotlib, seaborn  
- **NLP** :
  - TF-IDF Vectorizer
  - NLTK (VADER)
  - TextBlob  
- **Machine Learning** :
  - Logistic Regression (scikit-learn)

---

##  Pipeline du projet

### 1. Chargement des données
- Import des datasets (train / test)

### 2. Analyse exploratoire (EDA)
- Analyse des valeurs manquantes  
- Distribution des classes  
- Visualisation des données  

### 3. Prétraitement du texte
- Conversion en minuscules  
- Suppression des URLs  
- Nettoyage des caractères spéciaux  
- Réduction des répétitions  
- Suppression des espaces inutiles  

### 4. Feature Engineering
Création de variables supplémentaires :
- Longueur du texte  
- Nombre de mots  
- Nombre de caractères  
- Nombre de mots uniques  
- Nombre de majuscules  
- Nombre de ponctuations (!, ?)  

### 5. Extraction de sentiment
Ajout de features avancées :
- **VADER** :
  - positive, negative, neutral, compound  
- **TextBlob** :
  - polarity, subjectivity  

### 6. Vectorisation (TF-IDF)
- Utilisation de n-grammes (1 à 3)  
- Limitation du vocabulaire  
- Transformation du texte en matrice numérique  

### 7. Fusion des features
Combinaison de :
- TF-IDF  
- Features numériques  
- Scores de sentiment  

### 8. Modélisation
- Entraînement avec **Logistic Regression**  
- Ajustement des paramètres  

### 9. Prédiction
- Génération des labels sur le dataset test  

