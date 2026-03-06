# Banking DevOps Pipeline

A banking application project demonstrating **build automation, continuous integration, and code quality assurance** using modern DevOps practices.

---

![Java](https://img.shields.io/badge/Java-JDK-blue)
![DevOps](https://img.shields.io/badge/DevOps-CI%2FCD-green)
![Build Tool](https://img.shields.io/badge/Build-Apache%20Ant-orange)
![CI](https://img.shields.io/badge/CI-Jenkins-red)
![Testing](https://img.shields.io/badge/Testing-JUnit%205-yellow)
![Static Analysis](https://img.shields.io/badge/Static%20Analysis-SpotBugs-blueviolet)

---

## Project Overview

This project demonstrates how a **banking application can be integrated with a CI/CD pipeline** to automate software development workflows.

The pipeline automates key stages of the development lifecycle including:

* build automation
* automated testing
* mutation testing
* static code analysis

By integrating these practices, the project improves **code quality, reliability, and development efficiency**.

---

## Technologies Used

* **Java**
* **Apache Ant** – build automation
* **Git** – version control
* **Jenkins** – continuous integration pipeline
* **JUnit 5** – unit testing
* **PIT Mutation Testing** – testing effectiveness
* **SpotBugs** – static code analysis

---

## Continuous Integration Pipeline

The Jenkins pipeline automates the following stages:

### Clean

Removes previously compiled files and prepares a clean build environment.

### Build

Compiles the application source code using **Apache Ant build targets**.

### Test

Runs the **JUnit 5 test suite** to verify application functionality.

### Mutation Testing

Executes **PIT mutation testing** to evaluate how effective the unit tests are in detecting faults.

### Static Code Analysis

Runs **SpotBugs** to detect potential bugs, performance issues, and security vulnerabilities in the codebase.

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
├── src/                 # Application source code
├── test/                # Unit tests
├── build.xml            # Apache Ant build configuration
├── Jenkinsfile          # Jenkins pipeline definition
└── README.md
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

Rutuja Deshmukh
MSc Informatik — Germany

---

## License

This project is provided for **educational and portfolio purposes**.
