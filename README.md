🔐 Login & Signup Authentication System
A full-stack authentication system built with HTML, CSS, JavaScript, Node.js, Express, and MongoDB.
This project implements secure user registration and login with password hashing using bcrypt. It’s designed with a clean, user-friendly interface and modern backend architecture.

🚀 Features:

📝 User registration (Signup)

🔑 User login

🔒 Password hashing with bcrypt

⚙️ RESTful API architecture

🗄️ MongoDB integration with Mongoose

💡 Environment variables using dotenv

💬 CORS support for cross-origin requests

🎨 Clean and animated UI for toggling between login and signup

🧰 Tech Stack:

🖥️ Frontend-

HTML5

CSS3

Vanilla JavaScript

⚙️ Backend-

Node.js

Express.js

MongoDB

Mongoose

bcryptjs

dotenv

CORS

📁 Project Structure
```
login-signup-app/

├── backend/

│   ├── models/

│   │   └── user.js

│   ├── routes/

│   │   └── auth.js

│   ├── .env

│   ├── server.js

│   └── package.json
│
├── frontend/

│   └── public/

│       ├── index.html

│       ├── form1.css

│       └── form1.js
│
├── .gitignore

└── README.md
```

⚙️ Setup Instructions
```
1️⃣ Clone the Repository

git clone https://github.com/yourusername/login-signup-app.git
cd login-signup-app

2️⃣ Install Backend Dependencies

cd backend
npm install

3️⃣ Configure Environment Variables

Create a .env file inside the backend/ directory and add the following:
MONGO_URI=mongodb://127.0.0.1:27017/loginApp
PORT=5001

4️⃣ Start the Server

npm run dev
Server will run at:
http://localhost:5001
```

🔗 API Endpoints

Method	Endpoint	Description

POST	/api/auth/register	Register a new user

POST	/api/auth/login	Login an existing user

GET	/api/auth/all	Retrieve all users (for testing)

🧩 Future Improvements:

  🔐 JWT-based authentication

  🧱 Protected routes

  🔁 Password reset feature

  ✉️ Email verification

  ⚛️ Frontend integration with React

👤 Author

Developed by: Divyansh
💻 Passionate about full-stack web development and secure applications.
```
🗃️ GitHub Upload Commands

git init

git add .

git commit -m "Initial commit - Login Signup App"

git branch -M main

git remote add origin <your-repo-url>

git push -u origin main
```
