# First Spring Boot Project (Greeting App)

This is an educational project built using the **Spring Boot** framework and the **Thymeleaf** template engine. The project demonstrates basic web controller logic, query parameter handling, and static resource (image) integration.

## 🚀 Technologies
* **Java 17+**
* **Spring Boot** (Spring MVC)
* **Thymeleaf**
* **Maven** (for dependency management and building)

## 📁 Project Structure
```text
first-project-java-spring/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/firstproject/
│   │   │       ├── FirstProjectJavaSpringApplication.java
│   │   │       └── HelloController.java
│   │   └── resources/
│   │       ├── static/
│   │       │   └── images/
│   │       │       └── Vistula.jpeg
│   │       ├── templates/
│   │       │   └── greeting.html
│   │       └── application.properties
│   └── test/
└── pom.xml
🛠️ How to Run Locally
Open the project in IntelliJ IDEA.

Make sure you have Java 17 or a newer version installed.

Run the main application class: FirstProjectJavaSpringApplication.java.

Open your browser and go to:
👉 http://localhost:8080/greeting?name=Vistula

📌 Features
Handles the /greeting route, which accepts a name query parameter (e.g., user name or organization name).

Renders an HTML page via Thymeleaf displaying a personalized greeting.

Displays a local logo from the static resources folder (/images/...).
