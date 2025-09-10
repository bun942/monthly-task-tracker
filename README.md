# monthly-task-tracker
A simple Python CLI-based Task Manager that helps you create, view, and delete tasks organized by month and year. Tasks are stored in text files inside a dedicated folder (task/) with automatic numbering, making it easy to track and manage them. This project is a command-line task manager built with Python.

## Features:
- Add new tasks for a specific month & year.
- Store tasks in text files named as <month>_<year>.txt.
- Automatically assign task numbers.
- View all tasks for a given month.
- Mark tasks as complete (deletes them from the file).
- Lightweight, no external dependencies.

## How it works:
- When you create a new task, a file is created (if not already present) inside the task/ folder.
- Tasks are stored with numbering for easy tracking.
- You can manage tasks (view or delete them) through the menu-driven CLI.
