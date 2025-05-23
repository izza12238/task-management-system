# task-management-system
A simple yet powerful console-based Task Management System built with Java that helps you organize and track your tasks efficiently.

Features
Create tasks with title, description, and due date

Edit existing tasks (modify any field)

Delete tasks you no longer need

Mark tasks as complete/incomplete

Filter tasks by:

Completion status (completed/incomplete)

Due date

View all tasks in a clean format

Getting Started
Prerequisites
Java JDK 17 or later

Git (optional)

Installation
Clone the repository:

bash
git clone https://github.com/izza12238/task-management-system.git
cd task-management-system
Compile the Java file:

bash
javac TaskManagementSystem.java
Run the application:

bash
java TaskManagementSystem
Usage
After launching the application, you'll see a menu with these options:

--- Task Management System ---
1. Add Task
2. Edit Task
3. Delete Task
4. Mark Task as Complete
5. Mark Task as Incomplete
6. View All Tasks
7. Filter Tasks by Status
8. Filter Tasks by Due Date
9. Exit
Follow the on-screen prompts to manage your tasks. The system will guide you through each operation.

Code Structure
The application follows a clean architecture with three main layers:

Entity Layer (Task class)

Core task model with properties and basic methods

Service Layer (TaskService class)

Business logic for task operations

Handles task storage and retrieval

UI Layer (ConsoleUI class)

User interface and input handling

Menu navigation and display

Example Task
ID: 1
Title: Complete Project
Description: Finish the project documentation
Due Date: 2023-12-15
Status: Incomplete
Limitations

Future Enhancements
Add database persistence

Implement user authentication

Add priority levels to tasks

Enable task categories/tags

Develop a GUI version

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
