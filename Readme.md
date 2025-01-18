# Point of Sale Application

## Overview
This is a Point of Sale (POS) application built using Spring Boot. It provides a simple RESTful API to manage users and presentations.

## Features
- **Hello Endpoint**: Returns a greeting message.
- **User Endpoint**: Returns a list of users.
- **Presentation Endpoint**: Returns presentation details.

## Technologies Used
- Java 17
- Spring Boot
- Maven
- JUnit for testing

## Getting Started

### Prerequisites
- Java 17 or higher
- Maven

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/point-of-sale.git
   cd point-of-sale
   ```

2. Build the application:
   ```bash
   mvn clean install
   ```

3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

### Accessing the API
Once the application is running, you can access the following endpoints:

- **Hello**: `GET http://localhost:8282/`
- **Users**: `GET http://localhost:8282/user`
- **Presentation**: `GET http://localhost:8282/presentation`

## Running Tests
To run the tests, use the following command: