# GoogleSearchTest Project

This project is a simple example of using Selenium WebDriver with Java to automate a Google search and verify some features on the search results page. 
The project demonstrates how to interact with web elements and perform basic web automation tasks.

## Prerequisites

- JDK 18
- Selenium 3.14
- EdgeDriver (latest version)

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hadeel404/GoogleSearchTest.git
  ## Download EdgeDriver:
  Ensure that EdgeDriver executable is placed at the specified path in the code (e.g., D:/tools/msedgedriver.exe).
 ## Configure your project in Eclipse:
- Open Eclipse and import the project.
- Add the Selenium JAR files to the project's build path.
- ## Running the Test
- Open the SeleniumTest.java file in Eclipse.
- Run the main method to execute the test.
- ## The test will:
- Open Google.Perform a search for "Selenium WebDriver".
- Verify that the page title contains the search keyword.
- Check that search results are displayed.
- Verify that the Selenium official website is found in the results.
- Click on the first search result and print the new page title.
- ## Project Structure
-src/SeleniumTest.java
