# pulso-vivo-price-consumer

This microservice is dedicated to consuming messages from RabbitMQ using Spring Boot. It is focused solely on message listener logic, following best practices for microservice communication and clean separation from producer logic.

## Features
- Listens to RabbitMQ queues
- Handles message processing logic
- Easily extensible for additional consumers

## Getting Started

### Prerequisites
- Java 17+
- Maven 3.6+
- RabbitMQ instance

### Build
```
mvn clean package
```

### Run
```
mvn spring-boot:run
```

## Configuration
Edit `src/main/resources/application.properties` to set RabbitMQ connection details.

## License
MIT
