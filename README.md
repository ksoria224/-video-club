# Employee Management System with Java

The Employee Management System is a Java-based project designed to manage employee data efficiently.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes. Please refer to the deployment section for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

- Java Development Kit (JDK) installed
- Apache Maven installed
- Git installed (optional)

### Installing

A step by step series of examples that tell you how to get a development env running

1. Clone the repository from GitHub:

	clone https://github.com/your-username/employee-management-system.git(exemple)

2. Navigate to the project directory:

   cd employee-management-system

3. Compile the project using Maven:

   mvn compile

4. Run the project:

   mvn exec:java -Dexec.mainClass="com.example.EmployeeManagementSystemApplication"

5. Access the application in your web browser at `http://localhost:8080`.


## Running the tests

To run the automated tests for this system, use the following command:

	mvn test

### Break down into end to end tests

These tests validate the functionality of the entire system to ensure that it works as expected in real-world scenarios. For example, a test scenario might involve adding a new employee, updating their information, and then retrieving it to confirm the changes.

### And coding style tests

Coding style tests, such as those provided by tools like Checkstyle or PMD, ensure that the code adheres to specified coding standards and best practices. For example, a coding style test might check for proper indentation, variable naming conventions, and absence of code smells.

## Deployment

To deploy this project on a live system, follow these steps:

	1.Build the project using Maven:
	mvn package
	2.Deploy the generated employee-management-system.jar file to your server or cloud platform
	3.Run the application:
	java -jar target/employee-management-system.jar


## Built With

Dropwizard - The web framework used
Maven - Dependency Management
ROME - Used to generate RSS Feeds

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Santiago Soria** - *Initial work* 

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

	*Special thanks to our project mentor for valuable guidance and feedback.
	*Gratitude to the open-source community for providing essential libraries and tools.
	*Recognition to our colleagues who provided support and encouragement throughout the project.
	*Appreciation to users who provided feedback and helped shape the system's features.
	*Thanks to the team members who contributed ideas, code, and documentation to the project.
	*Acknowledgment to academic institutions or organizations that provided resources or funding for the project.
	*Shoutout to online forums and communities where we found solutions to technical challenges.
	*Gratefulness to friends and family for their patience and understanding during late-night coding sessions.
	*Recognition of any inspirational figures or works that influenced the project's design or goals.
