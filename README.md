# 🔐 Auth-API: Secure Identity Provider

[![Node.js](https://img.shields.io/badge/Node.js-v14+-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Security: JWT](https://img.shields.io/badge/Security-JWT-black?logo=json-web-tokens&logoColor=white)](https://jwt.io/)
[![Security: Bcrypt](https://img.shields.io/badge/Encryption-Bcrypt-blue)](https://www.npmjs.com/package/bcrypt)

**Auth-API** is a dedicated authentication microservice designed to handle secure user registration, login, and session management. Built with a "Security-First" mindset, it utilizes industry-standard encryption and tokenization to protect user data.

---

## 👨‍💻 Developed By
**Yehovayire Moise** *Backend Security Engineer | Kigali, Rwanda*

> "In software, security isn't a feature—it's the foundation."

---

## 🛡️ Security Features

* **🔑 JWT-Based Authorization:** Stateless authentication using JSON Web Tokens for secure cross-domain requests.
* **⚡ Password Hashing:** High-entropy salting and hashing powered by **Bcrypt v6.0**.
* **🏗️ Modern Middleware:** Built on **Express 5.x** for optimized asynchronous request flows.
* **🗄️ Schema Validation:** Strict data modeling using **Mongoose 9.x** to prevent NoSQL injection and data corruption.
* **🌐 CORS & Environment Safety:** Full separation of configuration and code using `dotenv`.

---

## 🛠️ Tech Stack

* **Server:** Node.js / Express.js
* **Database:** MongoDB (via Mongoose ODM)
* **Auth:** JSON Web Tokens (JWT)
* **Encryption:** Bcrypt
* **Dev Tools:** Nodemon

---

## 🚀 Installation & Local Setup

### 1. Clone & Dependencies
```bash
git clone [https://github.com/your-username/auth-api.git](https://github.com/your-username/auth-api.git)
cd auth-api
npm install
