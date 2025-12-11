# ecommerce-fullstack
Full-stack e-commerce application for Angular + Node + MySQL + Ionic (Portfolio + Interview Project)
# 🛒 Full-Stack E-Commerce Application  

**Tech Stack:** Angular + Node.js (Express) + MySQL + Ionic  

## Project Overview
This project is a full-stack e-commerce application for web and mobile. It includes:

- User registration & login
- Product list & details
- Cart & checkout
- Admin panel to manage products & orders
- Mobile app with Ionic

## Folder Structure
- **db/** → Database schema
- **backend/** → Node.js + Express API
- **frontend/** → Angular Web App
- **mobile/** → Ionic Mobile App

## Setup Instructions
1. Clone repo  
2. Import `db/schema.sql` into MySQL  
3. Setup backend: `cd backend && npm install`  
4. Setup frontend: `cd frontend && npm install`  
5. Setup mobile: `cd mobile && npm install`  
6. Start servers: Node backend + Angular frontend + Ionic mobile

Repo Structure:
ecommerce-fullstack/
│
├── db/
│   └── schema.sql           # MySQL database schema (Day 1)
│
├── backend/
│   ├── index.js             # Entry point of Node.js API
│   ├── db.js                # MySQL connection
│   ├── routes/
│   │    ├── auth.js
│   │    ├── products.js
│   │    ├── cart.js
│   │    └── orders.js
│   ├── middleware/
│   │    └── auth.js
│   ├── controllers/
│   │    ├── authController.js
│   │    ├── productController.js
│   │    ├── cartController.js
│   │    └── orderController.js
│   ├── package.json
│   └── .env.example
│
├── frontend/
│   ├── angular.json
│   ├── package.json
│   └── src/
│        ├── app/
│        │    ├── components/
│        │    ├── services/
│        │    ├── auth/
│        │    └── products/
│        └── index.html
│
├── mobile/
│   ├── ionic.config.json
│   ├── package.json
│   └── src/
│        ├── app/
│        │    ├── pages/
│        │    │    ├── home/
│        │    │    ├── products/
│        │    │    └── cart/
│        │    └── services/
│        └── index.html
│
└── README.md

## Current Status
Day 1 – Database schema ready
