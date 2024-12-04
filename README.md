
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
    ```bash
      localhost:8081
   ```

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
