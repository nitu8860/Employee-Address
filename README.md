# Employee-Address
This is a Java project that models the relationship between Employees and their Addresses. The project uses Spring Boot and JPA to provide a RESTful API for CRUD operations on the Employee and Address models.

## Technologies Used
This project uses the following technologies:
- Java
- Spring Framework
- Hibernate
- MySQL

## API Endpoints
The following endpoints are available in the API:

### Employee Endpoints
- **GET /employees-** Get a list of all employees
- **GET /employees/{id}-** Get an employee by ID
- **POST /employees-** Create a new employee
- **PUT /employees/{id}-** Update an existing employee
- **DELETE /employees/{id}-** Delete an employee

### Address Endpoints
- **GET /addresses-** Get a list of all addresses
- **GET /addresses/{id}-** Get an address by ID
- **POST /addresses-** Create a new address
- **PUT /addresses/{id}-** Update an existing address
- **DELETE /addresses/{id}-** Delete an address

## Controllers
The project has two controllers:
### EmployeeController
 - Handles requests related to the Employee model

### AddressController
 - Handles requests related to the Address model

## Services
The project has two services:
### EmployeeService
 - Handles CRUD operations on the Employee model

### AddressService
 - Handles CRUD operations on the Address model

## Repositories
The project has two repositories:
### EmployeeRepository
 - Provides access to the Employee data source
 
### AddressRepository
 - Provides access to the Address data source

## Summary
In summary, this Java-based Employee-Address management system provides an efficient way to manage employee and address information. It uses Java, Spring Framework, Hibernate, and MySQL to allow users to perform CRUD operations on both models and store data in a MySQL database. To contribute to this project, simply fork the repository and submit a pull request with your changes.
