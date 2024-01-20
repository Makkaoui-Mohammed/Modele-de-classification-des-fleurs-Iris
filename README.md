# Modele-de-classification-des-fleurs-Iris
L'application est ensuite déployée en utilisant Streamlit pour permettre à l'utilisateur de saisir les caractéristiques d'une fleur Iris (longueur et largeur du sépale, longueur et largeur du pétale) via une barre latérale interactive. Le modèle prédit la classe de la fleur et affiche le résultat ainsi que l'image associée à la classe prédite

Le code Python utilise la bibliothèque Scikit-learn pour créer un modèle de classification des fleurs Iris en utilisant l'algorithme RandomForest. L'application est ensuite déployée en utilisant Streamlit pour permettre à l'utilisateur de saisir les caractéristiques d'une fleur Iris (longueur et largeur du sépale, longueur et largeur du pétale) via une barre latérale interactive. Le modèle prédit la classe de la fleur et affiche le résultat ainsi que l'image associée à la classe prédite.

Voici une description détaillée du code :

Importation des bibliothèques :

datasets de Scikit-learn : pour charger le jeu de données Iris.
RandomForestClassifier de Scikit-learn : pour créer un modèle de classification utilisant l'algorithme RandomForest.
Image de PIL : pour travailler avec des images.
pandas : pour la manipulation de données tabulaires.
streamlit : pour créer une application web interactive.
Évaluation du modèle :

Les métriques de performance telles que l'exactitude, la précision, le rappel, le F1-score et la matrice de confusion sont calculées après l'entraînement du modèle.
Chargement du jeu de données Iris :

Le jeu de données Iris est chargé à l'aide de la fonction load_iris() de Scikit-learn.
Les caractéristiques et les étiquettes du jeu de données sont affichées.
Entraînement du modèle :

Un modèle RandomForestClassifier est créé et entraîné avec les données Iris.
Interface utilisateur Streamlit :

Une interface utilisateur Streamlit est créée pour permettre à l'utilisateur de saisir les caractéristiques d'une fleur Iris via des curseurs interactifs.
Les caractéristiques saisies sont utilisées pour faire une prédiction à l'aide du modèle entraîné.
Affichage des résultats :

La prédiction de la classe de la fleur est affichée.
Une image associée à la classe prédite est affichée à côté du résultat.
Mesures de performance supplémentaires :

Les métriques de performance (exactitude, précision, rappel, F1-score) et la matrice de confusion sont affichées pour évaluer le modèle.
Déploiement Streamlit :

L'application peut être déployée en exécutant la commande "streamlit run" dans la console


![image](https://github.com/Makkaoui-Mohammed/Modele-de-classification-des-fleurs-Iris/assets/108239380/7bf8f1c8-a52c-4936-b223-2731f15ea352)
![image](https://github.com/Makkaoui-Mohammed/Modele-de-classification-des-fleurs-Iris/assets/108239380/b0a72a91-4579-4868-967f-42c45484699b)


