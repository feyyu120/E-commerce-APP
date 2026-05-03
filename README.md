# 🛍 LuxeCart E-commerce

LuxeCart is a modern full-stack e-commerce platform built with React + TypeScript and Node.js (Express) + MongoDB.  
It provides a seamless shopping experience with AI assistance, secure authentication, and a powerful admin dashboard.

---

## 🚀 Live Demo

🌐 Frontend (Vercel):  
👉 https://e-commerce-csec-astu-bootcamp-ntct3vv0z.vercel.app/

---

## 🧠 Key Features

### 👤 User Features
- Browse products (Home, Shop)
- View product details
- Add to cart (Login required)
- Secure authentication (JWT)
- Forgot password with email support
- Order tracking via email updates
- Integrated payment using Chapa

---

### 🤖 AI Assistant (RAG Integration)
- Ask questions about:
  - Products
  - Website usage
  - General help
- Smart responses using AI-powered retrieval system

---
### 🛠 Admin Dashboard
- Manage users (suspend/activate accounts)
- Manage products (CRUD operations)
- Manage orders:
- Pending
- Shipped
- Completed
- View user messages / feedback
- Send automatic email updates
- Cart management (admin can view/delete user cart items)
- User analytics and statistics
---
### 🛠 Admin Dashboard
- Manage users
- Manage products
- Manage orders:
  - Pending
  - Shipped
- View user messages / feedback
- Send automatic email updates

---

### 📧 Email System (Nodemailer)
- Login notifications
- Password reset emails
- Order status updates (e.g., shipped)
- Email verification
- Admin notifications

---

## 🧱 Tech Stack

### Frontend
- React
- TypeScript
- Vite

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### Other Integrations
- Chapa Payment Gateway
- Nodemailer (Email)
- AI (RAG System)

---

## 📁 Project Structure
```bash
project/
│
├── frontend/                 # React + TypeScript (User & Admin UI)
│   ├── src/
│   │   ├── components/      # Reusable components
│   │   ├── pages/          # Page components
│   │   ├── context/        # React contexts
│   │   ├── lib/            # Utilities
│   │   └── types/          # TypeScript types
│   ├── public/
│   └── package.json
│
├── backend/                  # Express + MongoDB API
│   ├── src/
│   │   ├── models/         # MongoDB models
│   │   ├── routes/         # API routes
│   │   ├── middleware/     # Express middleware
│   │   ├── utils/          # Utility functions
│   │   └── server.js       # Server entry point
│   └── package.json
│
└── README.md                # This file
```
---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/feyyu120/E-commerce-APP.git
cd E-commerce-APP
```

---

## 🔧 Backend Setup
```bash
cd backend
npm install
```
### Create .env file inside backend/
```bash
 PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key_here

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_app_password

CHAPA_SECRET_KEY=your_chapa_secret_key

FRONTEND_URL=http://localhost:5173
CLIENT_URL=http://localhost:5173
```
### Run backend
```bash
npm run dev
```

---

## 💻 Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
---

## 🔐 Authentication Flow

- JWT-based authentication
- Token stored securely
- Protected routes (cart, checkout)
- Email verification & password reset

### Admin Credentials
Email: admin@gmail.com
Password: 1234567


---

## 💳 Payment Integration

- Chapa payment gateway
- Secure transaction handling
- Order confirmation after payment

---

## 🤝 Team Members

- Feysel
- Hayat
- Meaza
- Sarendem

---

## 📌 Usage Flow

1. User visits homepage
2. Browse products
3. Login to add to cart
4. Checkout with payment
5. Receive email confirmation
6. Track order updates
### Login to admin panel - Using admin credentials
Manage products - Add/edit/delete products
Manage users - View/suspend user accounts
Process orders - Update order status
View analytics - Dashboard statistics
---

## 🔄 Git Workflow (Team)

git checkout -b feature-name
git add .
git commit -m "your message"
git push origin feature-name

---

## ⚠️ Notes

- Do not push .env files
- Use .env.example for sharing variables
- Always pull latest changes before working:
```bash
git pull origin main
```
---

## 📄 License

This project is for educational purposes.

---

## ❤️ Acknowledgment

- Built with teamwork and dedication by the LuxeCart team 🚀
- Special thanks to:
- CSEC ASTU Bootcamp organizers
- Open source community
- Our mentors and supporters
## 📞 Support
### For questions or support:
- Create an issue in the GitHub repository
- Contact the development team
- Check the documentation for common solutions
### Happy Shopping! 🛍️
