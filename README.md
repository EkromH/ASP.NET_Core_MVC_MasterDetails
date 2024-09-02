# ASP.NET Core MVC Master-Details

This project is an ASP.NET Core MVC application demonstrating the Master-Details pattern. It showcases how to manage and display master-detail data using ASP.NET Core MVC with entity framework and a clean architecture.

## Features

- **Master-Detail View**: Display a list of master entities and their associated details.
- **CRUD Operations**: Create, Read, Update, and Delete operations for master and detail entities.
- **Entity Framework Core**: Utilizes EF Core for database interactions.
- **Responsive Design**: Basic styling to ensure the application is usable on various devices.

## Technologies Used

- **ASP.NET Core MVC**: Framework for building web applications.
- **Entity Framework Core**: ORM for database operations.
- **Bootstrap**: Styling framework for a responsive layout.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 7.0 or higher)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or another compatible database system

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/EkromH/ASP.NET_Core_MVC_MasterDetails.git
   cd ASP.NET_Core_MVC_MasterDetails
2. **Configure Database Connection**
   
Open the appsettings.json file and configure the ConnectionStrings section to point to your database.

3. **Apply Migrations**
Run the following commands to apply the database migrations:

   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
4. **Run the Application**
Start the application using:

   ```bash
   dotnet run

Navigate to http://localhost:5000 in your web browser to view the application.

Usage
Master View: Navigate to the master entity view to see a list of master entities.
Detail View: Click on an item in the master view to see its associated details.
CRUD Operations: Use the provided UI to create, update, or delete master and detail entities.
