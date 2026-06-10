# 🛒 FastAPI Ecommerce API

A RESTful Ecommerce Product Management API built using **FastAPI** and **Python**. This project provides complete product management functionality with CRUD operations, search, filtering, sorting, pagination, and auto-generated API documentation.

## 🚀 Features

* Full CRUD Operations (Create, Read, Update, Delete)
* Search Products by Name
* Filter Products by Price
* Sort Products by Price (Ascending/Descending)
* Pagination Support
* UUID-based Product Identification
* Request Validation using Pydantic
* Environment Variable Support using Python Dotenv
* Interactive Swagger API Documentation
* Fast and Lightweight REST API Architecture

## 🛠️ Tech Stack

* Python
* FastAPI
* Pydantic
* Uvicorn
* Python-Dotenv
* UUID
* JSON Data Storage

## 📂 Project Structure

```text
fastapi-ecommerce/
│
├── app/
│   ├── data/
│   │   └── products.json
│   │
│   ├── schema/
│   │   └── product.py
│   │
│   ├── service/
│   │   └── products.py
│   │
│   └── main.py
│
├── requirements.txt
├── README.md
└── .env
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/SnehaRathore16/fastapi-ecommerce-api.git
cd fastapi-ecommerce-api
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
uvicorn app.main:app --reload
```

Server will start at:

```text
http://127.0.0.1:8000
```

## 📖 API Documentation

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

ReDoc Documentation:

```text
http://127.0.0.1:8000/redoc
```

## 🔗 API Endpoints

### Product Operations

| Method | Endpoint         | Description                |
| ------ | ---------------- | -------------------------- |
| GET    | `/products`      | Get all products           |
| GET    | `/products/{id}` | Get product by ID          |
| POST   | `/products`      | Create a new product       |
| PUT    | `/products/{id}` | Update an existing product |
| DELETE | `/products/{id}` | Delete a product           |

### Additional Features

* Product Search
* Price Filtering
* Price Sorting
* Pagination Support

## 🧪 Sample Use Cases

* Ecommerce Product Management
* Backend API Learning
* FastAPI Practice Project
* REST API Development
* CRUD Operations with Python

## 🌱 Future Improvements

* Database Integration (SQLite/PostgreSQL/MySQL)
* User Authentication & Authorization
* JWT Token Security
* Product Categories
* Inventory Management
* Docker Deployment
* Cloud Deployment (AWS)

## 👩‍💻 Author

**Sneha Rathore**

* MCA Student, Manipal University Jaipur
* B.Sc. Computer Science (Hons.), University of Delhi
* Python | SQL | FastAPI | Backend Development

⭐ If you found this project useful, consider giving it a star.
<img width="1877" height="726" alt="image" src="https://github.com/user-attachments/assets/0fab189d-516e-40c0-9b6b-118bbe0a807a" />
<img width="1872" height="758" alt="image" src="https://github.com/user-attachments/assets/7fd105d9-079e-4814-aa66-edab72c26396" />

