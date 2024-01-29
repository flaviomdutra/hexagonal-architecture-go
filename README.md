# Hexagonal Architecture Overview

This project implements the Hexagonal Architecture (also known as Ports and Adapters) in Go.

### Hexagonal Architecture
Hexagonal Architecture is a design pattern that allows an application to be equally driven by users, programs, automated test or batch scripts, and to be developed and tested in isolation from its eventual run-time devices and databases.

The idea behind Hexagonal Architecture is to put inputs and outputs at the edges of our design. Business logic should not be concerned with the nature of inputs and outputs. It should be focused on executing business rules.

### Applicability
Hexagonal Architecture is applicable in situations where you need to create a loosely coupled application with clear separation of concerns. This architecture is particularly useful when you want to isolate your application core logic from the technologies used for inputs and outputs (like databases, web services, etc.).

## Setup
To run this project, you need to have Go installed on your machine. You can download and install Go from [here](https://golang.org/dl/).

### Project Structure
The project structure is as follows:
- `cmd`: contains the main application code
- `application`: contains the application core logic
- `adapters`: contains the adapters for the application

### Run
To run the project, execute the following command from the root directory:

```bash
go run main.go
```

### Test
To run the tests, execute the following command from the root directory:

```bash
go test ./...
```

## References
- [Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/)

