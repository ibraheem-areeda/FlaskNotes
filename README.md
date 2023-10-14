# FlaskNotes

FlaskNotes is a simple note-taking web application built using the Flask framework. It allows users to create, edit, and organize their notes easily. Whether you need a quick place to jot down your thoughts or keep organized to-do lists, FlaskNotes has you covered.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create, edit, and delete notes.
- Organize notes into categories or tags.
- User authentication for secure access to your notes.
- Responsive design for use on various devices.
- A simple and intuitive user interface.

## Installation

To run FlaskNotes on your local machine, follow these steps:

1. Clone this repository to your local environment:

```bash
git clone git@github.com:ibraheem-areeda/FlaskNotes.git
```

2. Create a virtual environment (optional but recommended):

```macOS and Linux
python -m venv .venv
```

3. Activate the virtual environment:

On macOS and Linux:

```bash
source .venv/bin/activate
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Create a `.env` file in the root directory of the project to store your environment variables. You can copy the example `.env.example` file provided and update it with your own settings:

```plaintext
FLASK_APP=app
FLASK_ENV=development
SECRET_KEY=your_secret_key
DATABASE_URI=your_database_uri
```

6. Initialize the database:

```bash
flask db init
flask db migrate
flask db upgrade
```

7. Start the Flask application:

```bash
flask run
```

Your FlaskNotes application should now be accessible at `http://localhost:5000` in your web browser.

## Usage

1. Create a new account or log in if you already have one.
2. Start creating and managing your notes by adding, editing, and categorizing them.
3. Enjoy using FlaskNotes to keep your notes organized.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out if you have any questions or suggestions. Happy note-taking with FlaskNotes!


