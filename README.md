# 📱 Streamify – Fullstack Chat & Video Calling App  

A modern fullstack application that combines **real-time chat**, **1-to-1 & group video calls**, and a unique **language exchange experience for learners across globe** — all wrapped in a customizable UI with 30+ themes.  

---

## 📖 About the Project  
Streamify is built to showcase **scalable, production-grade technologies** while solving a real problem: enabling meaningful conversations across borders.  
It includes **real-time messaging**, **video streaming**, **authentication**, and **state management**, designed with a clean architecture that can grow into a real-world product.  

---

## ✨ Features  
- 💬 **Live Chat** with typing indicators & emoji reactions  
- 🎥 **Video Calls** (1-to-1 & groups) with screen sharing + recording  
- 🔐 **JWT Authentication** & protected rout
- 🌍 **Language Exchange Mode** with 32 unique UI themes  
- 🧠 **Global State Management** using Zustand  
- ⚡ **Reliable Data Fetching** with TanStack Query  
- 🚨 **Error Handling** on frontend & backend  
- 🚀 Deployable for free on **Render (backend)** & **Vercel (frontend)**  

---

## 🛠 Tech Stack  
**Frontend:** React (Vite), Zustand, TanStack Query, TailwindCSS, Stream SDK  
**Backend:** Node.js, Express, MongoDB Atlas, JWT  
**Infrastructure:** Render (API)

---

## ⚙️ Environment Variables  

Create `.env` files for both **backend** and **frontend**.  

### 🔹 Backend → `/backend/.env`  
```env
PORT=5001
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/streamify_db
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend environment (/frontend/.env)
VITE_STREAM_API_KEY=your_stream_api_key

### Backend (local)
# from repo root
cd backend

# install dependencies
npm install

# run in development (watch / nodemon if configured)
npm run dev
