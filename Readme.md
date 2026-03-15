# Go Gin Task Manager API (JWT + RBAC)

A security-focused Task Manager API implementation adding JWT-based authentication and role-based authorization on top of persistent REST operations.

## Phase Position

- **A2SV Go Phase:** Task 6 (Security Layer)
- **Previous Project:** `go-gin-task-manager-api-mongodb`
- **Next Project:** `go-gin-task-manager-api-testing`

## Features

- User registration and login
- JWT token issuance and validation
- Role-based access control (admin/user)
- Protected task management routes

## Tech Stack

- Go
- Gin
- JWT
- MongoDB (project continuity)

## Project Structure

```text
.
├── controllers/
├── middleware/
├── models/
├── router/
├── data/
├── docs/
├── main.go
├── go.mod
├── go.sum
└── Readme.md
```

## Setup

```bash
go mod tidy
go run main.go
```

## Learning Outcomes

- Authentication middleware design
- Authorization policy enforcement
- Security-first API evolution in Go/Gin
