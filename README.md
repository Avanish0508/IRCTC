🚆 IRCTC Train Booking Backend System

This project is a backend simulation of the IRCTC (Indian Railway Catering and Tourism Corporation) platform, developed using Java Spring Boot. It offers RESTful services for train search, user registration, ticket booking, and more—emulating the core functionalities of a train reservation system.

✨ Features
✅ User registration and authentication

🚉 Train search and schedule lookup

🎟️ Ticket booking and cancellation

📄 Ticket and user data managed via JSON

🔁 Custom model creation for trains, users, and tickets

🧩 Modular service layer using Spring Boot architecture

🔧 Technologies Used
Java 11
Spring Boot
RESTful APIs
JSON for data persistence
Maven for build management

📁 Project Structure
bash
Copy
Edit
IRCTC-main/
├── app/
│   ├── src/main/java/org/example/
│   │   ├── Entities/      # User, Train, Ticket models
│   │   ├── Services/      # Business logic for booking, train lookup
│   │   └── App.java       # Entry point for the application
├── .idea/                 # IntelliJ project files
├── settings.gradle        # Gradle config


🚀 Getting Started
Prerequisites
JDK 11+
Maven or Gradle
IDE (IntelliJ IDEA recommended)

Run the App
bash
Copy
Edit
./gradlew bootRun

Or using Maven:

bash
Copy
Edit
mvn spring-boot:run
📬 API Endpoints (Sample)
Endpoint	Method	Description
/register	POST	Register a new user
/trains	GET	Fetch available trains
/book	POST	Book a train ticket
/cancel/{id}	DELETE	Cancel a ticket by ID

🧠 Future Enhancements
Database integration (MySQL or PostgreSQL)
Admin dashboard
Email notification service
JWT-based authentication
