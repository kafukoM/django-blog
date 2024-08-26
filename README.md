# Blog App

## Overview
This is a simple blog application built using Django. The app allows users to create, read, update, and delete blog posts. The project is structured to accommodate additional apps in the future.

## Features
- Create, edit, and delete blog posts
- List all blog posts
- View individual blog posts

## Project Structure
- **mysite2/**: The main project folder containing settings, URLs, and configurations.
- **blog/**: The Django app responsible for the blog functionality.

## Prerequisites
Before running the app, ensure you have the following installed:
- Python 3.x
- Django 4.x (or your specific version)
- Git
- Pip (Python package installer)
- Virtualenv (optional but recommended)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Create and Activate a Virtual Environment (Optional but Recommended)**
   ```python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies**
   ```pip install -r requirements.txt```
5. **Set Up the Database Run the following commands to set up the database:**
   ```python manage.py migrate```
7. **Create a Superuser Create an admin account to access the Django admin interface:**
   ```python manage.py createsuperuser```
9. **Run the Development Server Start the Django development server:**
    ```python manage.py runserver```
11. **Access the Application Open your browser and go to:**
    ```http://127.0.0.1:8000/```

