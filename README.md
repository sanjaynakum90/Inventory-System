<img width="1920" height="917" alt="image" src="https://github.com/user-attachments/assets/8ef682f7-b529-4421-994d-68d52cf806fe" />


# 🧾 Inventory Management System (Redux Toolkit)

An **Inventory Management System** built with **React**, **Redux Toolkit**, and **Vite**.
This application allows users to **add, view, edit, and delete products**, while automatically calculating the total price based on quantity and unit price.

---

## 🚀 Features

* ➕ Add new products
* ✏️ Edit existing products
* 🗑️ Delete products
* 📦 Manage product quantity and category
* 💰 Automatically calculate total price
* ⚡ Fast development with Vite
* 🧠 Centralized state management using Redux Toolkit

---

## 🛠️ Tech Stack

* **React**
* **Redux Toolkit**
* **Vite**
* **JavaScript (ES6+)**
* **CSS**

---

## 📂 Project Structure

```bash
05-Redux-Builder/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── ProductForm.jsx
│   │   └── ProductList.jsx
│   ├── features/
│   │   └── product/
│   │       └── productSlice.js
│   ├── store/
│   │   └── store.js
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```
## 🧠 Redux Logic Overview

* **productSlice.js**

  * Manages product state
  * Handles actions: add, update, delete
* **store.js**

  * Configures Redux store using `configureStore`
* **useSelector & useDispatch**

  * Used for accessing and modifying global state

---

## 📈 Future Improvements

* 🔍 Search & filter products
* 💾 Persist data using localStorage or backend
* 📊 Dashboard analytics
* 🔐 Authentication & role-based access


