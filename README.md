# Documentation de l'application
## Structure du projet
**Voici la structure du projet :**  


```
├── client  
|   ├── public  
|   |   ├── index.html  
|   |   ├── manifest.json  
|   |   ├── robots.txt  
|   ├── src  
|   |   ├── assets  
|   |   |   ├── images  
|   |   |   ├── styles  
|   |   ├── components  
|   |   |   ├── shared  
|   |   |   ├── workout  
|   |   |   ├── nutrition  
|   |   |   ├── tracking  
|   |   |   ├── planning  
|   |   ├── pages  
|   |   |   ├── home  
|   |   |   ├── workout  
|   |   |   ├── nutrition  
|   |   |   ├── tracking  
|   |   |   ├── planning  
|   |   ├── services  
|   |   |   ├── api  
|   |   |   ├── auth  
|   |   |   ├── storage  
|   |   ├── utils  
|   |   ├── App.js  
|   |   ├── index.js  
|   |   ├── serviceWorker.js  
├── server  
|   ├── config  
|   |   ├── db.js  
|   |   ├── env.js  
|   |   ├── index.js  
|   ├── controllers  
|   |   ├── authController.js  
|   |   ├── exerciseController.js  
|   |   ├── nutritionController.js  
|   |   ├── trackingController.js  
|   |   ├── workoutController.js  
|   ├── models  
|   |   ├── Exercise.js  
|   |   ├── Nutrition.js  
|   |   ├── Tracking.js  
|   |   ├── User.js  
|   |   ├── Workout.js  
|   ├── routes  
|   |   ├── auth.js  
|   |   ├── exercise.js  
|   |   ├── nutrition.js  
|   |   ├── tracking.js  
|   |   ├── workout.js  
|   ├── app.js  
├── .env  
├── package.json  
├── README.md  



mon-projet/
├── client/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
├── server/
│   ├── node_modules/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
├── .env
├── .gitignore
└── README.md
```


## Installation
### Voici les étapes à suivre pour installer l'application :

***Clonez le dépôt GitHub en utilisant la commande suivante :***  
- Clonez le dépôt avec ***git clone https://github.com/Adrien-25/training-app.git***  
- Installez les dépendances du serveur avec ***npm install*** dans le dossier `server`  
- Installez les dépendances du client avec ***npm install*** dans le dossier `client`  
- Créez un fichier `.env` à la racine du projet et configurez les variables d'environnement requises  
- Lancez le serveur avec npm start dans le dossier `server`  
- Démarrer l'application client avec npm start dans le dossier client.

 

### Variables d'environnement
*** Le fichier .env contient les variables d'environnement nécessaires pour l'application. Voici les variables à définir :***

```
PORT : le port sur lequel le serveur doit écouter.  
MONGODB_URI : URL de la base de données MongoDB.  
SECRET : la clé secrète utilisée pour générer les jetons JWT. 
```

## Fonctionnalités
### L'application a les fonctionnalités suivantes :

- Création de programmes d'entraînement personnalisés  
- Suivi de progrès  
- Planification de séances  
- Base de données d'exercices  
- Conseils nutritionnels  
- Suivi de diètes  
- Partage de données avec d'autres applications  
- Thème sombre et clair  
- PWA  

## Contributeurs
[Adrien SCHMIDT](https://www.linkedin.com/in/adrien-schmidt-2747871a2/)

## Licence
Ce projet est sous licence MIT.  
