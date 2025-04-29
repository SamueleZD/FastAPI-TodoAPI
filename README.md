FastAPI Todo App
================

A simple Todo web application built with FastAPI and SQLAlchemy
This project demonstrates how to build a modern web backend with API routes and user authentication.

-------------------------
Features
-------------------------

- User registration and login
- Create, read, update, and delete todos
- Secure password hashing
- SQLAlchemy ORM for database models
- Tests with pytest
- Alembic for database migrations

-------------------------
Tech Stack
-------------------------

- FastAPI
- SQLAlchemy
- Alembic
- SQLite
- Uvicorn

-------------------------
Installation
-------------------------

1. Clone the repository:

   git clone https://github.com/SamueleZD/Todo-FastAPI.git
   cd Todo-FastAPI

2. Create and activate a virtual environment:

   python -m venv venv
   On Linux/macOS: source venv/bin/activate
   On Windows: venv\Scripts\activate

3. Install dependencies:

   pip install -r requirements.txt

4. Run the app:

   uvicorn main:app --reload

   The app will be available at: http://127.0.0.1:8000

   
-------------------------
Running Tests
-------------------------

pytest

-------------------------
License
-------------------------

This project is licensed under the MIT License. See the LICENSE file for details.
