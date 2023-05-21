# Authentication-api

![Authentication Service Diagram drawio](https://github.com/ygtyzccc/authentication-api/assets/78899194/028b8f5f-01be-4509-ba10-f85203afadd5)

# Spring Boot 3.0 Spring Security 6.0 with JWT Implementation
This project using Spring Boot 3.0 and Spring Security 6.0 implementation of JWT

## Features
* User registration and login with JWT authentication
* Password encryption using BCrypt
* Role-based authorization with Spring Security
* Validation of token
* Refresh token

## Technologies
* Spring Boot 3.0
* Spring Security
* JSON Web Tokens (JWT)
* BCrypt
* Maven
* Jdk 17+
 
 ## How to run the application using Docker

1. Run `mvn clean package -DskipTests` to build the applications and create the docker image locally.
2. Run `docker-compose up -d` to start the applications.

## How to run the application without Docker


Create jwt_security database on PostgreSql on your local ip:5432, then run following commands

1. Run `mvn clean verify -DskipTests` by going inside each folder to build the applications.
2. After that run `mvn spring-boot:run` by going inside each folder to start the applications.
