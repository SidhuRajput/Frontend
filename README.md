# Todo List
GitHub Desktop tutorial repository
Todo list 
Explanation:
.The HTML structure consists of a container div that holds a heading, an input field to add tasks, an "Add Task" button, and an unordered list (<ul>) to display 
 the tasks.
.The CSS styles the elements to create a visually pleasing layout for the Todo list.
.In the JavaScript code, we start by getting references to the necessary DOM elements using getElementById.
.We add an event listener to the "Add Task" button using addEventListener. The callback function addTask is executed when the button is clicked.
.Inside the addTask function, we retrieve the task description from the input field and create a new list item (<li>).
.We set the HTML content of the list item with the task description and a "Delete" button.
.The list item is then appended to the task list (<ul>).
.After adding the task, we clear the input field by setting its value to an empty string.
.We also add an event listener to the "Delete" button inside the addTask function. The callback function deleteTask is executed when the button is clicked.
.In the deleteTask function, we retrieve the parent list item of the clicked "Delete" button using closest.
.We remove the list item from the task list using removeChild.
.This is a basic implementation of a Todo list using vanilla JavaScript. You can enhance it further by adding features like task editing, task completion, and 
storing tasks in local storage to persist data. Additionally, you can explore using frameworks like React or Vue.js to build more complex and interactive Todo 
list applications.
![Todo list](https://github.com/SidhuRajput/Frontend/assets/113462130/07805934-ef31-4eee-b626-f29d6106ae46)

