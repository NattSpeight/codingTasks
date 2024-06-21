# Sticky Note and Bulletin Board Application

## Description
This project is a Django application that allows users to create, view, edit, and delete sticky notes and bulletin board posts. It was developed as a final project during my bootcamp to demonstrate understanding of Django and web development concepts.

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Testing](#testing)
6. [Contributing](#contributing)
7. [License](#license)

## Overview
The application consists of two main functionalities:
- **Sticky Notes:** Users can create, view, edit, and delete personal notes.
- **Bulletin Board Posts:** Users can create, view, edit, and delete posts on a public bulletin board.

### Coding Task Name
Django Sticky Notes Application Part 1&2

### Short Description of the Coding Task
As part of my bootcamp's practical tasks, I developed a Sticky Note and Bulletin Board application using Django. The project required creating, viewing, editing, and deleting notes and posts. I refactored and extended the application, implemented and ran tests to ensure functionality, and documented the entire process. The project emphasized the importance of understanding web development fundamentals, such as handling user input, working with databases, and creating intuitive user interfaces.

## Installation

### Prerequisites
- Python 3.12
- Django 5.0.6
- Virtual environment tool (optional but recommended)

### Steps
1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/your-repository-name.git
    cd your-repository-name
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

6. **Access the application:**

    Open your web browser and go to `http://127.0.0.1:8000/`

## Usage

### Creating Notes
- Navigate to the Sticky Notes section.
- Click "Create a new note".
- Fill out the form and submit.

### Creating Posts
- Navigate to the Bulletin Board section.
- Click "Create a new post".
- Fill out the form and submit.

### Editing and Deleting
- Both notes and posts can be edited or deleted using the respective buttons next to each item.

## Features
- **Sticky Notes Management:** Create, view, edit, and delete sticky notes.
- **Bulletin Board Posts:** Create, view, edit, and delete bulletin board posts.
- **User-Friendly Interface:** Easy navigation and intuitive UI.

## Testing

### Running Tests

To run the tests, use the following command:

```bash
python manage.py test notes
```

### Test Coverage

The tests cover:
- Model validation
- View responses
- URL routing
- Form handling

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


