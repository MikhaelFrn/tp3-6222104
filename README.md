# Déploiment des services pour le TP3 d'infonuagique

## Liste des services dans le compose.yaml :

-   Portainer
-   NexCloud
-   Plex

### J'utilise traefik comme reverse proxy
### Le .env.example montre les variables d'environement pour :
-   Les identifiants pour la DB
-   Le claim pour Plex
-   Le token DuckDNS
-   Les infos pour traefik (email + domain DuckDNS)