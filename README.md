# Todo CLI (Go)

A simple and efficient command-line Todo application written in Go. This tool helps you manage your daily tasks directly from your terminal, making productivity fast and distraction-free.

## Features (Planned)

- Add new todo items
- List all todos (with status: pending, completed)
- Mark todos as completed
- Delete todo items
- Edit/update existing todos
- Prioritize tasks (low, medium, high)
- Due dates for tasks
- Filter/search todos (by status, priority, due date)
- Save todos to a local file (JSON or similar)
- Load todos from file on startup
- Archive completed tasks
- Clear all completed tasks
- Colorful output for better readability
- Help command and usage instructions

## Example Usage

```sh
# Add a new todo
todo add "Buy groceries"

# List all todos
todo list

# Mark a todo as completed
todo done 1

# Delete a todo
todo delete 2

# Edit a todo
todo edit 3 "Read a book"

# Set priority and due date
todo add "Finish project" --priority high --due 2026-01-31

# Filter by priority
todo list --priority high

# Archive completed tasks
todo archive
```

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/todo-cli.git
   cd todo-cli
   ```
2. Build the binary:
   ```sh
   go build -o todo
   ```
3. (Optional) Move the binary to your PATH:
   ```sh
   sudo mv todo /usr/local/bin/
   ```

## Roadmap

- [ ] Basic CRUD operations
- [ ] Prioritization and due dates
- [ ] Filtering and searching
- [ ] Archiving and clearing
- [ ] Colorful output
- [ ] Unit tests

## Contributing

Contributions are welcome! Please open issues or submit pull requests for new features, bug fixes, or improvements.

## License

This project is licensed under the MIT License. See LICENSE for details.
