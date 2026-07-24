# 🏥 HealthFlow SaaS

> A modern **multi-tenant Healthcare Management SaaS** built with **Ruby on Rails 8.1**, **React**, and **Vite**.

HealthFlow SaaS is a full-stack healthcare management platform designed for clinics and healthcare providers. It offers secure tenant-isolated APIs, JWT authentication, appointment scheduling, billing, prescription management, analytics dashboards, and a modern React frontend.

---

# ✨ Features

## 🔐 Authentication & Authorization

* JWT-based authentication
* Secure user signup & login
* Protected React routes
* Role-based access control
* Tenant-aware authentication

---

## 🏢 Multi-Tenant Architecture

* Complete tenant isolation
* Request-based tenant resolution
* Tenant-scoped database access
* Current user & tenant context
* Cross-tenant access protection

---

## 👨‍⚕️ Patient Management

* Patient registration
* Patient listing
* Tenant-specific records
* Secure CRUD operations

---

## 📅 Appointment Management

* Create appointments
* View appointments
* Prevent double booking
* Transaction-safe appointment creation
* Appointment reminder jobs

---

## 💊 Prescription & Inventory

* Prescription creation
* Inventory management
* Automatic medicine stock deduction
* Transaction-safe inventory updates

---

## 💳 Billing & Payments

* Invoice management
* Idempotent payment processing
* Safe payment retries
* Payment history

---

## 📊 Analytics Dashboard

Interactive dashboard with:

* 📈 Revenue reports
* 👥 Patient visit statistics
* 💊 Medicine usage analytics
* 📉 Charts powered by Recharts

---

## ⚙️ Background Jobs

* Sidekiq integration
* Redis-backed job queue
* Appointment reminder workers

---

## 📚 API Documentation

* OpenAPI specification
* Swagger UI using Rswag

---

## 🔒 Security

* JWT Authentication
* Rack::Attack rate limiting
* Global error handling
* Structured JSON logging
* Sensitive parameter filtering

---

## 🚀 Performance

* Redis caching
* Optimized database indexes
* Service Object architecture
* Transaction-safe operations

---

# 🛠️ Tech Stack

## Backend

* Ruby on Rails 8.1
* PostgreSQL
* Redis
* Sidekiq
* JWT
* Rswag
* Rack::Attack

## Frontend

* React
* Vite
* React Router
* Axios
* Bootstrap
* Recharts

## DevOps

* Docker
* Docker Compose

---

# 📁 Project Structure

```text
app/
├── controllers/
├── models/
├── services/
├── jobs/
├── middleware/
├── javascript/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── routes/
└── views/
```

---

# 🚀 Getting Started

## 📌 Prerequisites

* Ruby 3.3+
* Rails 8.1
* PostgreSQL
* Redis
* Node.js 20+
* npm or Yarn

---

## 📥 Clone Repository

```bash
git clone https://github.com/rounakpatidar18-dev/healthflow-saas.git
cd healthflow-saas
```

---

## 📦 Install Dependencies

### Ruby Gems

```bash
bundle install
```

### Node Packages

```bash
npm install
```

---

## 🗄️ Database Setup

```bash
bin/rails db:create
bin/rails db:migrate
```

---

## 🔑 Environment Variables

Create an environment file:

```bash
cp .env.example .env
```

Configure the required environment variables.

---

## ▶️ Run the Application

```bash
bin/dev
```

Application will be available at:

* 🌐 Frontend: http://localhost:3000
* ⚙️ Backend API: http://localhost:3000

---

# 📖 API Documentation

After running the application, Swagger UI is available at:

```text
/api-docs
```

---

# 🏗️ Architecture Highlights

* ✅ Multi-Tenant SaaS Architecture
* ✅ JWT Authentication
* ✅ RESTful APIs
* ✅ Service Object Pattern
* ✅ Background Jobs with Sidekiq
* ✅ Redis Caching
* ✅ React + Vite Frontend
* ✅ API-first Design
* ✅ Transaction-safe Business Logic

---

# 🌟 Implemented Modules

* ✅ Authentication
* ✅ Multi-Tenant Support
* ✅ Dashboard
* ✅ Patients
* ✅ Appointments
* ✅ Prescriptions
* ✅ Inventory
* ✅ Billing
* ✅ Payments
* ✅ Analytics
* ✅ Background Jobs
* ✅ API Documentation

---

# 🚧 Future Enhancements

* 📧 Email Notifications
* 📱 SMS Appointment Reminders
* 👨‍⚕️ Doctor Scheduling
* 📂 File Uploads
* 📝 Audit Logs
* 💬 Real-time Notifications
* ☁️ CI/CD Pipeline
* ☸️ Kubernetes Deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is intended for educational and portfolio purposes.

---

## 👨‍💻 Author

**ROUNAK**

Built with ❤️ using **Ruby on Rails**, **React**, and **Vite**.
