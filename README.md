# ASP.NET Core Developer Roadmap

## MVC

### Controllers

- **Routing**: Conventional vs Attribute based
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/routing?view=aspnetcore-7.0)
- **Route templates**
- **Action Methods and HTTP Verbs**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/actions?view=aspnetcore-7.0)
- **Helpers Methods**
- **URL Generation**
- **Filters**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-7.0)
- **Areas**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/areas?view=aspnetcore-7.0)
- **Methods Result**: e.g. Views, Json, File etc.
- **Dependency Injection in Controller**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/dependency-injection?view=aspnetcore-7.0)
- **Dependency Injection in Action**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/dependency-injection?view=aspnetcore-7.0)

### Views

- **Razor Syntax**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-7.0)
- **Tag Helpers**: Form, Input, Label, Select
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/intro?view=aspnetcore-7.0)
- **Partial Views**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/partial?view=aspnetcore-7.0)
- **View Components**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/view-components?view=aspnetcore-7.0)
- **View Discovery**
- **Layout**
- **ViewData and ViewBag**
- **Dependency Injection in View**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/dependency-injection?view=aspnetcore-7.0)

### Models

- **Model Binding**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/model-binding?view=aspnetcore-7.0)
- **Validation**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-7.0)
- **@model Directive**
- **View Models**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/overview?view=aspnetcore-7.0)

### Razor Pages

- **PageModel**
- **Scaffolding**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-7.0&tabs=visual-studio)

### Entity Framework with MVC

- **CRUD Operations**
- **Sorting, Filtering, Grouping**
- **Migrations**
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/?view=aspnetcore-7.0)
- **Complex Model**
- **Joins (Related Data)**
- **Updating Related Data**

## Web API

- **Web API with Controller**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-7.0)
- **Minimal web API**
- **Web API Routing**
- **Swagger**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-7.0&tabs=visual-studio)
- **Action Return types**
- **Validation in Web API**

## Security

### Authentication

- **Authentication with Identity**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-7.0&tabs=visual-studio)
- **Claims**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/claims?view=aspnetcore-7.0)
- **Scaffolding Identity**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/scaffold-identity?view=aspnetcore-7.0&tabs=visual-studio)
- **Cookies and JWT Authentication**

### Authorization

- **Role, Claims and Policy based authorization**
- **Authorize Attribute**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/simple?view=aspnetcore-7.0)
- **Authorization in Views**
- **User Principle, User Identity**

## Hosting and Deployment

- **Deployment with IIS**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/iis/?view=aspnetcore-7.0)
- **Deployment with Kestrel**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-7.0)
- **Deployment on Windows vs Linux**
- **Deployment with Docker**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/docker/?view=aspnetcore-7.0)

## Entity Framework Core

- **DbContext Configuration and Initialization**
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/dbcontext-configuration/)
- **Entity Model**
  - **Entity Properties**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/)
  - **Keys**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/keys)
  - **Fluent API Configuration**
  - **Generated Values**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/generated-properties)
  - **Relationships**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/relationships)
  - **Indexes and Constraints**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/indexes)
  - **Backing Fields**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/backing-field)
  - **Data Seeding**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/data-seeding)
- **Managing Migrations and Schemas**
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/?view=aspnetcore-7.0)
- **Querying Data**
  - **Client vs Server Evaluation**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/querying/client-eval)
  - **Change Tracker, Tracking and Non Tracking**
  - **Loading Related Data (Joins)**
    - **Eager, Explicit and Lazy Loading**
  - **Pagination**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/querying/related-data)
  - **Raw SQL Queries**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/querying/raw-sql)
  - **Global Query Filters**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/querying/filters)
  - **How Queries Work**
    - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/querying/)
- **Save Data**
  - **Update Operation**
  - **Updating Related Data**
  - **Cascade Delete**
  - **Concurrency**
  - **Transactions**
- **Performance**
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/performance/)
- **Asynchronous Programming**
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/miscellaneous/async)
- **Database Providers**
  - **MS SQL**
  - **SQLite**

## Advanced

- **Globalization and Localization**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/localization?view=aspnetcore-7.0)
- **Application Configuration and Options Pattern**
- **AutoMapper**: A convention-based object-object mapper.
  - [Official Documentation](https://docs.automapper.org/en/stable/Getting-started.html)
- **SignalR**: A library for ASP.NET developers that simplifies the process of adding real-time web functionality to applications.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/signalr/introduction?view=aspnetcore-7.0)
- **MediatR**: A simple library that uses the Mediator pattern for in-process messaging.
  - [GitHub Repository](https://github.com/jbogard/MediatR)
- **Hangfire**
- **Unit Testing**
  - **XUnit**
  - **NUnit**
  - **MSTest**
- **Middleware’s**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-7.0)
- **HttpContext**
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/http-context?view=aspnetcore-7.0)
- **Logging**

## Additional Topics

- **gRPC**: A high-performance, open-source and universal RPC framework.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/grpc/?view=aspnetcore-7.0)
- **GraphQL**: A data query language and runtime to request and deliver data to mobile and web apps.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/architecture/patterns/graphql)



---


# ASP.NET Core Backend Development Best Practices

## Purpose of this Section

This document outlines best practices, coding conventions, and architectural guidelines for ASP.NET Core backend development. It aims to foster consistency, efficiency, and excellence, ensuring scalable, maintainable, and performant backend solutions.

## Target Audience

- Backend Developers (Senior and Junior)
- CTO
- Project Managers
- Software Architects
- Quality Assurance Engineers

## Maintainability / Scalability Standards

### 1. Project Structure

Proper project organization is key for maintainability and scalability.


- **Organize by Feature**: Structure your project files and directories based on features for enhanced readability.
- **Adhere to SOLID Principles**: Design your codebase with SOLID principles to improve modularity.
- **Dependency Injection**: Use ASP.NET Core's dependency injection for managing dependencies.
- **Environment-specific Configurations**: Manage configurations using appsettings.json for different environments.
- **Centralize Database Migrations**: Keep database migrations in a specific location to manage schema changes efficiently.

### 2. Naming Conventions and Coding Standards

Consistent naming conventions and coding standards are crucial.


- **Follow C# Naming Conventions**: Use Microsoft's C# naming conventions.
- **Asynchronous Programming**: Use async/await for better scalability and non-blocking calls.
- **Exception Handling**: Implement global exception handling for unhandled exceptions.
- **Use of Var**: Use `var` when the type is apparent to enhance readability.
- **Comments and Documentation**: Comment complex logic and maintain XML documentation for public APIs.

### 3. Database Access and Entity Framework Core Best Practices

Entity Framework Core optimization ensures performance and maintainability.


- **Manage DbContext Lifecycle**: Use a scoped lifetime for DbContext in web applications.
- **Query Optimization**: Optimize queries by selecting only required fields and avoiding N+1 queries.
- **Use of Migrations**: Apply EF Core Migrations for database schema changes.
- **Separation of Concerns**: Separate entity models from business logic using DTOs.

### 4. Security Best Practices

Implementing robust security measures is paramount.


- **Authentication and Authorization**: Implement policy-based authorization with ASP.NET Core Identity.
- **Data Protection**: Encrypt sensitive data using ASP.NET Core's data protection APIs.
- **Secure API Endpoints**: Secure all API endpoints using appropriate authentication schemes.
- **Input Validation**: Validate incoming data to protect against vulnerabilities.

### 5. Performance Optimization

Optimizing application performance is essential.


- **Response Caching**: Use response caching to improve response times.
- **Efficient Use of Middleware**: Minimize middleware usage to reduce overhead.
- **Application Insights**: Use Application Insights for performance monitoring.
- **Use of Asynchronous Methods**: Improve scalability with asynchronous methods.

### 6. Code Reviews and Quality Assurance

Code reviews and quality assurance practices maintain code quality.


- **Implement Code Reviews**: Conduct regular code reviews to enforce standards and detect issues.
- **Static Code Analysis**: Use Roslyn analyzers for static code analysis.
- **Automated Testing**: Develop automated tests for reliability and facilitate CI/CD.
- **CI/CD Pipelines**: Implement CI/CD for automated testing and deployment.

## Conclusion

Adhering to these guidelines ensures that our backend solutions meet the highest standards of quality, maintainability, scalability, and security. This document will evolve with emerging technologies and practices.

