# **PMT - Documentation et Livrables**

## **Description**
Ce repository regroupe l'ensemble des livrables, rapports, et documents associés au projet **Project Management Tool (PMT)**. Ce projet a été développé pour répondre à des besoins de gestion collaborative, en intégrant des fonctionnalités telles que la création et la gestion de projets, l'attribution de tâches, et la gestion des rôles utilisateurs.

Ce dépôt sert de **complément au repository principal contenant le code source** de l'application PMT, disponible ici : [PMT-Project Repository](https://github.com/wa2l-99/project-management-tool).

---

## **Structure du Repository**

### 1. **Conception**
Ce dossier contient les éléments liés à la phase de conception de l'application :
- **Diagrammes de conception** :
  - `database-schema.png` : Schéma de la base de données.
- **Scripts SQL** :
  - `V1__create_db.sql` : Script de création des tables.
  - `V2__insert_initial_data.sql` : Script d’insertion des données de test.

### 2. **Documentation**
**Rapport du Projet** 
Le rapport complet du projet, détaillant la conception, le développement, les tests et le déploiement, est disponible ici :
- [Rapport Final - PMT](Documentation/Rapport_Final_Projet_PMT.pdf)

### 3. **Tests**
Ce dossier contient les livrables associés à la validation de l'application :
- **Rapports de couverture des tests** :
  - **Frontend** : Consultez le fichier `\frontend-coverage-report\lcov-report\index.html` pour visualiser la couverture des tests frontend.
  - **Backend** : Consultez le fichier `\backend-coverage-report\site\jacoco\index.html` pour visualiser la couverture des tests backend.
- Instructions pour exécuter les tests.

### 4. **Industrialisation**
Ce dossier regroupe les fichiers liés à l'automatisation et au déploiement :
- **Dockerfiles** :
  - `backend/Dockerfile`
  - `frontend/Dockerfile`
- **Fichier docker-compose** : 
  - `docker-compose.yml`
- **Pipelines CI/CD** :
  - `backend-pipeline.yml`
  - `frontend-pipeline.yml`
- Documentation de la procédure de déploiement.

---

## **Comment utiliser ce repository**

### **Étape 1 : Clonage**
Cloner ce repository ainsi que le repository contenant le code source.

```bash
# Clonage de la documentation
git clone https://github.com/wa2l99/PMT-Documentation

# Clonage du projet principal avec les sous-modules
git clone --recurse-submodules https://github.com/wa2l99/project-management-tool
