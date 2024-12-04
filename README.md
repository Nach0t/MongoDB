# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**
- **MongoDB Docker Image**

## Quick Setup

1. **Run docker-compose.yml**
   ```bash
   docker docker-compose up -d
   ```

## *installer 2 images*

### 1: Mongo Latex:
   * Mongo

### 2: Mongo Expres:
   * Web Aplication


# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**: Install from [here](https://www.docker.com/products/docker-desktop/).
- **MongoDB Docker Image**: Official MongoDB image from Docker Hub.

## Quick Setup

1. **Pull MongoDB Image**
   ```bash
   docker pull mongo
   ```

2. **Run MongoDB Container**
   ```bash
   docker run -d \
     --name mongodb-container \
     -p 27017:27017 \
     -e MONGO_INITDB_ROOT_USERNAME=admin \
     -e MONGO_INITDB_ROOT_PASSWORD=password \
     mongo
   ```

3. **Verify Container**
   ```bash
   docker ps
   ```

## Connecting to MongoDB

### Windows

- **Using CMD**:
  ```bash
  docker exec -it mongodb-container mongosh -u admin -p pass
  ```
- **Using GUI**:
  - Host: `8081`
  - Port: `27017`
  - Username: `admin`
  - Password: `pass`

### Linux

- **Using Terminal**:
  ```bash
  docker exec -it mongodb-container mongosh -u admin -p pass
  ```
- **Using GUI**:
  - Host: `8081`
  - Port: `27017`
  - Username: `admin`
  - Password: `pass`

## Stopping/Removing Container

- Stop:
  ```bash
  docker stop mongodb-container
  ```
- Remove:
  ```bash
  docker rm mongodb-container
  ```
