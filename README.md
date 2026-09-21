# HR Leave Management

A full-stack web application to manage employees, departments and leave/permission
requests through a hierarchical approval workflow.

## Features
- **Role-based interfaces**: each hierarchical manager has a dedicated dashboard
- **Multi-level approval**: leave requests must be validated by the hierarchical
  superiors before HR gives the final approval
- **HR administration**: HR registers and manages employees, services and departments
- **Internal messaging** between users

## Tech stack
- **Backend:** Java, Spring Boot
- **Frontend:** Angular
- **Database:** PostgreSQL

## Getting started
1. Clone the repository
2. Create a PostgreSQL database and set your credentials in `application.properties`
3. Run the backend: `./mvnw spring-boot:run`
4. Run the frontend: `npm install && ng serve`



## Author
Imane GBADAMASSI
