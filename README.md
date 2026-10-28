<img width="1355" height="598" alt="EcoNexus1" src="https://github.com/user-attachments/assets/b2f5eaf4-35d9-44a2-af6d-7b89154a774b" />
<img width="1350" height="600" alt="EcoNexus2" src="https://github.com/user-attachments/assets/d6d03a2e-c454-43ce-922f-cb2c7ab7faae" />
 
 # eco-innovation
# 🌱 Eco Innovation Platform

A full-stack web application that enables users to **share, explore, and manage eco-friendly ideas** aimed at solving environmental challenges.
The platform encourages innovation in sustainability by providing a collaborative space for green initiatives.

---

# 🚀 Features

* 🔐 User Authentication (Register / Login)
* 🌍 Submit eco-friendly innovation ideas
* 📊 Personal dashboard for managing ideas
* 🛡 Protected routes using authentication
* 💡 Organized idea management system
* 🎨 Responsive and modern UI

---

# 🏗️ Project Architecture

```
eco-innovation-platform
│
├── client/                     # React Frontend
│   ├── src/
│   │   ├── auth/               # Authentication logic
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # App pages
│   │   ├── services/           # API requests
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/                     # Node.js Backend
│   ├── controllers/            # Business logic
│   ├── middleware/             # Authentication middleware
│   ├── models/                 # MongoDB schemas
│   ├── routes/                 # API endpoints
│   └── index.js
│
└── README.md
```

---

# 🛠️ Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* React Router
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* dotenv

---

---

# Backend Setup

```
cd server
npm install
```

Run backend:

```
npm run dev
```

or

```
node index.js


```

---

# Frontend Setup

Open a new terminal:

```
cd client
npm install
```

Create `.env` inside `client`:

```
VITE_API_URL=http://localhost:8080
```

Run frontend:

```
npm run dev
```

---

# 🔒 Environment Variables

### Server

```
PORT=
MONGO_URI=
JWT_SECRET=
---



# 🌍 Deployment

Recommended deployment stack:

Frontend: **Vercel**
Backend: **Render / Railway**
Database: **MongoDB Atlas**

---


