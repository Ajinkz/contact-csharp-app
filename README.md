# Contact Management Application (C#)

A REST API for managing contacts built with ASP.NET Core 8.0.

## Features
- Get all contacts
- Get contact by ID
- Create new contact
- Update contact
- Delete contact
- OpenAPI/Swagger documentation

## Prerequisites
- .NET 8.0 SDK or later
- Docker (for containerization)

## Running Locally

```bash
dotnet restore
dotnet run
```

The application will be available at `http://localhost:5000`
Swagger UI: `http://localhost:5000/swagger`

## Docker

```bash
docker build -t contact-app:latest .
docker run -p 8080:8080 contact-app:latest
```

## API Endpoints

- `GET /api/contact` - Get all contacts
- `GET /api/contact/{id}` - Get contact by ID
- `POST /api/contact` - Create new contact
- `PUT /api/contact/{id}` - Update contact
- `DELETE /api/contact/{id}` - Delete contact
