# GradleMiniProject
# Gradle Mini Project

## Author
**NAME**:Nithish G
**email id :** nithishsathya089@gmail.com

---

## Objective

* To install Gradle on Windows using multiple methods (Chocolatey, manual, wrapper).
* To configure Java and Gradle environment variables.
* To compare Gradle with Maven in terms of performance and flexibility.
* To create a simple Java application using Gradle and test its build process.

---

## Tools Required

* Windows 10 / 11
* PowerShell (Admin)
* Chocolatey
* OpenJDK 11+
* Gradle 9.x
* IDE (Eclipse / VS Code / IntelliJ)

---

## Steps to Run

### 1. Clone the Repository

```bash
git clone https://github.com/nithishsathya089-sudo/GradleMiniProject.git
cd GradleMiniProject
```

### 2. Check Java Version

```powershell
java -version
```

### 3. Check Gradle Version

```powershell
gradle -v
```

### 4. Build the Project

```powershell
gradle build
```

### 5. Run the Project

```powershell
gradle run
```

### 6. Using Gradle Wrapper

```powershell
.\gradlew build
.\gradlew run
```

---

## Gradle vs Maven Comparison

| Feature         | Gradle                            | Maven                      |
| --------------- | --------------------------------- | -------------------------- |
| Build Language  | Groovy/Kotlin DSL                 | XML (pom.xml)              |
| Performance     | Faster (incremental build, cache) | Slower (no build cache)    |
| Flexibility     | Highly customizable               | Limited customization      |
| Wrapper Support | Yes (gradlew)                     | Yes (mvnw)                 |
| Build File      | build.gradle                      | pom.xml                    |
| Learning Curve  | Steeper                           | Easier                     |
| IDE Support     | IntelliJ, Eclipse, VS Code        | IntelliJ, Eclipse, VS Code |

---


## Result

* Gradle installed successfully on Windows using Chocolatey.
* Java environment configured correctly.
* Sample Gradle project created, built, and ran successfully.
* Gradle Wrapper generated for version consistency.
* IDE integration tested in Eclipse / VS Code.
* Gradle vs Maven comparison completed.

---

## Conclusion

Gradle is a modern, flexible, and faster build tool compared to Maven. Using Gradle Wrapper ensures consistent builds across different machines. This project demonstrates complete Gradle setup and configuration on Windows.
