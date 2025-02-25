# Recipes CRUD Application

This is a basic REST API for managing recipes using Node.js, Express, and MongoDB (Mongoose). The app follows the MVC architecture and implements CRUD operations.

## Endpoints

- **POST /api/recipes** - Create a new recipe
- **GET /api/recipes** - Get all recipes
- **GET /api/recipes/:id** - Get a single recipe by ID
- **PUT /api/recipes/:id** - Update a recipe by ID
- **DELETE /api/recipes/:id** - Delete a recipe by ID

## Setup

1. Clone the repository
2. Run `npm install` to install dependencies
3. Set up a `.env` file with your MongoDB URI.
4. Run the app in development mode with `npm run dev`.

## Tools

- Node.js
- Express.js
- Mongoose (MongoDB)
- Postman for API testing
