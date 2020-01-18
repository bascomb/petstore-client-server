# petstore-client-server
Use Swagger 2.0/3.0
    Use swagger codegen maven plugin to generate client sdk.
    Use swager codegen to generate petstore server stub. Then implement it with persistent storage (NoSQL?)
    Use Spring Boot for both client and server.
    Database Technologies?
    Authentication?
    
Part 1 Setup:
Create a multimodule maven project petstore-client-server. Add to Github.
Maven Archetype Simple.
Dependencies: Spring Starter Parent, Spring Web
Part 1:
Run Spring Boot Application - Petstore Server Stub
    No coding. Just Configuration.
    Use sample petstore openapi 2 definition.
    Generate serverstub using swagger with maven plugin
    Run serverstub as spring boot application
    
Part 2 Setup:
Create Echo Client Spring Boot Application Module
Part 2:
Run Spring Boot Application - Petstore Client
    Also an Spring Boot Rest API WS
    Use Swagger to generate Controller Classes, Model, and Service Interface.
    Implement Service Class