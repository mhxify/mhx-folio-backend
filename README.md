# Portfolio Platform Backend

Scalable backend built with Spring Boot for managing a modern personal portfolio and dashboard system.

---

# Features

- JWT Authentication
- Admin Dashboard APIs
- Projects Management
- Skills Management
- Experience Management
- Contact Messages
- Image Upload with Cloudinary
- Swagger/OpenAPI Documentation
- PostgreSQL Database
- Scalable Clean Architecture

---

# Tech Stack

## Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- JWT Authentication

## Database
- PostgreSQL

## Documentation
- Swagger / OpenAPI

## Storage
- Cloudinary

## Deployment
- Docker (Coming Soon)
- Render / Railway
- Vercel (Frontend)

---

# Project Structure

```text
src/main/java/com/mhx/portfolio
│
├── auth
├── project
├── skill
├── experience
├── contact
├── upload
├── config
├── security
└── common
```

---

# Getting Started

## Clone Repository

```bash
git clone git@github.com:YOUR_USERNAME/portfolio-platform-backend.git
```

## Configure PostgreSQL

Create database:

```sql
CREATE DATABASE portfolio_db;
```

## Configure Application

Update `application.properties`:

```properties
spring.application.name=portfolio

server.port=8081

spring.datasource.url=jdbc:postgresql://localhost:5432/portfolio_db
spring.datasource.username=postgres
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true

app.jwt.secret=CHANGE_THIS_SECRET_KEY
app.jwt.expiration=86400000
```

---

# Run Project

```bash
mvn spring-boot:run
```

---

# Swagger Documentation

After running the project:

```text
http://localhost:8081/swagger-ui/index.html
```

---

# Future Improvements

- Docker Support
- CI/CD Pipelines
- Redis Caching
- Role Management
- Analytics Dashboard
- Multi-language Support

---

# Author

## Mohamed Ali Benouarzeg

- Android & Multiplatform Developer
- Kotlin / KMP / Spring Boot Developer

LinkedIn:
https://www.linkedin.com/in/mohamed-ali-benouarzeg-3b55582b2/

GitHub:
https://github.com/mhxify
