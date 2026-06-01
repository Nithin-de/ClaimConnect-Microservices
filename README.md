# ClaimConnect - Insurance Claim Processing System

## Overview

ClaimConnect is a microservices-based insurance claim processing system developed using Spring Boot and Spring Cloud. The application streamlines the insurance claim lifecycle between hospitals, patients, and insurance companies through secure, scalable, and distributed backend services.

## Project Status

Completed

## Architecture

The application consists of the following microservices:

- Config Server
- Eureka Server
- API Gateway
- Hospital Service
- Patient Service
- Insurance Company Service
- Claim Request Service

## Features

- Service Discovery using Eureka Server
- Centralized Configuration using Config Server
- API Routing using Spring Cloud Gateway
- Inter-Service Communication using OpenFeign
- JWT-based Authentication and Authorization
- RESTful API Development
- MySQL Database Integration
- Exception Handling and Validation
- Layered Architecture Implementation

## Technology Stack

- Java
- Spring Boot
- Spring Cloud
- Eureka Server
- API Gateway
- Config Server
- OpenFeign
- Spring Security
- JWT
- JPA/Hibernate
- MySQL
- Maven
- Git
- Postman

## Service Startup Order

1. Config Server
2. Eureka Server
3. Hospital Service
4. Patient Service
5. Insurance Company Service
6. Claim Request Service
7. API Gateway

## Modules

### Hospital Service
Allows hospitals to create and manage insurance claim requests.

### Patient Service
Enables patients to view and respond to claim requests.

### Insurance Company Service
Processes and approves eligible insurance claims.

### Claim Request Service
Acts as the central service for claim lifecycle management.

## Key Implementations

- Developed backend microservices using Spring Boot and Spring Cloud.
- Implemented service discovery using Eureka Server.
- Configured centralized configuration management using Config Server.
- Enabled secure API routing through Spring Cloud Gateway.
- Implemented inter-service communication using OpenFeign.
- Secured APIs using Spring Security and JWT authentication.
- Integrated MySQL with JPA/Hibernate for persistent data storage.
- Tested and validated APIs using Postman.

## Architecture Diagram

![Architecture](architecture.png)
