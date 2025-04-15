Online Quiz Management System – Backend (Java)

This is the backend of an **Online Quiz Management System** developed using **Java** and **Spring (or Java Servlet-based)** architecture. The system supports basic functionalities for students and administrators to interact with quizzes.

Current Features

- **Admin Authentication** (`ValidateAdmin`)
- **Student Authentication** (`ValidateStudent`)
- **Student Registration** (`StudentInsert`)
- **Insert Quiz Questions** (`QuestionInsert`)
- **Insert Exam Instructions** (`InstructionInsert`)
- **Logout Functionality** for Admin and Student (`LogoutAdmin`, `LogoutStudent`)

📁 Controller Files

| File Name         | Description                           |
|------------------|---------------------------------------|
| `InstructionInsert` | Adds exam instructions to the system |
| `LogoutAdmin`       | Handles admin logout                 |
| `LogoutStudent`     | Handles student logout               |
| `QuestionInsert`    | Adds new questions to quizzes        |
| `StudentInsert`     | Inserts new student details          |
| `ValidateAdmin`     | Authenticates admin login            |
| `ValidateStudent`   | Authenticates student login          |

=Technologies Used

- Java (JDK 8/11/17+)
- Spring Boot / Java Servlets (depending on your stack)
- IntelliJ IDEA
- MySQL / H2 (if database connected)
- Maven or Gradle
