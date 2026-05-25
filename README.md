# Task 1 Spring Boot

This project is created using Spring Boot and Thymeleaf.

## Technologies

* Java 17
* Spring Boot
* Maven
* Thymeleaf

## Run Project

```bash
mvn spring-boot:run
```

## Application URL

```text
http://localhost:8080
```

## Endpoints

### GET /

Request:

```http
GET http://localhost:8080/
```

Response:

```text
Hello Vistula, in my first Spring controller.
```

### GET /greeting

Request:

```http
GET http://localhost:8080/greeting?name=Vistula
```

Response example:

```text
Hello, Vistula!
```

## Features

* Spring controller
* Thymeleaf page
* Dynamic request parameter
* Static image support
