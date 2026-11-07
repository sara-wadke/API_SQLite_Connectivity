Practical 8 – API SQLite Connectivity

Description

This practical demonstrates how to connect a FastAPI application with an SQLite database. It manages student records using CRUD operations (Create, Read, Update and Delete).

Project Files

create_db.py – Creates the database and students table.

main.py – Contains the FastAPI application and API endpoints.

students.db – Stores student records.

Execution

Create database:

python3 create_db.py

Run the application:

python3 -m uvicorn main:app --reload

Open API documentation:

http://127.0.0.1:8000/docs

API Operations

POST – Add student

GET – View students

PUT – Update student

DELETE – Delete student

Outcome

Successfully created a FastAPI application connected to SQLite for managing student records.
