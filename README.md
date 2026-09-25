# ResumeRoast 🚀

## AI-Powered Resume Analysis & Career Platform

ResumeRoast is a full-stack AI-powered career platform designed to help students and job seekers improve their resumes and prepare for career opportunities.

The platform analyzes resumes against job requirements, generates personalized improvement suggestions, and provides AI-assisted career preparation features through a modern web interface.

---

## ✨ Features

- 📄 Resume upload and analysis
- 🎯 Resume and job-description matching
- 📊 Resume-job match score generation
- 💡 Personalized resume improvement suggestions
- 🤖 AI-powered career guidance
- 🎤 AI-assisted mock interview functionality
- 📈 User dashboard for accessing career-related results
- 🔐 User authentication
- ⚡ Real-time communication using Socket.IO
- 📱 Responsive and user-friendly interface

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- Tailwind CSS
- Axios
- React Router DOM
- Socket.IO Client

### Backend

- Node.js
- Express.js
- Socket.IO

### Database

- MongoDB
- Mongoose

### AI & Intelligent Search

- Google Gemini / Generative AI
- Pinecone

### Authentication & Utilities

- JSON Web Tokens (JWT)
- bcrypt
- Multer
- PDF parsing

### Development Tools

- Git
- GitHub
- VS Code

---

## 🏗️ Project Architecture

```text
ResumeRoast/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── ...
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── server.js
│   └── package.json
│
└── .gitignore
