# 💞 LoveNotes – Proyecto MERN
---

## 🧠 Descripción

---

LoveNotes es una aplicación web desarrollada con la pila MERN (MongoDB, Express, React, Node.js).
Permite que dos personas compartan mensajes, fotos o recuerdos de forma privada y personalizada.

---

## ⚙️ Requerimientos del sistema

---

🖥️ Software necesario

Node.js v18 o superior

npm o yarn (gestor de paquetes)

MongoDB (local o en la nube con MongoDB Atlas)

Git (para control de versiones)

Editor de código recomendado: VS Code

---

## 📦 Dependencias principales

---

Backend (Node + Express)
npm install express mongoose cors dotenv
npm install --save-dev nodemon

---

Frontend (React)
npm install react react-dom axios
npm install --save-dev vite

---

## 🧩 Estructura recomendada

---

LoveNotes/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   └── controllers/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md

---

## 🚀 Comandos básicos

---

Iniciar el backend
cd backend
npm run dev

Iniciar el frontend
cd frontend
npm run dev

---

## 🔒 Variables de entorno (.env)

---

PORT=5000
MONGO_URI=tu_url_de_mongodb