## What is CQRS


### What is CQRS
- It is Command Query Responsibility Seggregation.
- This system design pattern seperates the responsibility of commands which changes the data (modifying the state of the system) from queries which retrieves the data.
- Here Commands and Queries are generic components of the system.
- This patterns allows flexibility and scalability.

  ### Key Components of CQRS
  - Command Service
  - Query Service
  - Event Bus / Message Broker
  - Data Store
  - API Gateway
