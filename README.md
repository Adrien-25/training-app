# Documentation de l'application
## Structure du projet
**Voici la structure du projet :**  


|--- client  
|---|--- public  
|---|---|--- index.html  
|   |   |-- manifest.json  
|   |   |-- robots.txt  
|   |-- src  
|   |   |-- assets  
|   |   |   |-- images  
|   |   |   |-- styles  
|   |   |-- components  
|   |   |   |-- shared  
|   |   |   |-- workout  
|   |   |   |-- nutrition  
|   |   |   |-- tracking  
|   |   |   |-- planning  
|   |   |-- pages  
|   |   |   |-- home  
|   |   |   |-- workout  
|   |   |   |-- nutrition  
|   |   |   |-- tracking  
|   |   |   |-- planning  
|   |   |-- services  
|   |   |   |-- api  
|   |   |   |-- auth  
|   |   |   |-- storage  
|   |   |-- utils  
|   |   |-- App.js  
|   |   |-- index.js  
|   |   |-- serviceWorker.js  
|-- server  
|   |-- config  
|   |   |-- db.js  
|   |   |-- env.js  
|   |   |-- index.js  
|   |-- controllers  
|   |   |-- authController.js  
|   |   |-- exerciseController.js  
|   |   |-- nutritionController.js  
|   |   |-- trackingController.js  
|   |   |-- workoutController.js  
|   |-- models  
|   |   |-- Exercise.js  
|   |   |-- Nutrition.js  
|   |   |-- Tracking.js  
|   |   |-- User.js  
|   |   |-- Workout.js  
|   |-- routes  
|   |   |-- auth.js  
|   |   |-- exercise.js  
|   |   |-- nutrition.js  
|   |   |-- tracking.js  
|   |   |-- workout.js  
|   |-- app.js  
|-- .env  
|-- package.json  
|-- README.md  

* (./tree-md)
 * [dir2](./dir2)
   * [file21.ext](./dir2/file21.ext)
   * [file22.ext](./dir2/file22.ext)
   * [file23.ext](./dir2/file23.ext)
 * [dir1](./dir1)
   * [file11.ext](./dir1/file11.ext)
   * [file12.ext](./dir1/file12.ext)
 * [file_in_root.ext](./file_in_root.ext)
 * [README.md](./README.md)
 * [dir3](./dir3)



## Installation
### Voici les étapes à suivre pour installer l'application :

***Clonez le dépôt GitHub en utilisant la commande suivante : git clone https://github.com/votre-utilisateur/mon-projet.git.
Allez dans le répertoire du client : cd mon-projet/client et installez les dépendances en utilisant la commande npm install.
Allez dans le répertoire du serveur : cd ../server et installez les dépendances en utilisant la commande npm install.
À la racine du projet, créez un fichier .env et ajoutez les variables d'environnement nécessaires.

## Utilisation
### Voici les étapes à suivre pour lancer l'application :

Dans le répertoire du serveur, lancez la commande npm start pour lancer le serveur.
Dans le répertoire du client, lancez la commande npm start pour lancer l'application.

## Variables d'environnement
### Le fichier .env contient les variables d'environnement nécessaires pour l'application. Voici les variables à définir :

PORT : le port sur lequel le serveur doit écouter.
MONGODB_URI : l'URL de la base de données MongoDB.
SECRET : la clé secrète utilisée pour générer les jetons JWT.

## Fonctionnalités
### L'application a les fonctionnalités suivantes :

Création de programmes d'entraînement personnalisés
Suivi de progrès
Planification de séances
Base de données d'exercices
Conseils nutritionnels
Suivi de diètes
Partage de données avec d'autres applications
Thème sombre et clair
PWA

## Contributeurs
Adrien SCHMIDT

## Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE.md pour plus d'informations.