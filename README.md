# E-Commerce Platform

A microservices-based E-Commerce Platform built to demonstrate backend engineering, distributed system design, and service-oriented architecture.

## Microservices

| Service | Responsibility | Repository |
|---|---|---|
| Product Catalog | Product information and catalog management | [productcatalog](https://github.com/BarnaliS/ProductCatalogService) |
| Authentication | User authentication and authorization | [auth](https://github.com/BarnaliS/UserAuthenticationService) |
| Payment | Payment processing | [payment](https://github.com/BarnaliS/PaymentService) |
| Service Discovery | Service registration and discovery | [servicediscovery](https://github.com/BarnaliS/ServiceDiscovery) |
| Notification Service | Notification Service | [NotificationService](https://github.com/BarnaliS/NotificationService) |

## Architecture Overview

The platform is divided into independently maintained services. Each service has its own repository and can be developed and maintained separately.

```text
                  E-Commerce Platform
                          |
          +---------------+---------------+----------------+
          |               |               |                |
    Product Catalog  Authentication    Payment       Notification Service  
          |               |               |                |
          +---------------+---------------+----------------+
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
