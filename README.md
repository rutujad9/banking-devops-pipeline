# Banking DevOps Pipeline

A banking application project demonstrating **build automation, continuous integration, and code quality assurance** using modern DevOps practices.

---

![Java](https://img.shields.io/badge/Java-JDK-blue)
![DevOps](https://img.shields.io/badge/DevOps-CI%2FCD-green)
![Build Tool](https://img.shields.io/badge/Build-Apache%20Ant-orange)
![CI](https://img.shields.io/badge/CI-Jenkins-red)
![Testing](https://img.shields.io/badge/Testing-JUnit%205-yellow)
![Static Analysis](https://img.shields.io/badge/Static%20Analysis-SpotBugs-blueviolet)
![Mutation Testing](https://img.shields.io/badge/Mutation%20Testing-PIT-purple)

---

## Project Overview

This project demonstrates how a **banking application can be integrated with a CI/CD pipeline** to automate software development workflows.

The repository also includes **generated HTML reports** from testing and mutation analysis tools such as **PIT**.

The pipeline automates key stages of the development lifecycle including:

* build automation
* automated testing
* mutation testing
* static code analysis

By integrating these practices, the project improves **code quality, reliability, and development efficiency**.

---

## CI Pipeline Workflow

```
Developer Push
      │
      ▼
   Jenkins Pipeline
      │
      ▼
   Clean Stage
(delete previous builds)
      │
      ▼
   Build Stage
(Apache Ant compilation)
      │
      ▼
   Test Stage
(JUnit test execution)
      │
      ▼
 Mutation Testing
      (PIT)
      │
      ▼
 Static Code Analysis
     (SpotBugs)
      │
      ▼
  Reports Generated
(HTML reports in demo1/reports/)
```

---

## Technologies Used

* **Java**
* **Apache Ant** – build automation
* **Git** – version control
* **Jenkins** – continuous integration pipeline
* **JUnit 5** – unit testing
* **PIT Mutation Testing** – evaluating test effectiveness
* **SpotBugs** – static code analysis

---

## CI Pipeline Stages

The Jenkins pipeline automates the following stages:

### 1. Clean

Removes compiled artifacts and resets the workspace.

### 2. Build

Compiles Java source code using **Apache Ant**.

### 3. Test

Executes **JUnit test cases** to verify application functionality.

### 4. Mutation Testing

Uses **PIT (Pitest)** to evaluate the effectiveness of the test suite.

### 5. Static Code Analysis

**SpotBugs** scans the code for potential defects and security issues.

### 6. Report Generation

Generates **HTML reports** for test results and mutation coverage.

---

## Testing Metrics

Mutation testing results generated using **PIT (Pitest)**:

* **Line Coverage:** 60%
* **Mutation Coverage:** 45%
* **Test Strength:** 59%

These metrics provide insight into the effectiveness of the unit tests and highlight opportunities for improving test coverage.

Detailed HTML reports can be found in the **`demo1/reports/`** directory.

---

## DevOps Goals

The project demonstrates how automated CI pipelines help:

* improve **code quality**
* detect bugs earlier in development
* ensure **test reliability**
* automate repetitive development tasks
* support **continuous integration workflows**

---

## Project Structure

```
banking-devops-pipeline/
│
├── demo1/
│   ├── src/          # Java source code
│   ├── junitest/     # JUnit test cases
│   ├── reports/      # Generated reports (PIT, SpotBugs, etc.)
│   ├── build.xml     # Apache Ant build configuration
│   └── Jenkinsfile   # Jenkins pipeline configuration
│
├── README.md
```

---

## Key DevOps Practices Demonstrated

* Build automation with **Apache Ant**
* Continuous integration with **Jenkins**
* Automated testing using **JUnit 5**
* Mutation testing with **PIT**
* Static code analysis using **SpotBugs**
* Version control with **Git**

---

## Author

**Rutuja Deshmukh**
MSc Informatik — Germany

---

## License

This project is provided for **educational and portfolio purposes**.
