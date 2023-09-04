# ASP.NET Core Developer Roadmap

## MVC

### Controllers

- **Model State**: Ensures data passed to action methods is valid.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/actions?view=aspnetcore-7.0)
- **Exception Handling**: Manage unexpected errors gracefully.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/error-handling?view=aspnetcore-7.0)
- **Controller Lifecycle**: Understand the sequence of method calls in a controller's life.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/actions?view=aspnetcore-7.0)

### Views

- **Strongly Typed Views**: Use model data effectively in views.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/overview?view=aspnetcore-7.0)
- **HTML Helpers vs Tag Helpers**: Compare traditional HTML helpers with the newer Tag helpers.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/intro?view=aspnetcore-7.0)
- **_ViewStart and _ViewImports**: Centralize view configurations and imports.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/layout?view=aspnetcore-7.0)

### Models

- **Data Annotations**: Attributes for model validation and display.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-7.0)
- **Remote Validation**: Server-side validation for form inputs.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-7.0#remote-attribute)

### Razor Pages

- **Handler Methods (OnGet, OnPost)**: Methods that handle GET and POST requests.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-7.0&tabs=visual-studio)
- **Page Filters**: Apply logic before or after page actions.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/filter?view=aspnetcore-7.0)

## Web API

- **Content Negotiation**: Determine the best response format based on client capabilities.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/web-api/advanced/formatting?view=aspnetcore-7.0)
- **Versioning**: Manage multiple versions of an API.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/web-api/versioning?view=aspnetcore-7.0)
- **Rate Limiting**: Control the number of requests from a client.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
- **CORS (Cross-Origin Resource Sharing)**: Securely handle requests from different origins.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/cors?view=aspnetcore-7.0)
- **API Conventions and ProducesResponseType**: Define standard behaviors and responses for APIs.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/web-api/action-return-types?view=aspnetcore-7.0)

## Communication and APIs

### gRPC

- **Introduction to gRPC**: A high-performance, open-source and universal RPC framework.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/grpc/?view=aspnetcore-7.0)
- **gRPC Services**: Building gRPC services with ASP.NET Core.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/grpc/services?view=aspnetcore-7.0)
- **gRPC Client**: Creating gRPC clients for ASP.NET Core gRPC services.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/grpc/client?view=aspnetcore-7.0)
- **gRPC Web**: Using gRPC-Web with .NET Core.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/grpc/browser?view=aspnetcore-7.0)

### GraphQL

- **Introduction to GraphQL**: A query language for your API, and a server-side runtime for executing queries.
  - [Official Site](https://graphql.org/)
- **GraphQL for .NET**: An implementation of GraphQL for .NET Core.
  - [GitHub Repository](https://github.com/graphql-dotnet/graphql-dotnet)
- **Hot Chocolate**: A platform for building GraphQL servers and clients in .NET.
  - [Official Documentation](https://chillicream.com/docs/hotchocolate)

## Security

- **Data Protection**: Safeguard sensitive data in your application.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/introduction?view=aspnetcore-7.0)
- **OAuth and OpenID Connect**: Standards for authorization and identity.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social?view=aspnetcore-7.0)
- **Two-Factor Authentication**: Enhance security with a second verification step.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/2fa?view=aspnetcore-7.0)
- **Anti-Forgery Tokens**: Protect against cross-site request forgery attacks.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/anti-request-forgery?view=aspnetcore-7.0)
- **Data Encryption and Decryption**: Secure data at rest and in transit.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/using-data-protection?view=aspnetcore-7.0)

## Hosting and Deployment

- **Environment Variables**: Store configuration separate from code.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-7.0)
- **Reverse Proxies (e.g., Nginx)**: Forward web requests to your app.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-7.0)
- **Continuous Integration and Continuous Deployment (CI/CD)**: Automate code testing and deployment.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-cicd)
- **Scaling and Load Balancing**: Distribute incoming network traffic across multiple servers.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/architecture/best-practices/load-balancing)

## Entity Framework Core

- **Entity Model**: Understand the core concepts of the Entity Framework.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/)
- **Shadow Properties**: Properties that don't exist in your entity class but do in the database.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/shadow-properties?view=aspnetcore-7.0)
- **Owned Entities**: Complex types that don't have their own database identity.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/modeling/owned-entities?view=aspnetcore-7.0)
- **Interceptors**: Intercept database operations.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/logging-events-diagnostics/interceptors?view=aspnetcore-7.0)
- **Database First vs Code First**: Approaches to database design and interaction.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/dbcontext-configuration/?view=aspnetcore-7.0)
- **Database Health Checks**: Ensure your database is running and accessible.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/health-checks?view=aspnetcore-7.0)

## Advanced

- **Caching (In-Memory, Distributed)**: Improve performance by storing frequently accessed data.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-7.0)
- **Background Services and IHostedService**: Execute background operations.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services?view=aspnetcore-7.0)
- **Custom Tag Helpers**: Create custom, reusable components for views.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/custom?view=aspnetcore-7.0)
- **Dependency Injection Lifetimes (Transient, Scoped, Singleton)**: Manage object lifetimes in your app.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-7.0)
- **Extensions Methods for IServiceCollection**: Add custom services to the DI container.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-7.0)
- **Integration with Azure Services**: Utilize cloud services for storage, databases, and more.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/developer/dotnet/)
- **Real-time Web Apps with SignalR**: Enable real-time communication in web apps.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/signalr/introduction?view=aspnetcore-7.0)
- **Health Checks and Monitoring**: Monitor the health and performance of your app.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/health-checks?view=aspnetcore-7.0)
- **Error Handling and Custom Exception Filters**: Handle errors consistently.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/error-handling?view=aspnetcore-7.0)
- **Custom Middleware Development**: Create custom logic that executes on each HTTP request.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/write?view=aspnetcore-7.0)
- **Working with Static Files and wwwroot**: Serve static files in ASP.NET Core.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/static-files?view=aspnetcore-7.0)
- **Configuration Providers (e.g., Azure Key Vault, Command Line)**: Source configuration from various providers.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-7.0)
- **Logging Providers (e.g., Serilog, ELK Stack)**: Implement advanced logging mechanisms.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/logging/?view=aspnetcore-7.0)
- **Integration Testing**: Test integration points in your application.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-7.0)

## Tools and Utilities

- **NuGet Package Management**: Manage third-party libraries in your project.
  - [Official Documentation](https://docs.microsoft.com/en-us/nuget/)
- **.NET CLI Tools**: Command-line tools for .NET operations.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/core/tools/)
- **Profiling and Diagnostics Tools**: Analyze and optimize your application's performance.
  - [Official Documentation](https://docs.microsoft.com/en-us/visualstudio/profiling/?view=vs-2019)
- **Source Control with Git and GitHub/GitLab**: Manage and track changes to your codebase.
  - [Official Documentation](https://docs.microsoft.com/en-us/azure/devops/repos/git/gitworkflow)

## Design Patterns and Best Practices

- **Repository Pattern**: Separate database logic from business logic.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design)
- **Unit of Work Pattern**: Group operations into a single transaction.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design)
- **Factory Pattern**: Create objects without specifying the exact class.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/design-patterns/factory-method)
- **Singleton Pattern**: Ensure a class has only one instance.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/design-patterns/singleton)
- **Strategy Pattern**: Define a family of algorithms and make them interchangeable.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/design-patterns/strategy)

## Front-end Technologies

- **Blazor (Server-side and WebAssembly)**: Build interactive web UIs using C#.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-7.0)
- **Razor Components**: Reusable UI components for Blazor apps.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/blazor/components/?view=aspnetcore-7.0)
- **JavaScript Interop**: Call JavaScript functions from C# and vice versa.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/blazor/call-javascript-from-dotnet?view=aspnetcore-7.0)
- **SPA Integration (e.g., Angular, React)**: Integrate with popular front-end frameworks.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/client-side/spa-services?view=aspnetcore-7.0)

## Resources

- **ASP.NET Core Documentation**: Comprehensive documentation for all ASP.NET Core topics.
  - [Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- **.NET Core Documentation**: Documentation for the .NET Core platform.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/core/)
- **C# Documentation**: Learn about the C# programming language.
  - [Official Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)
- **Entity Framework Core Documentation**: Documentation for Microsoft's ORM tool.
  - [Official Documentation](https://docs.microsoft.com/en-us/ef/core/)
- **Visual Studio Documentation**: Learn about Microsoft's integrated development environment.
  - [Official Documentation](https://docs.microsoft.com/en-us/visualstudio/?view=vs-2019)
