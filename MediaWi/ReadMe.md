
Pour lancer le contenneur:  
docker compose up -d 

Pour fermer le contenneur:  
docker compose down 

Reconstruire un container (si le Dockerfile change)
docker compose build
docker compose up -d


Les informations d'accès à la base de données (utilisateur, mot de passe) sont définis dans le compose.yaml 


Accès sur votre machine:
http://localhost:8080/
Le choix du port se fait dans le compose.yaml.

On utilise l'image docker de mediawiki: pas besoin de dockerfile.