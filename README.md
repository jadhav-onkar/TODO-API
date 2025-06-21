# 📝 ToDo App API

This is a RESTful API for a simple ToDo application built using **Node.js**, **Express.js**, **MongoDB** with **Mongoose**, **Zod** for input validation, and **JWT** for authentication. It includes secure user authentication and authorization using custom middleware.

## 🚀 Features

- User Signup & Login with JWT authentication
- Create, Read, Update, and Delete ToDo items
- Zod for request data validation
- Protected routes using custom auth middleware
- MongoDB as the database (via Mongoose)

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB & Mongoose
- Zod (input validation)
- JSON Web Tokens (JWT)
- dotenv for environment variable management

## 🏃‍♂️ Running Locally

To run this API on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone 'https://github.com/jadhav-onkar/TODO-API'
   ```

2. **Navigate to the root directory**:
   ```bash
   cd TODO-API
   ```

3. **Create a `.env` file** in the root directory and add the following environment variables:
   ```env
   JWT_SECRET=<your_jwt_secret_key>
   PORT=<your_preferred_port>
   DB_URL=<your_mongodb_connection_string>
   ```

4. **Install dependencies**:
   ```bash
   npm install
   ```

5. **Run the application**:
   ```bash
   node index.js
   ```
