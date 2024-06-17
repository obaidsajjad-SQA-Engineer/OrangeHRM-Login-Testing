# Orange HRM Login Page Testing Project

This project includes comprehensive testing for the Orange HRM login page. The testing encompasses 11 test cases, with 4 positive and 7 negative scenarios, based on a self-created hypothetical requirement document. The goal is to ensure robust validation of the login functionalities.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Test Cases](#test-cases)
    - [Positive Test Cases](#positive-test-cases)
    - [Negative Test Cases](#negative-test-cases)
3. [Screenshots](#screenshots)
4. [Conclusion](#conclusion)

## Project Overview

This project was created to test the login functionalities of the Orange HRM system. A total of 11 test cases were executed, covering various positive and negative scenarios to validate both correct and incorrect user inputs.

## Test Cases

### Positive Test Cases

1. **PTC-001: Verify login with valid credentials**
    - **Steps:** Enter valid username and password
    - **Data:** Username: Admin, Password: admin123
    - **Priority:** P0
    - **Expected Result:** User successfully logins to the dashboard
    - **Actual Result:** User successfully logins to the dashboard
    - **Status:** Pass

2. **PTC-002: Verify login page UI**
    - **Steps:** Check if all login page elements are displayed correctly
    - **Data:** N/A
    - **Priority:** P1
    - **Expected Result:** All UI elements are displayed correctly
    - **Actual Result:** All UI elements are displayed correctly
    - **Status:** Pass

3. **PTC-003: Verify password masking**
    - **Steps:** Ensure the password is masked when typing
    - **Data:** Password: admin123
    - **Priority:** P3
    - **Expected Result:** Password characters are masked
    - **Actual Result:** Password characters are masked
    - **Status:** Pass

4. **PTC-004: Verify login page title**
    - **Steps:** Check the title of the login page
    - **Data:** N/A
    - **Priority:** P3
    - **Expected Result:** Title is "OrangeHRM"
    - **Actual Result:** Title is "OrangeHRM"
    - **Status:** Pass

### Negative Test Cases

1. **NTC-005: Verify login with invalid username**
    - **Steps:** Enter an invalid username and valid password
    - **Data:** Username: invalidUser, Password: admin123
    - **Priority:** P0
    - **Expected Result:** Error message: "Invalid credentials"
    - **Actual Result:** Error message: "Invalid credentials"
    - **Status:** Pass

2. **NTC-006: Verify login with invalid password**
    - **Steps:** Enter a valid username and invalid password
    - **Data:** Username: Admin, Password: wrongPass123
    - **Priority:** P0
    - **Expected Result:** Error message: "Invalid credentials"
    - **Actual Result:** Error message: "Invalid credentials"
    - **Status:** Pass

3. **NTC-007: Verify login with empty fields**
    - **Steps:** Try to login without entering username and password
    - **Data:** Username: (empty), Password: (empty)
    - **Priority:** P0
    - **Expected Result:** Error message: "Required" for both fields
    - **Actual Result:** Error message: "Required" for both fields
    - **Status:** Pass

4. **NTC-008: Verify login with special characters**
    - **Steps:** Enter special characters in username and password
    - **Data:** Username: !@#$%^, Password: !@#$%^
    - **Priority:** P1
    - **Expected Result:** Error message: "Invalid credentials"
    - **Actual Result:** Error message: "Invalid credentials"
    - **Status:** Pass

5. **NTC-009: Verify login with excessive length**
    - **Steps:** Enter a username and password exceeding the maximum length allowed
    - **Data:** Username: 256+ char's, Password: 256+ char's
    - **Priority:** P3
    - **Expected Result:** Error message or truncation handling
    - **Actual Result:** Error message or truncation handling
    - **Status:** Pass

6. **NTC-010: Verify login with HTML tags**
    - **Steps:** Enter HTML tags in the username and password fields
    - **Data:** Username: <b>Admin</b>, Password: <b>admin123</b>
    - **Priority:** P3
    - **Expected Result:** Error message: "Invalid credentials"
    - **Actual Result:** Error message: "Invalid credentials"
    - **Status:** Pass

7. **NTC-011: Verify login with spaces only**
    - **Steps:** Enter spaces in the username and password fields
    - **Data:** Username: " ", Password: " "
    - **Priority:** P3
    - **Expected Result:** Error message: "Invalid credentials"
    - **Actual Result:** Error message: "Invalid credentials"
    - **Status:** Pass

## Screenshots

1. **Screenshot 1: Excel Screenshot**
    ![screenshots/1.png](#)

2. **Screenshot 2: Invalid Username Error**
    ![screenshots/2.png](#)

3. **Screenshot 3: Password Masking**
    ![screenshots/3.png](#)

4. **Screenshot 4: Login Page UI**
    ![screenshots/5.png](#)

5. **Screenshot 4: Login Page UI**
    ![screenshots/5.png](#)

## Conclusion

This project successfully validates the login functionalities of the Orange HRM system through a series of well-defined positive and negative test cases. All tests have been executed with the expected results, ensuring a robust and reliable login process.
