# Master2mag
développé par M. Varmel BITA SAYA BSV :

Titre du projet :
Détection de type de cancer du sein avec analyse d'images et statistiques

Objectif :
L'application permet de prédire le type de cancer du sein à partir d'images médicales, tout en fournissant des statistiques globales et des graphiques pour analyser les données collectées. Les utilisateurs peuvent sélectionner une image d'une base de données pour obtenir des informations détaillées sur le diagnostic, l'âge et d'autres caractéristiques.

Fonctionnalités principales :
Chargement d'images : L'utilisateur peut sélectionner une image (format PNG, JPG, JPEG) à partir de son système pour analyser son contenu. L'application redimensionne et affiche l'image choisie.

Prédiction du diagnostic : Lors de la sélection d'une image, l'application consulte une base de données CSV pour prédire le type de cancer (normal, bénin ou malin), l'âge du patient et l'étiquetage du diagnostic basé sur l'image.

Affichage des résultats : Après la prédiction, les informations sont affichées à l'utilisateur, et un message de confirmation est également donné.

Visualisation des statistiques :

Diagramme circulaire : Affiche la répartition des diagnostics en pourcentage.
Histogramme : Affiche la distribution des âges des patients pour une analyse démographique.
Sauvegarde des résultats : Les résultats peuvent être sauvegardés dans un fichier CSV pour une utilisation ultérieure.

Réinitialisation : Les champs peuvent être réinitialisés pour une nouvelle analyse.

Recherche d'image : Permet de rechercher une image spécifique dans la base de données en entrant un nom ou une partie du nom.

Page de connexion : L'application requiert une connexion sécurisée avec un nom d'utilisateur et un mot de passe pour accéder à la fenêtre principale de l'application.

Technologies utilisées :
Tkinter pour la création de l'interface graphique (GUI).
Pandas pour la gestion et l'analyse des données CSV.
Matplotlib pour la génération de graphiques statistiques.
Pillow (PIL) pour la gestion des images.
Interface :
L'application a une interface colorée et facile à utiliser, avec un fond rose et des boutons bien visibles. L'utilisateur interagit principalement avec des boutons pour sélectionner des images, afficher des statistiques, prédire des résultats et sauvegarder des informations.

Sécurité :
Une simple fonctionnalité de connexion avec un nom d'utilisateur et un mot de passe est implémentée pour garantir que seules les personnes autorisées peuvent accéder à l'application.

Conclusion :
Ce projet vise à aider à la détection précoce du cancer du sein, en fournissant des outils d'analyse d'images et de statistiques. Il combine des fonctionnalités d'apprentissage machine, de gestion d'images et d'affichage graphique, tout en offrant une interface conviviale et sécurisée.







