# Casio India UI Testing

A software-testing coursework project exploring the Casio India website with manual testing artifacts and Selenium UI automation. The repository contains page-object classes and TestNG tests for several website areas.

## Scope

- Homepage navigation, search and product/category visibility.
- Page objects and tests for product details, contact and footer areas.
- Manual test plan, scenarios, cases, bug report, mind map and summary report in [Manual testing deliverables](./Manual%20testing%20deliverables/).

## Technology

Java, Selenium WebDriver, TestNG and Maven. The Maven configuration targets Java 8 and declares Selenium 4.24.0 and TestNG 7.1.0.

## Setup and execution

1. Install a compatible JDK, Maven and a browser supported by the project's WebDriver configuration.
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

## Test evidence and limitations

Test code is under [src/test](./src/test/java/com/pom/tests/) and page objects under [src/main](./src/main/java/com/pom/Pages/). The checked-in `target/surefire-reports` files are historical, not evidence of a current passing suite; one saved May 2025 report records a failed test. The suite has not been rerun as part of this documentation update.

This is a learning project, not an official Casio product or production automation framework.
