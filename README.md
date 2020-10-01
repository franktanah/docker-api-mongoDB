## Docker Compose to run 2 (or more) containers: Express.js and MongoDB

A docker-compose yml file is required to run 2 containers.
To link the Express container with the MongoDB container
using the keyword: `link`

An index.js file contains the CRUD APIs to retrieve the data from
the MongoDB

Steps to run:

### 1: Get Source

`git clone https://github.com/franktanah/docker-api-mongo`

### 2: Change directory

`cd docker-api-mongo`

### 3: Run Docker Compose

`docker-compose up`  
