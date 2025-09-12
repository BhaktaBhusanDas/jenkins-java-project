# Jenkins Java Project

This project demonstrates a simple Java application integrated with Jenkins for continuous integration and delivery.

## Features

- Java application with sample code
- Jenkins pipeline configuration
- Automated build and test process

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/jenkins-java-project.git
    cd jenkins-java-project
    ```

2. **Build the project:**
    ```bash
    ./gradlew build
    ```
    or
    ```bash
    mvn clean install
    ```

3. **Run tests:**
    ```bash
    ./gradlew test
    ```
    or
    ```bash
    mvn test
    ```

## Jenkins Integration

- The project includes a `Jenkinsfile` for pipeline automation.
- Configure your Jenkins job to use this file for CI/CD.

## Requirements

- Java 11 or higher
- Gradle or Maven
- Jenkins (for CI/CD)

## License

This project is licensed under the MIT License.
