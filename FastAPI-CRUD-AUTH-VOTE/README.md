
# FastAPI REST API Backend

## Overview
This project is a backend application built using FastAPI, which provides user authentication, post creation, voting system, and CRUD operations for managing posts. It utilizes PostgreSQL as the database backend and SQLAlchemy as the ORM for database operations. The application exposes RESTful endpoints for various functionalities, supporting GET, POST, DELETE, and UPDATE methods.

## Features
- User Authentication: Users can register, login, and authenticate using JWT tokens.
- Post Management: Users can create, read, update, and delete posts.
- Voting System: Users can vote on posts.
- CRUD Operations: Full CRUD operations are supported for managing posts.

## Technologies Used
- FastAPI: A modern web framework for building APIs with Python.
- PostgreSQL: An open-source relational database management system.
- SQLAlchemy: An SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- JWT: JSON Web Tokens for user authentication.


## Usage
1. Clone the repository: `git clone https://github.com/k25harikesh/FastAPI-CRUD-AUTH-VOTE.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Configure environment variables for database connection.
4. Run the FastAPI application: `uvicorn app.main:app --reload`
5. Access the API at `http://localhost:8000`.

## API Documentation
Detailed API documentation and usage examples can be found in the [API documentation](API_DOCS.md) || (coming soon)

## License
This project is licensed under the MIT License

## Acknowledgments
- FastAPI Documentation: https://fastapi.tiangolo.com/
- SQLAlchemy Documentation: https://docs.sqlalchemy.org/
- PostgreSQL Documentation: https://www.postgresql.org/docs/
