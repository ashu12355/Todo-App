# To-Do App

A simple and intuitive to-do list application built using **HTML**, **CSS**, and **JavaScript**. This app allows users to add, mark, and delete tasks while ensuring that tasks are saved in the browser's local storage for persistence across page reloads.

## Features

- **Add Tasks:** Enter tasks in the input box and click the "Add" button to add them to the list.
- **Mark Tasks as Complete:** Click on a task to toggle its "completed" status, visually indicated by a strikethrough.
- **Delete Tasks:** Click the "×" button next to a task to remove it from the list.
- **Persistent Storage:** Tasks are saved in local storage, ensuring they remain available even after refreshing the page.

## How It Works

1. **Adding Tasks:**
   - Enter text in the input box and press the "Enter" key or click the "Add" button.
   - Tasks are appended to the list and stored in local storage.

2. **Marking Tasks as Completed:**
   - Click on any task to toggle a "checked" class that applies a strikethrough.

3. **Deleting Tasks:**
   - Click on the "×" icon next to a task to remove it from the list and update local storage.

4. **Local Storage:**
   - All tasks are saved in the browser's local storage using `localStorage.setItem`.
   - On page load, tasks are retrieved from local storage using `localStorage.getItem`.

## Technologies Used

- **HTML:** For structuring the app.
- **CSS:** For styling the to-do list and its components.
- **JavaScript:** For app functionality, including task management and local storage handling.

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd todo-app
   ```
3. Open `index.html` in your web browser.

### Usage

1. Type a task in the input box.
2. Click "Add" or press `Enter` to add the task to the list.
3. Click on a task to mark it as completed.
4. Click the "×" button to delete a task.

## Future Improvements

- Add a clear-all button to delete all tasks.
- Enable due dates for tasks.
- Implement category tags for better organization.
- Add drag-and-drop functionality to reorder tasks.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Developed by [Ashutosh Sharma](https://github.com/ashu12355).
