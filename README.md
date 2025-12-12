<img width="1365" height="716" alt="CO2" src="https://github.com/user-attachments/assets/c6b602ec-7fbf-458c-af3c-a3428dd5c1f4" />
<img width="687" height="506" alt="CO1" src="https://github.com/user-attachments/assets/10006688-7e10-4c1b-be74-62f870f61cfa" />
<img width="1365" height="709" alt="CO4" src="https://github.com/user-attachments/assets/4d2eaa06-1673-4c19-bf8c-79a1baa9802c" />
<img width="799" height="381" alt="CO3" src="https://github.com/user-attachments/assets/45af64d1-4b9f-422d-b371-09e002061f21" />

CRUD Operations
A simple backend-only CRUD application built with REST principles. This project exposes RESTful endpoints to creat

e, read, update, and delete resources. 
There is no frontend; the repository demonstrates API design, routing, data handling, and basic persistence for learning and development.

Features
RESTful API endpoints for Create, Read, Update, Delete operations,
Simple data model suitable for demos and testing,
Clear project structure for backend-focused development,
Minimal dependencies to keep the code easy to follow

Technologies
Java,
Specify framework used Spring Boot,
Mysql Workbench
Postman (Testing)
JSON for request and response payloads.

API Endpoints
Below are example endpoints. Adjust paths and payloads according to the actual implementation in the source.

POST /items — Create a new item. Request body: JSON object with item fields.
GET /items — Retrieve a list of items.
GET /items/{id} — Retrieve a single item by id.
PUT /items/{id} — Update an existing item. Request body: JSON with updated fields.
DELETE /items/{id} — Delete an item by id.

Project Structure
CRUD_operations/
 ├── src/                
 ├── pom.xml or build.gradle
 └── README.md

Adjust the structure above to match the repository contents.
