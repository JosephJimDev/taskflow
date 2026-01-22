# TaskFlow – Task Management System

## Project Overview

TaskFlow is a simple task management system designed to help users create, organize, track, and manage tasks efficiently. The system allows users to add tasks, update their status, view task lists, and delete completed or unwanted tasks. The project is intended for academic purposes and demonstrates the application of the Software Development Life Cycle (SDLC) in a real-world software project.

---

## Problem Statement

Many individuals and small teams struggle with organizing daily tasks and tracking progress effectively. Existing solutions may be overly complex or inaccessible for beginners. TaskFlow provides a lightweight and easy-to-use solution for basic task management needs.

---

## Objectives

- To design and implement a simple task management system
- To apply all phases of the Software Development Life Cycle (SDLC)
- To ensure consistency between system design and implementation
- To demonstrate clean coding and proper documentation practices

---

## Scope of the System

The TaskFlow system supports the following:

- Create a new task
- View all tasks
- Update task status (Pending / Completed)
- Delete a task
- Store tasks during program execution

The system does not include user authentication or cloud storage, as it is designed for learning purposes.

---

## Software Development Life Cycle (SDLC)

### 1. Requirement Analysis

At this stage, the functional and non-functional requirements of the system were identified.

**Functional Requirements**

- The system shall allow users to add tasks
- The system shall display a list of tasks
- The system shall allow users to update task status
- The system shall allow users to delete tasks

**Non-Functional Requirements**

- The system shall be easy to use
- The system shall be reliable
- The system shall run efficiently on a standard computer

---

### 2. System Design

The system follows a modular design approach.

**Key Design Components**

- `Task` class: Represents a task with attributes such as ID, title, and status
- `TaskManager` class: Handles task operations (add, update, delete, display)
- Main program: Controls user interaction and application flow

---

### 3. Implementation

The system is implemented using a structured programming approach. All class names, methods, and variables strictly follow the design specifications defined in the design phase.

**Technology Stack**

- Programming Language: C++
- Development Environment: Any standard C++ compiler (GCC, Dev-C++, Code::Blocks)

---

### 4. Testing

The system was tested using manual test cases to ensure correctness.

**Testing Techniques Used**

- Unit testing of individual functions
- Integration testing of modules
- User acceptance testing using sample inputs

---

### 5. Deployment

The application is deployed as a console-based program. Users can compile and run the program locally using a C++ compiler.

---

### 6. Maintenance

Future improvements may include:

- File-based or database storage
- User authentication
- Graphical user interface (GUI)
- Task prioritization and deadlines

---

### Project Structure
TaskFlow/
│
├── main.cpp
├── Task.h
├── TaskManager.h
├── TaskManager.cpp
└── README.md

### Limitations

- Data is not persisted after program termination

- Single-user system

- Console-based interface only

### Conclusion

TaskFlow successfully demonstrates the application of the Software Development Life Cycle (SDLC) in building a functional software system. The project meets all defined objectives and serves as a solid foundation for further enhancements.

### Author

- -Name: Jim Joseph Onyedikachi
- Course: Computer Science
- 24/15932

### rep link
[Rep link](https://github.com/JosephJimDev/taskflow)
[site link](https://josephjimdev.github.io/taskflow/)

