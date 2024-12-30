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


************** les outils et technologies utilisés pour développer cette application de détection de cancer du sein :  **********



### 1. **Tkinter (Python)**
   - **Rôle** : Tkinter est la bibliothèque principale utilisée pour créer l'interface graphique (GUI) de l'application. Elle permet de construire des fenêtres, des boutons, des champs de texte, et d'autres éléments d'interaction avec l'utilisateur.
   - **Avantages** : Tkinter est facile à utiliser pour les applications simples, offre une bonne compatibilité multiplateforme et est intégré directement dans Python.

### 2. **Pandas (Python)**
   - **Rôle** : Pandas est utilisé pour la gestion et l'analyse des données. L'application charge un fichier CSV contenant des informations sur les images et leurs classifications. Pandas permet de filtrer, manipuler et analyser ces données de manière efficace.
   - **Avantages** : Très puissant pour le traitement des données tabulaires, Pandas simplifie les opérations de lecture, filtrage et agrégation de données.

### 3. **Matplotlib (Python)**
   - **Rôle** : Matplotlib est utilisé pour générer des graphiques, tels que des diagrammes circulaires et des histogrammes. Cela permet à l'application de visualiser des statistiques sur les données, telles que la répartition des labels ou la distribution des âges.
   - **Avantages** : Matplotlib est une bibliothèque populaire et puissante pour créer des visualisations en Python, avec de nombreuses options de personnalisation des graphiques.

### 4. **Pillow (PIL) (Python)**
   - **Rôle** : Pillow (anciennement connu sous le nom de PIL - Python Imaging Library) est utilisé pour la gestion des images. L'application charge, redimensionne et affiche les images médicales sélectionnées par l'utilisateur.
   - **Avantages** : Pillow permet de travailler facilement avec des images en Python, offrant des fonctionnalités de traitement d'images telles que l'ouverture, la manipulation, et l'affichage.

### 5. **CSV (Fichier de données)**
   - **Rôle** : Le fichier CSV contient des informations sur les images médicales, telles que les noms de fichiers, les labels (diagnostics), les classifications (type de cancer), et les âges des patients. Ce fichier est utilisé pour fournir des informations pour la prédiction et l'analyse des images.
   - **Avantages** : Le format CSV est simple à utiliser pour stocker et manipuler des données tabulaires, et il peut être facilement ouvert avec Pandas pour l'analyse.

### 6. **Python (Langage de programmation)**
   - **Rôle** : Python est le langage de programmation utilisé pour développer l'application. Il est populaire pour sa simplicité et sa lisibilité, ainsi que pour sa large gamme de bibliothèques dédiées au traitement des données, à la gestion des images et à l'interaction avec l'utilisateur.
   - **Avantages** : Python est polyvalent, avec un écosystème riche de bibliothèques et de frameworks pour le traitement d'images, l'analyse de données, et la création d'interfaces graphiques.

### 7. **FileDialog (Tkinter)**
   - **Rôle** : FileDialog est une fonctionnalité de Tkinter qui permet à l'utilisateur de sélectionner un fichier (comme une image ou un fichier CSV) à partir de son système de fichiers local.
   - **Avantages** : Permet une interaction fluide avec le système de fichiers, facilitant la sélection d'images ou de fichiers pour l'application.

### 8. **SimpleDialog (Tkinter)**
   - **Rôle** : SimpleDialog est utilisé pour afficher une boîte de dialogue simple où l'utilisateur peut entrer des informations (comme le nom d'une image à rechercher dans la base de données).
   - **Avantages** : Facile à utiliser pour obtenir des entrées de texte simples sans avoir à créer une interface complexe.

### 9. **ImageTk (Pillow et Tkinter)**
   - **Rôle** : ImageTk est une interface entre Pillow et Tkinter, utilisée pour convertir les images traitées avec Pillow en objets compatibles avec Tkinter (pour les afficher dans l'interface graphique).
   - **Avantages** : Permet d'afficher des images dans une interface Tkinter de manière fluide et efficace.

### 10. **Fichier de données d'image (ex. CSV ou base de données)**
   - **Rôle** : Le fichier CSV ou toute autre base de données utilisée stocke les informations associées aux images médicales, y compris les diagnostics, les âges, et les classifications. Ces données sont essentielles pour prédire le type de cancer à partir des images.
   - **Avantages** : Permet de maintenir une base de données structurée et d'effectuer des recherches rapides pour associer une image à des informations médicales.

************** Bibliothèque à installer  *******

pip install pandas

pip install matplotlib

pip install numpy
pip install scikit-learn







