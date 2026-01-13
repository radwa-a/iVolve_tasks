# Building Tools: Gradle and Maven
This project demonstrates the use of **Gradle** and **Maven**, two popular build automation tools in the Java ecosystem, for compiling, testing, and packaging Java applications.

## Introduction

**Gradle** and **Maven** are build automation tools used to:

- Compile source code
- Run tests
- Package applications into deployable artifacts (JAR, WAR, etc.)
- Automate build processes in CI/CD pipelines

Both tools simplify project management and ensure reproducible builds.

## Prerequisites
**Gradle** and **Maven** run on all major operating systems and require only a Java JDK version 17 or higher to be installed.
run java-version:
```bash
$ java -version
```
<img width="800" height="175" alt="image" src="https://github.com/user-attachments/assets/6da6e4e4-128a-427a-b5d9-3e93e55e110b" />

## Artifacts
An artifact is the output of the build process.
It is deployable and can be a JAR, WAR, or other format depending on your project.
- Gradle: build/libs/project-name.jar
- Maven: target/project-name.jar

## Notes
- Gradle is flexible, supports many languages, and is faster for large projects.
- Maven uses a declarative XML configuration and is widely used in enterprise projects.
- Unit tests help detect bugs early but cannot guarantee 100% error-free code.
