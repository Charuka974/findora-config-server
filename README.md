# Findora Config Server

## Student Information
- **Student Name:** Charuka Hansaja
- **Student ID:** 241722035
- **Slack Handle:** Charuka (`U0BF12U29NF`)
- **GCP Project ID:** findora-cloud-platform

---

## Project Description
The Config Server provides centralized and externalized configuration management across all Findora microservices. It connects directly to the `findora-config-repo` to serve profile-specific configurations.

## Technology Stack
- **Language:** Java 25
- **Framework:** Spring Boot, Spring Cloud Config Server
- **Process Manager:** PM2

## Setup / Getting Started Instructions
```bash
# Build the application
mvn clean package -DskipTests

# Run locally on port 8888
java -jar target/config-server-0.0.1-SNAPSHOT.jar