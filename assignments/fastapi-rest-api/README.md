# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Learn how to build a RESTful API using FastAPI in Python, including route definitions, request/response models, and basic CRUD operations.

## 📝 Tasks

### 🛠️ Project Setup

#### Description
Initialize a FastAPI project, install dependencies, and create the main application file.

#### Requirements
Completed program should:

- Use `fastapi` and `uvicorn` packages
- Create a `main.py` with a `FastAPI()` app instance
- Include a root GET endpoint at `/` that returns a welcome message

### 🛠️ CRUD Endpoints

#### Description
Implement CRUD endpoints for a sample resource (e.g., `items`) and use Pydantic models for data validation.

#### Requirements
Completed program should:

- Define a Pydantic model `Item` with fields: `id`, `name`, `description`, and `price`
- Add endpoints:
  - `GET /items` (list items)
  - `GET /items/{item_id}` (get item by ID)
  - `POST /items` (create item)
  - `PUT /items/{item_id}` (update item)
  - `DELETE /items/{item_id}` (delete item)
- Use an in-memory list to store items for this exercise

### 🛠️ Error Handling and Documentation

#### Description
Add validation and error handling and verify automatic API docs.

#### Requirements
Completed program should:

- Return `404` with a JSON error message if an item is not found
- Validate item data types using Pydantic model checks
- Verify FastAPI auto-generated docs available at `/docs`

