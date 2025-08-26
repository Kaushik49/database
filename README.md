# Prisma & PostgreSQL Exploration

This repository contains two separate projects to explore working with **Prisma ORM** and **PostgreSQL**.  
Each project is placed in its own folder for clarity and modular experimentation.

---

## 📂 Project Structure
├── prisma-exploration/   # Playing with Prisma ORM
└── postgres-exploration/ # Raw PostgreSQL experiments
---

## 🚀 Projects

### 1. Prisma Exploration (`/prisma-exploration`)
This folder demonstrates how to use [Prisma](https://www.prisma.io/) as an ORM with a PostgreSQL database.

**Includes:**
- Prisma schema setup
- Database migrations
- Simple CRUD operations
- Example queries using Prisma Client

**Getting Started:**
```bash
cd prisma-exploration

# Install dependencies
npm install

# Generate Prisma client
npx prisma generate

# Run database migrations
npx prisma migrate dev

# Start development server (if applicable)
npm run dev
cd postgres-exploration

# Connect to Postgres (update credentials as needed)
psql -U your_user -d your_database

# Run SQL scripts
\i schema.sql
\i seed.sql
