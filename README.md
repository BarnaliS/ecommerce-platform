# E-Commerce Platform

A microservices-based E-Commerce Platform built to demonstrate backend engineering, distributed system design, and service-oriented architecture.

## Microservices

| Service | Responsibility | Repository |
|---|---|---|
| Product Catalog | Product information and catalog management | [productcatalog](../productcatalog) |
| Authentication | User authentication and authorization | [auth](../auth) |
| Payment | Payment processing | [payment](../payment) |
| Service Discovery | Service registration and discovery | [servicediscovery](../servicediscovery) |

## Architecture Overview

The platform is divided into independently maintained services. Each service has its own repository and can be developed and maintained separately.

```text
                  E-Commerce Platform
                          |
          +---------------+---------------+
          |               |               |
    Product Catalog  Authentication    Payment
          |               |               |
          +---------------+---------------+
                          |
                 Service Discovery
```

## Technology Stack

- **Language:** Java
- **Framework:** Spring Boot
- **Security:** Spring Security (where implemented)
- **Communication:** REST APIs
- **Architecture:** Microservices

## Project Goals

- Build independently maintainable backend services.
- Implement secure authentication and authorization.
- Design REST APIs for e-commerce operations.
- Explore service discovery and distributed system concepts.


## Status

Under active development.
