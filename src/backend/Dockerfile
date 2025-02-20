# Utiliser une image Node.js officielle comme image de base
FROM node:16
# Définir le répertoire de travail à l'intérieur du conteneur
WORKDIR /usr/src/app
# Copier le fichier package.json et package-lock.json
COPY package*.json ./
# Installer les dépendances de l'application
RUN npm install
# Copier le reste des fichiers de l'application dans le conteneur
COPY . .
# Exposer le port utilisé par l'application
EXPOSE 8080
# Démarrer l'application
CMD [ "npm", "start" ]
