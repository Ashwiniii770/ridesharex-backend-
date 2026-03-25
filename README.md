# 🚖 RideShareX Backend

A scalable backend for a **Ride Sharing Application** built using **Node.js, Express.js, and MongoDB**.
This project handles user management, ride booking, and backend operations for a ride-sharing platform.

---

## 📌 Project Overview

RideShareX Backend provides APIs for managing ride-sharing operations such as user registration, ride booking, and ride management.

It demonstrates backend development concepts like:

* REST API Development
* Database Integration
* MVC Architecture
* Authentication Handling

---

## 🚀 Features

* 👤 User Registration & Login
* 🔐 Authentication System
* 🚕 Ride Booking APIs
* 📍 Pickup & Drop Location Handling
* 📅 Ride Management
* 🗂 MongoDB Database Integration
* ⚡ Scalable Backend Structure

---

## 🛠️ Tech Stack

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB
* Mongoose

**Templating (if used)**

* EJS

**Tools**

* Git & GitHub
* Postman (API Testing)
* VS Code

---

## 📂 Project Structure

```
ridesharex-backend/
│
├── models/        # Database Models
├── routes/        # API Routes
├── controllers/   # Logic Handling
├── views/         # EJS Templates (if used)
├── public/        # Static Files
├── config/        # Database Configuration
├── app.js         # Main Server File
├── package.json   # Dependencies
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to run locally:

### 1️⃣ Clone the Repository

```
git clone https://github.com/Ashwiniii770/ridesharex-backend-.git
```

### 2️⃣ Go to Project Folder

```
cd ridesharex-backend-
```

### 3️⃣ Install Dependencies

```
npm install
```

### 4️⃣ Setup MongoDB

Make sure MongoDB is running locally.

Update MongoDB connection string in:

```
config/db.js
```

Example:

```
mongodb://127.0.0.1:27017/rideshareDB
```

### 5️⃣ Run the Server

```
npm start
```

OR

```
node app.js
```

### 6️⃣ Open in Browser / Postman

```
http://localhost:3000
```

---

## 🧪 API Testing

Use **Postman** to test API routes such as:

* Register User
* Login User
* Book Ride
* View Rides
* Cancel Ride

---

## 🎯 Learning Outcomes

This project helped in learning:

* REST API Development
* MongoDB Integration
* Express Routing
* MVC Pattern
* CRUD Operations
* Backend Project Structure

---

## 📌 Future Improvements

* Payment Integration 💳
* Google Maps Integration 🗺️
* Driver Module 🚗
* Real-time Ride Tracking 📍
* Notification System 🔔

---

## 👩‍💻 Author

**Ashwini**

GitHub:
https://github.com/Ashwiniii770

---

## 📜 License

This project is created for learning and educational purposes.
