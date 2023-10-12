# To-Do Console App

A simple yet robust console-based To-Do application built with C#. Designed using clean architecture principles to ensure maintainability and scalability.

## Features:

- **Interactive Console UI**: User-friendly interface for easy task management.
- **CRUD Operations**: Create, Read, Update, and Delete tasks seamlessly.
- **Task Status Management**: Mark tasks as Completed, Pending, or In-progress.
- **In-memory & SQL Storage**: Supports both in-memory storage (for testing) and SQL-based persistent storage.


## Structure:

The application is structured using the Clean Architecture pattern, ensuring separation of concerns:

- `ToDoConsoleApp`: Console/UI layer for interaction.
- `Application`: Application layer containing business operations.
- `Domain`: Contains core business logic and domain entities.
- `Infrastructure`: Handles external concerns like database operations.
