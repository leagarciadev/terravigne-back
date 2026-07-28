# terravigne-back

Backend API for Terravigne, built with Spring Boot.

## Requirements

- Java 25
- Maven (or use the included `mvnw` wrapper)

## Getting started

```bash
cd api
./mvnw spring-boot:run
```

The API will start on `http://localhost:8080`.

## Endpoints

- `GET /hello` — health/sanity check endpoint, returns `Hello, world!`

## Running tests

```bash
cd api
./mvnw test
```

## Project structure

```
api/
  src/main/java/com/terravigne/api/   Application source
  src/main/resources/                 Configuration
  src/test/java/com/terravigne/api/   Tests
```
