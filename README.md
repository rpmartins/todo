# Todo List App

A vanilla HTML/CSS/JavaScript todo list application with 5 switchable style themes and task owner management.

## Features

- **Add Tasks**: Create tasks with required owner assignment and optional due dates
- **Task Owners**: Assign tasks to specific owners (required field)
- **Complete Tasks**: Check off tasks when done with automatic completion timestamps
- **Delete Tasks**: Remove tasks you no longer need
- **Due Dates**: Assign due dates to tasks
- **Overdue Highlighting**: Tasks past their due date are highlighted in red
- **Chronological Sorting**: Tasks automatically sort by due date (earliest first)
- **Completion Timestamps**: See exactly when you completed each task
- **Autocomplete**: Smart task suggestions based on previously entered tasks
- **5 Style Themes**: Cycle through different visual styles
- **Admin Panel**: Secure admin interface to manage task owners

## Themes

1. **Modern Blue** - Clean purple-blue gradient
2. **Warm Sunset** - Pink and warm tones
3. **Minimal Dark** - Dark mode aesthetic
4. **Nature Green** - Soft green earth tones
5. **Neon Cyberpunk** - Black with cyan/magenta neon effects

## Usage

Simply open `index.html` in your web browser. No installation or build process required.

### Main App
- Type a task in the text field
- Select a due date (optional)
- **Select a task owner (required)**
- Click "Add" or press Enter
- Click checkboxes to mark tasks complete
- Click "Change Style" to cycle through themes
- Click "Delete" to remove tasks
- Use autocomplete suggestions for frequently used tasks

### Admin Panel
- Click "⚙️ Admin" in the top right corner
- Login with username: `admin`, password: `1234`
- Add or remove task owners
- Owners are automatically sorted alphabetically
- Default owners: April, Marina, Maxwell, Renato

## Technologies

- Pure HTML5
- CSS3 (with custom themes and transitions)
- Vanilla JavaScript (no frameworks or dependencies)
- LocalStorage for persistent owner data
- Session storage for admin authentication

## Files

- `index.html` - Main todo list application
- `admin.html` - Admin panel for managing task owners
- `README.md` - This file
