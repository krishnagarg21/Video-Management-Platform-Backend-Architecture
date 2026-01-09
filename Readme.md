## 🎥 Video Management Platform — Backend System

A scalable backend system for a video-based platform, designed to handle **authentication, video uploads, subscriptions, and user interactions** with clean architecture and production-style practices.

Built with a focus on **API design, maintainability, and real-world backend patterns**.

---

### ✨ Technologies
- **Node.js**
- **Express.js**
- **MongoDB & Mongoose**
- **JWT Authentication**
- **Multer (file handling)**
- **Cloudinary (media storage)**

---

### 🚀 Features
- User authentication & authorization (JWT-based)
- Video upload and management pipeline
- Subscription system between users
- Structured error handling with custom API responses
- Modular MVC-based code organization
- Middleware-driven request flow (auth, uploads, async handling)

---

### 🧠 Architecture Overview
The project follows a **modular MVC-style structure** to keep concerns separated and the codebase easy to scale.

```
src/
├── controllers/     # Request handling logic
├── routes/          # API route definitions
├── models/          # Mongoose schemas
├── middlewares/     # Auth, file upload, async handlers
├── utils/           # Error handling, responses, helpers
├── db/              # Database connection
├── app.js           # Express app setup
└── index.js         # Server entry point
```

---

### 🔧 The Process
The goal was to build something **close to how real backend services are structured** rather than a simple CRUD app.

I focused on:
- Writing **clean, predictable APIs**
- Keeping business logic out of routes
- Centralized error & response handling
- Making the codebase easy to extend (new features, new routes)

This project helped me strengthen my understanding of **backend fundamentals, authentication flows, and scalable folder structures**.

---

### ▶️ Running the Project

1. Clone the repository  
   ```bash
   git clone <repo-url>
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Set up environment variables  
   ```
   PORT=
   MONGODB_URI=
   JWT_SECRET=
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   ```

4. Start the development server  
   ```bash
   npm run dev
   ```

---

### 📌 Notes
- This is a **backend-only project**
- APIs can be tested using **Postman**
- Frontend integration can be layered on top easily

---

### 👤 Author
**Krishna Garg**  
- LinkedIn: https://linkedin.com/in/krishna-garg21  
- Email: krishnagarga21@gmail.com
