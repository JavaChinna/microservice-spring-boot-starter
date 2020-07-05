# microservice-spring-boot-starter

This project demonstrates how to build a custom Spring Boot Starter with multiple authentication profiles and default application.properties for microservices.

It has the following 3 modules:

microservice-spring-boot-starter module which uses the Spring Boot Starter Parent and defines the required dependencies in the pom.xml. Apart from that, it also contains all the security configurations and default application properties.

microservice-starter-parent module which has the parent POM.

microservice which makes use of the starter module via the parent POM.

# Read more [here](https://www.javachinna.com/2020/07/05/build-custom-spring-boot-starter-for-microservices/)
