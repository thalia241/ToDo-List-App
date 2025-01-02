# To-Do List App
A simple Python command-line to-do list application with persistent storage.

## Features
- View tasks with their status (completed or pending)
- Add new tasks
- Mark tasks as completed
- Delete tasks
- Persistent storage using a text file
# How It Works
## Task Storage:
Tasks are stored in a local file (tasks.txt) in the format: task_description|status.
## Commands:
View Tasks: Displays tasks with their status.
Add Task: Adds a new task as "pending."
Mark Completed: Changes the status of a task to "completed."
Delete Task: Removes a task from the list.
Exit: Saves all tasks to the file and exits the app.
Persistent Data:

Tasks are saved to and loaded from a text file, so they persist between app sessions.
