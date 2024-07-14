# Spring Boot Actuator Example

## Table of Contents

- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Running the Application](#running-the-application)
- [Testing](#testing)
- [Additional Notes](#additional-notes)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- **Spring Boot:** Framework for creating standalone, production-grade Spring-based applications.
- **Spring Actuator:** Monitoring and management of Spring Boot applications.
- **JUnit:** Testing framework for unit testing.
- **Spring Test:** Integration testing support.
- **Maven:** Build automation tool.

## Project Structure
````
SpringBootActuatorExample
├── src
│ └── main
│ └── java
│ └── com
│ └── javatpoint
│ ├── DemoRestController.java
│ └── SpringBootActuatorExampleApplication.java
└── src
└── test
└── java
└── com
└── javatpoint
└── SpringBootActuatorExampleApplicationTests.java
````


## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NelushGayashan/spring-boot-actuator-example.git
   cd spring-boot-actuator-example
   ````

2. **Run the application:**
        Execute the main class **SpringBootActuatorExampleApplication.java** to start the Spring Boot application.

## Running the Application

- The application will start on the default port (8080).
- Access the /hello endpoint to see the response Hello User!.

## Testing

- Unit tests are available in SpringBootActuatorExampleApplicationTests.java.
- Integration tests can be added as needed.

## Additional Notes

- This project integrates Spring Boot Actuator, providing monitoring and management endpoints.
- Ensure to configure Actuator endpoints as per security and monitoring requirements.

## Contributing

- Contributions are welcome! Fork the repository and submit a pull request.

## License

- This project is licensed under the MIT License - see the LICENSE file for details.
