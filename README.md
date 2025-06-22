# 🍽️ Food App Backend

A RESTful API for a full-featured Food Delivery Application built with **Node.js**, **Express**, and **MongoDB**. This backend supports user registration, login (with JWT), restaurant management, food categories, and order processing.

> 🚀 Deployed on: _[You can add link here if deployed]_

---

## 🔧 Tech Stack

- **Node.js** & **Express.js** – server & routing
- **MongoDB** & **Mongoose** – database
- **JWT** – authentication
- **bcryptjs** – password hashing
- **dotenv** – environment variables
- **morgan** & **colors** – dev logging & styling

---

## 📁 Folder Structure

```

foods-app/
├── config/
│   └── db.js                  # MongoDB connection
├── controllers/
│   └── authController.js      # Auth logic (login/signup)
├── models/
│   └── userModel.js           # User schema
├── routes/
│   └── authRoutes.js          # Auth endpoints
│   └── testRoutes.js          # Basic test route
├── middlewares/
│   └── authMiddleware.js      # Protect routes with JWT
├── .env                       # Environment variables
├── .gitignore
├── package.json
├── server.js                  # Main server entry point

````

---

## 🚀 API Endpoints

### ✅ Auth

| Method | Route                  | Description          |
|--------|------------------------|----------------------|
| POST   | `/api/v1/auth/register`| Register user        |
| POST   | `/api/v1/auth/login`   | Login + get token    |

### 🔐 Protected (JWT required)

| Method | Route                  | Description                |
|--------|------------------------|----------------------------|
| GET    | `/api/v1/test/private` | Test JWT-protected route   |

---

## 📦 Installation

```bash
# Clone repo
git clone https://github.com/Aiden781Xx/foods-app.git
cd foods-app

# Install dependencies
npm install

# Create .env file
touch .env
````

#### ✍️ `.env` example:

```env
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## ▶️ Running the Server

```bash
# Start with nodemon
npm run dev

# OR start normally
npm start
```

Server runs on: `http://localhost:5000/`

---

## 📬 API Testing (Postman)

* Register: `POST http://localhost:5000/api/v1/auth/register`
* Login: `POST http://localhost:5000/api/v1/auth/login`
* Test: `GET http://localhost:5000/api/v1/test`

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Contribute

Feel free to fork and submit pull requests. For major changes, open an issue first.

---

## 👤 Author

**Shivam Bhardwaj**
GitHub: [@Aiden781Xx](https://github.com/Aiden781Xx)

```

---

### ✅ Next Suggestions

Would you like me to:

- Auto-generate this README in your repo?
- Add a `LICENSE` file?
- Help write a frontend README (if you're connecting React/Vite)?

Just say **"Next: deploy"**, **"Next: frontend"**, or anything else!
```
