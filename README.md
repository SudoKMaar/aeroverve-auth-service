# AeroVerve - Auth Microservice

Welcome to the AeroVerve Auth Microservice repository! This microservice handles user authentication and authorization for the AeroVerve airline booking system.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

AeroVerve Auth Microservice is an integral part of the AeroVerve airline booking system, providing secure user authentication and authorization. It's designed using the MVC architecture and utilizes Express.js, Sequelize, and JWT for smooth operation.

## Features

- User registration and authentication
- JSON Web Token (JWT) based user session management
- Password hashing using bcrypt
- Role-based authorization with fine-grained control
- Validation and error handling for reliable user input

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SudoKMaar/flight-auth-service.git
   cd flight-auth-service
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up the configuration:

   Copy the `.env.example` file to `.env` and provide necessary environment variables.

4. Start the microservice:

   ```bash
   npm start
   ```

## Configuration

The microservice requires certain environment variables to run. You can configure them in the `.env` file:

- `PORT`: Port on which the microservice will run.
- `DB_URI`: URI of the database for storing user data.
- `JWT_KEY`: Secret key used for JWT encryption.

## Usage

To use the AeroVerve Auth Microservice, you can make HTTP requests to its API endpoints. Refer to the [API Endpoints](#api-endpoints) section below for detailed information.

## API Endpoints

- **POST /api/signup**: Create a new user account.
- **POST /api/signin**: Authenticate a user and generate a JWT token.
- **GET /api/isAuthenticated**: Check if a user's JWT token is valid and authenticated.
- **GET /api/isAdmin**: Check if a user has admin privileges.

For detailed request and response examples, refer to the source code or API documentation.

## Contributing

We welcome contributions from the community! To contribute to the AeroVerve Auth Microservice:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to your branch: `git push origin feature-name`
5. Create a pull request to the `main` branch of this repository.

Before submitting a pull request, ensure that your code is well-tested and adheres to the existing code style and conventions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

AeroVerve - Elevating Flight Booking Experiences
