# ToDo List

The ToDo List project is a web application built using Django, a Python web framework. This app allows users to sign up, log in, and create their own personalized to-do lists. Each user has their own individual to-do list, which they can manage by adding, editing, and completing tasks. The app utilizes Django's default SQLite3 database for backend storage.

## Features

- User Sign Up: Register a new account to create a personalized to-do list.
- User Login: Log in to access your own to-do list.
- Create Task: Add new tasks to your to-do list.
- Edit Task: Modify the details of existing tasks.
- Complete Task: Mark tasks as completed once they are finished.
- Delete Task: Remove tasks from your to-do list.

## Technologies Used

The following technologies and frameworks were used in the development of this app:

- Django: A high-level Python web framework that enables rapid development and clean design.
- Python: The programming language used for writing the backend logic and handling database operations.
- HTML/CSS: The standard markup language and styling technology used for structuring and presenting the app's content.
- SQLite3: The default database included with Django, used for storing user information and to-do lists.

## Installation

To set up the ToDo List app locally, follow these steps:

1. Clone the repository from GitHub.
2. Open a terminal or command prompt and navigate to the project's root directory.
3. Create a virtual environment for the project by running the following command:
### `python -m venv myenv`

4. Activate the virtual environment:

- On Windows:

  ```
  myenv\Scripts\activate
  ```

- On macOS and Linux:

  ```
  source myenv/bin/activate
  ```

5. Install the project dependencies by running the following command:
### `pip install -r requirements.txt`


6. Apply the database migrations by running the following command:
### `python manage.py migrate`

7. Start the development server with the following command:
###  `python manage.py runserver`

8. Open your web browser and navigate to `http://localhost:8000` to access the app.

Note: Ensure that you have Python and pip (Python package manager) installed on your machine before running the above commands.

## Contributing

If you'd like to contribute to this project, you can follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them with descriptive commit messages.
5. Push your changes to your forked repository on GitHub.
6. Submit a pull request to the main repository, explaining your changes and their benefits.

Please ensure that your contributions adhere to the project's coding standards and follow best practices.

## Contact

If you have any questions, suggestions, or feedback regarding this project, please feel free to reach out to me at [samlamba29@gmail.com].

Thank you for using the ToDo List app!



