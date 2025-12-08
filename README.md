# Flight Management System – Configuration Repository

This repository contains all **centralized configuration files** used by the
Flight Management System microservices.

These configuration files are loaded at runtime through the **Spring Cloud Config Server**, ensuring consistent, externalized, and environment-specific settings across all services.

---

## Microservices Using This Config Repository

The following services fetch their configuration from this repository:

* **auth-service**
* **flight-service**
* **booking-service**
* **email-service**
* **api-gateway**
* **service-registry (Eureka)**

## Repository Structure

```
/auth-service.properties
/flight-service.properties
/booking-service.properties
/email-service.properties
/api-gateway.properties
/service-registry.properties (if applicable)
```



