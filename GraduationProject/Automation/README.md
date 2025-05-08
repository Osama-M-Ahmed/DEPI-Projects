# QaFox Automation Framework

This is a Java-based UI automation framework for web applications, designed using the **Page Object Model (POM)** and built with **Selenium WebDriver**, **Cucumber**, and **TestNG**. The framework supports test organization, reporting, and efficient test execution.

## 🧰 Technologies Used

- **Java**
- **Maven**
- **Selenium WebDriver**
- **Cucumber (BDD)**
- **TestNG**
- **Page Object Model (POM)**

## 📁 Project Structure

Automation/
│
├── pom.xml # Maven configuration file
├── Runner.xml # TestNG XML test runner
├── src/
│ ├── main/
│ │ ├── java/Pages/ # Page Object classes
│ │ └── java/Utils/ # Utility classes (e.g., Screenshot)
│ │ └── resources/Features/ # Cucumber feature files
│ └── test/
│ ├── java/Base/ # Base test setup
│ ├── java/StepDefs/ # Step definition files
│ └── java/Tests/ # Test classes
└── target/ # Build output directory


## 🚀 How to Run the Tests

1. **Clone the repository** and navigate to the project root.

2. **Install dependencies**:
   ```bash
   mvn clean install
   
## Run tests:
mvn test

or via TestNG:
mvn test -DsuiteXmlFile=Runner.xml

✅ Features Covered
User registration

Login functionality

Add to cart

Change password

🧪 Cucumber Feature File
Located at:
src/main/resources/Features/Register.feature

📸 Screenshots
The framework includes a utility to capture screenshots on test failure.

📄 Reporting
Test reports can be generated via the default TestNG and Cucumber plugins. Integration with advanced reporting tools like Allure or ExtentReports can be added as needed.

📌 Notes
Java version: 23 (as specified in pom.xml)

Target browser and environment configs can be enhanced by externalizing into properties files or using WebDriverManager.






