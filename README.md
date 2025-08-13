<<<<<<< HEAD
# Expense Tracker – Microservices-Based Backend

A modular expense tracking backend system built with a microservices architecture using Java Spring Boot. It leverages Kafka for event-driven communication and is fully containerized with Docker for scalable deployments.

## 🧩 Microservices

1. **AuthService**
   - Handles user authentication and authorization using JWT.
   - Exposes login, signup, and token refresh APIs.
   
2. **UserService**
   - Manages user profiles, preferences, and related metadata.
   - Verifies user identity and forwards contextual data to other services.


3. **LedgerService**
   - Consumes events from Kafka.
   - Aggregates and stores categorized expense records for analytics and reporting.
   - Supports future ledger visualizations or budget projections.

## 🛠️ Tech Stack

- **Backend Framework:** Java (Spring Boot)
- **Communication:** Kafka (event-driven messaging)
- **Authentication:** JWT (JSON Web Tokens)
- **Persistence:** Hibernate, Spring Data JPA, MySQL
- **Containerization:** Docker
- **Build Tool:** Gradle
- **Architecture:** Microservices


=======
# Expense_Tracker.
>>>>>>> 22f313bc18c32f8eaedc99e1fac7cda9faf40452
