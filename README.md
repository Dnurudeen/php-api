# 🎯 Laravel 12 RESTful API Backend

This is a lightweight Laravel 12 backend built with an API-first approach. It exposes secure and structured endpoints (e.g., `/api/all-events`) to serve frontend clients like [Next.js](https://nextjs.org/), mobile apps, or any SPA (React, Vue, etc.).

---

## 📦 Tech Stack

- **Laravel 12** – Backend Framework (API Mode)
- **MySQL** – Relational Database
- **Eloquent ORM** – Data Modeling
- **Sanctum** *(optional)* – API authentication (token-based)
- **CORS Enabled** – For frontend/backend separation
- **JSON API responses** – All endpoints return JSON

---

## 📁 Project Structure
/app
└── Models/
└── Event.php # Event model for the events table

/routes
└── api.php # API-only routes

/database
└── migrations/
└── 202x_xx_xx_create_events_table.php

/.env # Environment configuration (DB, app keys, etc.)
composer.json # PHP dependencies