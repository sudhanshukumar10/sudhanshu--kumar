# 🚀 Sudhanshu Kumar | Backend Engineer

Hi, I'm **Sudhanshu Kumar** — a passionate backend developer with a love for clean architecture, scalable systems, and performance-first solutions. I specialize in **Node.js**, **Sequelize ORM**, and **MySQL**, and I love crafting robust APIs, automating workflows, and optimizing databases.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **ORM/Database:** Sequelize, MySQL
- **Utilities:** DTOs, Class Transformer & Validator, Middleware, JWT, Async Handlers
- **DevOps:** PM2, Nginx, Docker (learning)
- **Other:** TypeScript (preferred), EJS (for templating), RESTful APIs

---

## 🌟 Featured Project: `FRT - Flexible Routing Tool`

A dynamic lead-calling system built to filter and initiate calls based on parameters like language, score, and urgency.

**Key Features:**
- Intelligent lead distribution
- Real-time call triggers
- Admin-friendly configuration
- Modular codebase with DTOs

> *Technologies used:* Node.js, Express, MySQL, Sequelize, JWT, Cron Jobs

---

## 📌 Notable Highlights

- 🧠 Strong understanding of middleware pipelines and request lifecycle
- 📦 Created reusable `responseHandler` and `asyncHandler` wrappers for consistency
- 🎯 Focused on clean folder structure and code readability
- ✅ Experience in writing Sequelize models with **strict typing** and **associations**

---

## 🔧 Common Utilities I Use

```ts
// responseHandler.ts
export const responseHandler = (statusCode: number, message: string, data: any = null) => {
  return {
    success: statusCode < 400,
    statusCode,
    message,
    data,
  };
};
