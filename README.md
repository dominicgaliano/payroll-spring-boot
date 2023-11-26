[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
![Top Tech][tech-shield]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Spring Boot REST API for Employee Payroll and Order Tracking

## Description

A lightweight Spring Boot-based RESTful service for managing employee payroll and company orders.

## Tech Stack

- Spring Boot
- Spring Data JPA: Java Persistence API for efficient database access.
- H2 Database Engine: Embedded database for easy setup.
- Spring Web MVC: Framework for building robust web applications.
- Spring HATEOAS: Enhances API navigability.
- SLF4J: Simple Logging Facade for Java.

## Installation

1. [Install Gradle](https://gradle.org/install/)

```bash
# MacOS
brew install gradle
```

2. Clone this repo to your local machine

```bash
git clone https://github.com/dominicgaliano/payroll-spring-boot/
cd gs-rest-service/
```

3. Run the application

```bash
./gradlew bootRun
```
## API Endpoints

### Employees

- GET /employees: Retrieve a list of all employees.
- GET /employees/{employeeId}: Retrieve details of a specific employee.
- POST /employees: Add a new employee.
- PUT /employees/{employeeId}: Update details of a specific employee.
- DELETE /employees/{employeeId}: Remove a specific employee.

### Orders

- GET /orders: Retrieve a list of all orders.
- GET /orders/{orderId}: Retrieve details of a specific order.
- POST /orders: Add a new order.
- DELETE /orders/{orderId}/cancel: Mark a specific order as canceled.
- DELETE /orders/{orderId}/complete: Mark a specific order as complete.

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

[contributors-shield]: https://img.shields.io/github/contributors/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
[contributors-url]: https://github.com/dominicgaliano/payroll-spring-boot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
[forks-url]: https://github.com/dominicgaliano/payroll-spring-boot/network/members
[stars-shield]: https://img.shields.io/github/stars/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
[stars-url]: https://github.com/dominicgaliano/payroll-spring-boot/stargazers
[issues-shield]: https://img.shields.io/github/issues/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
[issues-url]: https://github.com/dominicgaliano/payroll-spring-boot/issues
[license-shield]: https://img.shields.io/github/license/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
[license-url]: https://github.com/dominicgaliano/payroll-spring-boot/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/dominic-galiano
[tech-shield]: https://img.shields.io/github/languages/top/dominicgaliano/payroll-spring-boot.svg?style=for-the-badge
<!-- [github-status-shield]: https://img.shields.io/github/actions/workflow/status/dominicgaliano/payroll-spring-boot/deploy.yml.svg?style=for-the-badge -->
<!-- ![GitHub Workflow Status (with event)][github-status-shield] -->
