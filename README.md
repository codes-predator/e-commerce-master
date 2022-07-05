# E-Commerce

## Problem

```
Develop a front-end page for an e-commerce application. Build a blog site with the following elements:
  - A front-end to display the blog.
  - A database to store the content.
  - CRUD Operations

Create a GitHub repository and push the code of the above two questions.
```


## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:codes-predator/e-commerce.git
$ cd e-commerce
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/e-commerce
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password
- Run this on chrome: http://localhost:5000/api/products/seed
- It creates 6 sample products

### 6. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin