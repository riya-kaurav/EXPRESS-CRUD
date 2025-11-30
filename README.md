# REST API CRUD Project

A fully containerised **REST API CRUD application** built with **Node.js** and **Express.js**, using **PostgreSQL** as the database. The project is designed to run seamlessly with **Docker**, ensuring easy setup and portability across environments.

---

## Introduction

This project demonstrates how to build a robust backend service with:

- **Node.js & Express.js** for handling HTTP requests and defining API routes.
- **PostgreSQL** as the relational database for storing and managing data.
- **Docker** for containerisation, making the application easy to run and deploy.
- **Centralised error handling** for consistent API responses.
- **Standardised response format** across all endpoints.

---

##  Tech Stack
- **Node.js** – JavaScript runtime for server-side development  
- **Express.js** – Web framework for building RESTful APIs  
- **PostgreSQL** – Relational database system  
- **Docker** – Containerisation for easy setup and deployment  


---

##  Architecture Overview
- **Routes Layer (`src/routes/`)**  
  Defines API endpoints for CRUD operations.

- **Controllers Layer (`src/controllers/`)**  
  Contains business logic for handling requests and responses.

- **Models Layer (`src/models/`)**  
  Defines database queries and interactions with PostgreSQL.

- **Middleware (`src/middleware/`)**  
  Includes error handling, validation, and response formatting.

- **App Initialization (`src/app.js`)**  
  Configures middleware, connects routes, and starts the Express server.

---


###  Key Features
- RESTful API design following industry best practices.
- Separation of concerns with routes, controllers, and models.
- Environment-based configuration using `.env`.
- Error handling and status codes for robust API responses.
  

###  Example Use Case
This project can serve as:
- A starter template for building backend services.
- A learning resource for understanding CRUD operations in Express.
- A foundation for integrating frontend frameworks (React, Angular, Vue) with a Node.js backend.
