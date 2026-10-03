# TodoRails

A task management web app built with Spring Boot. Users can register, log in, and manage their own to-do list through a priority-based daily dashboard.

> Built while completing Amazon's **Full Stack Web Development** course on Coursera. The project started from the course's starter template, and I completed the guided sections across the backend, templates, scripts and styling.

## Features
- User registration and login with Spring Security (passwords hashed with BCrypt)
- Add, edit, view, delete and mark tasks as done
- Dashboard showing today's tasks grouped by High, Medium and Low priority
- Task types (official, family, personal) and due dates
- Change password with current-password verification
- Client-side form validation (JavaScript) plus server-side checks, including duplicate-username detection

## Tech Stack
- Java 17, Spring Boot 3.3.4
- Spring Security, Spring Data JPA
- Thymeleaf, HTML, CSS, JavaScript
- H2 in-memory database
- Maven

## Concepts Covered
- MVC layering: controllers, services, repositories and models
- Authentication and authorization with Spring Security
- Spring Data JPA derived queries
- Thymeleaf form binding and template fragments
- Form validation on both client and server

- Real unit and integration tests
