# Spring Boot Task Manager API

A REST API built with Spring Boot for managing tasks — Create, Read, Update, and Delete operations.

## 🚀 Features
- REST endpoints for managing tasks
- CRUD operations
- In-memory H2 database
- Spring Data JPA
- JSON request/response

## 📦 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

## 📡 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/api/tasks` | Create a new task |
| GET    | `/api/tasks` | Get all tasks |
| PUT    | `/api/tasks/{id}` | Update a task |
| DELETE | `/api/tasks/{id}` | Delete a task |

## 🧪 Sample JSON
```json
{
  "title": "Finish Spring Boot Project"
}
