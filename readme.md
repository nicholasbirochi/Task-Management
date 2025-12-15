# Task Management System (CLI) — Python

A small task list with an interactive menu inside `main.ipynb`. It lets you add, list, complete and remove tasks; the list lives only in memory and is lost when the session ends.

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

## How to run

Open `main.ipynb` in Jupyter or a compatible editor and run the cells in order, including the cell that calls `main()`. There is no separate `main.py` in this repository.

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

Original code and documentation are covered by [MIT](license).
This project is under the MIT license. See the license file for more details.

---
Made with ♥ by Rocketseat
