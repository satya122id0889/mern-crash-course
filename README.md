MERN Crash Course Project 🚀
Overview
This repository contains the complete MERN stack crash course project, building a full-stack e-commerce application from scratch using MongoDB, Express, React, and Node.js. The project covers backend API development, frontend integration, authentication, and deployment essentials.

Features
RESTful API with Express.js

MongoDB database integration via Mongoose

User authentication with JWT

Product CRUD operations

Responsive React frontend

Environment variable management using dotenv

Deployment-ready setup

Installation & Setup
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/mern-crash-course.git
cd mern-crash-course
Backend setup:

bash
Copy
Edit
cd backend
npm install
Frontend setup:

bash
Copy
Edit
cd ../frontend
npm install
Environment variables:

Create a .env file inside the backend folder with the following keys:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
Run the application:

Start backend server:

bash
Copy
Edit
cd backend
npm run server
Start frontend:

bash
Copy
Edit
cd ../frontend
npm start
Access the app:
Open http://localhost:3000 in your browser.

Technologies Used
Node.js

Express.js

MongoDB & Mongoose

React.js

JWT Authentication

Axios for API requests

Bootstrap for UI styling
