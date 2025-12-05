# Todo App

A modern, feature-rich Todo Application built with React and Vite. This application allows users to manage their tasks efficiently with a clean and responsive user interface. It includes authentication, dark/light mode support, and detailed task views.

## Features

- **User Authentication**: Secure Login and Registration pages.
- **Task Management**:
  - View all todos.
  - View detailed information for specific todos.
  - Manage tasks effectively.
- **Dark/Light Mode**: Toggle between dark and light themes for better accessibility and user preference.
- **Responsive Design**: Optimized for various screen sizes.
- **Protected Routes**: Ensures that only authenticated users can access the main application features.
- **Routing**: Seamless navigation using React Router v6.

## Tech Stack

- **Frontend Framework**: [React](https://reactjs.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Routing**: [React Router DOM](https://reactrouter.com/)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **Utilities**:
  - `uuid` for generating unique IDs.
  - `react-spinners` for loading states.
- **Styling**: CSS Modules / Vanilla CSS.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Ensure you have Node.js installed on your system.

### Installation

1. **Clone the repository** (if applicable) or navigate to the project directory.

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser**:
   Navigate to `http://localhost:5173` (or the port shown in your terminal).

## Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run lint`: Runs ESLint to check for code quality issues.
- `npm run preview`: Locally preview the production build.

## Project Structure

```
src/
├── assets/         # Static assets
├── components/     # Reusable UI components (Login, Register, Layouts)
├── context/        # Context providers (e.g., ModeContext for theming)
├── hooks/          # Custom React hooks
├── pages/          # Page components (Home, About, Alltodos, TodoDetail)
├── App.jsx         # Main application component with routing
└── main.jsx        # Entry point
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
