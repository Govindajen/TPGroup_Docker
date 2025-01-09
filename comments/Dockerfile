# Utiliser une image Node officielle comme image de base
FROM node:18

# Définir le répertoire de travail dans le conteneur
WORKDIR /comments

# Copier les fichiers package.json et package-lock.json (si disponible)
COPY package.json ./

# Installer les dépendances
RUN npm install

# Copier tout le reste des fichiers de l'application dans le conteneur
COPY . .

# Exposer le port utilisé par l'application (4001)
EXPOSE 4001

# Commande pour démarrer l'application
CMD ["npm", "start"]
