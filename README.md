# 🌿 AyurSutra – Panchkarma Wellness Platform

AyurSutra is a full-stack wellness platform focused on Panchkarma therapies, enabling users to explore services, book treatments, and manage wellness journeys seamlessly.

---

## 🚀 Features

* 🧘‍♂️ Explore Panchkarma therapies and wellness services
* 📅 Booking and scheduling system
* 👤 User authentication and management
* 💳 (Optional) Payment integration
* 📊 Admin dashboard for managing services/users

---

## 🏗️ Project Structure

```
AyurSutra/
├── ayursutra-backend   # Backend (Node.js / Express)
└── ayursutra-frontend  # Frontend (React)
```

---

## ⚙️ Tech Stack

### Frontend

* React.js
* Axios
* Tailwind CSS / CSS

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/ArPiT-1310/AyurSutra---Panchkarma-Wellness-Platform.git
cd AyurSutra---Panchkarma-Wellness-Platform
```

---

### 2️⃣ Setup Backend

```bash
cd ayursutra-backend
npm install
```

Create a `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Setup Frontend

```bash
cd ../ayursutra-frontend
npm install
npm start
```

---

## 🔗 API Endpoints (Example)

| Method | Endpoint      | Description         |
| ------ | ------------- | ------------------- |
| GET    | /api/services | Get all services    |
| POST   | /api/auth     | User login/register |
| POST   | /api/book     | Book a service      |

---

## 📌 Future Improvements

* 🔐 Role-based authentication (Admin/User)
* 💳 Payment gateway integration
* 📱 Mobile responsiveness improvements
* 🌐 Deployment (AWS / Vercel / Render)

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Arpit**
GitHub: https://github.com/ArPiT-1310

---
