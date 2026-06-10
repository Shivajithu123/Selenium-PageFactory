# Selenium Page Factory Framework

🚀 A Selenium Automation Testing Framework developed using Java, Selenium WebDriver, TestNG, Maven, and the Page Factory Design Pattern.

## Overview

This project demonstrates the implementation of the Selenium Page Factory design pattern to create clean, maintainable, and reusable test automation scripts.

The framework follows industry-standard automation practices by separating page elements and actions from test logic, resulting in a scalable and easy-to-maintain project structure.

## Features

* Page Factory Design Pattern
* Page Object Model (POM)
* Selenium WebDriver Automation
* TestNG Test Execution
* Maven Dependency Management
* Reusable Page Classes
* Clean Project Structure
* Maintainable Automation Framework

## Tech Stack

| Technology         | Purpose                         |
| ------------------ | ------------------------------- |
| Java               | Programming Language            |
| Selenium WebDriver | Browser Automation              |
| TestNG             | Test Execution Framework        |
| Maven              | Build & Dependency Management   |
| Page Factory       | Design Pattern for Web Elements |

## Project Structure

```text
POMLEARN/
│
├── src/
│   └── test/
│       └── java/
│           ├── Pages/
│           │   └── LoginPagepf.java
│           │
│           └── tests/
│               └── LoginTestpf.java
│
├── pom.xml
└── README.md
```

## Page Factory Implementation

### Web Element Initialization

```java
@FindBy(id = "user-name")
WebElement username;

@FindBy(id = "password")
WebElement password;

@FindBy(id = "login-button")
WebElement loginButton;
```

### Initialize Elements

```java
PageFactory.initElements(driver, this);
```

## Benefits of Page Factory

✅ Better Code Readability

✅ Reduced Code Duplication

✅ Easier Maintenance

✅ Improved Reusability

✅ Better Separation of Concerns

✅ Scalable Framework Design

## Test Flow

1. Launch Browser
2. Navigate to Application
3. Initialize Web Elements using Page Factory
4. Perform User Actions
5. Validate Results
6. Close Browser

## Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Navigate to Project

```bash
cd your-repository-name
```

### Install Dependencies

```bash
mvn clean install
```

### Execute Tests

```bash
mvn test
```

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Selenium WebDriver
* Page Object Model (POM)
* Page Factory Design Pattern
* TestNG Framework
* Maven Project Management
* Automation Framework Development
* Writing Maintainable Test Scripts

## Future Enhancements

* Cross-browser Testing
* Data-Driven Testing
* Screenshot Capture on Failure
* Extent Reports Integration
* Log4j Logging
* CI/CD Integration with Jenkins/GitHub Actions

## Author

**Shivadath**

QA Automation Engineer | Java | Selenium | TestNG | Software Testing




⭐ If you found this project useful, consider giving it a star.
