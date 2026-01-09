# 🚀 Spring Evolution - Main Page

Welcome to my **Spring learning journey**! This repository serves as the central hub for all the modules I am completing as part of my course, from basic fundamentals to advanced topics like building a full online invoicing system.

---

## 📚 Course Overview

This course is divided into several sections:

1. [**Spring Boot Fundamentals & Spring MVC**](https://github.com/izhim/spring-fundamentals-mvc)
   Learn the basics of Spring Boot and MVC architecture, including:
   - Working with **REST Controllers**
   - **Thymeleaf** templates and directives
   - Key Spring annotations (`@Controller`, `@Service`, `@Repository`, `@RequestMapping`, `@GetMapping`, `@PostMapping`, etc.)
   - Using **DTO (Data Transfer Objects)**
   - **REST APIs** and parameter handling
   - Handling **POST requests**
   - **Spring Expression Language (SpEL)**, including `Map SpEL`  
   - Accessing the **Environment object**
   - Redirects and forwards
   - Using the **`href` directive** in Thymeleaf
  
2. [**Dependency Injection**](https://github.com/izhim/injection-of-control)
   A complete and practical explanation of **Dependency Injection (DI)** in Spring Boot, including:

   * How the **IoC container** manages beans
   * Types of dependency injection: field, setter, and constructor
   * Understanding **bean scopes** (`singleton`, `request`, `session`)
   * Using **@Primary** and **@Qualifier** to manage multiple implementations
   * Creating and injecting **custom beans** with `@Configuration` and `@Bean`
   * Reading data dynamically from JSON files using configuration classes
     
3. [**Exception Handling in Spring Boot**](https://github.com/izhim/spring-exception-handler)
   A practical guide to **handling errors in REST APIs**, including:

   - Centralized error handling with **`@RestControllerAdvice`**
   - Using **`@ExceptionHandler`** to handle specific exceptions
   - Difference between **`ResponseEntity`** and **`@ResponseStatus`**, and when to use each
   - Creating and using **custom exceptions** for better error representation
   - Implementing a **standard error response model** with consistent JSON structure
   - Using **`Optional`** in the service layer to safely handle absent values and avoid null pointer exceptions
   - Returning meaningful **HTTP status codes** and messages to API clients
  
4. [**Interceptors in Spring Boot**](https://github.com/izhim/spring-http-interceptors)
   A practical guide to using **interceptors** in Spring Boot for request processing, logging, and monitoring:

   - **Creating Custom Interceptors** to measure processing time and handle requests before they reach controllers.
   - Applying interceptors globally or to specific paths with `addPathPatterns()` and `excludePathPatterns()`.
   - Controlling the order of interceptors with the `order()` method to ensure they execute in the correct sequence.
   - Stopping request processing early using `return false` in `preHandle()` for error handling or validation.
   - Using interceptors to **log request details** or handle **exceptions** centrally.
   - Performance considerations: keeping interceptors lightweight and non-blocking.
   - Applying **logging** and **monitoring** in interceptors for debugging and production tracking.

5. [**Spring AOP (Aspect-Oriented Programming)**](https://github.com/izhim/spring-aop)
   A complete introduction to **Aspect-Oriented Programming** in Spring, focused on separating cross-cutting concerns such as logging and monitoring:

   - Core AOP concepts: **Aspect**, **JoinPoint**, **Advice**, and **Pointcut**
   - All **types of advices**: `@Before`, `@After`, `@AfterReturning`, `@AfterThrowing`, and `@Around`
   - Deep dive into **`@Around` advice** and execution flow control
   - **Pointcut designators** with practical examples (`execution`, `within`, `args`, `@annotation`, `bean`, etc.)
   - Declaring **reusable pointcuts** and combining them with logical operators
   - Accessing runtime information from **JoinPoint** and **ProceedingJoinPoint**
   - Controlling aspect precedence with **`@Order`**
   - Using **regular expressions in route annotations**
   - Defining pointcuts **inside an aspect** vs **external pointcut classes**

**... more modules coming soon!**



---

## 🧠 Notes & Learning Strategy

- Each module contains:
  - **Concept explanations**
  - **Code examples**
  - **Common mistakes and solutions**
- Commits are descriptive to track learning progress.
- A **personal Markdown guide** is maintained for quick reference.

---

## ⚙️ Technologies Used

- Java 17  
- Spring Boot 3.x  
- Maven  
- Thymeleaf  
- REST APIs  
- HTML5
- XML 

---
