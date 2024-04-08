# FeastFinder: A MERN Stack Food Delivery App

FeastFinder is a full-stack web application designed to bring the convenience of food delivery to users with just a few clicks. Built with the MERN stack (MongoDB, Express, React, and Node.js), this app features a sleek user interface for browsing menus and food items, a cart system for order management, and a secure sign-in/sign-up functionality. This README outlines the project setup, features, and future enhancements.

## Project Structure

- `frontend/`: Contains the React application.
  - `src/`: Source files for the React app.
    - `components/`: Reusable UI components.
    - `pages/`: Components representing entire pages (Home, Cart, Order, Auth).
    - `assets/`: Static assets like images and icons.
    - `App.js`: Main React application entry point.
- `backend/`: Houses the Express and Node.js server code.
  - `models/`: MongoDB models for data representation.
  - `routes/`: API endpoints for handling HTTP requests.
  - `controllers/`: Logic for responding to API requests.
- `README.md`: Project documentation.

## Features

- **Home Page**: Displays the menu and available food items.
- **Cart Page**: Allows users to review and modify their orders before checkout.
- **Order Page**: Shows order summary and status after checkout.
- **Sign In/Sign Up Popup**: Secure authentication mechanism for users.
- **Responsive Design**: Ensures a seamless experience across various devices.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager)
- MongoDB database setup (local or cloud-based with MongoDB Atlas)

### Setup

1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/your-username/feastfinder.git
   cd feastfinder
```
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```
# Open a new terminal in the `frontend/` directory
npm run dev

