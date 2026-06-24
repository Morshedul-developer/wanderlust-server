<div align="center">

# 🌍 Wanderlust — Server

**REST API backend for the Wanderlust travel app**
built with Express.js v5, Node.js & MongoDB

[![Node.js](https://img.shields.io/badge/Node.js-Express%20v5-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-v7-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)

🔗 **Frontend Repo:** [wanderlust](https://github.com/Morshedul-developer/wanderlust)

</div>

---

## 🌟 Overview

This is the backend REST API server for the Wanderlust travel discovery platform. It handles all data operations — destinations, trips, and user data — and exposes endpoints consumed by the Next.js frontend.

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Runtime | Node.js |
| Framework | Express.js v5 |
| Database | MongoDB v7 |
| Environment | dotenv |
| CORS | cors |

---

## 📁 Project Structure

```
wanderlust-server/
├── index.js          # Entry point — server & route setup
├── .gitignore
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js `v18+`
- MongoDB Atlas account
- npm

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Morshedul-developer/wanderlust-server.git
cd wanderlust-server
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

4. **Start the server**

```bash
node index.js
```

Server will run on [http://localhost:5000](http://localhost:5000).

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/` | Health check |
| GET | `/destinations` | Get all destinations |
| GET | `/destinations/:id` | Get single destination |
| POST | `/destinations` | Add new destination |

---

## 🌐 Deployment

Deploy on **Render** or **Railway** (free tiers):

1. Push code to GitHub
2. Connect repo on [render.com](https://render.com) or [railway.app](https://railway.app)
3. Add environment variables
4. Deploy!

---

## 👨‍💻 Author

**Morshedul Islam Nijhum**

[![GitHub](https://img.shields.io/badge/GitHub-Morshedul--developer-181717?style=flat&logo=github)](https://github.com/Morshedul-developer)