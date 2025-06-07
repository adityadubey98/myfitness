


# 🏋️‍♂️ Fitness Tracker Web App

A modern and responsive MERN stack web application that empowers users to manage and monitor their fitness goals. This app helps you track workouts, set goals, and stay motivated — whether you're a beginner or a seasoned athlete.

## 🌐 Live Site

👉 [https://fitnesstrackeradi.netlify.app/](https://fitnesstrackeradi.netlify.app/)

---

## ✨ Project Overview

The Fitness Tracker is designed to bring structure and motivation to users’ fitness journeys. It allows users to register and log in securely, add and manage workouts, and view progress at a glance. Built with React for a dynamic frontend and powered by a robust Express and MongoDB backend, the app delivers a seamless full-stack experience.

---
---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/9e0d31ab-ed5c-4727-810f-24ac72fe86b6)
![image](https://github.com/user-attachments/assets/146b585b-0c83-4c7f-87c2-f57466f6f4d1)


---
## 🔥 Key Features

- 👤 **User Authentication** — Secure login and registration using JWT tokens.
- 📆 **Workout Management** — Log workouts including title, load, and reps.
- 🧠 **Progress Visualization** — Easily monitor how your workouts evolve over time.
- 📱 **Responsive Design** — Fully optimized for desktop, tablet, and mobile screens.
- 🔐 **Secure Data Handling** — All sensitive data encrypted and managed through secure APIs.
- 🧩 **Modular Codebase** — Clear separation of concerns using MVC principles.

---

## 🧰 Tech Stack

### 🚀 Frontend

- React.js
- Context API / Redux (if used)
- CSS or Material-UI for styling
- Axios for API requests

### 🛠️ Backend

- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- bcrypt for hashing passwords
- dotenv for environment management

### 🧪 Dev Tools

- Nodemon (for local dev)
- ESLint & Prettier (for code consistency)
- Postman (for API testing)

---

## 📁 Project Structure

```plaintext
myfitness/
│
├── client/                 # React frontend
│   ├── components/         # Reusable UI components
│   ├── pages/              # Route-based pages (Login, Dashboard, etc.)
│   └── App.js
│
├── server/                 # Node.js backend
│   ├── controllers/        # Logic for route handling
│   ├── models/             # Mongoose data models
│   ├── routes/             # Express route handlers
│   └── index.js
│
├── .env                    # Environment variables
├── README.md
└── package.json

