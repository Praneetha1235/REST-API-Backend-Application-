# REST API Backend Application

A RESTful backend application built using Node.js and Express.js, implementing
core backend concepts such as request handling, input validation, and centralized
error management in a simple and scalable structure.

## Features
- RESTful API endpoints
- Input validation using Joi
- Centralized error handling
- Clean and maintainable backend logic
- In-memory data handling for simplicity

## Tech Stack
Node.js | Express.js | REST APIs | Input Validation | Error Handling

## Project Structure
This project is implemented in a single file to focus on core backend principles.
The logic is modular and can be easily refactored into a layered architecture
(controllers, services, middlewares) as the application scales.

## API Endpoints

### Create User
**POST** `/api/users`  
Request Body:
```json
