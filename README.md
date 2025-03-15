# Project Overview

This project focuses on automating the testing of the **Register** and **Login** functionalities using the **Page Object Model (POM)** with **Selenium WebDriver** and **TestNG**. It includes both **manual and automated test cases**, along with a **video demonstration** showcasing the execution of tests.

## Project Structure

The project follows a structured **Page Object Model (POM)** approach and includes the following packages inside `src/test/java/`:

```
src/test/java/
├── PageObjects/  # Contains Page Object classes (LoginPage, RegisterPage, etc.)
├── TestCases/    # Contains test cases implementing TestNG
├── TestBase/     # Contains base classes for setup and configurations
```

## Manual Testing

A set of **manual test cases** were created to validate the **Register** and **Login** functionalities. These test cases cover different scenarios, including:

- Valid and invalid registration attempts
- Login with correct and incorrect credentials
- Error message validation for missing or incorrect inputs

## Automation Testing

The automation script is built using:

1. **Selenium WebDriver** - For UI interactions
2. **TestNG** - For test execution
3. **Page Object Model (POM)** - For better maintainability
4. **Maven** - For dependency management and execution
5. **Assertions** - To validate expected results

## Video Demonstration

A full walkthrough of the project, including test execution, is available in the following video:

https://drive.google.com/file/d/1KboOUMU4pdqXkEga1uXUNvfpgK3uWV0v/view?usp=sharing ---

### **How to Run the Project**

1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   ```
2. **Navigate to the project directory**:
   ```sh
   cd project-directory
   ```
3. **Install dependencies using Maven**:
   ```sh
   mvn clean install
   ```
4. **Run test cases**:
   ```sh
   mvn test
   ```

---

### **Future Enhancements**
- Implementing **cross-browser testing**
- Adding **API testing** for authentication flows
- Enhancing **reporting with Extent Reports**


Feel free to contribute to the project and suggest improvements! 🚀

