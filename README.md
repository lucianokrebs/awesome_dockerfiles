# Awesome dockerfiles

A curated list of dockerfiles and docker-compose files to be used as reference for popular programming languages (e.g:
golang, nodejs, python).

## List of contents:

- [Golang](#golang)
- [Python](#python)
- [React app](#react-app)

### Golang

- [Dockerfile](Dockerfile.golang)
- [docker-compose](docker-compose.golang.yml)

### Python

- [Dockerfile for FastAPI in production environment](Dockerfile.fastapi)
- [Dockerfile for FastAPI in development environment](Dockerfile.fastapi_dev)
- [docker-compose for FastAPI in development environment](docker-compose.fastapi.yml)

### React app

- [Dockerfile](Dockerfile.react_app)

---

### Docker cheat sheet

```shell
# basic commands
docker login
docker build . -t my-user/my-app:latest
docker run -p 8080:80 my-user/my-app:latest
docker push my-user/my-app:latest

docker ps
docker ps -a
docker run hello-world
docker run -it ubuntu bash

# clean up
docker system df
docker system prune
```

### Docker compose cheat sheet

```shell
docker compose up --build
docker compose up --build my-specific-service
docker compose up --build --force-recreate --remove-orphans
```
