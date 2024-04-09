README pour Apache

# Serveur Apache

Ce dossier contient un fichier `docker-compose.yml` pour déployer un serveur Apache dans un conteneur Docker.

## Prérequis

- Docker et Docker Compose installés sur votre machine.

## Lancement

Pour démarrer le service, exécutez :

```bash
docker-compose -f docker-compose-apache.yml up -d
```

Configuration
Apache : Placez vos fichiers HTML/PHP dans le dossier ./html.
Arrêt et nettoyage
Pour arrêter le service et nettoyer les conteneurs, exécutez :

```bash
docker-compose -f docker-compose-apache.yml down
```
