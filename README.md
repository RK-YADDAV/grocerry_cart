# Grocery Cart – MERN Stack E-Commerce Application

## 📄 Overview

**Grocery Cart** is a full-stack **MERN-based E-Commerce platform** designed to streamline online grocery shopping for both buyers and sellers. The application features two independent portals that support real-time cart management, secure payment processing, inventory management, and seamless user experiences across devices.

The project incorporates modern web development best practices, secure authentication mechanisms, and third-party payment integration to build a scalable and efficient e-commerce solution.

---

## 🛠️ Key Components

### User Portals

* **Buyer Portal:** Enables users to browse products, add items to the cart, place orders, track order status, and make secure online payments.
* **Seller Portal:** Allows sellers to add, update, and manage inventory, as well as view and process incoming orders.

### Authentication

* **JWT-Based Authentication:** Separate JWT tokens for buyers and sellers to ensure secure, role-based access and protected route management.

### Payment Integration

* **Stripe Payment Gateway:** Provides a secure and reliable payment experience, with real-time payment validation and transaction support.

### UI/UX

* **Prebuilt, Responsive UI Components:** Utilizes reusable components for consistent styling and optimized performance across devices.

### State Management

* **Redux Integration:** Efficiently manages cart operations, user sessions, and inventory updates across the application.

---

## 🚀 Tech Stack

| Technology         | Purpose                     |
| ------------------ | --------------------------- |
| **React.js**       | Frontend Framework          |
| **Redux**          | State Management            |
| **Node.js**        | Backend Runtime Environment |
| **Express.js**     | Backend Framework           |
| **MongoDB**        | NoSQL Database              |
| **Mongoose**       | MongoDB ODM                 |
| **Stripe API**     | Payment Gateway Integration |
| **JWT**            | Authentication              |
| **Axios**          | API Communication           |
| **Vercel/Netlify** | Deployment (Frontend)       |
| **Render/Heroku**  | Deployment (Backend)        |

---

#### Backend: Create a `.env` file inside the `backend` directory:

```env
MONGODB_URI=YOUR_MONGODB_URI
JWT_SECRET='YOUR_JWT_SECRET'
NODE_ENV='development'

# Admin Credentials
SELLER_EMAIL='YOUR_SELLER_EMAIL'
SELLER_PASSWORD='YOUR_SELLER_PASSWORD'

# Cloudinary
CLOUDINARY_CLOUD_NAME='YOUR_CLOUDINARY_CLOUD_NAME'
CLOUDINARY_API_KEY='YOUR_CLOUDINARY_API_KEY'
CLOUDINARY_API_SECRET='YOUR_CLOUDINARY_API_SECRET'

# Stripe
STRIPE_PUBLISHABLE_KEY='YOUR_STRIPE_PUBLISHABLE_KEY'
STRIPE_SECRET_KEY='YOUR_STRIPE_SECRET_KEY'
STRIPE_WEBHOOK_SECRET='YOUR_STRIPE_WEBHOOK_SECRET'
```

Start the Application

#### Backend

```bash
npm start
```

#### Frontend

```bash
npm run dev
```

## 📚 Usage

Once the servers are running:

* Access the **Buyer Portal** at `http://localhost:4000`
* Access the **Seller Portal** through separate login credentials.

### Example Workflow:

1. Buyer registers and logs in.
2. Buyer browses products and adds items to cart.
3. Buyer proceeds to checkout and completes payment using Stripe.
4. Seller logs in to view and process incoming orders.

---

## 💡 Features

* Dual-portal system for buyers and sellers.
* Secure JWT-based authentication and route protection.
* Real-time cart and order updates.
* Stripe-based payment processing.
* Clean, modular frontend using prebuilt components.
* Scalable backend using RESTful APIs.

---
