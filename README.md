# Command Line To-Do List Application

## Project Description

This project is a Command Line To-Do List Application developed using C++. The purpose of this application is to help users manage their daily tasks efficiently through a simple menu-driven interface.

The application allows users to add new tasks, view existing tasks, and delete completed or unwanted tasks. To ensure that tasks are not lost when the program is closed, the application stores all tasks in a text file and automatically loads them when the program starts again.

This project helped me understand file handling, object-oriented programming, vectors, input validation, and data management in C++.

## Features

* Add new tasks to the to-do list.
* View all saved tasks.
* Delete tasks by selecting their task number.
* Automatically save tasks to a text file.
* Load previously saved tasks when the application starts.
* Handle invalid user input gracefully.
* User-friendly menu-driven interface.

## Technologies Used

* C++
* Object-Oriented Programming (OOP)
* Standard Template Library (STL)
* Vector Container
* File Handling (`ifstream` and `ofstream`)
* Input Validation


## How the Program Works

### 1. Load Existing Tasks

When the application starts, it reads all previously saved tasks from the `tasks.txt` file and stores them in memory.

### 2. Add Task

The user can enter a new task description. The task is added to the list and immediately saved to the file.

### 3. View Tasks

All saved tasks are displayed with a unique task number, making them easy to identify and manage.

### 4. Delete Task

The user can remove a task by entering its corresponding task number. The task is removed from both memory and the file.

### 5. Exit Application

The user can safely exit the application. Since tasks are automatically saved, all data remains available for future use.


## Example Output

### Main Menu

=====================================
      COMMAND LINE TO-DO LIST
=====================================
1. Add Task
2. View Tasks
3. Delete Task
4. Exit
=====================================
Enter your choice:


### Adding a Task

Enter Task Description: Complete C++ Internship Project

Task added successfully.


### Viewing Tasks
========== CURRENT TASKS ==========
[1] Complete C++ Internship Project
[2] Prepare Project Documentation
===================================


### Deleting a Task

```text
Enter Task Number to Delete: 1

Task deleted successfully.

## Concepts Learned

Through this project, I learned:

* Object-Oriented Programming using classes
* Managing data using vectors
* Reading and writing data to files
* Input validation and error handling
* Menu-driven program design
* Modular programming using functions
* Persistent data storage

## Applications

A To-Do List Application can be useful for:

* Personal task management
* Student assignment tracking
* Daily activity planning
* Project management
* Productivity improvement

## Future Enhancements

This project can be further improved by adding:

* Task priorities
* Due dates and deadlines
* Task completion status
* Search functionality
* Edit task feature
* Sorting and filtering tasks
* Graphical User Interface (GUI)

## Conclusion

The Command Line To-Do List Application is a practical project that demonstrates how C++ can be used to manage and organize tasks efficiently. By combining object-oriented programming, file handling, and data structures, this project provides a simple yet effective task management solution while strengthening core programming and problem-solving skills.
