# To-Do List App

### [Live Demo](https://xtlawrence.github.io/To-Do-App/)

A simple and responsive to-do list application where users can add tasks, mark them as completed, and delete them. The tasks are saved in `localStorage`, so the list persists even after refreshing the page.

## Features

- Add new tasks by typing in the input field and pressing the "Add" button.
- Mark tasks as completed by clicking on the task item. Completed tasks are shown with a strikethrough.
- Remove tasks by clicking the "×" button next to each task.
- Tasks are saved in `localStorage`, ensuring that the list persists across browser sessions.
- Mobile responsive design for a smooth experience on all screen sizes.

## Technologies Used

- **HTML5**: Structure of the application.
- **CSS3**: Styling, including media queries for mobile responsiveness.
- **JavaScript**: Functionality for adding, removing, marking tasks, and persisting data using `localStorage`.
- **LocalStorage**: Used to save tasks persistently in the browser.

## How to Use

1. Clone the repository or download the project files:
    ```bash
    git clone https://github.com/XTLawrence/todo-app.git
    ```
2. Open `index.html` in your browser.

### Adding a Task
- Type the task you want to add in the input field.
- Click on the "Add" button or press Enter.
- The task will appear in the list below the input field.

### Marking a Task as Complete
- Click on a task item to mark it as completed. Completed tasks will be shown with a strikethrough.

### Deleting a Task
- Click on the "×" button next to a task to remove it from the list.

### Saving Tasks
- The app automatically saves the tasks in `localStorage` and retrieves them when the page is reloaded.

## Responsive Design

- The app is fully responsive and works well on both desktop and mobile devices. The layout adjusts based on the screen width, providing a smooth experience on all screen sizes.

### Desktop View
- Full-width layout with centered content.
- Input field and task list styled for easy interaction.

### Mobile View
- Optimized for small screens.
- Input field and task list are stacked vertically for better user experience.

## Browser Compatibility

This project has been tested in the following browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge

## Future Improvements

- Add due dates and reminders for tasks.
- Categorize tasks by priority or tags.
- Implement drag-and-drop functionality for reordering tasks.
- Add task editing functionality.

## License

This project is licensed under the MIT License. Feel free to fork and modify the code as needed.

