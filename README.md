# My-final-Project

# E-Commerce App

## Overview

A full-stack e-commerce web application built using the MERN stack (MongoDB, Express, React, Node.js). This app allows users to browse products, add items to their cart, and make secure payments. An admin panel is also provided for managing products, users, and orders.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Demo](#demo)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Register, login, and password reset functionality.
- **Product Management**: Admin can manage product listings (CRUD operations).
- **Shopping Cart**: Users can add/remove products, view the cart, and proceed to checkout.
- **Order Management**: Users can place orders, view order history, and track orders.
- **Payment Integration**: Secure payments using Stripe.
- **Responsive Design**: Optimized for both mobile and desktop views.
- **Admin Panel**: Manage users, orders, and products.

## Tech Stack

**Frontend**:  
- React (JavaScript library for building UI)
- React Router (for navigation)
- Redux (state management)
- Axios (for making HTTP requests)
- CSS Modules or Styled Components

**Backend**:  
- Node.js (JavaScript runtime)
- Express.js (Node.js framework for building RESTful APIs)
- MongoDB (NoSQL database for storing user and product data)
- Mongoose (MongoDB ODM)
- JWT (JSON Web Token for authentication)
- Stripe API (for payment processing)

## Demo

You can check out a live demo of the project here:  
[Live Demo URL]()

## Installation

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) and npm (Node Package Manager)
- [MongoDB](https://www.mongodb.com/)

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ecommerce-app.git
   cd ecommerce-app

 2. Navigate to the /backend folder and install the dependencies:
    cd backend
    npm install
 3.Set up MongoDB either locally or using MongoDB Atlas (cloud).

 4.Create a .env file in the /backend folder with the following environment variables:
     NODE_ENV=development
     PORT=4000
    MONGO_URI=your_mongo_db_connection_string
    JWT_SECRET=your_jwt_secret
     STRIPE_SECRET_KEY=your_stripe_secret_key

     
