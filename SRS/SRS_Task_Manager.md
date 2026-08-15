# Software Requirements Specification (SRS)

## Task Manager — Command-Line Application

**Name:** Anushree Ajjappa Mangalgatti  
**College:** Jain College Of Engineering And Technology, Hubballi  
**Internship:** CodeOrbit Tech — Software Development Internship

---

## 1. Introduction

### 1.1 Purpose

The purpose of this project is to develop a simple command-line Task Manager application that allows users to create, view, complete, and delete tasks.

The application will provide a simple menu-driven interface and will be developed using Python.

### 1.2 Scope

The Task Manager application will allow users to:

- Add new tasks.
- View all available tasks.
- Mark tasks as completed.
- Delete tasks.
- Exit the application.

The application is intended for individual users who want to manage their daily tasks through a simple command-line interface.

### 1.3 Objectives

The main objectives of the application are:

- To provide a simple way to manage daily tasks.
- To allow users to track completed and pending tasks.
- To provide an easy-to-use command-line interface.
- To validate user input and prevent invalid operations.
- To practice software development and version control concepts.

---

## 2. Functional Requirements

The system shall provide the following functionality.

### FR1 — Add Task

The user shall be able to enter and add a new task to the task list.

### FR2 — View Tasks

The system shall display all stored tasks along with their completion status.

### FR3 — Mark Task as Completed

The user shall be able to select a task and mark it as completed.

### FR4 — Delete Task

The user shall be able to select a task and remove it from the task list.

### FR5 — Menu Navigation

The system shall provide a menu containing available operations and allow the user to select an option.

### FR6 — Exit

The user shall be able to safely exit the application.

### FR7 — Input Validation

The system shall validate user input and display an appropriate message when an invalid option or task number is entered.

---

## 3. Non-Functional Requirements

### NFR1 — Usability

The application should provide a simple and understandable menu-driven interface that is easy for users to operate.

### NFR2 — Performance

The application should respond quickly to user commands when managing a normal number of tasks.

### NFR3 — Reliability

The application should handle invalid inputs without crashing.

### NFR4 — Maintainability

The Python code should be organized, readable, and properly commented to make future modifications easier.

### NFR5 — Portability

The application should be capable of running on systems that have a compatible Python 3 installation.

---

## 4. User Stories

### User Story 1 — Add Task

As a user, I want to add a new task so that I can keep track of the work I need to complete.

### User Story 2 — View Tasks

As a user, I want to view my tasks so that I can know which tasks are pending or completed.

### User Story 3 — Complete Task

As a user, I want to mark a task as completed so that I can track my progress.

### User Story 4 — Delete Task

As a user, I want to delete an unnecessary task so that my task list remains organized.

### User Story 5 — Exit Application

As a user, I want to exit the application safely when I have finished managing my tasks.

---

## 5. Use Cases

| Use Case | Actor | Description |
|---|---|---|
| Add Task | User | The user enters and adds a new task. |
| View Tasks | User | The user views all available tasks and their status. |
| Complete Task | User | The user selects a task and marks it as completed. |
| Delete Task | User | The user selects and removes a task. |
| Exit Application | User | The user exits the application safely. |

---

## 6. System Requirements

### 6.1 Hardware Requirements

- Computer or laptop.
- Minimum 2 GB RAM.
- Keyboard and display.

### 6.2 Software Requirements

- Python 3.x.
- Visual Studio Code or any Python-compatible IDE.
- Git for version control.
- GitHub account for project hosting.

---

## 7. User Interface

The application will use a command-line interface with a simple menu.

Example:

```text
===== TASK MANAGER =====

1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Delete Task
5. Exit

Enter your choice:

Start Application
       ↓
Display Main Menu
       ↓
User Selects an Option
       ↓
Perform Selected Operation
       ↓
Display Result
       ↓
Return to Main Menu
       ↓
User Selects Exit
       ↓
End Application

```
## 9. Limitations

The initial version of the application will be a simple command-line program.

The application will not include:

- User authentication.
- Online synchronization.
- Graphical user interface.
- Database connectivity.
- Notifications or reminders.

These features may be considered for future versions.

## 10. Future Enhancements

The following features can be added in future versions:

- Graphical user interface.
- Permanent task storage using files or a database.
- Task priorities.
- Due dates and deadlines.
- Task search and filtering.
- User authentication.
- Task reminders and notifications.
- Web-based version of the application.

## 11. Conclusion

The Task Manager Command-Line Application is a simple software project designed to help users manage their daily tasks efficiently.

The project demonstrates important software development concepts including requirement analysis, functional and non-functional requirements, user stories, use cases, input validation, and Python programming.

The project will also provide practical experience with Git and GitHub through version control and project management.
