# Spring Boot Overview
Spring Boot is an advanced framework built on top of the Spring Framework, designed to simplify Java application development, especially for web applications. It provides built-in configurations, embedded servers, and a streamlined setup process. A core feature of Spring Boot is its integration with the Model-View-Controller (MVC) architecture, which is widely used for scalable web applications.

## Understanding Spring Boot MVC
Spring Boot MVC is a simplified version of the traditional Spring MVC framework, offering automatic configurations and reducing the need for complex setup. It follows the MVC design pattern, which consists of three main components:

- **Model (M)**: Handles data and business logic.
- **View (V)**: Manages the user interface and presentation (e.g., HTML, Thymeleaf).
- **Controller (C)**: Processes user requests and interacts with both the Model and View.

This separation of concerns improves code maintainability and scalability.

## How Spring Boot Works with MVC
1. A client (browser, API tool) makes an HTTP request.
2. The **DispatcherServlet** (Front Controller) intercepts the request.
3. It determines the correct Controller using `@RequestMapping`.
4. The Controller processes the request and interacts with the Model (database, business logic).
5. The response data is passed to the View (e.g., HTML, JSON, or Thymeleaf templates).
6. The processed response is sent back to the client.

## Setting Up Spring Tools for Eclipse
Spring Tools Suite (STS) is an IDE tailored for Spring Boot development, based on Eclipse.

### Installation Steps:
1. Go to the official Spring Tools website: [Spring Tools](https://spring.io/tools)
2. Download **Spring Tools 4 for Eclipse**, selecting the version compatible with your OS (Windows, macOS, or Linux).
3. Follow the installation instructions provided on the website.

## Screenshots

![Image](https://github.com/user-attachments/assets/a67abdcd-7b55-4992-85bf-434d60a519d5)
