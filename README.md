# Professional Project Portfolio

## 👨‍💻 About Me

I am a **Senior Full-Stack Web Developer** with 5+ years of experience building scalable and high-performance web applications using **React.js, Next.js, Node.js, Express.js, REST APIs, MySQL, SQL Server, and MongoDB**.

My experience includes developing applications across **retail, dairy management, enterprise administration, wellness, and SaaS-oriented business domains**.

This repository provides an overview of my professional project experience, technical contributions, architecture patterns, and key responsibilities.

> **Note:** Project details are presented at a high level for portfolio purposes. Proprietary business logic, confidential information, credentials, internal URLs, and client-sensitive source code are intentionally excluded.

---

# 📂 Professional Projects

## 1. NRTAIL – Retail Shop Management Platform

### 📌 Overview

NRTAIL is a **full-stack retail shop management platform** designed to support multiple shop categories and branches. The platform provides modules for retail operations, inventory-related activities, transactions, grading, master data, and reporting.

### 🔗 Project Links

- 🌐 **Live Production:** : (http://nrtailjs.nisanapps.com:3002/signin) *(Production environment is client-restricted and not publicly accessible)*

### 🛠️ Technology Stack

* **Frontend:** Next.js, React.js
* **Rendering:** Server-Side Rendering (SSR)
* **Backend:** Node.js, Express.js
* **Database:** MySQL
* **API:** REST APIs
* **Authentication:** Role-Based Access Control
* **Version Control:** Git

### 🚀 Key Features

* Multi-company and multi-branch management
* Company and branch-based login provisioning
* Live Sale management
* Live Grading
* Transaction management
* Master data management
* Reports
* Dynamic filtering
* Sorting
* Pagination
* Retail data management

### 👨‍💻 My Contributions

* Developed the application using **Next.js and React.js**.
* Implemented **SSR** to improve initial page loading and SEO.
* Developed RESTful APIs using **Node.js and Express.js**.
* Integrated APIs with **MySQL** for retail data management.
* Implemented dynamic **filtering, sorting, and pagination**.
* Developed role-based access and company/branch-level login functionality.
* Worked on modules including **Live Sale, Live Grading, Transactions, Masters, and Reports**.
* Contributed to frontend and backend development across the application.

### 🏗️ High-Level Architecture

```text
                    ┌──────────────────────┐
                    │      End User        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Next.js / React.js │
                    │        Frontend      │
                    └──────────┬───────────┘
                               │
                          REST API
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Node.js + Express.js │
                    │      Backend API     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │        MySQL         │
                    │       Database       │
                    └──────────────────────┘
```

---

# 2. NSAP – Super Admin Dashboard

### 📌 Overview

NSAP is a **Super Admin Dashboard** developed to manage companies, servers, and hosting-related payment information from a centralized administration platform.

### 🔗 Project Links

- 🌐 **Live Production:** : (http://154.61.75.36:3021/signin) *(Production environment is client-restricted and not publicly accessible)*
- 
### 🛠️ Technology Stack

* **Frontend:** Next.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **API:** REST APIs
* **Integration:** UltraMsg WhatsApp API
* **Version Control:** Git

### 🚀 Key Features

* Company management
* Server management
* Hosting payment management
* CRUD operations
* Centralized administration
* Automated WhatsApp notifications

### 👨‍💻 My Contributions

* Developed the Super Admin Dashboard using **Next.js**.
* Developed REST APIs using **Node.js and Express.js**.
* Implemented CRUD operations using **MongoDB**.
* Integrated the **UltraMsg WhatsApp API**.
* Implemented automated notifications for company creation and updates.
* Developed frontend and backend modules for administration workflows.

### 🏗️ High-Level Architecture

```text
                    ┌──────────────────────┐
                    │      Admin User      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       Next.js        │
                    │      Dashboard       │
                    └──────────┬───────────┘
                               │
                          REST API
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Node.js + Express.js │
                    │      Backend API     │
                    └───────┬───────┬──────┘
                            │       │
                            ▼       ▼
                    ┌──────────┐  ┌──────────────┐
                    │ MongoDB  │  │ UltraMsg API │
                    └──────────┘  └──────────────┘
```

---
