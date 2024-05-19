# Simple RESTful API

A simple RESTful API built with Node.js, Express, and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a simple RESTful API using Node.js, Express, and MongoDB. It serves as a starting point for building more complex APIs.

## Features

- CRUD operations for products
- Express for HTTP requests
- Mongoose for MongoDB

## Prerequisites

- [Node.js](https://nodejs.org/) (14 or later)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/EdithAugustine/simple-RESTful-API.git
   cd your-repository

Install dependencies:
npm install

Set up environment variables:
Create a .env file with:
MONGODB_URI=mongodb://localhost:27017/yourdbname
PORT=3000

Start the server:
node server.js
The server runs at 'http://localhost:3000'

Usage
Use Postman or cURL to interact with the API.

API Endpoints
GET /products: Get all products
GET /products/:id: Get product by ID
POST /products: Create a product
Body: { "name": "Product", "price": 100, "description": "Description" }
PUT /products/:id: Update a product by ID
Body: { "name": "Updated Name", "price": 150, "description": "Updated Description" }
DELETE /products/:id: Delete a product by ID

Project Structure;
├── models
│   └── Product.js
├── routes
│   └── products.js
├── server.js
├── package.json
├── .env
└── README.md

Contributing
Contributions are welcome! Fork the repo and create a pull request.

License
This project is licensed under the MIT License.

5. **Paste the Content**:
   - Click inside the `README.md` file you created.
   - Paste the copied content by pressing `Ctrl + V` (Windows/Linux) or `Cmd + V` (Mac).

6. **Save the File**:
   - Save the file by pressing `Ctrl + S` (Windows/Linux) or `Cmd + S` (Mac).

### Committing the README to GitHub

After creating the `README.md` file, you can commit and push it to GitHub:

1. **Stage the README.md File**:
   In the terminal, run:
   ```sh
   git add README.md

2. Commit the File:
git commit -m "Add README file"

3. Push to GitHub:
git push origin master




