# React To-Do List

A highly interactive and responsive To-Do List component built with React. This application allows users to add, remove, and mark tasks as completed. It includes input validation, dynamic task display, optional sorting and filtering, and integrates with localStorage to persist tasks across sessions.

## Features

- **Add Tasks**: Users can add new tasks to the list.
- **Remove Tasks**: Users can remove tasks from the list.
- **Mark Tasks as Completed**: Users can mark tasks as completed or undo the completion.
- **Input Validation**: Ensures tasks are not added with empty text.
- **Dynamic Task Display**: Tasks are displayed dynamically as they are added or removed.
- **Sorting and Filtering**: Option to filter tasks based on their completion status.
- **localStorage Integration**: Tasks persist across sessions using localStorage.


## Usage

1. **Add a task**: Enter a task in the input field and click "Add Task".
2. **Remove a task**: Click the "Remove" button next to a task.
3. **Mark a task as completed**: Click the "Complete" button next to a task.
4. **Filter tasks**: Use the filter buttons to view all, completed, or incomplete tasks.



### Components

- **ToDo**: The main component managing the state and rendering the to-do list.

### State Management

- **useState**: Manages tasks, input value, and filter state.
- **useEffect**: Syncs tasks with localStorage.

## Styling

The application uses CSS for styling. You can find the styles in the `App.css` file. The styling includes responsive design and animations for a better user experience.

## Testing

To test the application:

1. **Check task addition**: Add a new task and verify it appears in the list.
2. **Check task removal**: Remove a task and verify it is removed from the list.
3. **Check task completion**: Mark a task as completed and verify it is marked correctly.
4. **Check input validation**: Try adding an empty task and verify it is not added.
5. **Check localStorage**: Refresh the page and verify tasks persist.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by various React to-do list tutorials and examples.

