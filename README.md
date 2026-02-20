🛍️ ShopZone – React E-Commerce Project
📌 Project Overview

ShopZone is a fully functional React e-commerce web application built using:

⚛️ React (Vite)

🔀 React Router DOM

🧠 Context API (Cart + Auth)

💾 LocalStorage (Cart persistence)

🌐 DummyJSON API (Products data)

This project includes:

Product listing

Product details page

Add to cart functionality

Cart total calculation

Protected checkout page

Simple login system

Contact form validation

Navigation with dynamic cart count

🚀 Project Setup Instructions
1️⃣ Create Project
npm create vite@latest ShopZone

Choose:

Framework → React

Variant → JavaScript

Use Vite 8 beta → No

Install with npm → Yes

2️⃣ Navigate into project
cd ShopZone
3️⃣ Install Dependencies
npm install
npm install react-router-dom
4️⃣ Start Development Server
npm run dev

Open in browser:

http://localhost:5173
📁 Project Structure
ShopZone/
│
├── src/
│   ├── main.jsx
│   ├── App.jsx
│   │
│   ├── context/
│   │   ├── CartContext.jsx
│   │   └── AuthContext.jsx
│   │
│   ├── components/
│   │   ├── Navbar.jsx
│   │   └── ProtectedRoute.jsx
│   │
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Shop.jsx
│   │   ├── ProductDetails.jsx
│   │   ├── Cart.jsx
│   │   ├── Contact.jsx
│   │   ├── Login.jsx
│   │   └── Checkout.jsx
🔥 Core Features
🛒 Cart System

Add products to cart

Cart stored in localStorage

Total price auto calculated

Cart count visible in Navbar

🔐 Authentication System

Simple login toggle system

Protected checkout route

Redirects to login if not authenticated

🛍️ Product API

Products fetched from:

https://dummyjson.com/products
📄 Routing
Route	Page
/	Home
/shop	Product Listing
/product/:id	Product Details
/cart	Cart
/contact	Contact Form
/login	Login Page
/checkout	Protected Checkout
⚙️ Technologies Used

React 18+

Vite

React Router DOM

Context API

LocalStorage

Fetch API

🧠 Learning Concepts Covered

React functional components

useState

useEffect

useContext

useParams

useNavigate

Route protection

Dynamic routing

Form validation

API fetching

State persistence

🛠️ Troubleshooting
❌ react-router-dom not found

Fix:

npm install react-router-dom
❌ Module not resolved

Fix:

npm install
❌ Port already in use

Press:

Ctrl + C

Then restart:

npm run dev
🎯 Final Result

A fully working React e-commerce application with:

✅ Routing
✅ Context API
✅ Cart functionality
✅ Protected checkout
✅ Login simulation
✅ API integration
✅ Clean folder structure

👨‍💻 Developed By

Utsav Raj
Project Name: ShopZone
Tech Stack: React + Vite

