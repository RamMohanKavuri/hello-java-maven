# Hello Java Maven Project

This is a simple **Java Maven project** used to demonstrate building, testing, and deploying Java applications using Jenkins CI/CD.

---

## 🧩 Project Overview

This project contains:

* A basic **Java application** (Hello World)
* **Maven** build configuration (`pom.xml`)
* **Jenkins Pipeline** for automated build and test
* Integration with **GitHub**

---

## ⚙️ Technologies Used

* Java 11+
* Apache Maven
* Jenkins
* Git & GitHub
* Linux (Ubuntu)

---

## 🚀 Steps to Build with Maven

```bash
mvn clean install
```

This will compile the code, run tests, and package the application into a `.jar` file under the `target/` directory.

---

## 🧱 Jenkins Pipeline

Jenkins automatically pulls the latest code from GitHub and performs:

1. Maven clean and build
2. Unit testing
3. Archiving artifacts
4. Post-build actions (like deployment or reporting)

---

## 🖼️ Jenkins Build Screenshot

Below is a sample screenshot showing the successful Jenkins build:

![Jenkins Build Screenshot](screenshots/Screenshot%202025-10-31%20191110.png)

---

## 📂 Project Structure

```
hello-java-maven/
├── src/
│   ├── main/java/com/example/Hello.java
│   └── test/java/com/example/HelloTest.java
├── pom.xml
└── README.md
```

---

## 👨‍💻 Author

**Ram Mohan Kavuri**
DevOps & Cloud Enthusiast
[GitHub Profile](https://github.com/RamMohanKavuri)
