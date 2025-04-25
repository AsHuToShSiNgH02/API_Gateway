# ✈️ Airline Backend System – API Gateway

Welcome to the **API Gateway** repository of the **Airline Backend System**. This acts as the single entry point for client applications (web/mobile) to access multiple microservices behind the scenes. Built using Node.js and Express, it handles authentication, routing, request forwarding, and centralizes access control.

---

## 🌐 Overview

This project is based on a **microservices architecture** where each service is independently developed and deployed. The API Gateway plays a vital role in exposing unified endpoints to external clients and routing traffic internally to appropriate microservices.

---

## 📄 High-Level Design (HLD)

You can view the High-Level Design (HLD) document for more detailed information on the system architecture, flow, and implementation:

[🔗 HLD Document](https://drive.google.com/uc?id=1n1Y7nMOoXsJhSiYIiXObwpAP-hYgAd3q)

---

## 🏗️ Architecture Diagram

Below is a detailed architecture of the entire system:

![My Image](https://drive.google.com/uc?id=1yY4aO_ZgYiEmO7OYigrq0Taemaddvo0k)


---

## 🧩 Microservices

| Service Name              | Description                                            | Repository Link |
|--------------------------|--------------------------------------------------------|-----------------|
| **Authentication Service** | Handles user sign-up, login, JWT auth                 | [🔗 Auth Service](https://github.com/AsHuToShSiNgH02/Auth_Service) |
| **Searching Service**      | Allows users to search flights                        | [🔗 Flight Service](https://github.com/AsHuToShSiNgH02/FlightsAndSearchService) |
| **Booking Service**        | Books flights, allocates seats, confirms booking      | [🔗 Booking Service](https://github.com/AsHuToShSiNgH02/AirTicketBookingService) |
| **Reminder Service**       | Sends booking reminders and notifications via email   | [🔗 Reminder Service](https://github.com/AsHuToShSiNgH02/ReminderService) |
| **API Gateway**            | Central routing and access control                    | ✅ You are here |

---

## 🧠 Features

- ✅ Centralized API routing
- 🔐 JWT-based Authentication support
- 🚦 Handles rate-limiting and load balancing integration
- 🧭 Connects multiple microservices via clean RESTful routes
- 🛡️ Prevents direct client access to internal services
- 📨 Supports asynchronous event handling with RabbitMQ

---

## 🚀 Tech Stack

- **Node.js / Express**
- **JWT for Auth**
- **RabbitMQ** (for Reminder Service)
- **MySQL / MongoDB** (per-service DB strategy)
- **Docker & Postman** for dev & testing (optional)

---

## 🙌 Contributions

Feel free to open issues, create pull requests, or suggest improvements! Let's build something great together.

---

## 🧑‍💻 Developed By

Ashutosh Singh
Full-Stack Developer | MERN Stack | Microservices Enthusiast
📧 ashutoshin2002@gmail.com
