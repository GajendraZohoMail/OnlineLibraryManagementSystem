
# Project: Online Library Management System

## Technology Stack
- .NET 10
- ASP.NET Core Web API
- Angular
- PostgreSQL
- Entity Framework Core
- ASP.NET Core Identity
- JWT Authentication
- xUnit and Moq

## Architecture
- Follow Clean Architecture principles.
- Keep Domain independent of Infrastructure.
- Keep business logic in Application/Domain layers.
- Use dependency injection.
- Use RESTful API conventions.
- Follow SOLID principles and appropriate design patterns.

## Coding Standards
- Use asynchronous programming for I/O.
- Use CancellationToken where appropriate.
- Use DTOs for API requests and responses.
- Implement centralized exception handling.
- Implement structured logging.
- Validate all incoming requests.
- Never expose passwords or sensitive data.
- Follow secure coding practices.

## Database
- Use Entity Framework Core.
- Use migrations.
- Enforce appropriate database constraints.
- Avoid N+1 queries.
- Use transactions for critical operations.

## Testing
- Use xUnit and Moq.
- Write unit tests for business logic.
- Cover positive, negative and boundary scenarios.
- Test authorization and validation.
- Do not modify tests merely to hide implementation failures.

## Important Instructions
- Always refer to docs/SRS.pdf and approved requirements.
- Do not invent business requirements.
- Ask questions when requirements are ambiguous.
- Do not change existing architecture without approval.
- Explain the purpose of generated code.
- Build and test after implementation.
- Never hardcode credentials or secrets.
