# Todo List App with Flask and SQLAlchemy

## Description

The Todo List app is a web application built using Flask, a Python web framework, and SQLAlchemy, a SQL toolkit and Object-Relational Mapping (ORM) library. The app allows users to manage and organize their tasks by adding, updating, marking as complete, and deleting tasks.

## Features

- User Authentication: Users can create accounts and log in to manage their tasks.
- Create Task: Users can add new tasks with titles and descriptions.
- Update Task: Users can edit task details and mark tasks as complete.
- Delete Task: Users can remove tasks from their list.
- Persistent Storage: Tasks are stored in a relational database using SQLAlchemy.

## Technologies Used

- Python
- Flask
- SQLAlchemy
- HTML
- CSS
- JavaScript (for front-end enhancements)

## Installation

1. Clone this repository: `git clone https://github.com/your-username/todo-list-flask.git`
2. Navigate to the project directory: `cd todo-list-flask`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Set up the database:
   - Rename `config_example.py` to `config.py` and configure your database URL.
   - Run the database migration commands: `flask db init`, `flask db migrate`, `flask db upgrade`
5. Start the application: `flask run`

## Usage

1. Access the app in your web browser: `http://localhost:5000`
2. Register a new account or log in with an existing one.
3. Use the user interface to add, update, complete, and delete tasks.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit them: `git commit -m "Add new feature"`
4. Push to your forked repository: `git push origin feature/new-feature`
5. Create a pull request to the main repository's `master` branch.

## Credits

This app was developed as a learning project and is inspired by the need for a simple and effective task management tool.

---

Stay organized and manage your tasks effectively with the Todo List app built using Flask and SQLAlchemy.
