# SpendWise
A simple Node.js, Express, and MongoDB backend project for students to learn JWT authentication and basic CRUD operations.

Project Instruction
SpendWise is a backend-only project built using Node.js and Express.
Quick Start:
npm init
npm install
npm run dev

Steps to Create the Project:
●	Choose or create a directory for the backend project.

●	Open terminal and navigate to that directory.

●	Initialize Node.js project using npm init.

●	Install required packages: express, mongoose, jsonwebtoken, bcrypt, cors, dotenv.

●	Create folders: models, routes, controllers, middleware, config.

●	Start the server using npm run dev.

●	Test APIs using Postman or Thunder Client at http://localhost:5000.

Pre-requisites:

Software Requirements

Software	Purpose

Node.js	JavaScript runtime for backend

MongoDB	NoSQL database for data storage

npm	Package manager

Git	Version control system

Code Editor	VS Code or similar

Technical Architecture

Backend Architecture (Node.js + Express)

●	Controllers: Handle business logic for authentication and CRUD

●	Models: Mongoose schemas for User and Transaction

●	Routes: API endpoints for auth and CRUD operations

●	Middleware: JWT verification and request protection

●	Configuration: Database connection and environment variables


Database Architecture (MongoDB)

●	Users Collection:

 _id, name, email, password (hashed), createdAt
 
●	Transactions Collection:

 _id, userId (FK), title/description, amount/value, createdAt
 
●	Relationship:

 Many Transactions belong to One User



