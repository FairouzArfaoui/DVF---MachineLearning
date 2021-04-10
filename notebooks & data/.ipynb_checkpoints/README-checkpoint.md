# Test technique Data Science

## Description

Dans le cadre de ce test technique, il s'agit de construire un algorithme d'estimation d'un bien immobilier basé sur ses caractéristiques et sa localisation contenues dans la donnée publique 'Demande de Valeurs Foncières' (DVF). La donnée fournie au format CSV `dvf_train.csv`  contient les transactions immobilières parisiennes sur une période donnée. Le dataset de test `df_test.csv`, qui ne contient pas le prix, a été sélectionné pour évaluer les performances du modèle du candidat au delà de la période disponible dans le dataset `dvf_train.csv`.

## Consignes

Le candidat sélectionnera les variables les plus importantes pour prédire le prix, parmi celle fournies dans le dataset. En plus de celles présentes dans la base de donnée DVF, des variables, pertinentes ou non, sont fournies (il s'agit de lon, lat, code_IRIS, code_district_admin, code_district_custom).

Le candidat pourra rendre un code Python ou R (un `jupyter_notebook` par exemple) explicitant la démarche suivie, le preprocessing de la donnée, l'entraînement du modèle.

Le candidat accompagnera son code d'un fichier de prédictions de son modèle sur le dataset de test `dvf_test.csv` au format CSV.

Le candidat devra obtenir le meilleur score en terme de MAPE (Mean Absolute Percentage Error: https://en.wikipedia.org/wiki/Mean_absolute_percentage_error).

Exemple de fichier de prediction :
index, Valeur fonciere
249349, 300000
249370, 750000

Le candidat devra porter attention à :
* la qualité du code
* la compréhension métier de la donnée
* la compréhension des modèles utilisés
