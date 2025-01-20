# Configuration Repository pour Spring Cloud Config Server

Ce repository contient les fichiers de configuration pour les microservices dans notre architecture.

## Structure des fichiers

- **microservice-commandes.properties** : Configuration du microservice-commandes.
- **microservice-produit.properties** : Configuration du microservice-produit.
- **application.properties** : Configuration globale pour les microservices.

config-repo/
├── application.properties       # Configuration globale pour tous les services
├── commandes-service.properties # Configuration spécifique au service commandes
├── produit-service.properties   # Configuration spécifique au service produit
├── gateway-service.properties   # Configuration spécifique à l'API Gateway
