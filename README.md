# NUMPANDAS
Découverte de Numpy et Pandas (analyse et calcul de données)

### Exercices de Manipulation de Données avec NumPy et pandas

#### Partie 1 : NumPy
pip install numpy
##### Exercice 1 - Introduction à NumPy
Dans cet exercice, nous allons explorer les bases de NumPy et manipuler des tableaux.

1. Créez un tableau NumPy de dimensions (5, 5) rempli de valeurs aléatoires entre 0 et 99 inclus (int uniquement).
2. Calculez la somme de toutes les valeurs dans le tableau.
3. Calculez la moyenne des valeurs dans chaque colonne.
4. Remplacez toutes les valeurs impaires par 0.

##### Exercice 2 - Indexation et tris avec NumPy
Dans cet exercice, nous allons apprendre à effectuer des opérations d'indexation et de tri avec NumPy.

1. Créez un tableau NumPy de dimensions (10, 3) rempli de valeurs aléatoires entre 0 et 99 inclus (int uniquement).
2. Triez le tableau en fonction de la deuxième colonne (en ordre croissant).
3. Sélectionnez les lignes où la valeur de la troisième colonne est supérieure à 0.5.

##### Exercice 3 - Manipulation avancée de tableaux NumPy
Dans cet exercice, nous allons explorer des opérations plus avancées avec NumPy.

1. Créez un tableau NumPy de dimensions (8, 8) rempli de zéros.
2. Remplissez la diagonale principale avec des 1.
3. Ajoutez une bordure de 2 autour du tableau, en laissant les valeurs d'origine au centre.
4. Trouvez le produit des éléments non nuls du tableau.

#### Partie 2 : pandas

##### Exercice 4 - Introduction à pandas et chargement de données
Dans cette partie, nous allons explorer pandas en utilisant un DataFrame pour manipuler des données tabulaires.

1. Téléchargez le reporting 'ventes.csv' de données CSV et chargez-le dans un DataFrame pandas.
2. Affichez les 5 premières lignes du DataFrame.
3. Identifiez les valeurs manquantes et traitez-les (remplissez les valeurs manquantes).

##### Exercice 5 - Analyse et filtrage de données avec pandas
Dans cet exercice, nous allons effectuer des opérations d'analyse et de filtrage sur les données à l'aide de pandas.

1. Utilisez le DataFrame précédent pour calculer la somme des ventes totales.
2. Filtrer les lignes correspondant à un produit spécifique (le produit qui se vend le mieux).
3. Calcule le panier moyen en partant du principe que chaque vente équivaut à un panier

##### Exercice 6 - Visualisation de données avec pandas
Dans cet exercice, nous allons utiliser pandas en combinaison avec la bibliothèque de visualisation matplotlib pour créer des graphiques.

1. Utilisez le DataFrame et les résultats de l'exercice précédent pour tracer un diagramme à barres des moyennes de ventes par catégorie de produit.
2. Tracez un histogramme des ventes pour un produit spécifique.

