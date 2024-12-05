
# MongoDB Docker Project

## Prerequisites

- **Docker Desktop**

## Quick Setup

1. **Run docker-compose.yml**
   
   ```bash
   docker docker-compose up -d
   ```
   
## *Images to install*

### 1: Mongo:
   * Mongo database

### 2: Mongo Express:
   * Mongo database interface

   ```bash
localhost:8081
```  
Use in your browser to connect to interface

### Windows

- **Using CMD**:
  ```bash
  docker exec -it mongo-server mongosh -u admin -p pass
  ```
- **Using GUI**:
  - Host: `8081`
  - Port: `27017`
  - Username: `admin`
  - Password: `pass`

- **Using Visual studio code**:
  - Install MongoDB extension
  - Connect to localhost:27017
  - Create a .mongodb file in your proejct directory

Then you can start coding.
    
### Linux

- **Using Terminal**:
  ```bash
  docker exec -it mongo-server mongosh -u admin -p pass
  ```
- **Using GUI**:
  - Host: `8081` 
  - Port: `27017`
  - Username: `admin`
  - Password: `pass`

Then you can start coding.
## Stopping/Removing Container

- Stop:
  ```bash
  docker stop mongo-server mongo-client
  ```
- Remove:
  ```bash
  docker rm mongo-server mongo-client
  ```
