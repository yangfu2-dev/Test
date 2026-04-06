# SafeFlight
SafeFlight is a quality-driven flight booking application developed using Agile methodologies and Software Quality Assurance practices.

## Objectives
- Apply SQA throughout SDLC
- Demonstrate unit, integration, and system testing
- Handle boundary, concurrency, and validation scenarios
- Integrate continuous testing and static code analysis

## Features
SafeFlight application has several distinctive features:

- Management of user accounts i.e. signup and login validation
- Search for available flights (one-way or round-trip)
- Booking and Cancelling of a specific flight
- Maintanese of user's flight information (history of booking and cancellation)

## Tech Stack
- Backend: Java, Spring Boot
- Testing: JUnit, Selenium
- Static Analysis: SonarCloud

## System Requirements
- **Java**: JDK 17 or higher
- **Maven**: 3.6+ (for dependency management)
- **Git**: For version control
- **Web Browser**: Chrome, Firefox, or Edge (latest versions)

## Project Structure
```
SafeFlight-sqa/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/safeflight/backend/
│   │   │   │   ├── BackendApplication.java
│   │   │   │   ├── config/
│   │   │   │   ├── controller/
│   │   │   │   ├── model/
│   │   │   │   ├── repository/
│   │   │   │   ├── service/
│   │   │   │   └── exception/
│   │   │   └── resources/
│   │   │       ├── application.properties
│   │   │       ├── templates/     # JavaScript templates
│   │   │       └── static/        # CSS
│   │   └── test/
│   ├── pom.xml
│   └── mvnw/mvnw.cmd
├── data/                          # database files
└── README.md
```


## Application Start

### 1. Clone the Repository
```bash
git clone https://github.com/himanshukapse2/SafeFlight-sqa.git
cd SafeFlight-sqa
```

### 2. Navigate to Backend Directory
```bash
cd backend
```

### 3. Run the Application
```bash
mvn spring-boot:run
```

### 4. Open Frontend
```bash
# enter the following URL into your local browser
localhost:8082
```

## Usage

### signup and login
<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 49 00" src="https://github.com/user-attachments/assets/b383f92f-73ce-4cc6-8f0d-156d8ed15bce" />

### search for flights
<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 54 33" src="https://github.com/user-attachments/assets/ba63ef31-698c-4e28-948e-f1690b8c8971" />
<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 54 59" src="https://github.com/user-attachments/assets/28276d0e-0802-4443-8160-142130a888d8" />

### booking a flight
<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 55 24" src="https://github.com/user-attachments/assets/8c1e5ee8-f20f-44b8-85c1-f5e39e6d172e" />

### canceling a flight
<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 55 48" src="https://github.com/user-attachments/assets/636d2b53-9c1d-453d-a016-9bc71086141e" />

### reviewing myflight

<img width="500" height="350" alt="Screenshot 2026-04-02 at 21 55 58" src="https://github.com/user-attachments/assets/694dea8d-39af-40b3-bfa4-05176042a624" />

