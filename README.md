🧠 Analyse de Sentiments avec Machine Learning (NLP)
📌 Présentation du projet

Ce projet vise à construire un modèle de classification de sentiments en utilisant des techniques de Traitement du Langage Naturel (NLP) et de Machine Learning.
L’objectif est de transformer des données textuelles en variables exploitables afin de prédire le sentiment associé (positif, négatif, etc.).

⚙️ Stack technique
Langage : Python
Librairies principales : pandas, numpy, scikit-learn
NLP : TF-IDF, NLTK (VADER), TextBlob
Modèle : Logistic Regression
🔎 Pipeline du projet
Chargement des données
Analyse exploratoire (EDA) : distribution, valeurs manquantes
Nettoyage du texte :
Minuscule
Suppression des URLs
Nettoyage des caractères spéciaux
Feature Engineering :
Longueur du texte
Nombre de mots
Ponctuation (?!)
Extraction de sentiment :
Scores VADER
Polarity & Subjectivity (TextBlob)
Vectorisation :
TF-IDF (uni, bi, trigrammes)
Modélisation :
Entraînement avec Logistic Regression
Prédiction
📊 Points forts

✔ Pipeline NLP complet
✔ Combinaison TF-IDF + features linguistiques
✔ Ajout de scores de sentiment (VADER, TextBlob)
✔ Approche hybride (statistique + sémantique)
