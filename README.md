# Make my Trip Automation using Selenium

This Selenium project is a demonstration of automating web interactions using the Selenium WebDriver for Java. It simulates a scenario where a user searches for train tickets on MakeMyTrip's railway booking page.

## Project Overview

The project consists of the following main components:

1. **SeleniumProjectTest.java**: This file contains the Java code implementing the Selenium WebDriver test automation. It launches the Chrome browser, navigates to the MakeMyTrip railway booking page, performs various interactions like selecting source and destination cities, choosing travel dates and class, and finally clicking the search button.

## Setting Up the Project

### Prerequisites
- Java Development Kit (JDK) installed
- Selenium WebDriver for Java installed
- ChromeDriver compatible with Chrome version 114 downloaded

### Steps to Run the Project
1. **Set up ChromeDriver**: Download the ChromeDriver compatible with Chrome version 114 from the official website or any trusted source. Set the system property in the code with the path to your ChromeDriver.

2. **Import the Project**: Import the project into your preferred Java IDE.

3. **Ensure Selenium WebDriver is Configured**: Make sure you have configured Selenium WebDriver for Java in your project's build path or using a dependency management tool like Maven or Gradle.

4. **Run the SeleniumProjectTest.java class**: Execute the `main` method in the `SeleniumProjectTest` class. This will launch the Chrome browser, navigate to the MakeMyTrip railway booking page, perform the necessary actions, and close the browser after completing the test.

## Additional Notes

- **Chrome Version 114**: Ensure that you have Chrome version 114 installed on your system to run the ChromeDriver successfully. You can download older versions of Chrome from the official Chrome archive.

- **Thread.sleep()**: The use of `Thread.sleep()` is included for demonstration purposes and to handle synchronization issues. In production-level code, it's recommended to use explicit waits (`WebDriverWait`) for better synchronization.

- **Element Locators**: The project uses various methods to locate elements on the webpage, including XPath and CSS selectors. It's essential to choose robust locators to ensure the stability of the test scripts.

- **Error Handling**: Add appropriate error handling and logging mechanisms to make the automation scripts more robust and maintainable.

## Conclusion

This Selenium project provides a basic framework for automating web interactions using Selenium WebDriver in Java. It can serve as a starting point for building more complex test automation suites or integrating with continuous integration (CI) pipelines for web applications.



https://github.com/Ammaar19/Makemytrip-Automation-Software/assets/117352598/2918c144-9932-4d7b-a27e-6a3515cd9216

