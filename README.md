# ecommerce_μServices_api
This is an e-commerce microservices project built using Spring Boot and Spring Cloud framework, featuring a RESTful API architecture. It leverages modern software design principles and distributed system design patterns for scalability, maintainability and resilience.


# Architecture Diagram
![image](https://github.com/dexterousAniket/ecommerce_microservices_api/blob/main/app_architecture_v2.png)


# μServices
  - api-gaterway (LoadBalancing, Routing and Authentication)
  - identity-service (Authorization)
  - service-discovery
  - config-server
  - user-service
  - product-service
  - order-service
  - payment-service
  - inventory-service
  - notification-service
  - shipping-service
  - containers
      - Grafana (metric and circuit breaker dashboard)
      - Zipkin-server (distributed traing dashboard)
