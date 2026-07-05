# 💬 Codec Full-Stack Chat Application

<div align="center">

![MERN](https://img.shields.io/badge/MERN-Full%20Stack-success?style=for-the-badge)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Real--Time-black?style=for-the-badge&logo=socket.io)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**A modern real-time chat application built with the MERN Stack, featuring secure authentication, instant messaging, cloud image uploads, and a responsive user interface.**

</div>

---

## 🚀 Features

- 🔐 JWT Authentication
- 👤 User Registration & Login
- 🔒 Password Encryption using bcryptjs
- 💬 Real-Time Messaging with Socket.IO
- 🟢 Online / Offline User Status
- 👥 User Sidebar
- 🖼 Profile Picture Upload (Cloudinary)
- 📤 Image Message Support
- ⚡ Instant Message Delivery
- 🎨 Modern Responsive UI
- 🌙 Theme Management
- 📱 Mobile-Friendly Design
- 🔐 Protected API Routes
- ⚡ Global State Management with Zustand
- 🌐 RESTful Backend APIs

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- Zustand
- Socket.IO Client

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- bcryptjs
- Cloudinary
- Cookie Parser
- CORS
- dotenv

---

# 📁 Project Structure

```text
Codec_full-stack-chat-application
│
├── backend
│   ├── package.json
│   └── src
│       ├── controllers
│       │   ├── auth.controller.js
│       │   └── message.controller.js
│       │
│       ├── lib
│       │   ├── cloudinary.js
│       │   ├── db.js
│       │   ├── socket.js
│       │   └── utils.js
│       │
│       ├── middleware
│       │   └── auth.middleware.js
│       │
│       ├── models
│       │   ├── user.model.js
│       │   └── message.model.js
│       │
│       ├── routes
│       │   ├── auth.route.js
│       │   └── message.route.js
│       │
│       └── index.js
│
├── frontend
│   ├── public
│   │   ├── avatar.png
│   │   └── vite.svg
│   │
│   ├── src
│   │   ├── Pages
│   │   │   ├── HomePage.jsx
│   │   │   ├── LoginPage.jsx
│   │   │   ├── ProfilePage.jsx
│   │   │   ├── SettingsPage.jsx
│   │   │   └── SignUpPage.jsx
│   │   │
│   │   ├── components
│   │   │   ├── ChatContainer.jsx
│   │   │   ├── ChatHeader.jsx
│   │   │   ├── MessageInput.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── NoChatSelected.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   └── skeleton
│   │   │       ├── MessageSkeleton.jsx
│   │   │       └── SidebarSkeleton.jsx
│   │   │
│   │   ├── constants
│   │   ├── lib
│   │   ├── store
│   │   │   ├── useAuthStore.js
│   │   │   ├── useChatStore.js
│   │   │   └── useThemeStore.js
│   │   │
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
└── README.md
```

---

# ⚙ Installation

## Clone the Repository

```bash
git clone https://github.com/abhishek4712ak/Codec_full-stack-chat-application.git

cd Codec_full-stack-chat-application
```

---

## Install Backend Dependencies

```bash
cd backend
npm install
```

---

## Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **backend** directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

---

# ▶ Run the Project

### Start Backend

```bash
cd backend
npm run dev
```

### Start Frontend

```bash
cd frontend
npm run dev
```

Open your browser:

```
http://localhost:5173
```

---

# 🔐 Authentication Flow

```
Register/Login
      │
      ▼
JWT Token Generated
      │
      ▼
Stored in HTTP Cookie
      │
      ▼
Protected Routes
      │
      ▼
Authenticated User
```

---

# 💬 Real-Time Chat Flow

```
User A
   │
   ▼
Socket.IO Server
   │
   ▼
MongoDB
   │
   ▼
User B
```

---

# 📡 API Routes

## Authentication

```
POST   /api/auth/signup

POST   /api/auth/login

POST   /api/auth/logout

GET    /api/auth/check

PUT    /api/auth/update-profile
```

## Messages

```
GET    /api/messages/users

GET    /api/messages/:id

POST   /api/messages/send/:id
```

---

# 📸 Screenshots

Create a folder named:

```
screenshots/
```

Example:

```
screenshots/
├── login.png
├── signup.png
├── home.png
├── profile.png
├── settings.png
└── chat.png
```

---

# 🚀 Future Improvements

- ✅ Group Chats
- 🎥 Voice Calling
- 📹 Video Calling
- 😊 Emoji Picker
- 📎 File Sharing
- ✔ Read Receipts
- ⌨ Typing Indicator
- 🔔 Push Notifications
- 🌐 Multi-language Support
- 🤖 AI Chat Assistant

---

# 🤝 Contributing

Contributions are always welcome.

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/FeatureName
```

3. Commit your changes

```bash
git commit -m "Add Feature"
```

4. Push to GitHub

```bash
git push origin feature/FeatureName
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

**Abhishek Kumar Kushwaha**

- GitHub: https://github.com/abhishek4712ak

---

<div align="center">

### ⭐ If you like this project, don't forget to star the repository!

Made with ❤️ using the MERN Stack.

</div>
