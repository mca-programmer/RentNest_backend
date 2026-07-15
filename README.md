# 🏠 RentNest Backend API

A modern and scalable **Rental Property Management REST API** built with **Node.js, Express.js, TypeScript, Prisma ORM, and PostgreSQL**.

The system provides secure authentication, property management, rental requests, payment processing, reviews, and role-based access control for **Tenants**, **Landlords**, and **Admins**.

---

# 🚀 Live API

🔗 https://rent-nest-a4.vercel.app/

---

# 📂 GitHub Repository

🔗 https://github.com/mca-programmer/RentNest_backend

---

# 🧩 ER Diagram

🔗 https://drawsql.app/teams/musarraf-hosen/diagrams/rentnest-2

---

# 📖 Project Overview

RentNest is a rental property management platform where landlords can list rental properties, tenants can browse and request rentals, and administrators can manage the entire system securely.

The backend follows a clean RESTful API architecture with JWT authentication, role-based authorization, Prisma ORM, and PostgreSQL.

---

# ✨ Features

- 🔐 JWT Authentication & Authorization
- 👥 Role-Based Access Control (Admin, Landlord, Tenant)
- 🏠 Property Management
- 📄 Rental Request Management
- 💳 Payment Integration
- ⭐ Property Reviews & Ratings
- 👤 User Management
- 🔒 Password Hashing using bcrypt
- 📦 Prisma ORM
- 🗄 PostgreSQL Database
- 🌍 RESTful API Design
- ⚡ TypeScript Support
- ❌ Centralized Error Handling
- ✅ Request Validation
- 🌐 Environment Variable Configuration

---

# 🛠️ Tech Stack

## Backend

- Node.js
- Express.js
- TypeScript

## Database

- PostgreSQL
- Prisma ORM

## Authentication

- JWT (Access Token & Refresh Token)
- bcrypt

## Payment

- Stripe

## Development Tools

- ts-node-dev
- ESLint
- Prettier
- dotenv

---

# 📁 Project Structure

```text
src
├── app
│   ├── modules
│   ├── middleware
│   ├── routes
│   ├── utils
│   ├── interfaces
│   └── errors
│
├── config
├── prisma
├── app.ts
└── server.ts
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/mca-programmer/RentNest_backend.git
```

## Go to the Project Folder

```bash
cd RentNest_backend
```

## Install Dependencies

```bash
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file in the project root and configure the following variables:

```env
PORT=5000

DATABASE_URL=your_database_url

APP_URL=http://localhost:5000

BCRYPT_SALT_ROUNDS=10

JWT_ACCESS_TKN_SECRET=your_access_secret

JWT_REFRESH_TKN_SECRET=your_refresh_secret

JWT_ACCESS_EXPIRES_IN=1d

JWT_REFRESH_EXPIRES_IN=30d

STRIPE_SECRET_KEY=your_stripe_secret

STRIPE_PUBLISHABLE_KEY=your_publishable_key

STRIPE_WEBHOOK_SECRET=your_webhook_secret
```

---

# ▶️ Running the Project

## Development

```bash
npm run dev
```

## Production

```bash
npm run build
npm start
```

---

# 📌 API Modules

- Authentication
- Users
- Properties
- Rental Requests
- Payments
- Reviews
- Admin Dashboard

---

# 👥 User Roles

## 👤 Tenant

- Register
- Login
- Browse Properties
- Send Rental Requests
- Make Payments
- Add Reviews

---

## 🏠 Landlord

- Register
- Login
- Create Properties
- Update Properties
- Delete Properties
- Approve Rental Requests
- Reject Rental Requests

---

## 👨‍💼 Admin

- Manage Users
- Manage Properties
- Manage Rental Requests
- Manage Payments
- Dashboard Monitoring

---

# 📦 REST API Response

```json
{
  "success": true,
  "message": "Request Successful",
  "data": {}
}
```

---

# 📜 Scripts

```bash
npm run dev
npm run build
npm start
npm run lint
npm run lint:fix
```

---

# 🔒 Security Features

- JWT Authentication
- Refresh Token Support
- Password Hashing (bcrypt)
- Role-Based Authorization
- Environment Variables
- Centralized Error Handling
- Input Validation

---

# 📈 Future Improvements

- Email Verification
- Password Reset
- Image Upload
- Property Wishlist
- Real-time Notifications
- Analytics Dashboard

---

# 👨‍💻 Author

## MD Musarraf Hosen

🌐 GitHub

https://github.com/mca-programmer

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

Your support is greatly appreciated!

---

# 📄 License

This project is licensed under the MIT License.

© 2026 MD Musarraf Hosen