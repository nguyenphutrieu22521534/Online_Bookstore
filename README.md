# BookStore Web Application

A sample BookStore web application built with ASP.NET Core Razor Pages (.NET 8).  
This project demonstrates CRUD operations, category management, and product management using Entity Framework Core.

## Features

- Manage book categories and products
- Responsive UI with Bootstrap 5
- DataTables integration for enhanced tables
- Toastr notifications for user feedback
- SweetAlert2 for confirmation dialogs

## Technologies Used

- ASP.NET Core Razor Pages (.NET 8)
- Entity Framework Core
- Bootstrap 5
- jQuery
- DataTables
- Toastr
- SweetAlert2

## Getting Started

1. **Clone the repository:**

2. **Configure the database:**
- Update the connection string in `appsettings.json` (`DefaultConnection`).

3. **Apply migrations:**

4. **Run the application:**

5. **Access the app:**
- Open your browser and navigate to `https://localhost:5001`

## Project Structure

- `BookStore.Web` - Main web project (Razor Pages)
- `BookStore.DataAccess` - Data access layer and repositories
- `BookStore.Models` - Entity models

## License

This project uses Bootstrap under the MIT License.  
See [`wwwroot/lib/bootstrap/LICENSE`](BookStore.Web/wwwroot/lib/bootstrap/LICENSE) for details.
