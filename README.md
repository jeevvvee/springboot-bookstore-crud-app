# springboot-bookstore-crud-app

A simple CRUD Application with REST API, Springboot, Spring data JPA and H2 database

# Requirements: 
Java 21, Maven, Springboot 3.5.4 and H2 in-memory Database

# How to Run : 
1️) Clone the repository
git clone https://github.com/your-username/bookstore.git
cd bookstore

2️) Run the application (Maven)
./mvnw spring-boot:run

3️) Access
API Base URL: http://localhost:8080
H2 Console: http://localhost:8080/h2-console
(JDBC URL: jdbc:h2:mem:bookstore)


# API Endpoints : 
1. Create a Book - POST /api/books/create
2. Retrieve All Books - GET /api/books
3. Retrieve a Book by ID - GET /api/books/{id}
4. Update a Book - PUT /api/books/update?id={id}
5. Delete a Book -DELETE /api/books?id={id}



