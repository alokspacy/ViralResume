<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:2F4A3A,50:5B7C6A,100:8FB39C&text=Viral%20Resume&fontColor=ffffff&fontSize=65&animation=fadeIn&fontAlignY=40"/>
</p>

<p align="center">
  <h1 align="center">🚀 Viral Resume</h1>
  <p align="center">
    AI-Powered Resume Optimization Platform
  </p>
  <p align="center">
    Improve ATS Scores • Optimize Resume Content • Get More Interviews
  </p>
</p>

<p align="center">
  <a href="https://viral-resume.vercel.app">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-Viral_Resume-success?style=for-the-badge">
  </a>
  <img src="https://img.shields.io/github/stars/alokspacy/ViralResume?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/alokspacy/ViralResume?style=for-the-badge">
  <img src="https://img.shields.io/github/license/alokspacy/ViralResume?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-blue?style=flat-square&logo=react">
  <img src="https://img.shields.io/badge/Vite-Frontend-purple?style=flat-square&logo=vite">
  <img src="https://img.shields.io/badge/Node.js-Backend-green?style=flat-square&logo=node.js">
  <img src="https://img.shields.io/badge/Express.js-API-black?style=flat-square&logo=express">
  <img src="https://img.shields.io/badge/MongoDB-Atlas-success?style=flat-square&logo=mongodb">
  <img src="https://img.shields.io/badge/Gemini-AI-orange?style=flat-square&logo=google">
  <img src="https://img.shields.io/badge/TailwindCSS-UI-38BDF8?style=flat-square&logo=tailwindcss">
</p>

---

# 📖 Overview

Viral Resume is an AI-powered resume optimization platform built to help candidates improve their resumes for modern Applicant Tracking Systems (ATS).

The platform analyzes resumes, identifies weaknesses, detects missing keywords, and generates AI-powered improvements that increase the chances of landing interviews.

Whether you're a student, software engineer, designer, or experienced professional, Viral Resume helps transform ordinary resumes into ATS-friendly resumes.

---

# ✨ Features

| Feature | Description |
|----------|-------------|
| 📄 ATS Analysis | Analyze resume compatibility with ATS systems |
| 🤖 AI Resume Rewrites | Generate stronger resume bullet points using Gemini AI |
| 🔍 Keyword Matching | Detect missing and matched job-specific keywords |
| 📊 ATS Score Tracking | Monitor ATS score improvements over time |
| 📚 Resume Versioning | Track multiple versions of resumes |
| 📈 Dashboard Analytics | Visualize progress and performance |
| 🔐 Secure Authentication | JWT + HTTP-only cookie sessions |
| ⚡ Real-Time Insights | Instant analysis and recommendations |
| 📂 Resume Management | Upload, organize and manage resumes |
| 🎯 Resume Optimization | Actionable suggestions for improvement |

---

# 🏗 Architecture

```text
                 ┌────────────────────┐
                 │     Frontend       │
                 │    React + Vite    │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │    Express API     │
                 │   Node.js Backend  │
                 └─────────┬──────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                                 ▼

 ┌─────────────────┐             ┌─────────────────┐
 │  MongoDB Atlas  │             │   Gemini AI     │
 │ User & Resume   │             │ Resume Analysis │
 │     Storage     │             │ & Optimization  │
 └─────────────────┘             └─────────────────┘
```

---

# 🛠 Technology Stack

## Frontend

- React.js
- Vite
- React Router
- Axios
- Tailwind CSS
- Framer Motion
- Lucide React

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- Zod Validation
- Rate Limiting

## Artificial Intelligence

- Google Gemini API
- Gemini 2.5 Flash

## Deployment

- Vercel
- Render
- MongoDB Atlas

---

# 📂 Project Structure

```text
ViralResume
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── api
│   │   ├── assets
│   │   ├── components
│   │   ├── context
│   │   ├── hooks
│   │   ├── pages
│   │   └── routes
│   ├── package.json
│   └── vite.config.js
│
├── backend
│   ├── src
│   │   ├── config
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   └── utils
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

# 🚀 Live Deployment

| Service | URL |
|----------|-----|
| Frontend | https://viral-resume.vercel.app |
| Backend API | https://viral-resume-backend.onrender.com |
| Database | MongoDB Atlas |
| AI Provider | Google Gemini |

---

# ⚙️ Environment Variables

## Backend (.env)

```env
NODE_ENV=production

PORT=8000

MONGO_URI=

JWT_SECRET=

JWT_EXPIRES_IN=7d

COOKIE_NAME=arr_token

CLIENT_ORIGIN=https://viral-resume.vercel.app

GEMINI_API_KEY=

GEMINI_MODEL=gemini-2.5-flash
```

## Frontend (.env)

```env
VITE_API_URL=https://viral-resume-backend.onrender.com/api
```

---

# 💻 Local Development

## Clone Repository

```bash
git clone https://github.com/alokspacy/ViralResume.git

cd ViralResume
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## Backend Setup

```bash
cd backend

npm install

npm run dev
```

Backend runs on:

```text
http://localhost:8000
```

---

# 🎯 Roadmap

- [ ] Resume Templates
- [ ] Cover Letter Generator
- [ ] LinkedIn Profile Import
- [ ] Job Description Matching
- [ ] AI Interview Preparation
- [ ] Resume Sharing Links
- [ ] Team Collaboration
- [ ] Resume Benchmarking
- [ ] Export to Multiple Formats
- [ ] Chrome Extension

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 👨‍💻 Author

### Alok Singh

- GitHub: https://github.com/alokspacy

---

# ⭐ Support

If you found this project useful, please consider giving it a star.

```text
⭐ Star the repository to support future development.
```

---

<p align="center">
  Built with ❤️ using React, Node.js, MongoDB and Gemini AI
</p>

<p align="center">
  © 2026 Viral Resume
</p>
