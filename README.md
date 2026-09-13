# Hi, I'm Sebastian 👋

**Backend Developer · Java & Spring Boot · Madrid, Spain**

I build backend services and event-driven systems in Java. I currently work as a Java
Developer in an enterprise environment, focused on distributed messaging, containerised
services, and adding new functionality to an existing codebase while following Clean Code
principles.

I'm interested in going deeper into **distributed systems, cloud infrastructure and system
design** — mostly by building things and breaking them.

---

## 🚀 Featured project

### [AeroTracker](https://github.com/escalasebastian/AeroTracker) — Flight price tracker on Telegram

A Telegram bot that monitors flight prices and pushes real-time alerts when a fare drops.
Built as a production-shaped system rather than a demo:

- **5 decoupled services** (`api`, `scheduler`, `price-checker`, `notification`, `rabbitmq`)
  communicating asynchronously — a slow or failing price check never blocks user commands
- **Event-driven with RabbitMQ**, so price checks and notifications scale independently
- **Deployed on AWS** (ECS Fargate, RDS, VPC) with CloudWatch observability, kept entirely
  within free-tier limits
- **CI/CD with GitHub Actions**, containerised end to end with Docker
- Uses **Telegram Long Polling instead of Webhooks** — deliberate trade-off to avoid exposing
  a public endpoint and paying for a load balancer

`Java 21` · `Spring Boot 3` · `PostgreSQL 16` · `RabbitMQ` · `Docker` · `AWS` · `GitHub Actions`

---

## 🛠️ Tech stack

**Languages** — Java, Kotlin, C#, SQL

**Backend** — Spring, Spring Boot, REST APIs, RabbitMQ, MQTT, JUnit, Mockito

**Data** — PostgreSQL, SQL Server

**Infrastructure** — Docker, AWS (ECS Fargate, RDS, VPC, CloudWatch), GitHub Actions, Git

**Practices** — Clean Architecture, Clean Code, event-driven design, testing, CI/CD

---

## 📚 Currently

- **B.Sc. in Software Development and Testing** (joint degree — UOC, UNED, OUNL)

---

## 📫 Get in touch

[LinkedIn](https://linkedin.com/in/sebastian-escala-cuervo) · escalasebastian@gmail.com
