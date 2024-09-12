# SOLA (Static Online Analyzer)

### Project Overview
**SOLA** (Static Online Analyzer) is an innovative web-based tool designed for automated detection of common code smells in Java projects. By utilizing advanced static analysis techniques, SOLA helps developers maintain high code quality by identifying areas for improvement such as large classes, long methods, excessive comments, long parameter lists, and code duplication.

### Features
- **Large Class Detection**: Identifies classes that exceed predefined complexity thresholds.
- **Long Method Detection**: Flags methods that are too long, suggesting refactoring for readability and maintainability.
- **Excessive Comment Detection**: Highlights unnecessary or redundant comments that may indicate unclear code.
- **Long Parameter List Detection**: Detects methods with long parameter lists, recommending refactoring to improve clarity.
- **Code Duplication Detection**: Uses the Copy-Paste Detector (CPD) to find duplicated code blocks, promoting code reuse and simplicity.

### Technologies Used
- **Java**: Core language for code analysis.
- **Spring Boot**: Framework for managing the backend and web services.
- **JavaParser**: For parsing Java source files into Abstract Syntax Trees (AST).
- **CPD (Copy-Paste Detector)**: For detecting code duplication.
- **Thymeleaf**: For building dynamic web pages.
- **MySQL**: Database for storing reports and user data.

### Why SOLA?
In the modern software development lifecycle, maintaining clean, efficient, and maintainable code is crucial. SOLA empowers developers to proactively detect and resolve code smells that may affect the performance, readability, and maintainability of Java projects.

### Target Audience
SOLA is designed for:
- **Software Engineers**: Automate code quality checks and improve team productivity.
- **Tech Students**: Learn best coding practices and identify coding pitfalls early in the learning process.
- **Educational Institutions**: Integrate SOLA into curricula to teach students about code quality and maintainability.

### Getting Started
> *Note: The implementation files for SOLA have been intentionally hidden to safeguard against unauthorized access. For inquiries regarding the project or to collaborate, please contact the project maintainers.*

1. Clone the repository:
   ```bash
   git clone https://github.com/Graduation-Project-SOLA.git
   ```
2. Install the required dependencies:
   ```bash
   cd SOLA
   mvn clean install
   ```
3. Configure the database connection by updating the `application.properties` file with your MySQL credentials.

4. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

### Contribution
If you're interested in contributing to SOLA, please reach out via [email](mailto:sondosaied0@gmail.com). Contributions in the form of feature suggestions, issue reporting, or documentation improvements are welcomed.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Disclaimer**: The core implementation files are hidden in this repository to prevent unauthorized access and misuse. Please contact the authors if you would like to collaborate or request access for educational purposes.

### Contact
- **Author**: [Sondos Alfukaha] [Laila Dumra]
- **Email**: sondosaied0@gmail.com , lailadumra0@gmail.com
