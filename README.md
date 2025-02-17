# E-commerce Website

## Overview
This is a full-fledged **E-commerce Website** built using the **MERN (MongoDB, Express, React, Node.js) Stack**. It allows users to browse products, add them to a cart, and proceed with checkout. The project is designed to be scalable and user-friendly.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **State Management:** Context API / Redux (if used)
- **Authentication:** JWT (if implemented)

## Features
- User Authentication (Login/Signup)
- Product Listing & Details Page
- Add to Cart Functionality
- Checkout Process
- Order Management
- Admin Dashboard (if implemented)

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Node.js (v16 or later)
- MongoDB
- Git

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/MallikaSingh1773/EcommerceWebsite.git
   cd EcommerceWebsite
   ```

2. **Backend Setup**
   ```sh
   cd backend
   npm install
   npm start
   ```
   The backend will start running at `http://localhost:5000`

3. **Frontend Setup**
   ```sh
   cd frontend
   npm install
   npm start
   ```
   The frontend will start running at `http://localhost:3000`

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/products` | Fetch all products |
| GET | `/api/products/:id` | Fetch product details |
| POST | `/api/users/login` | User login |
| POST | `/api/users/register` | User registration |
| POST | `/api/orders` | Place an order |

## Contributing
Contributions are welcome! If you’d like to contribute, please fork the repository and submit a pull request.


