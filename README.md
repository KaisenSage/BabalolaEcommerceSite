Here’s the updated `README.md` for your **EcommerceWebsite** project:

---

# EcommerceWebsite

This project is part of the ALX software application program. The **EcommerceWebsite** is a modern e-commerce platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with Chakra UI for styling. It is designed to provide a responsive and dynamic user experience for online shopping.

## Tech Stack

- **Frontend:** React.js, Chakra UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Deployment:** [Render](https://render.com/)

## Features

- User Authentication (Login, Signup)
- Product Listings with Search and Filter
- Shopping Cart
- Order Management and History
- Responsive UI built with Chakra UI
- REST API built with Express.js and MongoDB

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KaisenSage/EcommerceWebsite.git
   ```

2. **Install dependencies for both frontend and backend:**
   ```bash
   # Frontend
   cd EcommerceWebsite/frontend
   npm install

   # Backend
   cd ../backend
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the `backend` directory with the following:

   ```bash
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```

4. **Run the app:**

   To build the frontend and start the project:

   ```bash
   # Frontend
   cd frontend
   npm run build

   # Backend
   cd ../backend
   npm start
   ```

5. **Access the app:**
   - The app will be available at `http://localhost:3000`.

## Deployment

This project is deployed on [Render](https://render.com/). You can access the live application at:

https://ecommercewebsite-wccj.onrender.com

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.

---
