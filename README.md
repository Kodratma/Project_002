# 🧪 Project_002 - Selenium Java Test Automation Framework

This project is a **Selenium-based test automation framework** built using **Java, TestNG, Maven**, and follows the **Page Object Model (POM)** design pattern. It is designed to automate UI testing of a sample web application.

---

## 🔧 Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- Jenkins (for CI/CD)
- MySQL (for test data or validation)
- GitHub (version control)

---

## 📁 Project Structure
Project_002/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── base/              # Base classes (e.g., BaseTest, BasePage)
│   │       ├── pages/             # Page Object classes (POM)
│   │       └── utils/             # Utility classes (e.g., driver, wait, config)
│   │
│   └── test/
│       └── java/
│           └── tests/             # TestNG test classes
│
├── screenshots/                   # Screenshots on test failure
├── test-output/                   # TestNG reports (auto-generated)
├── pom.xml                        # Maven dependencies and config
├── testng.xml                     # TestNG test suite configuration
├── .gitignore                     # Files and folders to ignore
└── README.md                      # Documentation

