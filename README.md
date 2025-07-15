# 💬 Real-Time Chat App

A full-stack real-time chat application built with **React.js**, **Node.js**, **Express**, **Socket.IO**, and **MongoDB**, allowing users to exchange messages instantly with a smooth and secure experience. 

---

## 🌟 Features

- 🔐 **JWT Authentication** — Secure login system using JSON Web Tokens
- 🟢 **Online Presence** — Real-time feedback using Socket.IO events
- 📌 **Message Persistence** — Messages saved in MongoDB with full chat history
- 🎨 **Responsive Design** — mobile/tablet support
- 🔒 **Message Encryption** — Data is encrypted in transit and at rest using CryptoJS
- 🧰 **Scalable Architecture** — Socket clustering support via Redis and PM2
- 🖼️ **Media Sharing** — Image upload support using Cloudinary

---

## 🛠️ Tech Stack

### Frontend:
- React.js
- Tailwind CSS
- Context API or Redux (if applicable)
- Axios

### Backend:
- Node.js
- Express.js
- Socket.IO
- MongoDB + Mongoose

### Auth & Security:
- JWT
- Bcrypt.js
- CryptoJS

### Additional Tools:
- Redis (for socket clustering and scaling)
- PM2 (for process management in production)
- Cloudinary (media upload & storage)

---

## 📦 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/KIRTI2901/chat-app.git
cd chat-app

Install backend dependencies
cd server
npm install

Install frontend dependencies
cd ../client
npm install

Set up environment variables
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

Start the backend server:
cd server
npm run server

Start the frontend:
cd ../client
npm run dev

Visit: http://localhost:5173





