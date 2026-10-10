# Yboost - Pokémon API

🌐 **Online Project:** [https://yboost-three.vercel.app/](https://yboost-three.vercel.app/)

**Individual School Project**
This project was completed individually as part of my computer science studies at Ynov Campus.

## Description
This project is a simple RESTful Pokémon management API developed in Node.js with the Express framework. It allows you to retrieve, add, modify, or delete Pokémons (full CRUD). Data is persistently stored in a local JavaScript file (`db-pokemons.js`) which acts as a database.

This project allowed me to learn the basics of backend development with Node.js, creating API endpoints, and file manipulation with the `fs` module.

## Tech Stack
- **Language**: JavaScript (Node.js)
- **Framework**: Express.js
- **Database**: Simulated flat file (`db-pokemons.js`)

## API Endpoints
- `GET /`: Basic HTML home page
- `GET /api/pokemons`: Retrieves the complete list of Pokémons
- `GET /api/pokemons/:id`: Retrieves a specific Pokémon by its ID
- `POST /api/pokemons`: Creates a new Pokémon
- `PUT /api/pokemons/:id`: Modifies an existing Pokémon
- `DELETE /api/pokemons/:id`: Deletes a Pokémon

## Installation and Launch
To run the API locally:

1. Make sure you have Node.js installed on your machine.
2. Clone this repository.
3. Install the dependencies via the terminal:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   node index.js
   ```
   *The API will start on port 3003 (or the one defined in the environment).*

## Project Structure
```
Yboost/
├── index.js              # Server entry point and Express routes
├── helper.js             # Utility function for JSON response
├── db-pokemons.js        # Core data (modified during POST/PUT/DELETE)
├── index.html            # Home page accessible on the root
├── package.json          # List of dependencies and scripts
├── vercel.json           # Configuration for a Vercel deployment
└── README.md             # Documentation
```
