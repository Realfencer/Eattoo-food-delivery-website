# Eattoo 🍽️ – MERN Stack Food Delivery App

**Eattoo** is a full-stack food delivery web application built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to browse food items, place orders, and make payments securely via Stripe. It also includes an Admin Panel to manage the platform effectively.

---

## 🚀 Features

### 👨‍🍳 User Side
- Browse categorized food items
- Add to cart and place orders
- Secure Stripe payments
- JWT-based user authentication
- Track order status

### 🛠 Admin Panel
- Admin login with protected routes
- Add/Edit/Delete food items
- View and manage users & orders
- Basic analytics dashboard (optional)

### ⚙️ Backend
- RESTful API with Express.js
- MongoDB (via Mongoose)
- JWT Authentication
- Stripe Payment Integration

---

## 🧱 Tech Stack

| Layer         | Tech Used                           |
|---------------|-------------------------------------|
| **Frontend**  | React.js, Axios, React Router       |
| **Backend**   | Node.js, Express.js                 |
| **Database**  | MongoDB + Mongoose ODM              |
| **Authentication** | JWT + bcryptjs                 |
| **Payments**  | Stripe (Checkout Integration)       |
| **Admin Panel** | React-based UI for admins         |

---

## 📁 Folder Structure

```bash
Eattoo/
├── client/               # React frontend (User)
├── admin/                # Admin Panel (React)
├── server/               # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── config/
├── .env.example
├── .gitignore
└── README.md
````

---

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Eattoo.git
cd Eattoo
```

### 2. Backend Setup (`/server`)

```bash
cd server
npm install
```

Create a `.env` file using the sample provided:

```bash
cp ../.env.example .env
```

Then start the backend:

```bash
npm run dev
```

### 3. Frontend Setup (`/client`)

```bash
cd ../client
npm install
npm start
```

### 4. Admin Panel Setup (`/admin`)

```bash
cd ../admin
npm install
npm start
```

---

## 🔐 Example `.env` File

Here’s a sample `.env` for your backend (`server/.env`):

```env
PORT=5000
MONGO_URI=mongodb+srv://your-db-uri
JWT_SECRET=yourSuperSecretKey123

STRIPE_SECRET_KEY=sk_test_your_secret_key
STRIPE_PUBLISHABLE_KEY=pk_test_your_publishable_key
CLIENT_URL=http://localhost:3000
```

> ⚠️ Add `.env` to `.gitignore` to keep credentials private.

---

## ✅ To Do

* [x] Add Stripe payment gateway
* [x] JWT-based authentication
* [ ] Add delivery tracking
* [ ] Admin charts and analytics
* [ ] SMS/email order updates (Twilio/SendGrid)

---

## 📸 Screenshots

> *You can add screenshots for UI/UX here.*

```markdown
![User Interface](screenshots/user-ui.png)
![Admin Panel](screenshots/admin-ui.png)
```

---

## 🧑‍💻 Author

* **Project Name:** Eattoo
* **Tech Stack:** MERN + Stripe + JWT
* **Developed by:** [sliger](https://github.com/Realfencer)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* [Stripe Docs](https://stripe.com/docs)
* [JWT.io](https://jwt.io)
* [React Router](https://reactrouter.com/)


