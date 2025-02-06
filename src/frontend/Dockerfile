#Image de base nginx, un serveur web très utilisé
FROM nginx:latest
# Copie vos fichiers statiques dans le répertoire par défaut d'NGINX
COPY . /usr/share/nginx/html

# Expose le port 80 pour servir l'application
EXPOSE 80

# Démarre NGINX
CMD ["nginx", "-g", "daemon off;"]
