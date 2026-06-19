# playwright-java-automation-framework
I have automated a sample website - ORANGEHRM using Playwright. Kindly go through the project for your reference

## Project Overview
Automation framework built using
- Playwright (Java)
- TestNG
- Page Object Model (POM)
- RRole-based login handling
- Session management using storage state

## Features
- Role based access testing (Admin vs User)
- Reusable BaseTest and BasePage
- Locator abstraction using properties files
- Trace and screenshot capture
- TestNG group-based execution

## Test Modules
- Add User
- Assign Role
- Role access Validation

## Technologies Used
- Java
- Playwright
- TestNG
- Maven

## How to Run
- Open Git bash and connect to this project
- Run the command to install dependencies from pom.xml
  mvn clean install -DskipTests
- Run the command to run the test
   mvn clean test
