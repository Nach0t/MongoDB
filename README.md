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
   docker docker-compose up
   ```

## Connecting to MongoDB

- **Using Shell**:
  ```bash
  docker exec -it mongodb-container mongosh -u admin -p password
  ```
- **Using GUI**:
  - Host: `localhost`
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
