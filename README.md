# 💬 CodeAlpha Real-Time Chat App

A modern full-stack real-time chat application using MERN stack, Socket.io, Zustand, and TailwindCSS + DaisyUI — built to impress!

---

## 🌟 Tech Stack

| Frontend     | Backend        | Utilities              |
|--------------|----------------|------------------------|
| React + Vite | Express.js     | Zustand (global state) |
| TailwindCSS  | Node.js        | JWT (Auth)             |
| DaisyUI      | MongoDB Atlas  | Socket.io (realtime)   |
|              | Cloudinary API | Axios                  |

---

## ⚙️ Features

- ✅ **Signup/Login/Logout** with secure JWT cookies
- 🛡️ **Protected Routes** using custom middleware
- 🔄 **Real-Time Messaging** via Socket.io
- 🟢 **Online User Status** tracking
- 🖼️ **Image Upload Support** via Cloudinary
- 🌗 **Dark/Light Themes** with DaisyUI
- 📦 **Global State Management** with Zustand
- ⚠️ **Error Handling** on both client & server
- 🚀 **Deployable** on Render (Free Tier)

---

## 🧠 Setup .env file

Create a `.env` file in your `backend` directory:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```
## Build the app
```
npm run build
```
## Start the app
```
npm start
```
