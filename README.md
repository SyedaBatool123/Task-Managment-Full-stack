# 🚀 Task Manager - Full Stack Application

A complete task management system with user authentication and admin panel.

## ✨ Features
- User login/signup
- Add/Edit/Delete tasks
- Admin dashboard
- Responsive design
# 📝 Task Manager Application

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb)

A full-stack task management system with user authentication and admin privileges.

## ✨ Features
- ✅ User registration and login
- 🔐 JWT authentication
- 📋 Create, read, update and delete tasks
- 👨‍💻 Admin dashboard for user management
- 📱 Responsive design (works on mobile/desktop)

## 🚀 Installation

### Prerequisites
- Node.js (v16+)
- MongoDB Atlas account or local MongoDB
- Git

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/your-username/Task-Manager-FullStack.git
cd Task-Manager-FullStack

Backend Setup
cd backend
npm install
echo "MONGO_URI=mongodb://localhost:27017/taskmanager
JWT_SECRET=your_secret_key_here
PORT=5000" > .env
npm start

Frontend Setup
cd ../frontend
npm install
npm start

📂 Project Structure
Task-Manager-FullStack/
├── backend/          # Node.js + Express server
│   ├── models/       # MongoDB schemas
│   ├── routes/       # API endpoints
│   └── app.js        # Main server file
├── frontend/         # React application
│   ├── src/
│   │   ├── components/ # React components
│   │   └── App.js     # Main React component
└── README.md         # This file
