# 🚀 JobNest API

JobNest API is the backend component of the JobNest recruitment platform, developed using ASP.NET Core Web API. It provides RESTful endpoints for authentication, job management, and job applications while serving as the communication layer between the mobile application and the database.

The project was developed collaboratively as part of a university software engineering project.

---

# 📖 Overview

The API is responsible for handling business logic, authentication, authorization, database operations, and secure communication between clients and the persistence layer.

It exposes endpoints for managing users, job postings, and applications while using JWT authentication to secure protected resources.

---

# ✨ Features

- User authentication
- JWT authorization
- User registration
- Job management
- Create job posts
- Browse available jobs
- Submit job applications
- Entity Framework Core integration
- RESTful API architecture
- Database migrations
- Docker support

---

# 📂 Project Structure

```
JobNest API
│
├── Controllers
│   ├── AuthController
│   ├── JobsController
│   └── ApplicationsController
│
├── Data
│   └── AppDbContext
│
├── Models
│   ├── User
│   ├── Job
│   └── Application
│
├── Services
│   └── JwtService
│
├── Migrations
│
├── Program.cs
│
├── appsettings.json
│
└── Dockerfile
```

---

# 🏗 Architecture

The backend follows a layered architecture consisting of:

- Controllers
- Services
- Entity Framework Core
- Database Context
- Models
- Authentication Layer

---

# 🔐 Authentication

Authentication is implemented using JSON Web Tokens (JWT).

Users can:

- Register
- Login
- Receive access tokens
- Access protected API endpoints

---

# 📦 API Modules

## Authentication

- Register
- Login
- JWT Token generation

## Jobs

- Create jobs
- Retrieve jobs
- Update jobs
- Delete jobs

## Applications

- Submit applications
- Retrieve submitted applications

---

# 🗄 Database

The project uses Entity Framework Core.

Main entities include:

- User
- Job
- Application

Database schema evolution is managed using EF Core Migrations.

---

# 🛠 Technologies

### Backend

- ASP.NET Core Web API
- .NET 8
- C#

### Database

- SQLite
- Entity Framework Core

### Authentication

- JWT

### Tools

- Visual Studio 2022
- Docker

---

# 👥 Team Collaboration

This backend was developed collaboratively as part of a university software engineering project.

Development included:

- API design
- Authentication
- Database modeling
- Business logic
- Testing
- Bug fixing
- Documentation

---

# 📚 Learning Outcomes

The project demonstrates practical knowledge of:

- REST API development
- ASP.NET Core
- JWT Authentication
- Entity Framework Core
- Database migrations
- Docker
- Clean Architecture concepts
- Team collaboration

---

# 🔮 Future Improvements

- Refresh Tokens
- Role-based Authorization
- Swagger Documentation
- Cloud Deployment
- SQL Server support
- Email verification
- Password reset
- Logging
- Unit Testing
- CI/CD Pipeline

---

# 📄 License

Educational project developed for university coursework.

---

# ⭐ Status

Completed.
