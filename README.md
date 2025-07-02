# week10

# 🧪 Selenium Page Object Model (POM) - Login Test

This project demonstrates a basic Page Object Model (POM) structure in Selenium with Java to automate a simple login test.

---

## 📁 Project Structure

project-root/
├── pages/
│ └── LoginPage.java
├── tests/
│ └── LoginTest.java
├── utils/
│ ├── BaseTest.java
│ ├── ConfigReader.java (optional)
│ └── DriverFactory.java (optional)
├── config.properties (optional)
└── README.md


---

## ✅ Prerequisites

- Java JDK 8 or higher installed
- Chrome browser
- ChromeDriver in system PATH
- [Optional] Maven or Gradle for dependency management

---

## 📦 Dependencies

If using Maven, include the following in your `pom.xml`:

```xml
<dependencies>
    <!-- Selenium -->
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.21.0</version>
    </dependency>

    <!-- TestNG (optional for test structure) -->
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.9.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>

How to Run the Program
▶️ Option 1: Using an IDE (like IntelliJ or Eclipse)
Open the project in your IDE.

Ensure all dependencies are resolved.

Right-click on LoginTest.java in the tests folder.

Select Run.

▶️ Option 2: Using Terminal (Maven Project)
bash
Copy
Edit
mvn clean compile
mvn exec:java -Dexec.mainClass="tests.LoginTest"
