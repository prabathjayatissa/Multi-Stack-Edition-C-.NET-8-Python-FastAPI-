# Multi-Stack-Edition-C-.NET-8-Python-FastAPI

# 🎓 Software Engineering 3 Lab (BIF)

## Multi-Stack Edition: C# (.NET 8) & Python (FastAPI)

This repository contains the official course structure and reference architecture for the **Software Engineering 3 Lab** (5th semester, BIF program).

The course teaches modern backend engineering using **component-based architecture, REST APIs, messaging systems, and DevOps practices**, implemented in either:

- 🟦 C# / .NET 8 (ASP.NET Core)
- 🐍 Python (FastAPI)

Both tracks follow the same architectural principles and learning outcomes.

---

# 🧭 Course Overview

Students design and implement a **multi-layer business application** inspired by real-world systems such as:

- Booking & reservation systems
- Billing and invoicing platforms
- Document management systems
- Logistics / inventory systems

The course emphasizes:

- Clean software architecture
- RESTful API design
- Event-driven systems
- Microservice-ready patterns
- DevOps & CI/CD workflows
- Agile Scrum teamwork

---

# 🧱 Architecture Principles (Technology Independent)

All implementations follow:

- Clean Architecture (Domain / Application / Infrastructure / API)
- Dependency Inversion Principle
- Component-based system design
- Service-oriented decomposition
- Event-driven communication

---

# ⚙️ Technology Stack

## 🟦 C# Track (.NET 8)

- ASP.NET Core Web API
- Entity Framework Core
- Swagger / OpenAPI (Swashbuckle)
- RabbitMQ + MassTransit
- Background Services (IHostedService)
- Serilog (logging)
- Docker + Docker Compose
- GitHub Actions CI/CD

---

## 🐍 Python Track (FastAPI)

- FastAPI
- SQLAlchemy / SQLModel
- Pydantic (validation / DTOs)
- RabbitMQ + Celery / aio-pika
- Async background tasks
- httpx (HTTP clients)
- MongoDB (PyMongo / Motor optional)
- Docker + Docker Compose
- GitHub Actions CI/CD

---

# 🧩 Course Structure (7 Scrum Sprints)

Each sprint includes:
- lecture input
- guided lab work
- team implementation
- sprint review & code review

---

## 🟦 Sprint 1 — Architecture & Project Setup

- Clean Architecture setup
- Git workflow & Scrum introduction
- API scaffold

✔ Deliverable:
- Running backend with `/health` endpoint
- Layered project structure

---

## 🟦 Sprint 2 — Domain Modeling & Persistence

- Domain-driven design basics
- ORM introduction
- Database schema design

✔ Deliverable:
- CRUD persistence with PostgreSQL

---

## 🟦 Sprint 3 — REST API & OpenAPI

- REST principles
- DTO design
- API documentation

✔ Deliverable:
- Fully documented REST API

---

## 🟦 Sprint 4 — Service Layer & Dependency Injection

- Business logic separation
- Dependency injection
- Mapping layers

✔ Deliverable:
- Clean service-oriented backend

---

## 🟦 Sprint 5 — Messaging & Background Processing

- Event-driven architecture
- Message brokers (RabbitMQ)
- Async processing

✔ Deliverable:
- Producer → broker → consumer workflow

---

## 🟦 Sprint 6 — External Services & NoSQL

- External API integration
- File storage (MinIO)
- NoSQL databases

✔ Deliverable:
- External service integration layer

---

## 🟦 Sprint 7 — DevOps & Production Readiness

- Docker containerization
- CI/CD pipelines
- Logging & monitoring

✔ Deliverable:
- Fully containerized application with CI pipeline

---

# 🎯 Learning Outcomes

Upon completion, students will be able to:

## 🧱 Architecture
- Design layered enterprise-grade systems
- Apply separation of concerns and dependency inversion

## 🌐 Backend Development
- Build RESTful APIs
- Design DTO-based communication layers
- Implement business logic services

## 🔄 Distributed Systems
- Use message brokers for decoupling
- Build asynchronous event-driven systems

## 🛠 DevOps
- Containerize applications using Docker
- Set up CI/CD pipelines using GitHub Actions

## 👥 Team Development
- Work in Scrum teams
- Manage tasks using agile workflows
- Conduct structured code reviews

---

# 🧪 Assessment Model

| Component | Weight | Description |
|----------|--------|-------------|
| Semester Project | 70% | Full backend system implementation |
| Code Reviews | 20% | Two formal review checkpoints |
| Participation | 10% | Scrum engagement & sprint demos |

---

# 🧠 Repository Purpose

This repository serves as:

- Course reference architecture
- Teaching scaffold for lecturers
- Student starting template
- Technology-neutral learning structure (C# / Python)
 
---

# 🚀 Optional Extensions

Advanced students may explore:

- Kubernetes deployment
- gRPC services
- API Gateway (YARP / FastAPI Gateway)
- Distributed tracing (OpenTelemetry)
- AI integration (LLM-based services)

---

# 📌 License

Educational use only.
