# 1. Simple To-Do List (Python)

A simple command-line **To-Do List App** written in Python.  
It lets you view, add, and remove tasks, with all tasks saved to a local file (`tasks.txt`).

---

# 2. Features

-  **View Tasks** – Display all your saved to-do items.  
-  **Add Tasks** – Add a new task to your list.  
-  **Remove Tasks** – Delete a completed or unwanted task.  
-  **Persistent Storage** – Tasks are automatically saved in `tasks.txt` so they’re available the next time you run the app.  
-  **Simple Text-Based Interface** – Easy to use directly from the terminal.

---

# 3. How It Works

When you start the program:
1. It loads existing tasks from `tasks.txt` (if available).
2. Displays a simple menu with options:
   - View tasks
   - Add a new task
   - Remove a task
   - Exit
3. After each operation, the list is automatically saved.

---

# 4. Example Usage

```bash
=== To-Do List Menu ===
1. View tasks
2. Add task
3. Remove task
4. Exit
Choose an option (1-4): 2
Enter a new task: Finish Python project
Task added: Finish Python project
