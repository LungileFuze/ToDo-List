# Blazor To-Do App

## Overview
This is a simple To-Do application built using the Blazor framework. The app allows users to manage tasks efficiently by adding, editing, marking as complete, and deleting them.

## Features
- Add new tasks
- Edit existing tasks
- Mark tasks as completed
- Delete tasks
- Persist tasks using local storage or a database (optional)

## Technologies Used
- **Blazor (Server/WebAssembly)** – for building interactive UI
- **.NET** – for backend logic
- **Entity Framework Core (optional)** – for database interactions
- **SQLite/SQL Server (optional)** – for data persistence
- **Bootstrap (optional)** – for styling

## Installation & Setup
### Prerequisites
- .NET SDK 6.0 or later
- Visual Studio 2022 or Visual Studio Code

### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/blazor-todo-app.git
   cd blazor-todo-app
   ```
2. Open the project in Visual Studio or VS Code.
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Build and run the project:
   ```sh
   dotnet run
   ```
5. Open a browser and navigate to `https://localhost:5001` (or the port specified in your settings).

## Usage
- Click "Add Task" to create a new task.
- Click on a task to edit its details.
- Use the checkbox to mark a task as complete.
- Click the delete button to remove a task.

## Deployment
To deploy the application, you can publish it to a web server or host it on Azure:
```sh
dotnet publish -c Release -o ./publish
```
Follow the deployment guide for your chosen hosting platform.

## Contributions
Feel free to fork the repository and submit pull requests. Ensure that your changes align with the project goals.

## License
This project is open-source under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or suggestions, reach out via email at `your-email@example.com` or create an issue on GitHub.

