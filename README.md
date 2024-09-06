# Student Management API

This is a simple Django REST API for managing student records. It supports creating, retrieving, updating, and deleting student records using Django REST Framework (DRF) and ViewSets.

## Features
- **List Students**: Retrieve a list of all students.
- **Retrieve a Student**: Get details of a single student by ID.
- **Create a Student**: Add a new student record.
- **Update a Student**: Update an existing student record.
- **Partial Update a Student**: Partially update an existing student record.
- **Delete a Student**: Remove a student record by ID.

## API Endpoints

### 1. List Students
- **URL**: `/students/`
- **Method**: `GET`
- **Response**: Returns a list of all students in JSON format.

### 2. Retrieve a Student
- **URL**: `/students/<id>/`
- **Method**: `GET`
- **Response**: Returns the details of a specific student.

### 3. Create a Student
- **URL**: `/students/`
- **Method**: `POST`
- **Request Body**: JSON data with student details.
- **Response**: Success message with status code `201` on successful creation.

### 4. Update a Student
- **URL**: `/students/<id>/`
- **Method**: `PUT`
- **Request Body**: JSON data with updated student details.
- **Response**: Success message with status code `200` on successful update.

### 5. Partial Update a Student
- **URL**: `/students/<id>/`
- **Method**: `PATCH`
- **Request Body**: Partial JSON data to update student details.
- **Response**: Success message with status code `200` on partial update.

### 6. Delete a Student
- **URL**: `/students/<id>/`
- **Method**: `DELETE`
- **Response**: Success message with status code `204` on successful deletion.

## Installation & Setup

### Prerequisites
- Python 3.x
- Django 3.x or 4.x
- Django REST Framework

