# Deep-Learning

                                                                Exercice de classification

Contexte

Il s’agit d’un problème de classification d’images de visages. Le critère de classification n’est
pas décrit ici, il est défini de façon implicite par les labels de la base d’apprentissage.

- Data
Les données sont les suivantes :
  - Une base : 122670 images de visage, numérotée de 000001 à 122670. Les fichiers sont au format jpg, les images font 130x130 et sont en couleur.
  - La liste d’apprentissage : un fichier nommé « esiea_train_2022_DL.txt », contenant 102670 lignes de la forme « Nom_d’image label_associé (-1 ou 1) »
  - La liste de test : un fichier nommé « esiea_valid_2022_DL.txt », contenant 20000 lignes de la forme : « Nom_d’image »
  
- Résultats attendus
  - Le travail s’effectue en binôme. Un trinôme max par classe.
  - La métrique retenue est la moyenne des erreurs sur chaque classe. Notez que le nb d’élément dans chaque classe est différent. Cela devra être pris en compte dans les
apprentissages pour des performances optimales
  - J’ai volontairement bruité un faible pourcentage des labels. Une loss robuste pourrait aider lors de l’apprentissage.
  - Il est demandé aux étudiants de fournir les prédictions du jeu de test pour l’évaluation, sous forme de fichier texte, nommé « Nom_d’image predictions_nom1_nom2.txt »,
d’exactement 20000 lignes, au même format que le fichier de liste d’apprentissage
mais pour la liste de la base de test (en respectant l’ordre des images de la liste
« esiea_valid_2022_DL.txt ».
  - Il est demandé aux étudiants de fournir le modèle appris, le code python/tensorflow/pytorch/keras ayant servi à apprendre le modèle ainsi qu’un code python permettant
de générer « predictions_nom1_nom2.txt » à partir du modèle.
  - Le rendu définitif est attendu pour le 21 décembre à 19h
  - Il est demandé aux étudiants de fournir un document répondant synthétiquement auxquestions suivantes :
  
        1. Quel type d’architecture avez-vous utilisé, pourquoi ?
        
        2. Combien de convolutions contient votre architecture, pourquoi ?
        
        3. Comment vous êtes-vous préoccupé de l’over-fitting ?
        
        4. Est-ce que l’asymétrie de le base d’apprentissage est un problème ? si oui, comment
        avez traité ?
        
        5. Est-ce que les labels bruités ont posé problème. Comment l’avez-vous géré ?
        
        6. Pour les images de la base de test, à partir de la sortie de votre réseau, comment attribuez-vous le label ?
        
        7. Avec un mois supplémentaire pour travailler, que feriez-vous pour améliorer vos résultats ?
        
        8. Question non notée : A quoi correspond le label recherché ?
