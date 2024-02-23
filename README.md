# The-Fullstack

## Description

This project uses Docker to run multiple services including Redis, PostgreSQL, MongoDB, Tooljet, Percona, MSSQL, n8n, and NocoDB. Each service has its own dedicated data volume for persistence.

## Prerequisites

- Docker
- Docker Compose

## Setup

1. Clone the repository.
2. Copy the `.env.example` file to `.env` and fill in the necessary environment variables.

## Running the Project

To start all services, run the following command in the root directory of the project:

```sh
docker-compose up
```

This will start all the services as defined in the docker-compose.yml file. The services include:

Redis: A key-value database.
PostgreSQL: A relational database.
MongoDB: A NoSQL database.
Tooljet: An open-source data visualization tool.
Percona: A MySQL variant with advanced features.
MSSQL: Microsoft's SQL Server.
n8n: A workflow automation tool.
NocoDB: A NoSQL database.

Each service has its own dedicated data volume for persistence.

Stopping the Project
To stop all services, run the following command in the root directory of the project:
```ssh
docker-compose down
```

License
This project is licensed under the MIT License - see the LICENSE.md file for details