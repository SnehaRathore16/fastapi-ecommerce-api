# FastAPI Ecommerce API

A REST API built with FastAPI for managing ecommerce products.

## Features
- Full CRUD operations (Create, Read, Update, Delete)
- Search products by name
- Filter and sort by price
- Pagination support
- Auto-generated Swagger documentation
- UUID-based product identification

## Tech Stack
- Python
- FastAPI
- Pydantic
- UUID

## How to Run
pip install fastapi uvicorn pydantic python-dotenv
uvicorn main:app --reload

## API Endpoints
- GET /products - List all products
- POST /products - Create product
- GET /products/{id} - Get product by ID
- PUT /products/{id} - Update product
- DELETE /products/{id} - Delete product
