Intro to Backend 🚀

A beginner-friendly backend project built with Node.js, Express.js, and MongoDB to learn and implement RESTful APIs step by step.

This project covers the fundamentals of backend development, including server setup, database integration, user authentication, password hashing, and CRUD operations for posts.

✨ Features
🔐 Authentication

User registration API

User login API

User logout API

Password hashing for secure password storage

APIs tested and verified using Postman

📝 Post CRUD APIs

Create a new post

Get all posts

Update a post by ID

Delete a post by ID

APIs tested and verified using Postman

⚙️ Backend Setup

Express.js server configuration

MongoDB database integration using Mongoose

Environment variable configuration with .env

Organized folder structure with routes, controllers, and database configuration

Development server with Nodemon

🛠️ Tech Stack
Technology	Purpose
Node.js	JavaScript Runtime
Express.js	Backend Framework
MongoDB	Database
Mongoose	MongoDB ODM
bcrypt	Password Hashing
Postman	API Testing
Nodemon	Development Server
Git & GitHub	Version Control
📂 Project Structure
Backend Directory
backend/
├── src/
│   ├── config/
│   │   └── database.js
│   ├── controllers/
│   │   ├── user.controller.js
│   │   └── post.controller.js
│   ├── routes/
│   │   ├── user.route.js
│   │   └── post.route.js
│   ├── app.js
│   └── index.js
├── .env
├── package.json
└── README.md

🔗 API Endpoints
👤 User APIs
Method	Endpoint	Description
POST	/api/v1/users/register	Register a new user
POST	/api/v1/users/login	Login user
POST	/api/v1/users/logout	Logout user
📝 Post APIs
Method	Endpoint	Description
POST	/api/v1/posts/create	Create a new post
GET	/api/v1/posts	Get all posts
PUT	/api/v1/posts/:id	Update post by ID
DELETE	/api/v1/posts/:id	Delete post by ID
🚀 Getting Started
1. Clone the Repository
git clone <your-repository-url>

2. Navigate to the Backend Directory
cd backend

3. Install Dependencies
npm install

4. Configure Environment Variables

Create a .env file in the backend root directory:

PORT=4000
MONGODB_URI=your_mongodb_connection_string


Note: Never commit your .env file or expose your database credentials.

5. Start the Development Server
npm run dev


The server will run on:

http://localhost:4000

🧪 API Testing

All implemented APIs have been tested and verified using Postman.

Current API Testing

✅ Register

✅ Login

✅ Logout

✅ Create Post

✅ Get All Posts

✅ Update Post by ID

✅ Delete Post by ID

📌 Current Progress
Backend

 Backend server setup

 MongoDB connection

Authentication

 User registration API

 User login API

 User logout API

 Password hashing

Post CRUD

 Create Post API

 Get All Posts API

 Update Post by ID API

 Delete Post by ID API

Testing

 Postman API testing

Upcoming

 Additional validation and error handling

 More advanced backend features

🎯 Purpose

This project is developed for learning and practicing backend development with Node.js, Express.js, MongoDB, and REST APIs.

The project will continue to evolve as new backend concepts and features are implemented.

👨‍💻 Author
PCsujan

Built with ❤️ while learning backend development.