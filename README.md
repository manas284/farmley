
# 🌾 Farmley - Premium Dry Fruits E-Commerce Platform

**Farmley** is a full-stack web application designed for selling premium dry fruits online. It includes features like product browsing, user authentication, cart, contact form, and admin functionality for managing products and categories.

---

## 📁 Project Structure

### Backend: Node.js + Express + MongoDB

```
farmley-backend/
│
├── controllers/        # Business logic for each route
├── models/             # Mongoose models
├── routes/             # Route definitions
├── middleware/         # Auth and error middleware
├── config/             # DB config and env variables
├── .env                # Environment variables
├── server.js           # Entry point
```

### Frontend: React

```
farmley-frontend/
│
├── pages/              # Page components (Home, Products, About, etc.)
├── components/         # Shared UI components (Header, Footer, etc.)
├── api/axios.js        # Axios instance
├── App.js              # Main router file
├── index.js            # Entry point
```

---

## 🔧 Features

### User Features:
- 🛒 Browse products by category
- 🔍 Search bar for quick access
- 🔐 Register/Login functionality
- 🧺 Add items to cart
- 📩 Contact form to reach Farmley team

### Admin Features:
- ✍️ Add/Edit/Delete products
- 📂 Category management

---

## 🚀 Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/manas284/Farmley-Backend.git
git clone https://github.com/manas284/Farmley-Frontend.git
```

### 2. Backend Setup

```bash
cd Farmley-Backend
npm install
```

Create a `.env` file with:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Then run:

```bash
npm run dev
```

### 3. Frontend Setup

```bash
cd Farmley-Frontend
npm install
npm start
```

---

## 🌐 Deployment

### Backend Deployment (Render or Railway)

1. Push to GitHub
2. Create a Render service
3. Add environment variables (from `.env`)
4. Add a `start` script to `package.json`:
```json
"scripts": {
  "start": "node server.js"
}
```

---

### Frontend Deployment (Netlify or Vercel)

1. Push frontend to GitHub
2. Connect repo to [Netlify](https://netlify.com) or [Vercel](https://vercel.com)
3. Set build command to:
```bash
npm run build
```
4. Set publish directory:
```bash
build
```

---

## 📄 Tech Stack

- **Frontend:** React, Axios, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, Bcrypt
- **Deployment:** Render (backend), Netlify (frontend)

---

## 🙋‍♂️ Contact

If you have any questions or feedback, feel free to reach out at [support@farmley.com](mailto:support@farmley.com).
