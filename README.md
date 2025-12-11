CRUD Operations
A simple backend-only CRUD application built with REST principles. This project exposes RESTful endpoints to create, read, update, and delete resources. 
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
