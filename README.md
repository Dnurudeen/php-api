# 🎯 PHP RESTful API Backend

This is a lightweight PHP backend built with an API-first approach. It exposes secure and structured endpoints (e.g., `/api/all-events`) to serve frontend clients like [Next.js](https://nextjs.org/), mobile apps, or any SPA (React, Vue, etc.).

---

## 📦 Tech Stack

- **PHP** – Backend (API Mode)
- **MySQL** – Relational Database
- **Eloquent ORM** – Data Modeling
- **CORS Enabled** – For frontend/backend separation
- **JSON API responses** – All endpoints return JSON

---

## 📁 Project Structure
/app <br>
└── Models/ <br>
└── Event.php # Event model for the events table <br><br>

/routes <br>
└── api.php # API-only routes <br><br>

/database <br>
└── migrations/ <br>

/.env # Environment configuration (DB, app keys, etc.)<br>
composer.json # PHP dependencies
