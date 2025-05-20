# library-catalogue-api
A RESTful API for managing a library catalogue, including books, authors, categories, and users. Designed using best practices including Richardson Maturity Model Level 3, token-based authentication, pagination, and caching.

## Features
- CRUD operations for books, authors, categories
- OAuth 2.0 JWT-based authentication
- Role-based access: admin vs. user
- Filtering and pagination
- HTTP caching for GET endpoints
- Full REST compliance (Level 3 maturity)

## Technologies
- REST API Design
- OpenAPI (Swagger)
- JSON
- JWT (Authentication)

## API Documentation

See [API_SPEC.md](./API_SPEC.md) for full API structure and descriptions.

## Authentication

The API uses OAuth 2.0 with JWT tokens. Include the token in the `Authorization` header:
