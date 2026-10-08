# Yboost - Pokémon API

🌐 **Projet en ligne :** [https://yboost-three.vercel.app/](https://yboost-three.vercel.app/)

**Projet scolaire individuel**
Ce projet a été réalisé de manière individuelle dans le cadre de mes études en informatique à Ynov Campus.

## Description
Ce projet est une API RESTful simple de gestion de Pokémons développée en Node.js avec le framework Express. Il permet de récupérer, ajouter, modifier ou supprimer des Pokémons (CRUD complet). Les données sont stockées de façon persistante dans un fichier JavaScript local (`db-pokemons.js`) qui fait office de base de données.

Ce projet m'a permis d'apprendre les bases du backend avec Node.js, la création d'endpoints d'API, et la manipulation de fichiers avec le module `fs`.

## Stack Technique
- **Langage** : JavaScript (Node.js)
- **Framework** : Express.js
- **Base de données** : Fichier plat simulé (`db-pokemons.js`)

## Endpoints de l'API
- `GET /` : Page d'accueil HTML basique
- `GET /api/pokemons` : Récupère la liste complète des Pokémons
- `GET /api/pokemons/:id` : Récupère un Pokémon spécifique par son ID
- `POST /api/pokemons` : Crée un nouveau Pokémon
- `PUT /api/pokemons/:id` : Modifie un Pokémon existant
- `DELETE /api/pokemons/:id` : Supprime un Pokémon

## Installation et Lancement
Pour faire fonctionner l'API en local :

1. Assurez-vous d'avoir Node.js installé sur votre machine.
2. Clonez ce dépôt.
3. Installez les dépendances via le terminal :
   ```bash
   npm install
   ```
4. Lancez le serveur de développement :
   ```bash
   node index.js
   ```
   *L'API démarrera sur le port 3003 (ou celui défini dans l'environnement).*

## Arborescence du Projet
```
Yboost/
├── index.js              # Point d'entrée du serveur et routes Express
├── helper.js             # Fonction utilitaire pour la réponse JSON
├── db-pokemons.js        # Données de base (modifié lors des POST/PUT/DELETE)
├── index.html            # Page de garde accessible sur la racine
├── package.json          # Liste des dépendances et scripts
├── vercel.json           # Configuration pour un déploiement Vercel
└── README.md             # Documentation
```
