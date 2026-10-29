# Casio India UI Testing

## Project Description

A software-testing coursework project exploring the Casio India website with manual testing artifacts and Selenium UI automation. The repository contains page-object classes and TestNG tests for several website areas.

## Tech Stack Used

Java, Selenium WebDriver, TestNG and Maven. The Maven configuration targets Java 8 and declares Selenium 4.24.0 and TestNG 7.1.0.

## Setup & Installation

1. Install a compatible JDK, Maven and Google Chrome. The included homepage test uses ChromeDriver; browser and driver compatibility may need adjustment.
2. Clone the repository and enter its directory:

   ```bash
   git clone https://github.com/abhijeet2829/Casio-India-E2E-testing.git
   cd Casio-India-E2E-testing
   ```

3. Inspect `testng.xml` and the test classes for their target URLs and browser setup, then run:

   ```bash
   mvn test
   ```

The project targets a live external website, so selectors, browser setup and site changes can affect execution.

## Key Features

- Homepage navigation, search and product/category visibility.
- Page objects and tests for product details, contact and footer areas.
- Manual test plan, scenarios, cases, bug report, mind map and summary report in [Manual testing deliverables](./Manual%20testing%20deliverables/).

