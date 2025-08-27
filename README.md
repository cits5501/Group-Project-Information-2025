# Group-Project-Information-2025 – Phase 1

## Overview
This repository contains our group’s work for **Project Phase 1** of the CITS5501/CITS3501 unit.  
The project implements a prototype **terminal-based interface** for the Tachi flight reservation system.  
Phase 1 tasks focus on:
- Setting up the GitHub repository and workflow
- Completing the `DateTimeChecker` utility class
- Writing JUnit tests for validation
- Establishing a basic software quality assurance plan

---

## Repository Structure
├── src/ # Java source files
│ └── DateTimeChecker.java # Utility class for date/datetime validation
├── test/ # JUnit test cases
│ └── DateTimeCheckerTest.java
├── config.txt # Configuration file
├── README.md # Project introduction (this file)
└── project-phase1-report.md # Phase 1 written answers

---

## How to Compile and Run
Requirements:  
- Java 17+  
- JUnit 5  

Compile:
```bash
javac -d bin src/*.java

---

Run tests:
```bash
java -jar junit-platform-console-standalone.jar -cp bin --scan-class-path

---

##Contribution Workflow

Work is done in feature branches

Code is merged to main via Pull Requests after at least two people reviewed.

Each PR requires peer review

---

Team Members

Wanqi Zhang (Student ID: 24080897)

Max Cutlyp (Student ID: 23368261)

Aaryan Sachdevani (Student ID: 23351863)

Atharva Ganesh Dalvi Dalvi (Student ID: 24591632)

Jean Wang (Student ID: 24137024)
