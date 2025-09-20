AI Virtual Assistant (JARVIS-style) — MERN + Gemini + Web Speech API

Live like it’s alive. Build your own JARVIS-style assistant with voice, AI thinking, authentication, and custom images.
This repository contains a full-stack MERN (MongoDB, Express, React, Node) project that uses Gemini AI for responses, Web Speech API for voice I/O, Cloudinary for image uploads, JWT + bcrypt for auth, and can be deployed to Render.

🚀 Features

Voice input (speech-to-text) and voice output (text-to-speech) using the Web Speech API

AI thinking/answers with Gemini (or configurable LLM API)

User authentication: Sign Up / Sign In (JWT + bcryptjs)

Upload custom assistant avatar (Cloudinary + Multer)

Customize assistant name / voice / image per user

Mobile responsive UI (React)

Full-stack: backend APIs (Express + Node), frontend (React)

Ready to deploy on Render (free tier instructions included)
/ (root)
├─ backend/                # Express server
│  ├─ controllers/
│  ├─ middlewares/
│  ├─ models/
│  ├─ routes/
│  ├─ utils/
│  ├─ package.json
│  └─ index.js (or server.js)
├─ frontend/               # React app (create-react-app / Vite)
│  ├─ src/
│  ├─ public/
│  └─ package.json
├─ .gitignore
└─ README.md

