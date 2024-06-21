## E-Commerce Platform with Microservices Architecture

# Project Overview

This project involves building an e-commerce platform using a microservices architecture. Each microservice handles a specific domain (e.g., Product, Order, User). The services communicate using REST APIs and are containerized using Docker.

# Technologies Used

- Java, Spring Boot
- Spring Cloud (Eureka, Zuul, Config)
- Docker, Kubernetes
- PostgreSQL, Redis
- Maven
- REST APIs
- CI/CD with Jenkins
- HTML, JavaScript (Angular for frontend)

# How to Run
Make sure you have Docker and Docker Compose installed.

# Build and run the services using Docker Compose:
docker-compose up --build

# Access the services:
Config Service: http://localhost:8888
Discovery Service: http://localhost:8761
Gateway Service: http://localhost:8080
Product Service: http://localhost:8081
Order Service: http://localhost:8082
User Service: http://localhost:8083