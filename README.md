# 🚀 Inventory & Order Management System

A full-stack Inventory & Order Management System built using **FastAPI**, **React.js**, and **PostgreSQL**. The application helps businesses manage products, customers, orders, and inventory efficiently through a clean and responsive user interface.

---

## 📌 Project Overview

This project was developed as part of a technical assessment to demonstrate:

- Backend API Development using FastAPI
- Frontend Development using React.js
- Database Design & Management
- CRUD Operations
- Inventory Tracking Logic
- REST API Integration
- Error Handling & Validation

---

## ✨ Features

### 📦 Product Management
- Create Products
- Update Products
- Delete Products
- View Product List
- Unique SKU Validation

### 👥 Customer Management
- Create Customers
- Update Customer Information
- Delete Customers
- View Customer List
- Unique Email Validation

### 🛒 Order Management
- Create Orders
- View Orders
- Cancel Orders
- Automatic Inventory Updates

### 📊 Inventory Tracking
- Real-time Stock Management
- Automatic Stock Reduction
- Stock Restoration on Order Cancellation
- Prevent Orders When Stock Is Insufficient

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Axios
- CSS

### Backend
- FastAPI
- SQLAlchemy
- Pydantic
- Uvicorn

### Database
- PostgreSQL

### Deployment
- Vercel (Frontend)
- Render (Backend)

---

## 📂 Project Structure

```bash
inventory-management/
│
├── backend/
│   ├── app/
│   │   ├── routes/
│   │   ├── models.py
│   │   ├── schemas.py
│   │   └── database.py
│   │
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   │
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/inventory-management.git

cd inventory-management
```

---

### 2️⃣ Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

uvicorn app.main:app --reload
```

Backend will run on:

```bash
http://localhost:8000
```

API Documentation:

```bash
http://localhost:8000/docs
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

---

## 🔗 Live Demo

### Frontend
[Live Frontend Demo](YOUR_FRONTEND_LINK)

### Backend API
[Live Backend API](YOUR_BACKEND_LINK)

### API Documentation
[Swagger Docs](YOUR_API_DOCS_LINK)

---

## 📡 API Endpoints

### Products

| Method | Endpoint |
|----------|----------|
| GET | /api/products |
| GET | /api/products/{id} |
| POST | /api/products |
| PUT | /api/products/{id} |
| DELETE | /api/products/{id} |

---

### Customers

| Method | Endpoint |
|----------|----------|
| GET | /api/customers |
| GET | /api/customers/{id} |
| POST | /api/customers |
| PUT | /api/customers/{id} |
| DELETE | /api/customers/{id} |

---

### Orders

| Method | Endpoint |
|----------|----------|
| GET | /api/orders |
| GET | /api/orders/{id} |
| POST | /api/orders |
| DELETE | /api/orders/{id} |

---

## 🔒 Business Rules

### Product Rules
- SKU must be unique.

### Customer Rules
- Email must be unique.

### Order Rules
- Order cannot be placed if stock is unavailable.
- Stock automatically decreases after successful order creation.
- Stock is restored when an order is cancelled.

---

## 📸 Screenshots

### Dashboard
_Add Screenshot Here_

### Product Management
_Add Screenshot Here_

### Customer Management
_Add Screenshot Here_

### Order Management
_Add Screenshot Here_

---

## 🚀 Future Improvements

- Authentication & Authorization
- Role-Based Access Control
- Dashboard Analytics
- Export Reports (CSV/PDF)
- Search & Filter Functionality
- Order Status Tracking

---

## 👨‍💻 Author

**Sandeep Kumar Yadav**




