# ddabo7-Databricks-Accidents-Project
## une présentation du projet
Dans ce projet, nous avons utilisé des techniques d'apprentissage automatique pour classer les accidents de la route en fonction de leur gravité. L'objectif principal est de développer des modèles prédictifs capables de prédire la gravité des accidents en fonction de diverses caractéristiques telles que les conditions météorologiques, les types de route, etc.

Prétraitement des données : Les données ont été nettoyées et préparées pour l'analyse. Cela comprenait le traitement des valeurs manquantes, la conversion des variables catégorielles en variables numériques, etc.

Entraînement des modèles : Trois modèles d'apprentissage automatique ont été entraînés sur les données : KNeighborsClassifier, DecisionTreeClassifier et RandomForestClassifier. Pour chaque modèle, une recherche des meilleurs hyperparamètres a été effectuée à l'aide de GridSearchCV pour optimiser les performances.

Évaluation des modèles : Les modèles ont été évalués en utilisant des métriques telles que l'accuracy et le f1-score sur un ensemble de test séparé.

Sauvegarde des modèles : Les meilleurs modèles ont été sauvegardés à l'aide de MLflow pour permettre une utilisation facile et une reproductibilité dans le futur.

## les sources des données (cf : Ilyes Talbi )
Les données utilisées dans ce projet ont été fournies par Ilyes Talbi, et comprennent plusieurs caractéristiques telles que le type de véhicule impliqué, l'âge du conducteur, le moment de la journée, les conditions météorologiques.

## les éléments de mon repository
Dans mon repository j'ai 3 fichiers, deux fichiers dbc (Modelisation et Test API) et un readme. Dans modelisation on a le preprocessing et les differentes modeles. et dans Test API on teste si on peut executer depuis l'API.

## le modèle retenu et ses performances
le modele retenu c'est RandomForest avec 64% d'accuracy. 

## le lien de l'endpoint du modèle
https://adb-2079615058985360.0.azuredatabricks.net/serving-endpoints/exam/invocations
