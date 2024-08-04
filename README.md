# Task Management App
This repository contains a simple yet functional task management application built with React. The application allows users to add, edit, delete, and search for tasks. Tasks are displayed as sticky notes and are fetched from a dummy JSON file. The UI is responsive and adapts to various screen sizes.

# Overview of the System Design

The application is divided into several key components:
• App Component: The main component that orchestrates the application, handling state management and routing.

• CustomForm Component: A form component used to add new tasks.

• EditForm Component: A form component used to edit existing tasks.

• TaskList Component: A component that displays the list of tasks.

• TaskItem Component: A component that represents an individual task.

• SearchBox Component: A component that provides search functionality.

• Dummy JSON File: A static file (tasks.json) that serves as the data source for tasks.

Implementation

# State Management

State management is handled using the useState and useEffect hooks. The useLocalStorage custom hook is used to persist tasks in the local storage of the browser.

# Task Operations

• Add Task: The CustomForm component allows users to add new tasks. The new task is appended to the current state of tasks.

• Edit Task: The EditForm component allows users to edit existing tasks. The edited task is updated in the current state of tasks.

• Delete Task: Each task can be deleted, which removes it from the current state of tasks.

• Toggle Task: Each task has a checkbox to mark it as completed or not, which toggles the checked state of the task.

• Search Task: The SearchBox component allows users to search for tasks by name. The search query is reflected in the URL parameters for easy navigation.

# Task Display

Tasks are displayed as sticky notes using CSS. When a task is clicked, it opens in a popup for a detailed view.

Instructions to Set Up and Run the Application

# Prerequisites
Node.js and npm should be installed on your machine.

# Setup

1. Clone the Repository:
```sh
git clone https://github.com/your-username/task-management-app.git
cd task-management-app
```
2. Install Dependencies:
```console
npm install
```
3. Start the Application:
```console
npm start
```
