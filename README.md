# 🛒 MERN E-Commerce Website

## 📌 Project Description

This is a full-stack E-Commerce web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js).
It allows users to browse products, add items to cart, and place orders online.

---

## 🚀 Features

* 🔐 User Authentication (Login / Register)
* 🛍️ Product Listing & Details
* 🛒 Add to Cart / Remove from Cart
* 💳 Checkout & Order Placement
* 📦 Order History
* 🛠️ Admin Panel (Add / Update / Delete Products)
* 📱 Responsive Design

---

## 🏗️ Tech Stack

### Frontend

* React.js
* CSS / Bootstrap / Tailwind (mention what you used)

### Backend

* Node.js
* Express.js

### Database

* MongoDB

---

## 📂 Project Structure

```
ecommerce-app/
│
├── client/        # React frontend
├── server/        # Node + Express backend
├── models/        # MongoDB models
├── routes/        # API routes
├── controllers/   # Business logic
├── config/        # DB connection
└── .env           # Environment variables
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/ecommerce-app.git
cd ecommerce-app
```

### 2️⃣ Install dependencies

#### Backend

```
cd server
npm install
```

#### Frontend

```
cd client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the **server** folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the Application

### Start Backend

```
cd server
npm start
```

### Start Frontend

```
cd client
npm start
```

---

## 🌐 API Endpoints (Example)

* `POST /api/users/register` → Register user
* `POST /api/users/login` → Login user
* `GET /api/products` → Get all products
* `POST /api/orders` → Create order

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Saikam Johnson**

---
