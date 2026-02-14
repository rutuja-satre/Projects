## EduTrack – Classroom and Student Management Portal

## Technology Stack
- Backend: Java, Spring Boot
- Database: MongoDB (NoSQL)
- Frontend: Java-based Client Application
- Build Tool: Maven
- API Testing Tool: Postman

---

## Project Overview
EduTrack is a full-stack Java-based classroom management system designed to manage
academic batches and student records efficiently.

The application provides RESTful CRUD APIs using Spring Boot and stores data in
MongoDB for scalable NoSQL storage.

A Java-based client application interacts with
the backend services to perform operations such as batch creation, student
management, and record updates.

---

## Key Features

### Batch Management
- Create, update, delete, and view batches
- Store batch details such as batch name, schedule, duration, and trainer information

### Student Records
- Maintain student details including name, contact number, and enrollment date
- Dynamically associate students with their respective batches

### CRUD Operations
- REST APIs for Create, Read, Update, and Delete operations

### Database Integration
- MongoDB used for flexible and scalable data storage

### Client-Side Application
- Java-based menu-driven client to interact with backend REST APIs

### Scalable & Modular Design
- Built using Spring Boot layered architecture
- Easy to extend with future features like attendance and performance tracking

---

## Project Structure

src/
├── controller
├── service
├── repository
├── entity
└── config

## Example Usage
## Client Application Menu

===== EduTrack Portal =====
1. Create New Batch
2. View All Batches
3. Update Batch Information
4. Delete Batch
5. Add Student to Batch
6. View Students in a Batch
7. Exit
