Smoke Shop E-Commerce App

Welcome to our B2C smoke shop e-commerce app! This application is built using React Native for the frontend, Node.js with Express for the backend, MongoDB for the database, and Tailwind CSS for styling.

Getting Started

Prerequisites
Before you begin, ensure you have the following installed on your machine:

Node.js and npm
MongoDB
React Native CLI
Expo CLI (optional, if you plan to use Expo)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/smoke-shop-app.git
cd smoke-shop-app
Install dependencies for both the frontend and backend:
bash
Copy code
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
`npm install`
Configure environment variables:
Create a .env file in the backend directory and set the following variables:
env
Copy code
PORT=3001
MONGODB_URI=your_mongodb_connection_string
Replace your_mongodb_connection_string with your actual MongoDB connection string.
Start the backend server:
bash
Copy code
# From the backend directory
npm start
Start the frontend development server:
bash
Copy code
# From the frontend directory
npm start
If using Expo:
bash
Copy code
expo start
Follow the instructions to run the app on an emulator or physical device.
Features

Browse and search for a variety of smoke products.
User authentication and account management.
Add products to the shopping cart.
Secure checkout process.
Order history and tracking.
Technologies Used

React Native
Node.js
Express
MongoDB
Tailwind CSS
Contributing

We welcome contributions! If you find any issues or have ideas for improvement, please submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE.md file for details.

