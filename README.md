# FridgeHelper - Fridge Management Application

FridgeHelper is a web-based application designed to help users manage and track items in their refrigerator, including multiple fridge units. This project is built using Django, a powerful Python-based web framework.

## Features

- **User Authentication:** Secure user registration, login, and logout.
- **Fridge Management:** Users can add and manage multiple fridges.
- **Item Management:** Add, update, and view items in different fridges.
- **User-Friendly Interface:** Simple and intuitive interface with templates for ease of use.

## Project Structure

- `FridgeManagerProject/`: The main Django project directory.
- `FridgeManager/`: Contains the core app with models, views, and templates for fridge and item management.
- `templates/`: Contains the HTML templates used for rendering the web pages.
- `static/`: Holds static assets like CSS files for styling the web pages.
- `db.sqlite3`: SQLite database file for storing user, fridge, and item information.

## Key Files

- `manage.py`: Django’s command-line utility to manage the project.
- `settings.py`: Configuration settings for the Django project.
- `urls.py`: URL routing for the project.
- `models.py`: Defines the database models for users, fridges, and items.
- `views.py`: Contains the logic for handling requests and rendering templates.

## Prerequisites

- Python 3.x
- Django (version used in this project: 3.x)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/fridgehelper.git
    cd fridgehelper
    ```

2. **Install dependencies:**
    Make sure you have Python and Django installed.
    ```bash
    pip install -r requirements.txt
    ```

3. **Run database migrations:**
    ```bash
    python manage.py migrate
    ```

4. **Run the server:**
    ```bash
    python manage.py runserver
    ```

5. **Access the application:**
    Open your browser and go to `http://127.0.0.1:8000/` to access the FridgeHelper application.

## Usage

- **User Registration and Login:** Create an account or log in to manage your fridges.
- **Add a Fridge:** Click the "Add Fridge" button and fill out the details to register a new fridge.
- **Manage Items:** Once the fridge is added, you can view, add, or remove items from it.

## Project Development

This project is built using the following technologies:
- **Django**: For the web framework and backend logic.
- **SQLite**: As the database for storing user, fridge, and item data.
- **HTML/CSS**: For the front-end templates.
