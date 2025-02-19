# Ticket Booking System

This is a basic ticket booking system built as a practice mini-project while learning Java. The project is managed using Gradle and developed in IntelliJ IDEA.

## Project Structure
```
📂 ticket-booking
│── 📁 app
│   ├── 📁 src
│   │   ├── 📁 main
│   │   │   ├── 📁 java/ticket.booking
│   │   │   │   ├── 📁 entities
│   │   │   │   │   ├── 📝 Ticket.java
│   │   │   │   │   ├── 📝 Train.java
│   │   │   │   │   ├── 📝 User.java
│   │   │   │   ├── 📁 localDB
│   │   │   │   │   ├── 📝 trains.json
│   │   │   │   │   ├── 📝 users.json
│   │   │   │   ├── 📁 services
│   │   │   │   │   ├── 📝 TrainService.java
│   │   │   │   │   ├── 📝 UserBookingService.java
│   │   │   │   ├── 📝 App.java
│   │   ├── 📁 resources
│   ├── 📁 test
│── 📁 build
│── 📁 gradle
│── 📄 build.gradle
│── 📄 gradle.properties
│── 📄 .gitignore
│── 📄 .gitattributes
```

## Features
- User registration and management
- Train details storage in JSON files
- Booking and ticket management
- Basic service layer for handling user and train data

## Technologies Used
- Java
- Gradle (Build & Dependency Management)
- JSON for local database storage
- IntelliJ IDEA (Development Environment)

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/akshatpandey1903/ticket-booking-system
   ```
2. Open the project in IntelliJ IDEA.
3. Build the project using Gradle:
   ```sh
   ./gradlew build
   ```
4. Run the `App.java` file to start the system.

## Future Enhancements
- Implement database integration (MySQL/PostgreSQL)
- Add a GUI for better user experience
- Improve ticket booking algorithms

---
Happy Coding! 🚀
