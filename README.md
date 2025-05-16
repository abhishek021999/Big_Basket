# Big Basket E-commerce Platform

A full-stack e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js) that provides a seamless shopping experience with modern features and secure authentication.

## 🌟 Features

- **User Authentication**
  - JWT-based authentication
  - Google OAuth 2.0 integration
  - Secure password hashing with bcrypt

- **Product Management**
  - Browse products by categories
  - Search functionality
  - Product details and specifications

- **Shopping Experience**
  - Shopping cart functionality
  - Wishlist management
  - Secure payment integration

- **User Features**
  - User profile management
  - Order history
  - Address management

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit for state management
- Chakra UI for component styling
- Framer Motion for animations
- React Router for navigation
- React Slick for carousels
- Axios for API calls

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- Passport.js for OAuth
- Express Rate Limit for API protection
- CORS enabled

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/big-basket.git
cd big-basket
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=
PORT=
ACCESS_TOKEN_SECRET_KEY=
REFRESH_TOKEN_SECRET_KEY=
```

5. Start the development servers

Backend:
```bash
cd backend
npm run server
```

Frontend:
```bash
cd frontend
npm run dev
```
Create a `.env` file in the frontend directory with the following variables:
VITE_API_URL=""
## 📦 Project Structure

```
big-basket/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── Redux-Toolkit/
│   │   └── assets/
│   └── public/
└── backend/
    ├── controllers/
    ├── models/
    ├── routes/
    ├── middlewares/
    └── db_config/
```

## 🔒 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- Rate limiting for API protection
- CORS configuration
- Secure payment processing


## 🙏 Acknowledgments

- Chakra UI for the component library
- MongoDB for the database
- Vercel for hosting 
