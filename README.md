# PROJET-H419-MEFENYA

  Ce projet a pour objectif de développer un modèle d’intelligence artificielle capable de classifier des images échographiques du sein afin de distinguer trois catégories : tumeurs bénignes, tumeurs malignes et cas normaux. Une telle approche peut contribuer à la détection précoce du cancer du sein, améliorant ainsi les chances de guérison et la qualité de vie des patientes.
Les données utilisées proviennent du dataset public Breast Ultrasound Images disponible sur Kaggle. Avant l’entraînement, un prétraitement des images a été réalisé : redimensionnement en 256×256, normalisation des pixels et augmentation de données pour enrichir la base d’apprentissage.
  Le modèle choisi est un Convolutional Neural Network (CNN) implémenté avec TensorFlow/Keras. Cette architecture est particulièrement adaptée à la reconnaissance d’images, grâce à l’extraction automatique de caractéristiques locales via des convolutions et des couches de pooling. Le modèle a été évalué à l’aide de métriques standards en classification : précision, rappel, F1-score et matrice de confusion.

Les résultats obtenus montrent une précision globale de 0.81. Le modèle identifie correctement de nombreuses images, mais il reste des difficultés à distinguer les tumeurs bénignes des tumeurs malignes, ce qui constitue une limite importante. Ces confusions s’expliquent principalement par la taille réduite du dataset et la variabilité de qualité des images.

Pour améliorer ce travail, il serait intéressant d’utiliser une base de données plus large et diversifiée, d’explorer des architectures plus profondes et d’envisager une validation clinique dans un environnement hospitalier.
