# RescueMeals: Food Management System

RescueMeals is a powerful food management system designed to address the issue of food wastage by enabling collaboration between restaurants, NGOs, and volunteers. This MERN (MongoDB, Express.js, React.js, Node.js) stack-powered platform facilitates the efficient distribution of surplus food to those in need, fostering a more sustainable and responsible approach to food consumption.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Razorpay Integration](#razorpay-integration)
- [Contributing](#contributing)
- [License](#license)

## Features
- Donators (Restaurants) can post details of surplus raw and cooked food.
- Volunteers can view and accept donation requests.
- Users can add food items to their cart for easy management.
- Secure user authentication and role-based access control.
- Intuitive user interfaces for donators, receivers, and volunteers.
- Real-time updates on accepted donation requests.
- Easy-to-use product management and browsing.
- Integration with Razorpay for secure online payments.

## Technology Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Payment Gateway**: Razorpay
- **Email Service**: Nodemailer
- **Styling**: CSS with Bootstrap
- **Deployment**: Heroku for backend, Vercel for frontend

## Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/RescueMeals.git`
2. Navigate to the project folder: `cd RescueMeals`
3. Install backend dependencies: `npm install`
4. Navigate to the `client` folder: `cd client`
5. Install frontend dependencies: `npm install`
6. Run the backend server: `npm start` (in the project root)
7. Run the frontend development server: `npm start` (in the `client` folder)

## Razorpay Integration
RescueMeals features secure online payments via the Razorpay payment gateway. To enable this integration, you need to:
1. Sign up for a Razorpay account: [https://razorpay.com](https://razorpay.com)
2. Obtain your Razorpay API key and secret key.
3. Add your API key and secret key to the `.env` file in the backend directory:
