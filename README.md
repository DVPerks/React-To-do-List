
# React To-do List

**[Live Demo](https://dvperks.github.io/portfolio/project-viewer.html?project=1)** | **[Developer Portfolio](https://dvperks.github.io/portfolio/)**

A responsive task management application built with React and Vite. The application demonstrates component-based development, React Hooks, state management, persistent browser storage, and accessible user interactions.

## Features

- Create, edit, complete, and delete tasks.
- Filter tasks by all, active, or completed status.
- Dynamically update the interface as task state changes.
- Persist tasks using local storage.
- Support keyboard-accessible interactions.
- Provide a responsive user interface.

## Built With

- React
- React Hooks
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite
- ESLint
- Nano ID

## Technical Highlights

### Component-Based Development

The application separates responsibilities into reusable components, including task creation, filtering, and individual task interactions.

### State Management

React Hooks manage application state and update the interface in response to user interactions. Task creation, editing, completion, deletion, and filtering are handled through state-driven rendering.

### Persistent Storage

Local storage preserves task information between browser sessions without requiring a backend or database.

### Accessibility

The interface incorporates semantic HTML, descriptive form controls, and keyboard-accessible interactions.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/DVPerks/todo-react.git
cd todo-react
```

Install dependencies and start the development server:

```bash
npm install
npm run dev
```

Open the URL displayed in the terminal.

## Development Commands

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Generate a production build |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint checks |

## Project Structure

```text
├── public/             # Public assets
├── src/                # React components and application source
├── index.html          # Application entry point
├── package.json        # Dependencies and development scripts
├── vite.config.js      # Vite configuration
├── eslint.config.js    # ESLint configuration
└── README.md           # Project documentation
```

## Development Focus

This project demonstrates practical React development through reusable components, declarative rendering, state management, persistent data, and interactive UI behavior.

## Author

Drake Perkins — Frontend Software Engineer

- [Developer Portfolio](https://dvperks.github.io/portfolio/)
- [GitHub](https://github.com/DVPerks)
- [LinkedIn](https://www.linkedin.com/in/drake-p-0a9472398/)
