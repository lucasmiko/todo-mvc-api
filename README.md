# Todo MVC API

## Overview

This is a simple Todo MVC API project built using ASP.NET and Entity Framework with SQLite as the database provider. The project implements CRUD (Create, Read, Update, Delete) operations for managing Todo items.

## Prerequisites

Before you start, make sure you have the following installed on your machine:

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) or any other preferred IDE

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/lucasmiko/todo-mvc-api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-mvc-api
   ```

3. Open the project in your preferred IDE (Visual Studio recommended).

4. Build and run the project.

## Database Setup

This project uses SQLite as the database. The database file (`app.db`) will be created in the project root directory.

If you need to apply migrations or update the database schema, you can use the following commands in the terminal:

```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```

## Usage

Once the project is running, you can access the CRUD operations through the following endpoints:

- **Get All Todos:** `GET /`
- **Get Todo by ID:** `GET /{id:int}`
- **Create Todo:** `POST /`
- **Update Todo by ID:** `PUT /{id:int}`
- **Delete Todo by ID:** `DELETE /{id:int}`

Make sure to replace `{id}` with the actual ID of the item you want to retrieve, update, or delete.

## Contributing

Feel free to contribute to the project by creating issues or submitting pull requests. Your feedback and contributions are highly appreciated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the ASP.NET and Entity Framework communities for their excellent documentation and resources.

Happy coding!
