# InventoryPro

InventoryPro is a full-stack inventory management system developed using the MERN stack (MongoDB, Express.js, React, and Node.js). It allows businesses and factories to efficiently track and manage their inventory in real-time.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Screenshots](#Screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Overview

InventoryPro provides a user-friendly interface for real-time monitoring of stock levels, seamless product management, order tracking, and detailed reporting. Built with scalability and security in mind, it ensures businesses can streamline their operations effectively.

## Features

- **Real-time Inventory Tracking**: Monitor stock levels and updates in real-time.
- **User Authentication & Authorization**: Secure login and role-based access control.
- **Product Management**: Add, update, delete, and view products in the inventory.
- **Order Management**: Track and manage orders, update stock levels accordingly.
- **Notifications**: Receive alerts for low stock levels.
- **Reporting**: Generate detailed reports on inventory, orders, and product performance.
- **Responsive Design**: Optimized for various devices and screen sizes.

## Screenshots

![Screenshot from 2024-06-15 20-17-58](https://github.com/ivedantsharma/Inventory-Application/assets/153631137/7be80ae8-8848-4f85-b5b7-e93795102606)
![Screenshot from 2024-06-15 20-26-52](https://github.com/ivedantsharma/Inventory-Application/assets/153631137/46da72f0-b1ab-4037-97d4-3102731bf1ea)
![Screenshot from 2024-06-15 20-27-50](https://github.com/ivedantsharma/Inventory-Application/assets/153631137/4fc1c5d2-9336-45e1-9f65-39c1960bb9c5)
![Screenshot from 2024-06-15 20-27-50](https://github.com/ivedantsharma/Inventory-Application/assets/153631137/8be14230-bb30-4e50-9f57-938aa4bbf95c)


## Installation

To run InventoryPro locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ivedantsharma/Inventory-Application.git
   cd Inventory-app
2. **Install server dependencies:**
   ```bash
   cd backend
   npm install
3. **Install client dependencies:**
   ```bash
   cd ../client
   npm install
4. **Set up environment variables:**
   ```bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
5. **Run the application:**
   ```bash
   cd server
   npm start
   cd client
   npm start
6. **Access the application:**
   Open your browser and go to http://localhost:3000.

## Usage

1. **Register and Login**: Create a new account or log in with existing credentials.
2. **Manage Inventory**: Add, update, and delete products.
3. **Track Orders**: Create and manage orders.
4. **Generate Reports**: View and download inventory reports.

## Technologies Used

- **Frontend**: React, Redux, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git, GitHub

## Conclusion

Thank you for exploring InventoryPro! We hope this application provides you with valuable insights into efficient inventory management. Feel free to contribute, provide feedback, or reach out with any questions. Happy tracking!
