# Gradle Mini Project

## Author

**Nithish G**
**Email:** [nithishsathya089@gmail.com](mailto:nithishsathya089@gmail.com)

---

## Objective

* Install Gradle on Windows using three methods: Binary, Package Manager (Chocolatey), and Wrapper.
* Configure Java and Gradle environment variables.
* Compare Gradle with Maven in terms of performance and flexibility.
* Create a simple Java application using Gradle and test its build process.
* Test IDE integration in Eclipse.

---

## Tools Required

* Windows 10 / 11
* PowerShell (Admin)
* Chocolatey (for Package Manager method)
* OpenJDK 11+
* Gradle 9.x (Binary & Wrapper)
* Eclipse IDE

---

## Gradle Installation Methods

### 1. Binary Download (Manual)

* Download Gradle ZIP from [https://gradle.org/releases/](https://gradle.org/releases/)
* Extract to folder (example): `C:\Gradle\gradle-9.1`
* Add `C:\Gradle\gradle-9.1\bin` to PATH
* Verify:

```powershell
gradle -v
```

### 2. Package Manager (Chocolatey)

* Install Chocolatey if not installed.
* Run in PowerShell (Admin):

```powershell
choco install gradle -y
```

* Installed location:

```
C:\ProgramData\chocolatey\lib\gradle\tools\gradle-9.1
C:\ProgramData\chocolatey\bin\gradle.exe
```

* Verify:

```powershell
gradle -v
```

### 3. Gradle Wrapper

* Inside your project folder, run:

```powershell
gradle wrapper
```

* Wrapper files generated:

```
C:\GradleTest\gradlew
C:\GradleTest\gradlew.bat
C:\GradleTest\gradle\wrapper\
```

* Use wrapper to build/run project:

```powershell
.\gradlew build
.\gradlew run
```

---

## Steps to Run Project

1. Clone the repository:

```powershell
git clone https://github.com/nithishsathya089-sudo/GradleMiniProject.git
cd GradleMiniProject
```

2. Check Java version:

```powershell
java -version
```

3. Build and run using Gradle (Binary / Chocolatey):

```powershell
gradle build
gradle run
```

4. Build and run using Wrapper:

```powershell
.\gradlew build
.\gradlew run
```

5. IDE Integration in Eclipse:

* Open Eclipse → File → Import → Gradle → Existing Gradle Project.
* Select project folder `C:\GradleTest` → Finish.
* Open Gradle Tasks view: Window → Show View → Other → Gradle → Gradle Tasks.
* Run `build` and `run` tasks.
* Run Java application: Right-click `App.java` → Run As → Java Application.
* Check Console for output to confirm IDE integration.

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
| IDE Support     | Eclipse, IntelliJ, VS Code        | Eclipse, IntelliJ, VS Code |

---

## Result

* Gradle installed successfully using **Binary, Chocolatey, and Wrapper** methods.
* Java environment configured correctly.
* Sample Gradle project created, built, and ran successfully using all methods.
* Eclipse IDE integration tested and verified.
* Gradle vs Maven comparison completed.

---

## Conclusion

Gradle is a modern, flexible, and faster build tool compared to Maven.
Using the **Gradle Wrapper** ensures consistent builds across different machines.
This project demonstrates complete Gradle setup, multiple installation methods, and IDE integration in Eclipse on Windows.
