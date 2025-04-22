
# Booking API

A RESTful API built with ASP.NET Core (.NET 6/7) and SQL Server for managing booking operations such as creating, viewing, updating, and deleting bookings. This API can be used for hotel reservations, event scheduling, room bookings, and more.

## Features

- User registration and authentication (JWT-based)
- CRUD operations for Bookings
- Management of Rooms or Services
- Date conflict checking
- Filtering and pagination
- SQL Server database integration using Entity Framework Core
- Clean layered architecture (Controller > Service > Repository)

## Technologies Used

- ASP.NET Core
- Entity Framework Core
- SQL Server
- AutoMapper
- Swagger / Swashbuckle
- JWT Authentication

## Getting Started

### Prerequisites

- [.NET 6 SDK or later](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- [Postman](https://www.postman.com/) (optional, for testing API)
- [Visual Studio](https://visualstudio.microsoft.com/) or [VS Code](https://code.visualstudio.com/)

### Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/booking-api.git
   cd booking-api
