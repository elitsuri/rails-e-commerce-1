# Rails E-Commerce

> E-commerce store with Rails, Stripe, PostgreSQL, and Active Storage

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Ruby, Rails, PostgreSQL, Redis, Sidekiq

## 🏗️ Architecture
Backend service with Ruby, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rails-e-commerce
cd rails-e-commerce

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
