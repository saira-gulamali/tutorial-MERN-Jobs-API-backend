# 06 - Jobs API App Backend

Taken from John Smilga - Node Course - Section 9 - Jobs API

## Description

Full stack App (API and React frontend) providing data for Jobs, with authenticated/protected routes.

This repo contains the backend only. For the frontend repo, refer to https://github.com/saira-gulamali/tutorial-MERN-Jobs-API-frontend

## Tech stack

### backend

- node
- express
- mongoose
- mongoDB
- nodemon
- express-async-errors
- express-rate-limit
- dotenv
- cors
- bcryptjs
- helmet
- http-status-codes
- joi
- jsonwebtoken
- rate-limiter
- swagger-ui-express
- xss-clean
- yamljs

## Usage

### backend

- npm install

- configure .env file with PORT, MONGO_URI & JWT_SECRET, JWT_LIFETIME & CORS

* PORT is the port the backend API server will run on
* MONGO_URI is the mongoDB database connection string (ensure to include the database name, username and password)
* JWT_SECRET is a 256-bit encryption key
* JWT_LIFETIME can be set to 30d
* CORS is the url of the frontend server

- npm start
- connect with postman to localhost:5000 or connect with frontend

#### API Documentation

- for api documentation run /documentation/redoc/redoc-static.html in browser

#### Routers

- /routes/auth.js
- /routes/jobs.js
