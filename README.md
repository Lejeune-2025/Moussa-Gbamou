# Moussa-Gbamou
Gestion des Factures
# Gestion de Factures

## Description
Ce projet est une application de gestion de factures qui nous a été confiée par notre chef de stage. Elle permet aux entreprises de gérer leurs factures de manière efficace et simplifiée. Le backend assure l'authentification sécurisée des utilisateurs, tandis que le frontend offre une interface intuitive et réactive.

## Technologies utilisées
- **Frontend** : React avec Vite, Redux Toolkit, TypeScript, Tailwind CSS, Lucide React (icônes)
- **Backend** : Node.js, Express
- **Base de données** : MongoDB (MongoDB Compass, 3T Studio)
- **Authentification** : JWT (JSON Web Token)
- **Génération de PDF** : jsPDF, html2canvas

## Fonctionnalités principales
1. **Authentification** : Connexion sécurisée des utilisateurs.
2. **Création et suivi des factures**.
3. **Gestion des clients** : Enregistrement des informations clients.
4. **Gestion des articles** : Ajout, modification, suppression et calcul des montants.
5. **Calcul automatique de la TVA**.
6. **Aperçu en temps réel** : Visualisation de la facture lors de sa création.
7. **Statut des factures** : Factures payées, en attente ou en retard.
8. **Stockage en base de données** : Sauvegarde automatique des factures.
9. **Téléchargement en PDF** : Génération et export des factures au format PDF.

## Installation
1. **Cloner le dépôt**
   ```bash
   git clone 
   cd gestion-facture
   ```

2. **Installation des dépendances**
   - **Backend**
     ```bash
     cd backend
     npm install express mongoose dotenv jsonwebtoken bcryptjs cors
     npm install --save-dev nodemon
     ```
   - **Frontend**
     ```bash
     cd frontend
     npm install react react-dom vite redux react-redux @reduxjs/toolkit typescript tailwindcss postcss autoprefixer lucide-react jspdf html2canvas
     ```

3. **Configuration de l'environnement**
   Créer un fichier `.env` à la racine du backend et y ajouter :
   ```env
   MONGODB_URI=mongodb://localhost:27017//Users
   JWT_SECRET=your-jwt-secret
  

4. **Démarrer l'application**
   - **Backend**
     ```bash
     cd backend
     node serveur.js # Lance le backend avec Nodemon
     ```
   - **Frontend**
     ```bash
     cd frontend
     npm run dev  # Lance le frontend avec Vite
     ```

## API Endpoints
| Méthode | Endpoint        | Description                  |
|---------|----------------|------------------------------|
| POST    | /api/auth/login | Connexion de l'utilisateur   |


## Auteur
- **Votre Nom** - Moussa Gbamou

## Licence
Ce projet est sous licence MIT.

