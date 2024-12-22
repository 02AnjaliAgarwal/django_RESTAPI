# Django REST Framework Project

Build powerful REST API endpoints using Django REST Framework (DRF)!

## Endpoint Structure:

- /students: Handles actions on the collection (e.g., retrieving all students or adding a new student).
- /students/<id>: Handles actions on individual resources (e.g., retrieving, updating, or deleting a specific student).

## Workflow:

- GET /students: Fetches the list of all students.
- GET /students/22: Fetches details of the student with specified id.
- POST /students: Adds a new student.
- PUT /students/<id>: Updates the student with specified id.
- DELETE /students/<id>: Deletes the student with specified id.


## Features
Function-Based Views, Class-Based Views, Mixins, Generics, and Viewsets.
