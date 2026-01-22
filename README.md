 # 🌿 Purenation Web Application

Purenation is a full‑stack web application built using **React**, **Node.js**, and **MongoDB**. The platform is designed to provide a modern, scalable, and efficient web experience with a clean user interface and a robust backend API.

---

## 🚀 Tech Stack

### Frontend

* **React.js** – User interface
* **HTML5 / CSS3 / JavaScript**
* **Axios / Fetch API** – API communication

### Backend

* **Node.js** – Runtime environment
* **Express.js** – Web framework
* **MongoDB** – NoSQL database
* **Mongoose** – ODM for MongoDB

### Tools & Utilities

* **Git & GitHub** – Version control
* **npm** – Package manager
* **dotenv** – Environment variables
* **Postman** – API testing

---

## ✨ Features

* 🔐 User authentication (Register / Login)
* 📦 RESTful API architecture
* ⚡ Fast and responsive UI
* 🗄️ Secure data storage with MongoDB
* 🌐 Full CRUD operations
* 📱 Responsive design for all devices

---

## 📁 Project Structure

```
Purenation/
│
├── client/                # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       ├── App.js
│       └── index.js
│
├── server/                # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── .env
├── README.md
└── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/purenation.git
cd purenation
```

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside the `server` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Run the backend server:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd client
npm install
npm start
```

The application will run at:

* Frontend: `http://localhost:3000`
* Backend API: `http://localhost:5000`

---

## 🔗 API Endpoints (Example)

| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/auth/register | Register user |
| POST   | /api/auth/login    | Login user    |
| GET    | /api/items         | Get all items |
| POST   | /api/items         | Create item   |

---

## 🛡️ Environment Variables

Ensure you keep your `.env` file private and never commit it to version control.

---

## 📸 Screenshots

*Add screenshots here if available*

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Purenation Team**
Built with ❤️ using React, Node.js, and MongoDB

---

⭐ If you like this project, don’t forget to give it a star!
