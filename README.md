# Java Advanced Calculator

![Language](https://img.shields.io/badge/Language-Java-orange) ![GUI](https://img.shields.io/badge/GUI-Swing-blue) ![Build](https://img.shields.io/badge/Build-Maven-red) ![Testing](https://img.shields.io/badge/Testing-JUnit5-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Overview

Advanced calculator built in Java with both a Swing GUI and a console interface. Supports standard arithmetic, scientific operations (trigonometry, logarithms, exponents), memory storage, and history logging. Built with a Maven structure and fully covered with JUnit 5 unit tests.

## Features

- Basic arithmetic: addition, subtraction, multiplication, division
- Scientific operations: sin, cos, tan, log, ln, sqrt, power
- Memory functions: M+, M-, MR, MC
- Calculation history with session log
- Input validation and division-by-zero handling
- Swing GUI with button layout and display panel
- Console interface as alternative input mode

## Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Java 17 |
| GUI Framework | Java Swing |
| Build Tool | Maven |
| Testing | JUnit 5 |
| IDE | IntelliJ IDEA |

## Project Structure

```
java-advanced-calculator/
├── src/
│   ├── main/java/com/nikoandes/calculator/
│   │   ├── Main.java          # Entry point
│   │   ├── Calculator.java    # Core calculation logic
│   │   ├── CalculatorGUI.java # Swing GUI
│   │   └── History.java       # Calculation history
│   └── test/java/com/nikoandes/calculator/
│       └── CalculatorTest.java
├── pom.xml
├── .gitignore
├── LICENSE
└── README.md
```

## How to Run

### Prerequisites
- Java 17+
- Maven 3.8+

```bash
git clone https://github.com/NikoAndes/java-advanced-calculator.git
cd java-advanced-calculator
mvn clean package
java -jar target/calculator.jar
```

### Run Tests
```bash
mvn test
```

## What I Learned

- Building desktop GUIs with Java Swing (layout managers, event listeners)
- Separating UI from business logic (MVC pattern)
- Unit testing mathematical operations with JUnit 5
- Maven project setup and JAR packaging
- Exception handling and input validation strategies

## Future Improvements

- [ ] Add graphing functionality for functions
- [ ] Implement expression parser for complex input strings
- [ ] Add dark/light theme toggle
- [ ] Export history to CSV
- [ ] Extend scientific functions (hyperbolic, factorial)

## Author

**Nicolas Isaza Sierra** — [GitHub @NikoAndes](https://github.com/NikoAndes)

Mechatronics engineering student | Java developer | UMNG, Colombia

## License

MIT License — see [LICENSE](LICENSE) for details.
