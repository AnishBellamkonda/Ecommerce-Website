# E-commerce Website

Welcome to the E-commerce Website project repository! This project showcases a fully functional e-commerce website built using modern web development technologies.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [Contact](#contact)

## Introduction

This project demonstrates the creation of an e-commerce platform where users can browse products, add them to a cart, and purchase them. The website is designed to be user-friendly, responsive, and secure.

## Features

- User Authentication and Authorization
- Product Listing and Search
- Shopping Cart
- Order Management
- Admin Panel for Product Management
- Secure Payment Integration

## Technologies Used

- **Frontend**:
  - HTML, CSS, JavaScript
  - React.js
- **Backend**:
  - Node.js
  - Express.js
- **Database**:
  - MongoDB
- **Authentication**:
  - JWT (JSON Web Tokens)
- **Payment Gateway**:
  - Stripe API

## Setup and Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/AnishBellamkonda/Ecommerce-Website.git
    cd Ecommerce-Website
    ```

2. **Install dependencies**:
    ```bash
    # For backend
    cd backend
    npm install

    # For frontend
    cd ../frontend
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the `backend` directory and add the following:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Start the development servers**:
    ```bash
    # Start backend server
    cd backend
    npm run dev

    # Start frontend server
    cd ../frontend
    npm start
    ```

## Usage

- **Homepage**: Browse featured products and search for items.
- **Product Page**: View detailed information about a product and add it to the cart.
- **Cart**: Review selected items, adjust quantities, and proceed to checkout.
- **Checkout**: Enter shipping details and payment information to place an order.
- **Admin Panel**: (For admin users) Manage product listings and view orders.

## Contributing

We welcome contributions to improve this project! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.


## Contact

For any questions or suggestions, please feel free to contact the project maintainer:

- **Anish Bellamkonda**
- GitHub: [AnishBellamkonda](https://github.com/AnishBellamkonda)
