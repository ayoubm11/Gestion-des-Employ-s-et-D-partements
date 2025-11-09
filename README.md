# Gestion des Employés et Départements OCP

Ce projet est une application web complète pour la gestion des employés et des départements, développée avec Spring Boot pour le backend et Angular pour le frontend.

## 🚀 Fonctionnalités

- Gestion complète des employés (CRUD)
- Gestion des départements (CRUD)
- Interface utilisateur intuitive
- Système de navigation réactif
- Architecture modulaire

## �️ Captures d'écran de l'Application

### Interface de Gestion des Employés
![Interface de Gestion des Employés](assest/1.png)

### Interface de Gestion des Départements
![Interface de Gestion des Départements](assest/2.png)

## �🛠 Technologies Utilisées

### Backend
- Java 11+
- Spring Boot
- Spring Data JPA
- Spring Web
- Base de données (configurée dans application.properties)
- Maven pour la gestion des dépendances

### Frontend
- Angular 14+
- TypeScript
- Bootstrap pour le style
- Services HTTP pour la communication avec l'API
- Routing Angular pour la navigation

## 📦 Structure du Projet

```
OcpPfe/
├── OCP-Gestion-des-employes-et-Departement/     # Backend
│   ├── src/
│   │   ├── main/java/com/ecom/ocppfe/
│   │   └── resources/
│   └── pom.xml
│
└── OCP-Gestion-des-employes-et-Departement_FrontEnd/    # Frontend
    ├── src/
    │   ├── app/
    │   │   ├── pages/
    │   │   ├── services/
    │   │   └── shared/
    │   └── assets/
    └── package.json
```

## 🚀 Installation et Démarrage

### Backend (Spring Boot)

1. Naviguer vers le dossier backend :
```bash
cd OCP-Gestion-des-employes-et-Departement
```

2. Installer les dépendances et compiler :
```bash
./mvnw clean install
```

3. Lancer l'application :
```bash
./mvnw spring-boot:run
```

Le serveur démarre sur `http://localhost:8080`

### Frontend (Angular)

1. Naviguer vers le dossier frontend :
```bash
cd OCP-Gestion-des-employes-et-Departement_FrontEnd
```

2. Installer les dépendances :
```bash
npm install
```

3. Lancer l'application :
```bash
ng serve
```

L'application est accessible sur `http://localhost:4200`

## 📚 Documentation API

L'API REST expose les endpoints suivants :

### Employés
- GET /api/employees - Liste tous les employés
- GET /api/employees/{id} - Détails d'un employé
- POST /api/employees - Créer un employé
- PUT /api/employees/{id} - Modifier un employé
- DELETE /api/employees/{id} - Supprimer un employé

### Départements
- GET /api/departments - Liste tous les départements
- GET /api/departments/{id} - Détails d'un département
- POST /api/departments - Créer un département
- PUT /api/departments/{id} - Modifier un département
- DELETE /api/departments/{id} - Supprimer un département

## 👥 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## 📝 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 📧 Contact

Ayoub MOURADI - [Github](https://github.com/ayoubm11)

Lien du projet : [https://github.com/ayoubm11/Gestion-des-Employ-s-et-D-partements](https://github.com/ayoubm11/Gestion-des-Employ-s-et-D-partements)
