# 📚 BookStore – MERN Stack Application

BookStore is a **full-stack MERN application** that allows users to browse books/courses, view free and paid content, and authenticate using a secure login/signup system.
The project is built with **MongoDB, Express.js, React.js, and Node.js**, featuring a modern UI powered by **Tailwind CSS**.

---

## 🚀 Features

### 🔐 Authentication

* User Signup & Login
* Password hashing using **bcryptjs**
* Auth state managed with **React Context API**
* Persistent login via **localStorage**

### 📘 Books / Courses

* Fetch books from MongoDB
* Free & Paid book categories
* Responsive book cards
* Carousel slider for free books

### 🎨 Frontend

* Built with **React + Vite**
* **Tailwind CSS** for styling
* Dark / Light theme toggle
* Protected routes

### ⚙️ Backend

* RESTful APIs using **Express**
* MongoDB integration using **Mongoose**
* Modular MVC folder structure
* CORS enabled for frontend-backend communication

---

## 🗂️ Project Structure

```
BookStore
│
├── Backend
│   ├── controller
│   │   ├── book.controller.js
│   │   └── user.controller.js
│   ├── model
│   │   ├── book.model.js
│   │   └── user.model.js
│   ├── route
│   │   ├── book.route.js
│   │   └── user.route.js
│   ├── index.js
│   └── package.json
│
├── Frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── context
│   │   ├── courses
│   │   ├── home
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── package.json
│
└── README.md
```

---

## 🧩 Tech Stack

**Frontend**

* React.js
* Vite
* Tailwind CSS
* Axios
* React Router DOM
* React Hook Form
* React Hot Toast
* Slick Carousel

**Backend**

* Node.js
* Express.js
* MongoDB
* Mongoose
* bcryptjs
* dotenv
* cors

---

## 📌 Future Enhancements

* JWT-based authentication
* Admin dashboard
* Book purchase & payment gateway
* Search & filter functionality
* Pagination
