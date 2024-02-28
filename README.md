# Déploiement de WordPress avec Docker Compose

Ce dépôt contient les fichiers nécessaires pour déployer 2 conteneurs WordPress et 1 conteneur MySQL en utilisant Docker Compose.

## Utilisation

1. Assurez-vous d'avoir Docker et Docker Compose installés sur votre système.

2. Créez un fichier `.env` contenant les variables d'environnement sensibles. Voici un exemple : MYSQL_ROOT_PASSWORD=wordadmin

3. Utilisez le fichier `docker-compose.yaml` pour définir vos services Docker. Il contient la configuration pour MySQL et deux instances de WordPress.

4. Exécutez la commande suivante pour démarrer les conteneurs en arrière-plan : docker-compose up -d

5. Une fois les conteneurs démarrés, vous pouvez accéder à votre site WordPress via votre navigateur web. Les instances de WordPress sont accessibles aux adresses suivantes :

- <http://localhost:8080>

- <http://localhost:8081>

## Contenu du dépôt

- `docker-compose.yaml`: Le fichier Docker Compose contenant la configuration des services.
- `.env`: Le fichier de configuration des variables d'environnement sensibles.
- `.gitignore`: Le fichier ignorer spécifie les fichiers et répertoires à ignorer dans le dépôt Git.
- `README.md`: Ce fichier.
- [E-mail](ewan.angoujard@gmail.com)

&copy; Angoujard - 2024
