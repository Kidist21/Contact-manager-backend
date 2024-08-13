# Contact Manager Backend

![License](https://img.shields.io/github/license/Kidist21/Contact-manager-backend)
![Issues](https://img.shields.io/github/issues/Kidist21/Contact-manager-backend)
![Stars](https://img.shields.io/github/stars/Kidist21/Contact-manager-backend)
![Forks](https://img.shields.io/github/forks/Kidist21/Contact-manager-backend)

## Overview

The Contact Manager Backend is a RESTful API built with Node.js, Express, and MongoDB, designed to efficiently manage contact information. It supports full CRUD operations and includes authentication with JWT for secure access to contact data.

## Features

- **CRUD Operations:** Create, Read, Update, and Delete contacts.
- **User Authentication:** User registration and login with JWT-based authentication.
- **Protected Routes:** Secure routes accessible only by authenticated users.
- **MongoDB Integration:** Leverages Mongoose for database modeling and interaction.
- **Error Handling:** Robust error handling with custom middleware.
- **Asynchronous Operations:** Efficient async operations using Express async handlers.

## Technology Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose ODM
- **Authentication:** JSON Web Tokens (JWT)
- **API Testing:** Thunder Client (or Postman)
- **Middleware:** Custom error handling, JWT verification

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Thunder Client (or Postman)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Kidist21/Contact-manager-backend.git
   cd Contact-manager-backend

2. **Install dependencies:**

   ```bash
   npm install

3. **Run the application:**

   ```bash
   npm run dev


## API Endpoints

- **GET /api/contacts** - Retrieve all contacts
- **GET /api/contacts/:id** - Retrieve a specific contact by ID
- **POST /api/contacts** - Create a new contact
- **PUT /api/contacts/:id** - Update an existing contact
- **DELETE /api/contacts/:id** - Delete a contact by ID
- **POST /api/users/register** - Register a new user
- **POST /api/users/login** - Login a user and receive a JWT token
- **GET /api/users/current** - Get the current logged-in user

### Testing the API

Use Thunder Client or Postman to test the API endpoints. Ensure you include the JWT token in the Authorization header for protected routes.

