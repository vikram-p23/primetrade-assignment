# API Documentation

Base URL: `http://localhost:5000/api`

## Authentication

### 1. Register User
* **Endpoint:** `POST /auth/register`
* **Body:**
    ```json
    {
      "name": "Vikram P",
      "email": "vikram@example.com",
      "password": "password123"
    }
    ```
* **Response:** Returns JWT Token.

### 2. Login User
* **Endpoint:** `POST /auth/login`
* **Body:**
    ```json
    {
      "email": "vikram@example.com",
      "password": "password123"
    }
    ```

## Tasks (Protected Routes)
*Requires Header:* `x-auth-token: <your_jwt_token>`

### 3. Get All Tasks
* **Endpoint:** `GET /tasks`
* **Response:** Array of task objects.

### 4. Create Task
* **Endpoint:** `POST /tasks`
* **Body:**
    ```json
    {
      "title": "Complete Assignment",
      "description": "Finish the documentation",
      "priority": "high"
    }
    ```

### 5. Delete Task
* **Endpoint:** `DELETE /tasks/:id`