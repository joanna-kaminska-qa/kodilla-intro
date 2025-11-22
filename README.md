# kodilla-intro

![Java](https://img.shields.io/badge/Java-21-blue)
![Gradle](https://img.shields.io/badge/Gradle-8-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Simple overview of the purpose of this repository:  
This project contains exercises, homework tasks, and example implementations completed as part of a module in the Kodilla "Automated Tester" Java course, focusing on **Object-Oriented Programming (OOP)** in Java 21.

The project was developed in **IntelliJ IDEA** as part of the learning path for future **QA/Test Automation Engineers**.

---

## Description

This repository includes Java code written while learning the fundamentals of Object-Oriented Programming.

The module covered:

- creating classes and objects
- constructors with parameters
- instance methods using `this`
- conditional logic (`if / else`)
- arrays and loops
- refactoring structural code to OOP
- static variables and static methods
- `switch` statements
- enums and their usage in Java

The project reflects practical work completed in IntelliJ IDEA as part of the Kodilla learning path for aspiring QA/Testers.

---

## Project Structure
```
kodilla-intro/
├── src/
│   └── main/
│       └── java/
│           ├── AdvCalcApplication.java
│           ├── AdvCalculator.java
│           ├── Application.java
│           ├── Book.java
│           ├── CalcApplication.java
│           ├── Calculator.java
│           ├── Colors.java
│           ├── DebugExample.java
│           ├── FirstClass.java
│           ├── Grades.java
│           ├── HelloWorld.java
│           ├── LeapYear.java
│           ├── Loops.java
│           ├── Main.java
│           ├── MainExtended.java
│           ├── Notebook.java
│           ├── RandomNumbers.java
│           ├── SimpleArray.java
│           ├── User.java
│           ├── UserDialogs.java
│           └── com/
│               └── kodilla/
│                   └── Main.java
├── build.gradle
├── settings.gradle
├── gradlew
├── gradlew.bat
├── LICENSE
└── README.md
```

## Getting Started

### Dependencies

This project uses **Gradle** for build automation.

Main dependencies from `build.gradle`:

```gradle
plugins {
    id 'java'
}

group = 'com.kodilla'
version = '1.0-SNAPSHOT'

repositories {
    mavenCentral()
}

dependencies {
    testImplementation platform('org.junit:junit-bom:5.10.0')
    testImplementation 'org.junit.jupiter:junit-jupiter'
}

test {
    useJUnitPlatform()
}
```

### Explanation

Here is a brief explanation of the main components used in this project:

- **Java plugin** – enables compilation and running of Java code within Gradle.  
- **JUnit 5 (Jupiter)** – used for writing and executing unit tests.  
- **Maven Central** – main repository for resolving dependencies.  
- **Gradle wrapper (`gradlew` / `gradlew.bat`)** – ensures the project can be built on any machine without requiring Gradle to be installed globally.  

No additional external libraries are required for running the main project code. All classes can be executed directly in IntelliJ IDEA or via the terminal using Gradle commands.

---

### Optional Terminal Commands

- Build the project:

```bash
./gradlew build
```
- Run tests:
```bash
./gradlew test
```
- Clean the project:
```bash
./gradlew clean
```
## Authors

Created by:

**Joanna Kamińska**  
GitHub: [https://github.com/joanna-kaminska-qa](https://github.com/joanna-kaminska-qa)

---

## Version History

- **0.2** – Minor improvements in structure (README added)
- **0.1** – Initial upload

---

## License

This project is licensed under the **MIT License**.  
See the LICENSE file for details.

---

## Acknowledgments

- Kodilla "Automated Tester" Java course materials
- Java documentation