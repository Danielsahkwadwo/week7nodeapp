# ToDo Application
================


A simple yet elegant ToDo application built with Node.js, Express, and EJS.


## Features
------------

* Create, read, update, and delete tasks
* Mark tasks as complete/incomplete
* Set priority levels for tasks
* Beautiful, responsive UI


## Project Structure
-------------------

```
todo-app/
├── controllers/
│   └── todoController.js
├── models/
│   └── todoModel.js
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
├── routes/
│   └── todoRoutes.js
├── views/
│   └── index.ejs
└── app.js
```


## Getting Started
---------------

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the application: `npm start`
4. Open your web browser and navigate to `http://localhost:3000`


## API Endpoints
----------------

### GET /todos

* Retrieve all tasks

### GET /todos/:id

* Retrieve a single task by ID

### POST /todos

* Create a new task

### PUT /todos/:id

* Update a task

### DELETE /todos/:id

* Delete a task

# week7nodeapp
