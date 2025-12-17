# Login & Signup Authentication System

A full-stack authentication system built using **HTML, CSS, JavaScript, Node.js, Express, and MongoDB**.  
This project demonstrates secure user registration and login with password hashing.

---

## 🚀 Features

- User Registration (Signup)
- User Login
- Password hashing using bcrypt
- REST API architecture
- MongoDB database integration
- Clean UI with animated login/signup toggle

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- bcryptjs
- dotenv
- CORS

---

## 📂 Project Structure

login-signup-app/
├── backend/
│ ├── models/
│ │ └── user.js
│ ├── routes/
│ │ └── auth.js
│ ├── .env
│ ├── server.js
│ └── package.json
│
├── frontend/
│ └── public/
│ ├── index.html
│ ├── form1.css
│ └── from1.js
│
├── .gitignore
└── README.md

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/login-signup-app.git
cd login-signup-app
2️⃣ Install Backend Dependencies
bash
Copy code
cd backend
npm install
3️⃣ Configure Environment Variables
Create a .env file inside backend/:

ini
Copy code
MONGO_URI=mongodb://127.0.0.1:27017/loginApp
PORT=5001
4️⃣ Run the Server
bash
Copy code
npm run dev
Server will start at:

arduino
Copy code
http://localhost:5001
🔗 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	Login user
GET	/api/auth/all	Get all users (test)

📌 Future Improvements
JWT authentication

Protected routes

Password reset functionality

Email verification

Frontend framework (React)

👤 Author
Developed by Divyansh

---

## 6. Ready for GitHub Upload

```bash
git init
git add .
git commit -m "Initial commit - Login Signup App"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
