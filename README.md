# Todo List Application

This is a simple todo list application built using React.  
It allows users to add new todos, mark todos as completed, and delete todos.  
Todos are stored locally using browser's localStorage API, so they persist even after the page is refreshed.

## Features

- Add new todos: Users can add new todos by entering a title and submitting the form.
- Mark todos as completed: Users can mark todos as completed by clicking on the checkbox next to each todo.
- Delete todos: Users can delete todos by clicking on the delete button next to each todo.
- Local Storage: Todos are stored in the browser's local storage, so they persist even after the browser is refreshed.

## Technologies Used

- React: The application is built using the React library.
- useState Hook: Used to manage state in functional components.
- useEffect Hook: Used to perform side effects, such as saving todos to local storage.
- CSS: Styles are applied using CSS.
- `localStorage` API (for storing todos locally).

## Project Structure

- `App.jsx`: Main component managing the state of todos and rendering the todo list.
- `NewTodoForm.jsx`: Component for adding new todos.
- `TodoList.jsx`: Component for rendering the list of todos.
   
Source: https://www.youtube.com/watch?v=Rh3tobg7hEo