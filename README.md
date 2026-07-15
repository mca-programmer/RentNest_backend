<div align="center">

# 🏠 RentNest
### Rental Property Management REST API

`Node.js` · `Express` · `TypeScript` · `Prisma` · `PostgreSQL` · `Stripe`

**[🔴 Live API](https://rent-nest-a4.vercel.app/)** &nbsp;·&nbsp; **[🧩 ER Diagram](https://drawsql.app/teams/musarraf-hosen/diagrams/rentnest-2)** &nbsp;·&nbsp; **[📦 Repo](https://github.com/mca-programmer/RentNest_backend)**

</div>

<br/>

A secure, role-based REST API for rental property management — Landlords list properties, Tenants browse & request rentals, Admins oversee the platform.

## Features

> 🔐 JWT Auth &nbsp;|&nbsp; 👥 RBAC &nbsp;|&nbsp; 🏠 Property Management &nbsp;|&nbsp; 📄 Rental Requests &nbsp;|&nbsp; 💳 Stripe Payments &nbsp;|&nbsp; ⭐ Reviews &nbsp;|&nbsp; ❌ Centralized Errors &nbsp;|&nbsp; ✅ Validation

## Roles

| 👤 Tenant | 🏠 Landlord | 👨‍💼 Admin |
|---|---|---|
| Browse & request rentals | List & manage properties | Manage users & platform |
| Make payments | Approve / reject requests | Monitor dashboard |
| Leave reviews | — | Full access control |

## Getting Started

```bash
git clone https://github.com/mca-programmer/RentNest_backend.git
cd RentNest_backend
npm install
```

**`.env`**
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

```bash
npm run dev                  # development
npm run build && npm start   # production
```

## Structure

```text
src
├── app/{modules, middleware, routes, utils, interfaces, errors}
├── config
├── prisma
├── app.ts
└── server.ts
```

## API Response Format

```json
{ "success": true, "message": "Request Successful", "data": {} }
```

## Scripts

`npm run dev` · `npm run build` · `npm start` · `npm run lint` · `npm run lint:fix`

## Roadmap

Email Verification · Password Reset · Image Upload · Wishlist · Real-time Notifications · Analytics

---

<div align="center">

**MD Musarraf Hosen** — [@mca-programmer](https://github.com/mca-programmer)

⭐ Star this repo if you found it useful · MIT License © 2026

</div>