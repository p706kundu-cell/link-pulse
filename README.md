# 🔗 Link Pulse

Link Pulse is a URL shortener and link analytics application built with
Next.js, Node.js, Express, PostgreSQL, Redis, and Docker.

## 🚀 Features

- Create short URLs from long URLs
- Redirect users using short URLs
- View link analytics
- Track clicks
- Store link and click data in PostgreSQL
- Use Redis for caching and background jobs
- Rate limiting for API requests
- Dockerized PostgreSQL and Redis
- Next.js frontend
- Express.js backend

## 🛠️ Tech Stack

### Frontend
- Next.js
- React
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- Sequelize
- PostgreSQL
- Redis
- BullMQ

### DevOps
- Docker
- Docker Compose
- Git & GitHub

## 📁 Project Structure

```text
link-pulse/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── queues/
│   │   ├── routes/
│   │   └── server.js
│   ├── Dockerfile
│   ├── docker-compose.yml
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── components/
│   │   └── services/
│   └── package.json
│
├── .gitignore
└── README.md
