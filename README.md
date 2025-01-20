
### Backend README

```markdown
# eCommerce Application - Backend

This is the **backend** of the eCommerce application, responsible for managing products, orders, users, and cart data. The backend is built using **Node.js**, **Express.js**, and **MongoDB**.

## Features

- User authentication and authorization.
- CRUD operations for products (admin only).
- Cart management.
- Order management.
- RESTful API for the frontend.

## Tech Stack

- **Node.js**: JavaScript runtime.
- **Express.js**: Web framework.
- **MongoDB**: NoSQL database for data storage.
- **JWT**: For user authentication.
- **Mongoose**: Object Data Modeling (ODM) library.
- **Bcrypt**: For password hashing.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone <backend-repo-url>

2.Navigate to the project directory:
 ```bash
 cd ecommerce-backend
3.Install dependencies:
 ```bash
npm install
 4.Set up the
.env file with the following variables:
```env
 PORT=5000
 MONGO_URI
JWT_SECRET
5.Start the server:
 ```bash
 npm start
