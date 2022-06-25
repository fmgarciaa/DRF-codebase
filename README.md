# DRF-CODEBASE
------

This is a code base for projects with Django Rest Framework (DRF) and Docker. It is a simple setup to get started with your projects with these two technologies.

## Features
- It has environment variables (.env)
- The configuration (config.settings) of django is separated into base, local and production.
- Docker is configured with postgres

## Installation
It is easy to install the only requirement is to have **docker installed** on your machine and **create an .env file** with the data from the .env_template file. 

After creating the .env file run the following commands

The first one is:
- This command create the container with requeriments.txt and database (postgress).
    ```sh
    docker-compose build
    ```

Second is:
- This command run the database and server (port:8000)
    ```sh
    docker-compose up
    ```