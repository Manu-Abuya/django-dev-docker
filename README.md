# django-dev-docker

This repository contains a simple Todo application built with Django and Docker. The application allows users to manage their tasks by creating, updating, and deleting todo items.

## Prerequisites

Make sure you have the following software installed on your local machine:

- Python 3.x
- Django 3.x
- Docker

## Getting Started

To run the Todo app locally, follow these steps:

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/django-todo-app.git
   ```

2. Navigate to the project directory:
   ```
   cd django-todo-app
   ```

3. Build the Docker image:
   ```
   docker build -t todo-app:latest .
   ```

4. Run the Docker container:
   ```
   docker run -p 8000:8000 todo-app:latest
   ```

5. Open your web browser and visit `http://localhost:8000` to access the Todo app.

## Usage

- To create a new todo item, click on the "Add Task" button and enter the task details.
- To mark a task as completed, click on the checkbox next to the task.
- To edit a task, click on the "Edit" button and update the task details.
- To delete a task, click on the "Delete" button.

## Contributing

Contributions are welcome! If you would like to enhance the Todo app or fix any issues, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This Todo app was developed as a personal project for learning purposes.
- The project structure and Docker configuration were inspired by best practices in Django and Docker development.
