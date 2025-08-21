# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will be able to create, read, update, and delete resources through HTTP endpoints.

## 📝 Tasks

### 🛠️ Project Setup

#### Description
Set up a new FastAPI project and ensure it runs locally.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main application file (e.g., `main.py`)
- Run the FastAPI server locally and access the default docs at `/docs`

### 🛠️ Implement CRUD Endpoints

#### Description
Create RESTful endpoints for a simple resource (e.g., books, users, or tasks).

#### Requirements
Completed program should:

- Define a Pydantic model for the resource
- Implement endpoints to create, read (all and by ID), update, and delete the resource
- Use in-memory storage (e.g., a Python list) for data

### 🛠️ Test and Document the API

#### Description
Test your endpoints and explore FastAPI's automatic documentation features.

#### Requirements
Completed program should:

- Use the interactive docs at `/docs` to test all endpoints
- Add clear docstrings to your endpoint functions
- Ensure all endpoints return appropriate HTTP status codes

---
You may use the following command to install dependencies:

```bash
pip install fastapi uvicorn
```

If you have questions or get stuck, ask your teacher or classmates for help. Good luck!
