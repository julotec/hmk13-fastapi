# REST API for Storing and Managing Contacts

This repository contains the source code for a REST API application that allows storing and managing contacts. The API is built using FastAPI framework and utilizes SQLAlchemy for interaction with a PostgreSQL database.

## Features

- **Create a new contact:** Add new contacts to the database with basic information such as first name, last name, email address, phone number, date of birth, and additional data (optional).
- **Get a list of all contacts:** Returns a list of all contacts stored in the database.
- **Get contact by ID:** Retrieves detailed information about a contact based on its identifier.
- **Update an existing contact:** Updates an existing contact based on the provided ID.
- **Delete a contact:** Removes a contact from the database based on its identifier.
- **Search contacts:** Allows searching for contacts by first name, last name, or email address.
- **Get contacts with upcoming birthdays:** Returns a list of contacts whose birthday falls within the next 7 days.

## Technologies

- **FastAPI:** We use FastAPI for fast and efficient API development.
- **SQLAlchemy ORM:** SQLAlchemy ORM is used for managing the PostgreSQL database.
- **PostgreSQL:** We chose PostgreSQL as the database due to its reliability and performance.
- **Pydantic:** Pydantic data validation module is used to validate input data.

## Requirements

- Python 3.7 or newer
- FastAPI
- SQLAlchemy
- PostgreSQL

## Documentation

API documentation is available after running the application at `http://localhost:8000/docs`.

## Getting Started

1. Install all the required dependencies from the `requirements.txt` file.
2. Configure the connection to the PostgreSQL database in the `.env` file.
3. Run the application using the command `uvicorn main:app --reload`.






