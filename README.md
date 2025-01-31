# E-commerce Store

Overview

E-commerce Store is a full-stack web application that allows users to browse, search, and purchase products online. The platform includes authentication, product management, a shopping cart, and a secure checkout process.

Features

User authentication (signup, login, logout)

Product listing with categories and search functionality

Shopping cart and checkout system

Order management for users and admins

Payment gateway integration

Admin dashboard for managing products and orders

Tech Stack

Frontend: React, Redux, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT
Payment Gateway: Stripe

Installation

Clone the repository:

git clone https://github.com/yourusername/ecommerce-store.git
cd ecommerce-store

Install dependencies for both frontend and backend:

cd client
npm install
cd ../server
npm install

Set up environment variables:

Create a .env file in the server directory

Add the necessary configurations (MongoDB URI, JWT secret, Stripe keys, etc.)

Start the application:

# Start backend
cd server
npm start

# Start frontend
cd ../client
npm start

API Endpoints

Auth

POST /api/auth/register - Register a new user

POST /api/auth/login - Authenticate a user

Products

GET /api/products - Get all products

GET /api/products/:id - Get product details

POST /api/products - Add a new product (Admin only)

Orders

POST /api/orders - Create a new order

GET /api/orders/:id - Get order details

Contribution

Feel free to fork the repository and submit pull requests for improvements.



