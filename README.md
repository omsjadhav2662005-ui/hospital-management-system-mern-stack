# Hospital Management System (MERN Stack)

## 🏥 Overview
This is a **Hospital Management System** built with the **MERN stack** — **MongoDB**, **Express.js**, **React.js**, and **Node.js**. It provides role-based access for administrators, medical staff, and patients to manage appointments, doctor profiles, patient records, and hospital operations.

## 🚀 Features
✔️ User authentication (login/signup)  
✔️ Role-based access control (Admin / Patient / Doctor)  
✔️ Patient appointment booking and management  
✔️ Doctor management (add/view/update/delete)  
✔️ Secure JWT authentication  
✔️ API endpoints for CRUD operations  
✔️ Modular backend structure  
✔️ User-friendly frontend interface

## 🧰 Tech Stack
**Frontend**
- React.js (UI)
- React Router
- Axios (API calls)
- CSS / Tailwind CSS (optional)

**Backend**
- Node.js
- Express.js
- MongoDB (Atlas or local)
- Mongoose (ORM)
- JSON Web Tokens (JWT)

## 🔧 Prerequisites
Before running locally, make sure you have installed:
- **Node.js** (v14+)
- **MongoDB** (local or remote Atlas)
- **npm** or **yarn**

## 🚀 Installation

### 1. Clone the repository
```bash
git clone https://github.com/omsjadhav2662005-ui/hospital-management-system-mern-stack.git
2. Backend Setup
cd hospital-management-system-mern-stack/backend
npm install

Create a .env file:

PORT=5000
MONGO_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret>
3. Frontend Setup
cd ../frontend
npm install

Create a .env file:

REACT_APP_API_URL=http://localhost:5000/api
▶️ Running the Application
Backend
cd backend
npm start
Frontend
cd frontend
npm start

Open your browser and go to:

http://localhost:3000
📌 API Endpoints (Example)

POST /api/auth/signup – User signup

POST /api/auth/login – Login

GET /api/patients – List patients

POST /api/appointments – Create appointment

GET /api/doctors – List doctors

You can expand this section with detailed routes for patients, doctors, admin, and appointments.

📦 Environment Variables
Variable	Description
MONGO_URI	MongoDB connection URI
JWT_SECRET	Secret for JWT auth
PORT	Backend port
💡 Features to Add (Future Work)

✔ Online payment integration (Razorpay / Stripe)
✔ Real-time notifications with WebSockets
✔ Admin dashboard analytics
✔ Multi-department support
✔ Email/OTP verification

❓ Contributing

Contributions are welcome! Feel free to open an issue or pull request.

📄 License

This project is open source — feel free to use, modify, and redistribute.
