# Express + MongoDB Starter API

This is a simple personal project where I'm learning **Express.js**, **MongoDB Atlas**, and **Mongoose**. Right now it only includes a basic CRUD for products, but later it will probably grow—maybe adding **authentication**, **middleware**, and other features.

This repo is mainly for practicing backend basics and keeping the code clean.

---

## 🚀 What This Project Has So Far

* Basic CRUD API (Create, Read, Update, Delete)
* MongoDB Atlas cloud database
* Clean folder structure using controllers + routes
* Environment variables with `dotenv`
* Nodemon for easier development

Planned additions:

* Authentication (probably JWT)
* Custom middleware
* Input validation

---

## 📁 Project Structure

```
project/
├── config/
│   └── db.js
├── controllers/
│   └── productController.js
├── models/
│   └── Product.js
├── routes/
│   └── productRoutes.js
├── server.js
├── .env
└── README.md
```

---

## 🛠 Tech Used

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* dotenv
* Nodemon

---

## 🔧 Setup

Install dependencies:

```bash
npm install
```

Add your `.env` file:

```
MONGO_URI=your_mongodb_atlas_url
PORT=5000
```

Run in development:

```bash
npm run dev
```

Run normally:

```bash
npm start
```

---

## 📌 API Routes (Products)

| Method | Route             | Description      |
| ------ | ----------------- | ---------------- |
| POST   | /api/products     | Create a product |
| GET    | /api/products     | Get all products |
| GET    | /api/products/:id | Get one product  |
| PUT    | /api/products/:id | Update a product |
| DELETE | /api/products/:id | Delete a product |

---

Feel free to modify or expand later when new ideas come in!
