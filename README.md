# GameStore Web API

A backend-only RESTful Web API built using ASP.NET Core.

## Features
- CRUD operations for games
- RESTful endpoints (GET, POST, PUT, DELETE)
- SQLite database with Entity Framework Core
- Clean project structure using DTOs and Endpoints

## Tech Stack
- C#
- ASP.NET Core Web API
- Entity Framework Core
- SQLite

## Endpoints
- GET /games
- GET /games/{id}
- POST /games
- PUT /games/{id}
- DELETE /games/{id}

## Project Structure
- Models – Domain entities
- DTOs – API request/response contracts
- Endpoints – Minimal API endpoints
- Data – Database context and persistence


## How to Run
1. Clone the repository
2. Open the solution in Visual Studio / VS Code
3. Run the project using `dotnet run`
4. Test endpoints using the provided `.http` file

## Status
Backend completed. Frontend can be added later.
