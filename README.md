# Eureka Server
## Overview
- The Eureka Server provides service discovery and registration for all microservices in the Mazadak platform using Netflix Eureka.

- It maintains a registry of all running service instances, enables client-side load balancing, and provides real-time service health monitoring across the platform.

- The Eureka Server is the central service registry that enables dynamic service discovery and inter-service communication.

## API Endpoints
- Eureka Dashboard available at `http://localhost:18050` when running locally

## How to Run
You can run it via [Docker Compose](https://github.com/Mazaadak/mazadak-infrastructure) or [Kubernetes](https://github.com/Mazaadak/mazadak-k8s/)

## Tech Stack
- **Spring Boot 3.5.6** (Java 21)
- **Netflix Eureka Server** - Service Discovery & Registration
- **Docker & Kubernetes** - Deployment & Containerization

## For Further Information
Refer to [Eureka Server Wiki Page](https://github.com/Mazaadak/.github/wiki/Eureka-Server).
