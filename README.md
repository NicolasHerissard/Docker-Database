# Docker-Database

Ce projet configure un environnement Docker pour utiliser une base de données MariaDB avec une interface de gestion phpMyAdmin.

## Contenu

### Services
- **MariaDB** : Base de données relationnelle.
- **phpMyAdmin** : Interface web pour gérer la base de données.

### Ports exposés
- MariaDB : `3307` (interne : `3306`).
- phpMyAdmin : `8081` (interne : `80`).

### Persistance
Les données de MariaDB sont sauvegardées localement dans `./mariadb`.

## Installation

1. **Clonez ce dépôt** :  
   ```bash
   git clone <URL_DU_DEPOT>
   cd Docker-Database

2. **Lancez le conteneur** :  
   ```bash
   docker-compose up -d
   ```