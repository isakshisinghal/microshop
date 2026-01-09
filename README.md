### Microshop 🛒

A microservices-based e-commerce backend built with **Spring Boot**, **Kafka**, **Eureka**, **MongoDB**, **Postgres** and **Docker**.  
This project includes product, order, inventory, notification services, and an API Gateway, with metrics and monitoring via **Prometheus** and **Grafana**.


---

## Features 

- Microservices architecture
- API Gateway for routing requests
- MongoDB and Postgres database for storage
- Security implementation using KeyCloak
- Kafka for asynchronous communication between services
- Resilience4j for circuit breaker and fault tolerance
- Eureka service discovery
- Prometheus metrics and Grafana dashboards
- Dockerized for easy deployment

---

## Technologies

- Spring Boot
- Spring Cloud (Eureka, Gateway)
- Apache Kafka
- KeyCloak
- Resilience4j
- Postgres, MongoDB  
- Prometheus & Grafana  
- Docker

---

## Docker Images 🐳

All services are available on Docker Hub under my account.

| Service               | Docker Image                                         |
|-----------------------|-----------------------------------------------------|
| API Gateway           | `sakshisinghal/api-gateway:latest`     |
| DiscoveryServer       | `sakshisinghal/discovery-server:latest`        |
| Product Service       | `sakshisinghal/product-service:latest` |
| Order Service         | `sakshisinghal/order-service:latest`   |
| Inventory Service     | `sakshisinghal/inventory-service:latest` |
| Notification Service  | `sakshisinghal/notification-service:latest` |

---

## Architecture

![Ach drawio](https://github.com/user-attachments/assets/1c3834e7-1d20-417c-8662-bd21d4f56439)
