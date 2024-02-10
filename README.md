# Employee-Microservices

This repository includes a basic microservice project. My aim in doing this project was to learn microservice structure and to see how to create a successfully project by using Spring Cloud.

# Technologies/Framework/Tools
--------------------------------
* Spring Framework
* Spring Boot
* Postman
* Spring Web
   * Restful API
* Spring Cloud
   * Netflix Eureka
   * Config Server
   * Reactive Gateway
* Docker
   * Zipkin

     <br>

## Microservice Schema:
![microservice_schema drawio (1)](https://github.com/muhammedsametakgul/Employee-Microservices/assets/93324656/90d88ff0-0ee6-4b4f-90be-c3cec0b3b3de)


To download project:

Please clone the project
```bash 
    https://github.com/muhammedsametakgul/Employee-Microservices.git
```
Then open the folder and make sure configure maven folders( Recommended open with Intellij Idea and make maven setups)

Then run the projects by one. Ports ->
```bash 
    Config Server -> 8088
    Eureka Server(Service Registry) -> 8761
    API-Gateway -> 8060
    Department Service -> 8081
    Employee Service -> 8082
```

To try endpoints, please go to Postman and import the Employee Microservice.postman_collection.json inside of project.






