# Dentistry

Dentistry is a Java backend application built with Spring Boot that models a basic dentistry management system.

## Project Description

The project demonstrates a typical **Spring Boot REST application structure** and focuses on backend development principles such as layered architecture, request handling, and data modelling.

It includes controllers, services, repositories, DTOs, and entities, following common Spring Boot and MVC best practices.

## Application Structure

The project is organized using a clean and readable package structure:

- **controllers** – handle HTTP requests and define REST endpoints  
- **services** – contain business logic  
- **repositories** – interact with the database using Spring Data  
- **entities** – represent domain models (User, Patient, Doctor, Appointment, etc.)  
- **dto** – data transfer objects for API responses and requests  
- **enums** – application enums (e.g. user roles)

## Features

- User roles (Admin, Doctor, Patient)
- Patient and doctor management
- Appointment management
- Authorization logic
- RESTful API endpoints

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Maven

## Project Goal

The main goal of this project was to practice:
- building REST APIs with Spring Boot
- structuring a backend application using layered architecture
- working with controllers, services, repositories, and DTOs
- understanding request flow inside a Spring Boot application

This project was created as a learning project and serves as a foundation for more advanced backend systems.
