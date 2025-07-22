# QuickBite - Food Delivery Web Application

QuickBite is a modern, responsive food delivery web application built with React.js for the frontend and Node.js with Express for the backend. The application allows users to browse restaurants, view menus, add items to cart, and place orders.

## Features

- 🍽️ **Restaurant Listings**: Browse through various restaurants
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 🛒 **Shopping Cart**: Add/remove items, update quantities
- 💳 **Payment Integration**: Multiple payment options including COD and online payment
- 📦 **Order Tracking**: Track your order status
- 👤 **User Authentication**: Secure login and registration system

## Screenshots

### Home Page & Hero Section
![Home Page](https://github.com/user-attachments/assets/740236d6-9ab2-40a4-b310-7c1c1db78c43)


*Our welcoming homepage featuring a delectable array of dishes and our mission statement.*

### Menu Categories
![Menu Categories](https://github.com/user-attachments/assets/17fb474a-e4a4-4c03-970a-533e313c3625)
*Explore our diverse menu categories including Salads, Rolls, Desserts, Sandwiches, and more.*

### Shopping Cart
![Shopping Cart](https://github.com/user-attachments/assets/6997cfb9-ddf8-470a-8342-03a1d61fef9b)

*Easy-to-use shopping cart with item management and delivery fee calculation.*

### Checkout Process
![Delivery Details](https://github.com/user-attachments/assets/983d0bd0-19ec-4581-b267-0e7b4e725df1)

*Simple and secure delivery information collection.*

![Payment Options](https://github.com/user-attachments/assets/c9f8bf57-ad98-4c64-a111-a3a3ae0bd989)
*Multiple payment options including Cash on 
Delivery, Card, and UPI.*

### Order Tracking
![Order Status](https://github.com/user-attachments/assets/e98eee42-1ad7-4b88-8e39-30831c0fe905)

*Track your order status and view order details.*

### Mobile App Promotion
![Mobile App](https://github.com/user-attachments/assets/0a7b6258-284b-42d4-af67-b810fc2afb75)

*Download our mobile app for an enhanced ordering experience.*

## Tech Stack

### Frontend
- React.js
- React Router for navigation
- CSS3 for styling
- Font Awesome for icons
- Axios for API calls

### Backend
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Mongoose for database operations

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Food-Web-App.git
cd Food-Web-App
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd backend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

## Running the Application

1. Start the backend server:
```bash
cd backend
cd server
npm start
```

2. Start the frontend development server:
```bash
cd frontend
npm start
```

3. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
Food-Web-App/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
└── README.md
```

## API Endpoints

### Authentication
- POST `/api/auth/register` - Register a new user
- POST `/api/auth/login` - Login user
- GET `/api/auth/me` - Get current user

### Restaurants
- GET `/api/restaurants` - Get all restaurants
- GET `/api/restaurants/:id` - Get restaurant by ID
- GET `/api/restaurants/search` - Search restaurants

### Orders
- POST `/api/orders` - Create new order
- GET `/api/orders` - Get user's orders
- GET `/api/orders/:id` - Get order by ID


