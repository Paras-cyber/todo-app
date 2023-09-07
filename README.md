# MERN | Redux Todo App

This is a MERN (MongoDB, Express.js, React, Node.js) web application that serves as a todo list manager. It allows users to organize tasks into different categories(doing , done).

## Live Demo

Check out the live version of this project [here](https://todo-app-16k.pages.dev/).

## Front-end Requirements

### 1. Homepage
The homepage displays all tasks, categorized by their status groups: To Do, Doing, and Done.

### 2. Task Card
Each task is represented by a card that showcases the task's title and description.

### 3. Add Task
Users can create a new task by using a form that prompts them for the title and description of the task.

### 4. Edit Task
The app provides an option to edit an existing task's title and description.

### 5. Delete Task
Users can delete a task permanently, removing it from the list.

### 6. Task Status
To enhance user experience, the app allows users to easily drag and drop tasks between the To Do, Doing, and Done categories to update their statuses.

## Back-end Requirements

### 1. API Endpoints
The backend of this application includes API endpoints that support CRUD (Create, Read, Update, Delete) operations for tasks. The API provides the necessary functionality to interact with tasks.

### 2. Database Storage
Tasks are stored in a database, ensuring data persistence and allowing users to retrieve their tasks across different sessions.

## Usage

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Paras-cyber/todo-app.git
   cd todo-app
   ```

2. Install dependencies for both the client and server:

   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. Set up your MongoDB database and configure the connection in the server's `.env` file.

4. Start the server and client:

   ```bash
   # Start the server
   cd ../server
   npm start

   # Start the client
   cd ../client
   npm start
   ```

Now, you can access the application in your web browser at `http://localhost:3000`. Enjoy managing your tasks!

## Technologies Used

- MongoDB: Database storage for tasks.
- Express.js: Backend framework for API development.
- React: Front-end library for building the user interface.
- Node.js: JavaScript runtime for the server.
- Redux: State management for the React application.

Feel free to customize and enhance this project to meet your specific requirements. Happy coding!
