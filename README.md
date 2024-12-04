# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**
- **MongoDB Docker Image**

## Quick Setup

1. **Pull MongoDB Image**
   ```bash
   docker pull mongo
   ```

2. **Run docker-compose.yml**
   ```bash
   docker docker-compose up -d
   ```

## *installer 2 images*

### 1: Mongo Latex:
   * MongoDB

### 2: Mongo Expres:
   * Web Aplication


## Connecting to MongoDB

- **Using Shell**:
  ```bash
  docker exec -it mongodb-container mongosh -u admin -p password
  ```
- **Using GUI**:
  - Host: `8081`
  - Port: `27017`
  - Username: `admin`
  - Password: `password`

## Stopping/Removing Container

- Stop:
  ```bash
  docker stop mongodb-container
  ```
- Remove:
  ```bash
  docker rm mongodb-container
  ```
