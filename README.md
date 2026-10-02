# 📚 LibraryBoy

LibraryBoy is a full-stack library management system for managing students, shifts, fees, payments, and transactions.

## 🌐 Live Demo

👉 https://library-managment-system-five.vercel.app/


## ✨ Features

- 🔐 User authentication with Clerk
- 🏫 Create and manage library
- 👨‍🎓 Add, edit, and manage students
- 🕐 Create and manage library shifts
- 💰 Manage monthly student fees
- 💳 Support Cash and Online payments
- 🧾 View payment transactions
- 📊 Dashboard with students and revenue statistics
- 🔒 Library-specific data access

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Express, TypeScript, Bun
- **Database:** PostgreSQL, Prisma
- **Authentication:** Clerk

## 🚀 Setup

### 1. Clone the repository

```bash
git clone https://github.com/sahilguptatech01-droid/LibraryBoy.git
cd LibraryBoy

### 2. Setup backend
cd backend
bun install

Create a .env file:

DATABASE_URL="your_postgresql_database_url"
CLERK_SECRET_KEY="your_clerk_secret_key"

Setup Prisma:

bunx prisma generate
bunx prisma migrate dev

Start the backend:

bun run dev

Backend runs on:

http://localhost:3000


3. Setup Frontend

Open a new terminal:

cd frontend
npm install

Create a .env file:

VITE_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"

Start the frontend:

npm run dev

Frontend runs on:

http://localhost:5173


