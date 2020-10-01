## Docker Compose to run 2 (or more) containers: Express.js and MongoDB

---

### Establish connection to Mongo and write APIs 
The `index.js` file contains the CRUD APIs to add and retrieve 
the data from MongoDB
![](index.jpg)

### Design the database schema
`Items.js`
![](Items.jpg)

### Create a simple HTML view
`index.ejs`
![](ejs.jpg)

### Create a Dockerfile
`Dockerfile`
![](Dockerfile.jpg)

### Create a docker-compose.yml file
A docker-compose yml file is required to run 2 or more containers.
To link the Express container with the MongoDB container, 
use the keyword: `link`

`docker-compose.yml`
![](docker-compose.jpg)

---

Steps to run:

### 1: Get Source

`git clone https://github.com/franktanah/docker-api-mongoDB`

### 2: Change directory

`cd docker-api-mongoDB`

### 3: Run Docker Compose

`docker-compose up`

### 4: Add data to the database 

`website address: localhost:80`

There is a frontend interface with a textbox and a "Add" button
to add items to the database - if everything runs successfully

