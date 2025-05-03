# 📦 JSON Server API for React CRUD App

This repository hosts a mock REST API using [JSON Server](https://github.com/typicode/json-server). It supports full CRUD operations and serves as a backend for a React User Management application.

## 🌐 Live API Endpoint

The API is deployed and publicly accessible via:

👉 [https://json-server-api.onrender.com/users](https://json-server-api.onrender.com/users)

> Replace with your actual Render URL if different.

---

## 📁 Folder Structure

## 📋 API Endpoints

| Method | Endpoint           | Description          |
|--------|--------------------|----------------------|
| GET    | `/users`           | Get all users        |
| GET    | `/users/:id`       | Get a user by ID     |
| POST   | `/users`           | Add new user         |
| PUT    | `/users/:id`       | Update existing user |
| DELETE | `/users/:id`       | Delete user          |

---

## 🚀 Deployment (Render)

### 1. Create a Render Account
- Go to [https://render.com](https://render.com)
- Sign in with GitHub and create a new "Web Service"

### 2. Configuration
- **Build Command:** `npm install`
- **Start Command:** `npx json-server --watch db.json --port 10000`
- **Environment:** Choose Node
- **Port:** `10000` (or any open port)

> Make sure `db.json` is in the root directory.

### 3. Deploy and Copy the API URL
This URL is used in the React frontend to make API requests.

---

## 💾 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/YourUsername/json-server-api.git

cd json-server-api

# Install JSON Server
npm install -g json-server

# Start the server
json-server --watch db.json --port 5000
The API will be available at http://localhost:5000/users

🧑‍💻 Used By
This API is used in the React CRUD project:
👉 https://github.com/YourUsername/react-crud-app

