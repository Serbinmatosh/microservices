# microservices

This project is a simple microservice architecture project using Distributed Systems.
Project consists of:

- An API gateway
- 3 Microservices (Customer, Fraud, and Notification)
- Eureka Server Service Discovery
- Sleuth for Distributed Tracing
- RabbitMQ Message Queue (Customer sends the message to the queue, Notification reads of queue)
- Complete dockerization using the Jib library
- Kubernetes setup
