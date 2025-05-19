# 📝 TaskManagerAPI

A simple Task Management Web API built using ASP.NET Core 6 and Entity Framework Core (InMemory) as part of a .NET Developer Hiring Challenge.  
This app allows users to create, read, update, and delete tasks through a RESTful API.

---

## 🚀 Features

- CRUD operations for tasks (Create, Read, Update, Delete)
- In-memory database using Entity Framework Core
- JSON-based REST API with proper status codes
- Swagger UI for easy API testing

---

## 🧰 Tech Stack

- ASP.NET Core 6 Web API
- C#
- Entity Framework Core (InMemory provider)
- Swagger / OpenAPI

---

## 🗃️ Task Data Model

```json
{
  "id": 1,
  "title": "Buy groceries",
  "description": "Milk, Bread, Eggs",
  "dueDate": "2025-05-01T00:00:00",
  "isComplete": false
}
```

---

## 📁 Project Structure

```
TaskManagerAPI/
├── Controllers/
│   └── TasksController.cs
├── Models/
│   └── TaskItem.cs
├── Data/
│   └── TaskDbContext.cs
├── Program.cs
├── TaskManagerAPI.csproj
└── README.md
```

---

## 🧪 API Endpoints

| Method | Endpoint          | Description             |
|--------|-------------------|-------------------------|
| GET    | /api/tasks        | Get all tasks           |
| GET    | /api/tasks/{id}   | Get a task by ID        |
| POST   | /api/tasks        | Create a new task       |
| PUT    | /api/tasks/{id}   | Update a task           |
| DELETE | /api/tasks/{id}   | Delete a task by ID     |

---

## 🛠️ How to Run the Project

### Prerequisites

- Visual Studio 2022 or later
- .NET 6 SDK or higher

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TaskManagerAPI.git
   ```

2. Open the project in **Visual Studio**

3. Press **F5** to run

4. Navigate to: `https://localhost:5001/swagger` to test the API

---

## 📹 Video Walkthrough (optional)

Include a short video demonstrating:
- Running the API
- Performing basic CRUD operations
- Explaining your folder and code structure

---

## ✅ Notes & Assumptions

- Title is required for all tasks
- Description and due date are optional
- Data resets every time the app restarts (in-memory DB)
- Clean RESTful practices are followed

---

## 👤 Author

Built by Harshit Suman for the Sdaemon Infotech .NET Developer Challenge.