# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**
- **MongoDB Docker Image**

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
