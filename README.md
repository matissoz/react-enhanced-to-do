# Enhanced To-Do App with React, JSON-Server, and React Router

## Overview

This version of the to-do application expands upon the basic version by introducing React Router for navigation and JSON-Server for simulating a backend. This allows for a more comprehensive development experience, including the ability to view task details on separate pages.

## Application Features

- **List View:** Display all tasks in a list, offering an overview and easy access to edit, delete, or mark tasks as completed directly from the list.
- **Full Task View:** Open tasks in a new page to view details, enhancing user experience.
- **Add Task:** Users can create tasks with titles and content.
- **Edit Task:** Existing tasks can be edited.
- **Delete Task:** Unwanted tasks can be removed.
- **Mark as Completed:** Tasks can be marked off as completed.
- **Add Commentary:** Allows for adding comments to tasks.
- **Edit Commentary:** Comments can be edited.
- **Delete Commentary:** Comments can be deleted.

## Technical Requirements

- **Use Components:** Structure the application using React components to ensure code modularity, reusability, and maintainability.
- **JSON-Server:** Simulates a backend to work with real data without backend development.
- **React Router:** Manages navigation within the app, enabling page transitions without reloading.

## Getting Started

### Step 1: Project Setup

Create a new project with Vite, specifying React and TypeScript:

```bash
npm create vite@latest
```
- Project name: `to-do app`
- Select a framework: `React`
- Select a variant: `TypeScript`

### Step 2: Navigate to Your Project

Change into your project directory:

```bash
cd "to-do app"
```

### Step 3: Install Dependencies

Install necessary dependencies, including React Router and JSON-Server:

```bash
npm install react-router-dom json-server
```

### Step 4: Set Up JSON-Server

1. Create a `db.json` file in the root directory with your initial data.
2. Add a JSON-Server start script to `package.json`:

```json
"scripts": {
  "server": "json-server --watch db.json --port 3004"
}
```

### Step 5: Running Your Project

1. Start the development server:

```bash
npm run dev
```

2. In a separate terminal, start JSON-Server:

```bash
npm run server
```
