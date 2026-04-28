# FASTAPI-DOCKER-GITHUB-ACTIONS

![CI/CD Pipeline](https://github.com/NandiniBansal16/fastapi-docker-github-actions/raw/main/assets/fastapi-docker-github-actions.png)
## Overview 🔮

Welcome to the FastAPI-Docker-GitHub-Actions Lab! This repository serves as an educational example of a CI/CD project that demonstrates the usage of GitHub Actions for deploying a simple FastAPI server. Key components include:

- Source Code: [Python Runtime](https://www.python.org)
- Dependency Management: [Python Poetry](https://python-poetry.org)
- Web Framework: [FastAPI](https://fastapi.tiangolo.com)
- Containerization Tools: [Docker](https://www.docker.com) and [Docker-Compose](https://docs.docker.com/compose/)
- Testing: [PyTest Framework](https://docs.pytest.org/) and [Coverage](https://coverage.readthedocs.io/en/latest/)
- Artifact Repository: [DockerHub](https://hub.docker.com)
- Continuous Integration/Continuous Delivery (CI/CD): [GitHub Actions](https://github.com/features/actions)

## Usage 👻

The core idea is to have a CI/CD pipeline that illustrates the automation with Continuous Integration, however, you can follow these steps to configure/run the project locally:

### Clone the repository

```bash
git clone https://github.com/NandiniBansal16/fastapi-docker-github-actions
cd fastapi-docker-github-actions
```

### Configure Python Dependencies with Poetry

Install [Poetry](https://python-poetry.org/docs/) then run:

```bash
poetry shell
poetry install
```

### Run the Server Locally with Uvicorn

```bash
poe fastapi-local
```

### Run the Server Locally with Docker-Compose

```bash
# Start the service
poe fastapi-docker-up

# Stop the service
poe fastapi-docker-down
```

### Run Unit Tests

```bash
poe test-unit
```

### Validate the Server

After running the server, try these REST API endpoints:

- `[GET]`: http://127.0.0.1:8000/
- `[GET]`: http://127.0.0.1:8000/status

## Special thanks

A big thank you to all the dedicated contributors who have made the open-source projects used in this repository possible.

## Author 🎹

### Nandini Bansal

This repository is built as a hands-on DevOps project demonstrating CI/CD with FastAPI, Docker, and GitHub Actions.

## LICENSE

Copyright 2024 Nandini Bansal
