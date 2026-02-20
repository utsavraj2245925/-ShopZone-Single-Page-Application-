📄 prompt.md – ShopZone Project Prompt
🧠 Project Prompt

Build a fully functional E-Commerce web application using React (Vite) that includes routing, authentication, cart management, protected routes, and API integration.

The application should simulate a real-world online shopping platform with product listing, product details, cart functionality, and a protected checkout page.

🎯 Core Requirements
1️⃣ Use Modern React

Functional Components

Hooks (useState, useEffect, useContext)

Context API for global state

2️⃣ Implement Routing

Use react-router-dom to create the following routes:

/ → Home Page

/shop → Product Listing Page

/product/:id → Product Details Page

/cart → Cart Page

/contact → Contact Form Page

/login → Login Page

/checkout → Protected Checkout Page

3️⃣ Product API Integration

Fetch products from:

https://dummyjson.com/products

Requirements:

Display product image

Display product title

Display price

Link to product details page

4️⃣ Product Details Page

Fetch single product by ID

Show:

Image

Title

Description

Price

Add to Cart button

5️⃣ Cart Management

Use Context API to:

Store cart items

Add products to cart

Calculate total price

Persist cart in LocalStorage

6️⃣ Authentication System

Create an AuthContext that:

Stores user login state

Has login function

Has logout function

7️⃣ Protected Route

Create a ProtectedRoute component that:

Allows access to /checkout only if user is logged in

Redirects to /login if not authenticated

8️⃣ Contact Form

Create a contact form with:

Name

Email

Message

Basic validation

Success message

🏗️ Required Folder Structure
src/
│
├── main.jsx
├── App.jsx
│
├── context/
│   ├── CartContext.jsx
│   └── AuthContext.jsx
│
├── components/
│   ├── Navbar.jsx
│   └── ProtectedRoute.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── Shop.jsx
│   ├── ProductDetails.jsx
│   ├── Cart.jsx
│   ├── Contact.jsx
│   ├── Login.jsx
│   └── Checkout.jsx
⚙️ Development Setup Requirements

Use Vite

Use JavaScript (not TypeScript)

Install react-router-dom

Use functional components only

No class components

💡 Optional Enhancements

Remove item from cart

Add product quantity feature

Add styling using Tailwind CSS

Add search functionality

Add product filtering

Improve UI/UX

🎓 Learning Objectives

This project demonstrates:

React project setup with Vite

SPA routing

Global state management with Context API

Protected routes

API integration

LocalStorage persistence

Form validation

Component structure best practices

🏁 Final Goal

Create a working E-Commerce SPA that:

Runs without errors

Handles routing correctly

Manages global state properly

Protects private routes

Fetches real API data

Demonstrates modern React architecture
