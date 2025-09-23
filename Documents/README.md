
# 📱 **QueryCart Mobile Test Automation Project**
This project is designed to test the **mobile application** of the [QueryCart](https://querycart.com/) website on a **Pixel 8 Pro** device running **Android 14.0**. The tests are performed using the **Cucumber** framework with **Appium** automation tool, and the results are reported through **Allure Reports**..
---


## 🚀 **Technologies and Tools Used**
| **Tool / Technology**  | **Description**                                           |
|------------------------|-----------------------------------------------------------|
| **Java (OpenJDK 17)**  | The programming language for writing test scenarios       |
| **Cucumber**           | BDD (Behavior Driven Development) approach                |
| **Appium 2.0**         | Mobile application automation tool                        |
| **Selenium WebDriver** | UI interactions (mobile browser)                          |
| **TestNG**             | Test management                                            |
| **Allure**             | Reporting tool                                            |
| **Maven**              | Dependency management and project configuration           |
| **Android Emulator**   | Pixel 8 Pro / Android 14.0                                |
---

## 📱 **Tested Platform**
- **Site:** [QueryCart](https://querycart.com/)
- **Device:** Pixel 8 Pro.etc
- **Android Version:** 14.0
- **Browser (Mobile Web Test):** Chrome / WebView
- **Test Type:** Mobile Web Automation Test
---

## 📁 **QueryCartMobileTest Project Structure**
The project structure is as follows:
```

QueryCartMobileTest/


│   ├── Apps/
│   ├── Documents/
│   ├── logs/
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── config/
│   │       ├── drivers/
│   │       ├── pages/
│   │       ├── pagesBrowser/
│   │       ├── utilities/
│   │       ├── resources/
                ├── configuration.properties/
│   │           └── log4j2.xml/
│   ├── test/
│   │   └── java/
│   │       ├── stepdefinitions/
│   │       └── runners/
├── resources/
│   ├── features/
│   └── config.properties
├── pom.xml


```
---
## 🧭 **Test Coverage (Backlog)**
The tests cover the following user stories (examples):
- ✅ **US_001** - User can access the homepage
- ✅ **US_007** - User can register
- ✅ **US_008** - User can log in
- ✅ **US_012** - User can view product details
- ✅ **US_027** - Cart management
  ... and more than 25 user stories.
  For detailed backlog information, check the **`docs/backlog.md`** or **`features/`** folder.
---

 ## **  Sprint Scenario   **

- ✅ As a registered user,
- ✅ I want to log in to the QUERYCART mobile application,
- ✅ easily find the product I want,
- ✅ add the product to my cart,
- ✅ successfully complete the payment process,
- ✅ and finally log out of the application securely.









