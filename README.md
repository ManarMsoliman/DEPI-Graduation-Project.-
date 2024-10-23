# DEPI-Graduation-Project
## Selenium Test Automation Project
This project automates the process of navigating to the OrangeHRM web application, logging in with valid credentials, performing administrative tasks such as creating and deleting users, navigating the recruitment menu, and managing leave entitlements. The scripts are written in Java using Selenium WebDriver and TestNG framework.

##Project Structure
src/main/java/org/example: Contains the main classes for the project, including LoginPage, DashBoard, AdminPage, RecruitmentPage, and LeavePage.

src/test/java/org/example/Test.java: The test class containing the test methods for validating the various functionalities of the OrangeHRM application.

##Prerequisites
Java Development Kit (JDK-17)

Maven: Used for managing project dependencies.

ChromeDriver: Required for running tests on the Chrome browser.

##Test Scenarios
1.Login with Valid Credentials

Description: Verifies that a user can log in with valid credentials.

Assertions: Confirms the URL changes to the dashboard page upon successful login and verifies the presence of the "Dashboard" text.

2.Navigate to Admin Menu

Description: Validates navigation to the Admin menu after logging in.

Assertions: Checks that the current URL contains "/admin" and verifies the presence of "System Users" text.

3.Create a New Admin User

Description: Automates the creation of a new admin user.

Assertions: Verifies the user is created successfully and can be found using the search functionality.

4.Delete the Created User

Description: Verifies the deletion of the previously created user.

Assertions: Confirms the user is removed successfully and no records are found upon searching for the user.

5.Navigate to Recruitment Menu

Description: Validates navigation to the Recruitment menu.

Assertions: Confirms the URL changes appropriately.

6.Search for a Payroll Administrator Vacancy

Description: Verifies the search functionality in the Recruitment menu.

Assertions: Checks that the search results are correct and the vacancy can be deleted.

7.Add Leave Entitlement

Description: Automates the process of adding leave entitlement.

Assertions: Verifies the leave entitlement is added successfully.
