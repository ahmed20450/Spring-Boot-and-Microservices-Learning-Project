# Microservices Project

This project is a microservices-based application built with Java 17 and Spring Boot. It consists of multiple services including school, student, gateway,config and discovery services.

## Technologies Used

- Java 17
- Spring Boot
- Spring Cloud (for microservices architecture)
- Docker

## Quick Start

1. Ensure you have the following installed:
   - Java 17 JDK
   - Maven
   - Docker and Docker Compose

2. Clone the repository:
git clone https://github.com/ahmed20450/Spring-Boot-and-Microservices-Learning-Project.git  
cd micro-services
Copy
4. Build the project:
mvn clean package
Copy
5. Start the services using Docker Compose:
docker-compose up -d
Copy
6. The services should now be running. You can access them at:
- Discovery Service: http://localhost:8761
- Gateway Service: http://localhost:8080

## Services

- Discovery: Service registry and discovery
- Gateway: API Gateway for routing requests
- School: Manages school-related operations
- Student: Handles student-related functionalities
