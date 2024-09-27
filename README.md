# Django ToDo App

A simple ToDo application built with Django that allows multiple users to sign up, log in, add, update, and delete tasks.

## Features

- User authentication (sign up, log in, log out)
- Add new tasks
- Update existing tasks
- Delete tasks
- View all tasks

## Installation

1. **Clone the repository:**

    ```bash
    git clone [https://github.com/Anilnayak126/TO-DO-App.git]
    cd todo-app
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

7. **Access the app:**

    Open your browser and go to `http://127.0.0.1:8000/`

## Usage

- **Sign Up:** Create a new account.
- **Log In:** Log in with your credentials.
- **Log Out:** Log out.
- **Add Task:** Add a new task using the form.
- **Update Task:** Click on a task to update its details.
- **Delete Task:** Click the delete button to remove a task.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Django documentation
- Stack Overflow community
