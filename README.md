☁️ Cloud-Based E-Commerce Microservices System

📌 Overview

This project is a cloud-based microservices architecture designed for an e-commerce platform. It demonstrates modern cloud computing concepts such as scalability, distributed systems, secure communication, and event-driven architecture.

The system is built using Node.js and follows a modular microservices approach where different services handle specific functionalities.

---

 🏗️ System Architecture

The project follows a microservices architecture where each service is independent and communicates via APIs and messaging queues.

 Key Components:

* E-commerce Backend Service** – Handles cart, inventory, and payment operations
* Patient Service** – Secondary microservice (for distributed architecture demonstration)
* RabbitMQ** – Event-driven communication between services
* Database Layer** – MongoDB for data storage
* Security Layer** – Authentication & encryption mechanisms

---

🚀 Technologies Used

* Backend:** Node.js, Express.js
* Database:** MongoDB
* Messaging Queue:** RabbitMQ
* Authentication:** Keycloak (IAM)
* Version Control:** Git & GitHub
* Security:** AES Encryption, HTTPS (TLS)

---

🔐 Security Features

* Role-Based Access Control (RBAC)
* Secure API endpoints
* Data encryption using AES
* HTTPS communication (TLS)
* Authentication via Keycloak

---

 📂 Project Structure

```
e-commerce-project/
│
├── ecommerce-backend/
│   ├── src/
│   │   ├── config/
│   │   ├── routes/
│   │   ├── services/
│   │   └── consumers/
│   ├── server.js
│   └── package.json
│
├── patient-service/
│
├── README.md
└── .gitignore
```

---

⚙️ Features Implemented

* Cart Management System
* Inventory Management
* Payment Processing
* Discount Service
* Event-driven communication using RabbitMQ
* Microservices-based modular design

---

 🔄 API Modules

* `/cart` → Cart operations
* `/inventory` → Inventory tracking
* `/payment` → Payment processing

---

 ⚙️ Installation & Setup

 1. Clone Repository

```bash
git clone https://github.com/evelinrosems/e-commerce-_.git
cd e-commerce-_
```

 2. Install Dependencies

```bash
npm install
```

 3. Run the Application

```bash
node server.js
```

---

📡 How It Works

1. Client sends request to backend
2. Backend processes request via routes
3. Services handle business logic
4. RabbitMQ manages asynchronous communication
5. Data stored/retrieved from database

---

📊 Cloud Concepts Demonstrated

* Microservices Architecture
* Event-Driven Systems
* Secure Cloud Communication
* Distributed System Design
* Scalability & Modularity

---

🔮 Future Enhancements

* Deployment on AWS / Azure
* Containerization using Docker
* Kubernetes orchestration
* API Gateway integration
* Monitoring & Logging (Prometheus, Grafana)

---

 👨‍💻 Author

**Evelin Rose**
Cloud Computing Project Submission

---
