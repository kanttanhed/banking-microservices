# 🚀 Banking Microservices System

Welcome to the **Banking Microservices System**, where finance meets cutting-edge technology in a geeky dance of microservices magic! This project is a showcase of modern banking operations managed through a robust microservices architecture. We’ve built two key services:

1. **Account Opening Service** – Where new bank accounts come to life! 🌟
2. **Credit Card Request Service** – Your gateway to the world of credit! 💳

## 🌟 What’s Under the Hood?

This project utilizes a host of modern technologies to ensure a smooth, scalable, and geeky experience:

- **Spring Boot** with **Java 17** for high-performance service development.
- **API Gateway** for smart routing and load balancing.
- **Docker Compose** to orchestrate our containerized services.
- **Kafka** for seamless asynchronous communication.
- **Redis** for super-fast caching.
- **PostgreSQL** to handle our data with reliability.
- **SLF4J** for logging every detail.
- **Lombok** to keep our code elegant and concise.
- **JUnit5** for ensuring our code is rock-solid.
- **Swagger** for documenting and testing APIs like a boss!

## 📊 Architecture Overview

Dive into the architecture that powers our geeky banking system. With microservices communicating seamlessly and data managed efficiently, the system is a testament to modern engineering practices.

### Architecture Diagram

![Architecture Diagram](https://via.placeholder.com/800x400.png?text=Architecture+Diagram+of+Banking+Microservices)

## 🚀 Getting Started

1. **Clone the Repository**

    ```bash
    git clone https://github.com/kanttanhed/banking-microservices.git
    cd banking-microservices
    ```

2. **Start the Services**

    Build and start the Docker containers:

    ```bash
    docker-compose up --build
    ```

3. **Access Swagger UI**

    - **Account Service**: [http://localhost:8081/swagger-ui.html](http://localhost:8081/swagger-ui.html)
    - **Card Service**: [http://localhost:8082/swagger-ui.html](http://localhost:8082/swagger-ui.html)

   Explore and interact with the APIs directly!

4. **Test with Postman**

    Use [Postman](https://www.postman.com) to test the APIs:
    - **Account Opening**: `POST http://localhost:8081/accounts`
    - **Credit Card Requests**: `POST http://localhost:8082/cards`

## 🧪 Testing

Run unit and integration tests with JUnit5:

```bash
mvn test
