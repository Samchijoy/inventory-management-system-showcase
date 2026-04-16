## 📦 Inventory Management System (Showcase)

A full-stack inventory management system built to support real-world business operations across multiple departments and warehouse locations.

The system enables companies to track stock levels, manage inventory movements, and coordinate workflows between sales, warehouse, purchasing, and production teams.

Designed with scalability, role-based access, and deployment flexibility in mind.

---

## 🎯 Key Features

* Multi-warehouse inventory tracking
* Stock movement management (inbound, outbound, transfers)
* Role-based access control (Admin, Manager, Sales, Warehouse, etc.)
* User management system with permission-based roles
* Google Sheets integration for reporting (optional)
* Secure environment-based configuration
* Automated setup and deployment workflow

---

## 🧠 System Architecture

The system follows a modular architecture designed for scalability and real-world usage:

* **Frontend**: TypeScript-based web application
* **Backend**: Supabase (authentication, database, API)
* **Database**:

  * Structured tables for inventory, users, and transactions
  * SQL functions, triggers, and views
  * Row Level Security (RLS) for data protection
* **Environment Management**:

  * Secure configuration using `.env.local`
  * Separation of public and service-level keys

This architecture supports multi-role operations and ensures secure, scalable data handling.

---

## ⚙️ Setup & Deployment

The project includes a one-command setup script for quick deployment:

```bash
./CLONE-UI.sh
```

This script automatically:

* Clones the repository
* Installs dependencies
* Configures environment variables
* Prepares the application for local development or production

### Requirements

* Node.js (v18 or higher)
* Git
* Supabase project with database initialized

---

## 🗄️ Database Setup

The system includes a full database setup script:

* Creates tables, views, and relationships
* Implements triggers and business logic
* Enforces Row Level Security (RLS)
* Supports role-based access control

Database initialization is done via:

```sql
CLONE-DB.sql
```

Executed inside the Supabase SQL Editor.

---

## 👥 User Roles

The system supports multiple operational roles:

* admin
* manager
* sales
* warehouse
* production
* purchasing
* production_manager
* purchasing_manager

Each role is assigned controlled access based on business responsibilities.

---

## 🎥 Demo

(https://www.youtube.com/@SAMCHIKO)

---

## 🖼️ Screenshots

(Will add screeshots here)

---

## 🤖 AI-Assisted Development

AI tools were used to:

* Assist in structuring parts of the application
* Validate logic and workflows
* Improve development efficiency

All core architecture, database design, and system logic were designed and implemented manually.

---

## 🚀 Future Improvements

* Real-time inventory synchronization across clients
* Advanced analytics and reporting dashboard
* API integrations with external systems (ERP, e-commerce)
* Mobile-friendly interface
* Notification and alert system

---

## 🔒 Note

The full source code is kept private, but is available upon request for evaluation or technical discussion.

---

## 📌 Summary

This project demonstrates:

* End-to-end system design
* Real-world business logic implementation
* Deployment-ready architecture
* Integration of frontend, backend, and database systems

Built as a practical solution for inventory and operations management.
