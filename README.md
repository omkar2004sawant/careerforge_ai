# 🚀 CareerForge AI - Backend

> Backend API for CareerForge AI, an AI-powered career platform that provides resume analysis, ATS scoring, job matching, resume building, and interview preparation.

---

## 🌐 Live API

**Backend URL**

https://careerforge-ai-v1kl.onrender.com

---

## ✨ Features

- 🔐 Google OAuth Authentication
- 🔑 JWT Authentication
- 📄 AI Resume Analysis API
- 📊 ATS Score Generation
- 💼 AI Job Matching API
- 📝 AI Resume Builder API
- 🎯 AI Interview Preparation API
- ☁️ MongoDB Database Integration
- 💳 Razorpay Payment Integration
- ⚡ RESTful API Architecture

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- Google Gemini API
- Google OAuth
- JWT
- Razorpay
- Axios
- dotenv

---

## 📂 Project Structure

```text
backend
│
├── src
│   ├── config
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   └── index.ts
│
├── package.json
├── tsconfig.json
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/omkar2004sawant/careerforgeai-backend.git
```

### Navigate into the Project

```bash
cd careerforgeai-backend
```

### Install Dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

JWT_SEC=YOUR_SECRET_KEY

GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID

GOOGLE_CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

RAZORPAY_KEY_ID=YOUR_RAZORPAY_KEY_ID

RAZORPAY_KEY_SECRET=YOUR_RAZORPAY_KEY_SECRET
```

---

## ▶️ Run Development Server

```bash
npm run dev
```

---

## 📦 Build for Production

```bash
npm run build
```

---

## 🚀 Deployment

Backend is deployed on **Render**.

---

## 📡 API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/user/login` | Google OAuth Login |
| GET | `/api/user/me` | Get Logged-in User |

---

### AI Services

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/ai/analyse` | Resume Analysis |
| POST | `/api/ai/jobmatcher` | AI Job Matcher |
| POST | `/api/ai/resumebuilder` | Resume Builder |
| POST | `/api/ai/interviewprep` | Interview Preparation |

---

### Payment

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/payment/create-order` | Create Razorpay Order |
| POST | `/api/payment/verify` | Verify Payment |

---

## 🔒 Authentication

Protected routes require a JWT token.

Example:

```http
Authorization: Bearer YOUR_JWT_TOKEN
```

---

## 👨‍💻 Author

**Omkar Sawant**

- GitHub: https://github.com/omkar2004sawant
- LinkedIn: https://www.linkedin.com/in/osomkarsawant/

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.