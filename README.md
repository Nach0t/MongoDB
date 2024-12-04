
# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**

## Quick Setup

1. **Run docker-compose.yml**
   
   ```bash
   docker docker-compose up -d
   ```
   
## *installer 2 images*

### 1: Mongo:
   * Mongo

### 2: Mongo Express:
   * Web aplication for database interface
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
  docker stop mongo-server mongo-client
  ```
- Remove:
  ```bash
  docker rm mongo-server mongo-client
  ```
