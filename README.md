# Ayur Naturals – Clinic Management System

## Overview

Ayur Naturals is a full-stack Clinic Management System developed using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The system streamlines clinic operations by managing products, orders, inventory, and employee records through a centralized platform.

## Features

* User Authentication and Authorization
* Role-Based Access Control (Admin, Staff, etc.)
* Product Management
* Order Management
* Inventory Tracking
* Employee Management
* Responsive User Interface
* RESTful API Integration
* Secure Data Management

## Tech Stack

### Frontend

* React.js
* Vite
* HTML5
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT (JSON Web Tokens)
* Role-Based Access Control (RBAC)

## Project Structure

```text
Ayur-Naturals/
├── ayur-frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── ayur-backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── package.json
│
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Ayur-Naturals.git
cd Ayur-Naturals
```

### Frontend Setup

```bash
cd ayur-frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd ayur-backend
npm install
npm start
```

## Environment Variables

Create a `.env` file in the backend directory and configure:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Key Functionalities

### Product Management

* Add, update, view, and delete products
* Track product availability

### Order Management

* Create and manage customer orders
* Monitor order status

### Inventory Management

* Track stock levels
* Update inventory records in real time

### Employee Management

* Maintain employee information
* Manage employee roles and permissions

### Security Features

* Secure login and registration
* JWT-based authentication
* Role-based access control
* Protected routes and APIs

## Future Enhancements

* Appointment Scheduling
* Online Payments
* Email Notifications
* Analytics Dashboard
* Report Generation

## Contributors

* Kaveesha Nirmal
* Project Team Members

## License

This project is developed for educational and academic purposes.
