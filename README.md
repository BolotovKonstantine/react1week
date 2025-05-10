# Todo List Application

A simple, elegant Todo List application built with React and Vite. This application allows users to create, manage, and track their tasks with a clean and intuitive interface.

## Features

- Add new todo items
- Mark todos as complete/incomplete
- Delete todos
- Persistent storage using localStorage
- Responsive design with a dark theme
- Clean and intuitive user interface

## Demo

![Todo List App Screenshot](https://via.placeholder.com/400x300?text=Todo+List+App)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/react1week.git
   cd react1week
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

1. **Adding a Todo**: Enter a task in the input field and click "Add" or press Enter.
2. **Completing a Todo**: Click the checkbox next to a todo to mark it as complete.
3. **Deleting a Todo**: Click the "Delete" button next to a todo to remove it from the list.

## Technologies Used

- **React 19**: For building the user interface
- **Vite**: For fast development and optimized builds
- **localStorage API**: For persisting todos between sessions
- **CSS**: For styling the application

## Project Structure

```
react1week/
├── public/
├── src/
│   ├── App.jsx            # Main application component
│   ├── NewTodoForm.jsx    # Form for adding new todos
│   ├── TodoItem.jsx       # Individual todo item component
│   ├── TodoList.jsx       # List of todo items
│   ├── main.jsx           # Application entry point
│   └── styles.css         # Application styles
├── index.html             # HTML template
├── package.json           # Project dependencies and scripts
└── README.md              # Project documentation
```

## Scripts

- `npm run dev`: Start the development server
- `npm run build`: Build the application for production
- `npm run lint`: Run ESLint to check for code issues
- `npm run preview`: Preview the production build locally

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
