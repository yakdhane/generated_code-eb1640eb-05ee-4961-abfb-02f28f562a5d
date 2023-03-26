Here's a sample README.md file:

# Todo App

A simple todo app built with React.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Docker](#docker)
- [Files](#files)

## Installation

To install the dependencies, run the following command:

```
npm install
```

## Usage

To start the app, run the following command:

```
npm start
```

This will start the app on [http://localhost:3000](http://localhost:3000).

## Docker

To run the app using Docker, first build the Docker image:

```
docker build -t todo-app .
```

Then, run the Docker container:

```
docker run -p 3000:3000 todo-app
```

This will start the app on [http://localhost:3000](http://localhost:3000).

## Files

- `App.js`: The main component of the app.
- `TodoList.js`: A component that renders the list of todos.
- `TodoItem.js`: A component that renders a single todo item.
- `index.js`: The entry point of the app.
- `package.json`: The npm package file that lists the dependencies of the app.
- `Dockerfile`: A Dockerfile that builds a Docker image for the app.