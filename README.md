📦 ShopZone – React E-Commerce Application

A fully functional E-Commerce web application built using React + Vite.
This project demonstrates routing, authentication, protected routes, cart management, and API integration.

🚀 Features

🏠 Home Page

🛍️ Shop Page (Products fetched from API)

🔍 Product Details Page

🛒 Add to Cart

💾 Cart stored in LocalStorage

🔐 Login Authentication (Context API)

🔒 Protected Checkout Route

📩 Contact Form with Validation

⚡ Built with Vite for fast development

🛠️ Tech Stack

React (Vite)

React Router DOM

Context API

JavaScript (ES6+)

DummyJSON API

LocalStorage

📁 Project Structure
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
⚙️ Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone or Create Project

If starting fresh:

npm create vite@latest ShopZone

Select:

Framework → React

Variant → JavaScript

Use Vite 8 Beta → No

2️⃣ Navigate to Project
cd ShopZone
3️⃣ Install Dependencies
npm install
npm install react-router-dom
4️⃣ Start Development Server
npm run dev

Open in browser:

http://localhost:5173/
🔐 Authentication Flow

User clicks Login

AuthContext sets user state to true

Checkout page is protected using ProtectedRoute

If not logged in → Redirects to Login page

🛒 Cart Functionality

Products can be added to cart

Cart state is managed using Context API

Cart is stored in LocalStorage

Total price is calculated dynamically

🌐 API Used

Products are fetched from:

https://dummyjson.com/products
📌 Future Improvements

Remove items from cart

Add quantity selection

Payment gateway integration

Better UI styling (Tailwind / CSS)

Admin dashboard

Product search & filtering



