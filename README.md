# Appium TestNG POM Framework (Android)

Appium TestNG Page Object Model (POM) automation framework for Android mobile testing with Maven, CI/CD ready structure.

This repository contains a **sample Mobile Automation Testing framework** built using **Appium + TestNG + Page Object Model (POM)** with Maven.

> ⚠️ Note: This is a demo framework created for learning and portfolio purposes.  
> All credentials, app details, and test data are **dummy** (no company/client confidential data included).

---

## ✅ Tech Stack
- **Language:** Java
- **Automation Tool:** Appium (UiAutomator2)
- **Test Framework:** TestNG
- **Build Tool:** Maven
- **Design Pattern:** Page Object Model (POM)
- **Version Control:** Git / GitHub

---

## ✅ Features
- Page Object Model (POM) structure
- Reusable driver setup and teardown
- Supports parallel execution using TestNG (optional)
- Wait utilities for stable automation
- Config-driven execution using properties file
- CI/CD ready setup (Jenkins)

---

## 📁 Project Structure

```text
appium-testng-pom-framework/
 ┣ pom.xml
 ┣ testng.xml
 ┣ README.md
 ┣ src/
 ┃  ┣ main/
 ┃  ┃  ┗ java/
 ┃  ┃     ┣ base/
 ┃  ┃     ┣ pages/
 ┃  ┃     ┗ utils/
 ┃  ┗ test/
 ┃     ┣ java/
 ┃     ┃  ┗ tests/
 ┃     ┗ resources/
 ┃        ┗ config.properties
⚙️ Prerequisites
Java 11+

Maven

Android Studio (SDK)

Appium Server

Appium Inspector

Real device / Emulator

🔧 Setup
Install Appium Server

Connect Android device (USB debugging ON)

Start Appium Server

Update values in:
src/test/resources/config.properties

Example keys:

udid

platformVersion

appPackage

appActivity

▶️ How to Run Tests
Run using TestNG XML
Right click testng.xml → Run As → TestNG Suite

Run using Maven
mvn clean test
🧪 Sample Test Scenarios Covered
Login flow

Booking / form submission flow

Validations (positive/negative cases)

Navigation checks

👤 Author
Chandrakiran Yata
QA Engineer | Manual + Automation Testing
Skills: Appium | Selenium | Playwright | TestNG | API Testing | Postman | SQL
