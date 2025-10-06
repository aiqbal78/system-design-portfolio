# 🧠 System Design Portfolio

Hands-on system design projects, architecture diagrams, and interview preparation notes for FAANG-style interviews.

---

## 📘 Overview
This repository contains a collection of **end-to-end system design implementations** with:
- Architecture diagrams
- Trade-off discussions
- Scalability and reliability patterns
- Load testing results
- Monitoring and observability examples

Each project is self-contained with `docker-compose.yml` or Kubernetes manifests and focuses on a specific design problem.

-

## 🗂 Repository Structure
| Folder | Project | Concepts Covered |
|---------|----------|------------------|
| 01-url-shortener | Scalable URL Shortener | Caching, database design, hash collisions, rate limiting |
| 02-order-kafka-shipment | Event-driven Order Workflow | Kafka, idempotency, saga pattern, retries, compensation |
| 03-realtime-chat | Real-time Chat Service | WebSockets, message ordering, backpressure, Redis pub/sub |
| 04-object-storage | Object Store with Presigned URLs | CDN, multipart uploads, MinIO, caching |
| docs | Design notes, capacity planning, SLOs | - |
| diagrams | Architecture diagrams (.drawio, .png) | - |

---

## 🧰 Tech Stack
- **Languages:** Java (Spring Boot), Node.js
- **Infrastructure:** Docker, Kubernetes, Kafka, Redis, PostgreSQL, MinIO
- **Observability:** Prometheus, Grafana, Jaeger
- **Load Testing:** k6, Apache Bench
- **Visualization:** diagrams.net (Draw.io)

---

## 📊 Project Template
Each project folder follows this structure:

