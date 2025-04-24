# 4.01-SpringBootIntroduction Level 2

This Spring Boot application is configured with Gradle to run on port 9001 by setting the following in the application.properties file:

server.port=9001

The application exposes a simple REST API with a controller class named HelloWorldController, located in the controller subpackage.
📌 Endpoints

The controller contains two GET methods that receive a String parameter called name and return the message:

    "Hello, {name}. You are running a Gradle project."

1️⃣ GET /HelloWorld

- Accepts name as a RequestParam
- Default value: "UNKNOWN"
- Example requests:
    - http://localhost:9001/HelloWorld
    - http://localhost:9001/HelloWorld?name=YourName

2️⃣ GET /HelloWorld2/{name}

- Accepts name as a PathVariable
- The parameter is optional
- Example requests:
    - http://localhost:9001/HelloWorld2
    - http://localhost:9001/HelloWorld2/YourName




💻Stack used: Project created with:

    Java v.21
    Gradle v.8.13
    IDE IntelliJ Idea v. 24.3.1.1

📋Requirements: No specific requirement but the Java and Gradle version or newer.

🛠️Installation:

    Clone this repo: -> git clone

▶️Execution: No specific instruction.

🌐Deployment: N/A.

🤝Contributions:

Contributions are welcome! Please follow the following steps to contribute:

    Fork the repository.
    Create a new: git checkout branch -b feature/News.
    Make your changes and commit them: git commit - 'Add New Functionality'.
    Upload the changes to your branch: git push feature/News.
    Do a pull request.
