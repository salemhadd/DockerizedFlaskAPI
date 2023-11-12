# Dockerized Flask API

This project is a Flask API Application containerized with Docker, utilizing PostgreSQL as the database.

## Prerequisites

- **Docker Desktop**: Install Docker Desktop on your Windows machine to run and manage containers.
  - Download Docker Desktop from [here](https://www.docker.com/products/docker-desktop) and follow the installation instructions.

## Usage

1. **Clone the Repository**:

    ```bash
    git clone  https://github.com/salemhadd/DockerizedFlaskAPI.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd dockerized-flask-api
    ```

3. **Build and Run Docker Containers**:

    ```bash
    docker-compose up
    ```

    The Flask API will be accessible at `http://localhost:5000`.

## API Endpoints

- `GET /users` - Retrieve all users
- `POST /users` - Create a new user
- `PUT /users/<id>` - Update a user by ID
- `DELETE /users/<id>` - Delete a user by ID

## Environment Variables

- `DB_URL`: Database connection URL

## Note

Ensure that PostgreSQL is running before starting the Flask application using Docker. Adjust the `DB_URL` environment variable to match your database connection settings.



