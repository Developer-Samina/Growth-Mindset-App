#     Growth-Mindset-App
# Growth Mindset Challenge: Web App with Streamlit.

# To-Do List CLI Application
# This is a simple Command-Line Interface (CLI) application for managing a to-do list using Python. The application allows users to add, list, mark as complete, and remove tasks efficiently. It uses the click library for CLI interactions and stores tasks in a JSON file for persistence.

# Features
# Add a new task
# List all tasks with their status
# Mark a task as completed
# Remove a task from the list
# Data persistence using JSON
# Requirements
# To run this project, ensure you have the following installed:

# Python 3.x
# click library
# You can install the required library using:

# pip install click
# Usage
# Run the script using the command:

# python todo.py <command> [arguments]
# Available Commands
# 1. Add a Task
# python todo.py add "Task description"
# Example:

# python todo.py add "Buy groceries"
# This will add "Buy groceries" to the to-do list.

# 2. List All Tasks
# python todo.py list
# This command will display all tasks with their status (✓ for completed, ✗ for pending).

# 3. Mark a Task as Completed
# python todo.py complete <task_number>
# Example:

# python todo.py complete 1
# Marks the first task as completed.

# 4. Remove a Task
# python todo.py remove <task_number>
# Example:

# python todo.py remove 2
# Removes the second task from the list.

# How It Works
# Tasks are stored in a JSON file (todo.json).
# When a command is executed, tasks are loaded from the file.
# The required action (add, list, complete, remove) is performed.
# The updated tasks are saved back to the file.
# File Structure
# .
# ├── todo.py  # Main script
# ├── todo.json  # Data storage (created automatically)
# Example Usage
#  python todo.py add "Learn Python"
# Task added: Learn Python

#  python todo.py list
# 1. Learn Python [✗]

#  python todo.py complete 1
# Task 1 marked as completed!

#  python todo.py list
# 1. Learn Python [✓]

#  python todo.py remove 1
# Removed task: Learn Python
# Notes
# The task numbers in complete and remove commands correspond to the order shown in list.
# The JSON file is automatically created if it doesn’t exist.
