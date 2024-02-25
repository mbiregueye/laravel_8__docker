1- Installation de Docker : Tout d'abord, assurez-vous d'avoir Docker installé sur votre machine. Vous pouvez le faire en téléchargeant et en installant Docker Desktop depuis le site officiel de Docker.

2- Configuration des fichiers Docker : Créez un dossier nommé docker à la racine de votre projet Laravel. À l'intérieur, créez un fichier Dockerfile pour définir les dépendances de votre conteneur Docker, et un fichier docker-compose.yml pour configurer les services.

3- Configuration du Dockerfile : Dans le fichier Dockerfile, spécifiez l'image de base, installez les dépendances PHP nécessaires, activez les extensions PHP requises, et configurez le répertoire de travail.

4- Configuration du docker-compose.yml : Dans le fichier docker-compose.yml, déclarez les services nécessaires, tels que le service PHP, le service MySQL (ou tout autre base de données), 
