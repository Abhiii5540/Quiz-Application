## Quiz-Application
A Quiz Application backend built using Spring Boot and Microservices architecture. This project demonstrates service-to-service communication, service registry, API Gateway, and load balancing in a microservice environment.

# Features
Question Service – Handles all quiz questions (CRUD operations). Quiz Service – Fetches questions via Feign client and compiles quizzes. Service Registry (Eureka Server) – Enables service discovery and registration. Feign Client – Simplifies REST calls between microservices. API Gateway – Single entry point for all microservices. Load Balancing – Distributes requests across multiple instances.

# Technologies Used
Java 17 
Spring Boot (Web, Actuator, etc.) 
Spring Cloud Netflix Eureka (Service Registry) 
Spring Cloud OpenFeign (Microservice communication) 
Spring Cloud Gateway (API Gateway) 
Spring Boot DevTools (Hot reload) 
Lombok (Boilerplate reduction) 
Maven (Build tool) 
Postman (API Testing)
