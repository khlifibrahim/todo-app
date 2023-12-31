## Screenshots

![Screenshot of the Task Manager](screenShot.png)
# JavaScript Task Manager

This JavaScript project is a simple task manager that allows you to add, complete, and filter tasks. It also features a dark mode toggle.

## Features

- Add tasks with a description.
- Mark tasks as completed.
- Filter tasks by All, Active, and Completed.
- Toggle between light and dark mode.

## Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

## Code Overview

- `bodyBg`, `darkModeIcon`, `taskValue`, `addTask`, and other variables are used to select elements from the HTML document for interaction.
- Event listeners are set up to handle user interactions, such as adding tasks, toggling dark mode, and filtering tasks.
- The `createTask` function adds a new task to the list when the "Add" button is clicked.
- The `deletefinish` function handles task completion and deletion when the checkmark or cross icon is clicked.
- The `counter` function updates the task counter and enables drag-and-drop functionality for tasks.
- The `menu` function filters tasks based on the selected menu option.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
