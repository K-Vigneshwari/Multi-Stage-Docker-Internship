# Multi-Stage Docker Containerization & Optimization

## Project Overview

This project demonstrates a lightweight Flask web application containerized using a multi-stage Docker build, with PostgreSQL running through Docker Compose.

## Features

* Multi-stage Docker build
* Optimized application image: 77.2 MB
* Non-root application user
* Flask health-check endpoint
* PostgreSQL database service
* Persistent database volume
* Docker Compose orchestration

## Technologies

* Python
* Flask
* Docker
* Docker Compose
* PostgreSQL

## Run the Project

```bash
docker compose up --build -d
```

## Test the Application

Open these addresses in your browser:

* http://localhost:5000
* http://localhost:5000/health

## Stop the Project

```bash
docker compose down
```

The PostgreSQL named volume is preserved when using `docker compose down` without the `-v` option.
