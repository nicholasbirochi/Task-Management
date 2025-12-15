# Task Management System (CLI) — Python

A simple **Python** project to manage tasks via the **terminal**, allowing you to **add**, **view**, **mark as completed**, and **remove** tasks through an interactive menu.

## Features
- Add a task (with description)
- List tasks with status:
  - `[ ]` pending
  - `[X]` completed
- Mark a task as completed (by number)
- Remove a task (by number)
- Exit the system

## Tech Stack
- Python 3.x
- CLI (Terminal)

## How to Run

### Option 1 — Run as a `.py` script (recommended)
1. Create a file named `main.py` (or any name) and paste the project code.
2. Run in the terminal:

    python main.py

> On some environments (Linux/macOS), you may need:

    python3 main.py

### Option 2 — Run in Jupyter Notebook (`.ipynb`)
1. Open the notebook in Jupyter/VS Code
2. Run the cells in order
3. Execute the cell that calls `main()`

## Usage

When the program starts, choose an option from the menu:

1. Add Task
2. View Tasks
3. Mark Task as Completed
4. Remove Task
5. Exit

Example output when listing tasks:

1. [ ] Study Python
2. [X] Update README

## Data Structure

Tasks are stored in memory (they are not persisted after the program ends) using a list of dictionaries:

{"descricao": "My task", "concluida": False}

## Future Improvements (ideas)
- Save/load tasks using JSON
- Filters (pending/completed)
- Priority and due date
- Unit tests

## License
This project is under the MIT license. See the LICENSE file for more details.

---
Made with ♥ by Rocketseat
