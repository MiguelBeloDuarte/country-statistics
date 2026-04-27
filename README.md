# Country Statistics Engine

A Java application for parsing, validating, and querying large CSV datasets containing demographic data of countries and cities. Built as a university project for the **Algoritmia e Estruturas de Dados** course at Universidade Lusófona (2025/2026).

## Features

- CSV file parsing with comprehensive error handling
- Custom OOP models for Country and City entities
- Memory-efficient data structures
- Comprehensive unit testing with JUnit 5
- Input validation and malformed data detection

## Technical Constraints

This project was built under strict academic constraints to deepen understanding of fundamental data structures and algorithms:

- No `Set`, `Map`, or any of their variants (`HashMap`, `TreeMap`, `HashSet`, etc.)
- No streams API
- Custom-built data organization using arrays and basic Java classes only

## Tech Stack

- **Language:** Java 17
- **Testing:** JUnit 5
- **Build:** Plain `javac` / IntelliJ IDEA

## How to Run

```bash
javac -d out src/pt/ulusofona/aed/deisiworldmeter/*.java
java -cp out pt.ulusofona.aed.deisiworldmeter.Main
```

The application reads three CSV files (`paises.csv`, `cidades.csv`, etc.) and processes them according to the project specification.

## Testing

Run JUnit tests from IntelliJ or via Maven/Gradle if configured. Test files are located in the `test-files/` directory.

## Project Context

Built collaboratively in a 2-person team. Evaluated through automated testing (Drop Project platform) and individual defense.

## Authors

- Miguel Duarte
- Guilherme Costa
