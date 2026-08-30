# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API using FastAPI that manages a collection of items and returns JSON responses. Students will practice creating routes, handling HTTP methods, and validating request data.

## 📝 Tasks

### 🛠️ Create the FastAPI App

#### Description
Set up a FastAPI application and define a basic route that responds with a friendly welcome message.

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Define a `GET /` endpoint
- Return a JSON response such as `{"message": "Welcome to the items API"}`
- Run the app locally with `uvicorn`

### 🛠️ Build CRUD Endpoints

#### Description
Create endpoints for adding, reading, updating, and deleting items in memory.

#### Requirements
Completed program should:

- Store items in a Python list or dictionary while the server is running
- Create a `GET /items` endpoint to return all items
- Create a `GET /items/{item_id}` endpoint to return one item
- Create a `POST /items` endpoint to add a new item
- Create a `PUT /items/{item_id}` endpoint to update an existing item
- Create a `DELETE /items/{item_id}` endpoint to remove an item
- Return JSON responses with clear status information

### 🛠️ Validate Request Data

#### Description
Use FastAPI request validation so the API accepts properly formatted item data and rejects invalid input.

#### Requirements
Completed program should:

- Define a simple item model with fields such as `id`, `name`, and `description`
- Require meaningful values for essential fields
- Return a validation error when required fields are missing or invalid
- Show a sample successful request and response in your notes or comments

### 🛠️ Bonus Challenge

#### Description
Add a small improvement to make the API more useful and professional.

#### Requirements
Completed program should:

- Add one additional feature such as filtering, search, or a status endpoint
- Keep the output clear and easy to test in a browser or API client
- Explain briefly what your extra feature does
