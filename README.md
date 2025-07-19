# 🍔 Food Delivery Platform

A full-stack food delivery web application built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and integrated with **Stripe** for secure online payments.

---

## 🚀 Features

- 🛍️ Browse restaurant menus and food items
- 🛒 Add/remove items from cart with quantity control
- 🔐 User authentication using JWT (Login & Register)
- 💳 Stripe integration for secure online payments
- 📦 Place orders with real-time tracking
- 🧑‍💼 Admin panel to manage products and orders
- 📱 Fully responsive design (mobile + desktop)

---

## 🧰 Tech Stack

| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React.js, Tailwind CSS         |
| Backend    | Node.js, Express.js            |
| Database   | MongoDB with Mongoose          |
| Auth       | JSON Web Tokens (JWT)          |
| Payments   | Stripe API                     |

---

## 📁 Folder Structure

```
react-food-delivery-platform/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
├── frontend/
│   ├── src/
│   └── public/
├── .gitignore
├── README.md
└── package.json
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `backend/` folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

> ✅ Be sure to add `.env` to `.gitignore` to avoid pushing secrets to GitHub.

---

## 🧑‍💻 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/satishkoppanathi/react-food-delivery-platform.git
cd react-food-delivery-platform
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 4. Run the Project

```bash
# Start backend
cd backend
npm run dev

# Start frontend (in a new terminal)
cd ../frontend
npm start
```

---

## 💳 Stripe Test Card

Use the following Stripe test card to simulate payments:

```
Card Number: 4242 4242 4242 4242
Expiry Date: Any future date
CVV: Any 3 digits
ZIP: Any 5 digits
```

---


## 📬 Contact

**Satish Koppanathi**  
📧 Email: satishkoppanathi2005@gmail.com  

---

> 🌟 Feel free to ⭐ star this repo if you found it useful!
