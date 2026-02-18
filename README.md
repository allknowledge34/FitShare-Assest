# 🚀 FitShare – Production-Ready Fitness Social App

FitShare is a full-stack fitness-focused social media application built using **React Native (Expo)** and the **MERN stack**.  

Inspired by platforms like Twitter, FitShare allows users to share fitness routines, experiences, and progress with a clean, modern UI and scalable backend architecture.

This project demonstrates how real production mobile apps are built from scratch.

---

![Demo App](Mobile/assets/images/maxresdefault-21.jpg)

---

## 📱 Tech Stack

### 🔹 Mobile
- React Native (Expo)
- JavaScript
- Zustand / Context API (State Management)
- React Navigation

### 🔹 Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### 🔹 Cloud Services
- Cloudinary (Image Upload & Storage)
- REST API Architecture

---

## ✨ Key Features

- 🏋️ Social Fitness Feed (Image posts with title, level & description)
- ❤️ Like & Comment System
- 🔁 Share to WhatsApp, Twitter, etc.
- 🔐 Authentication (Signup / Login)
- 👤 Profile Page with User Posts
- 🗑 Create & Delete Posts
- 🔔 Real-Time Notifications (Likes & Comments)
- ⚙ Settings Page (Privacy Policy & Terms)
- 📂 Separate Backend & Mobile Architecture
- 🧱 Scalable Folder Structure
- 🎨 Clean, Production-Level UI Design

---

## 🏗 Architecture Overview

FitShare follows a scalable architecture:

- Mobile app communicates with REST API
- Backend handles authentication & database operations
- Images are uploaded to Cloudinary
- MongoDB stores user & post data
- JWT used for secure authentication

---

## 📂 Project Structure

FitShare/
│
├── backend/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── controllers/
│ └── server.js
│
├── mobile/
│ ├── components/
│ ├── screens/
│ ├── navigation/
│ ├── store/
│ └── App.js
---
## 📁 .env Setup

### ⚙️ Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=<YOUR_MONGO_DB_URI>
JWT_SECRET=<YOUR_VERY_HARD_TO_FIND_SECRET>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

API_URL=<YOUR_DEPLOYED_API_URL>
```
### ⚙️ Mobile (`/mobile`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>

EXPO_PUBLIC_API_URL=<your_backend_api_url>
```

## ⚙️ Run the backend

```bash
cd backend
npm install
npm run dev

```

## 📱 Run the mobile

```bash
cd mobile
npm install
npx expo start
```
---

## 🎯 Use Cases
✔ Resume projects
✔ Hackathons
✔ AI demos
✔ Full stack practice
✔ Startup MVP

---
## 🤝 Contributing
Contributions are welcome.

---
## ⭐ Support
If you found this project useful, give it a star ⭐
