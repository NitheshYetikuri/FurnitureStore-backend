# FurnitureStore Backend

## Description
The `FurnitureStore-backend` is a Java-based backend application for an e-commerce furniture store. This project leverages Spring Boot, JWT for authentication, MySQL for the database, and JPA for data persistence. It provides a robust and scalable backend solution for managing furniture store operations.

## Features
- **Spring Boot**: Framework for building the backend application.
- **JWT Authentication**: Secure authentication mechanism using JSON Web Tokens.
- **MySQL Database**: Relational database for storing application data.
- **JPA**: Java Persistence API for managing database interactions.
- **Maven**: Project management and build automation tool.
- **Lombok**: Library to reduce boilerplate code.
- **CORS Setup**: Configured Cross-Origin Resource Sharing for secure API access.

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/NitheshYetikuri/FurnitureStore-backend.git
   cd FurnitureStore-backend
   ```

2. **Configure the database**:
   - Ensure MySQL is installed and running.
   - Create a database named `furniture_store`.
   - Update the `application.properties` file with your MySQL credentials.

3. **Set up CORS**:
   - Ensure CORS is configured in your Spring Boot application to allow secure API access from different origins.

## Frontend
For the frontend of this application, please check the FurnitureStore-frontend repository, which is built using Angular.
