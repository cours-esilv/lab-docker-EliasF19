# Utiliser l'image nginx comme base
FROM nginx:latest

# Copier les fichiers de l'application dans le conteneur
COPY . /usr/share/nginx/html

# Exposer le port 80
EXPOSE 80

# Commande d'entrée pour démarrer nginx
CMD ["nginx", "-g", "daemon off;"]
