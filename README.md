# Pdm_backend
{
  "name": "pdm-backend",
  "version": "1.0.0",
  "description": "Praise Deliverance Ministries backend prototype",
  "main": "src/app.js",
  "scripts": {
    "dev": "nodemon src/app.js",
    "start": "node src/app.js"
  },
  "dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "sequelize": "^6.32.1",
    "sqlite3": "^5.1.6",
    "pg": "^8.11.1",
    "swagger-jsdoc": "^6.2.8",
    "swagger-ui-express": "^4.6.3"
  },
  "devDependencies": {
    "nodemon": "^3.0.1"
  }
}
# Praise Deliverance Ministries Backend

Backend API prototype for Praise Deliverance Ministries, built with **Node.js**, **Express**, and **Sequelize**.  
It supports **PostgreSQL** in production (Railway) and falls back to **SQLite** for local development.

## Features
- 📖 **Prayers Catalogue** – Retrieve and store prayers
- 🗣 **Testimonies** – Submit testimonies
- 📅 **Schedules** – View and add church service schedules
- 📜 **Daily Scripture** – Random verse endpoint
- 📄 **Swagger Docs** – Auto-generated API documentation

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pdm-backend.git
   cd pdm-backend
npm install
cp .env.example .env
npm run dev
