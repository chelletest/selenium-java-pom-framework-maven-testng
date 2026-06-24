# Selenium Java POM Framework using Maven , TestNG
# Login Test Framework 

This repository contains a **Selenium-based automation framework** built with **Java** for performing login test. It uses the **Page Object Model (POM)** design pattern, **Maven** for dependency management, **TestNG** for running tests, and  reporting.

## Technologies and Tools Used:
- **Java**: Primary programming language.
- **Selenium WebDriver**: For browser automation.
- **Maven**: Build automation and dependency management.
- **TestNG**: For running tests and organizing test suites.
- **Page Object Model (POM)**: A design pattern for creating reusable, maintainable test code.

#  Features
#  Page Object Model (POM):

The POM design pattern is used to separate the test logic from the UI interaction. This improves code maintainability and readability. All web elements and actions for the login page are abstracted in the LoginPage class.

#  Maven:
Maven is used for managing project dependencies and build configurations. It ensures that all necessary libraries are included and simplifies the build process.

#  TestNG:
TestNG is used for managing test execution. It allows you to create test suites, set up parallel execution, and handle test configurations. 


#  Prerequisites
Java 8+ installed.
Maven installed.
Selenium WebDriver setup (e.g., ChromeDriver).
TestNG dependencies will be downloaded automatically via Maven.

#  Setup Instructions
1. Clone the Repository
2. Install Dependencies
- mvn clean install
3. WebDriver Setup, manager
4. Run Tests
- mvn test
5. TestNG will execute the test cases defined in the LoginTest.java file, and the results will be logged in the test-output folder.

#  TestNG Configuration
TestNG configurations can be customized using the testng.xml file. Here you can define:
Test suite(s)
Parallel execution
Test groups (e.g., smoke, regression)
Test listeners (for logging and reporting)

![Screenshot 2025-06-04 at 10 57 33](https://github.com/user-attachments/assets/4f37fab7-30b4-4157-932a-a69249615669)


![Screenshot 2025-06-04 at 10 53 59](https://github.com/user-attachments/assets/40cc9650-e6c1-4c5f-a11b-fbe4f46d50e5)

#  Licence   

This project is licenced under the MIT Licence.

