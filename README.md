# /test-planning-demo

This branch will demonstrate basic software testing competencies of Myron Dizon. Herewith lies a demonstration of his test case writing, test design, and test planning. 

----

# Scope
This branch provides a demonstration of testing activities on a public web application from Swag Labs: https://www.saucedemo.com/

# Approach
The test approach for this effort would be creating test cases for the login and page navigation features of the web app. The test cases will be written in the Gherkin format. 

# Test Objectives
The test objective for this effort is to test logging in into the Swag Labs web application. As such, the user should be able to:
- valid user should be able to login successfully; and
- clicking the hamburger icon should show the correct menu options.

# Test Suites
- [/login page](https://github.com/myrondizon/test-planning-demo/blob/main/login-tests.txt)
- [/navigation](https://github.com/myrondizon/test-planning-demo/blob/main/navigation-tests.txt)

----

# Bug Reports

### *Title*: X icon in the login input field looks clickable
*Description*: When the validation prompts appear in the input fields, the user might think that the user can click the x buttons to close the red validation prompts. The only clickable x button is at the red banner below the password input field.

#### *Steps to replicate*:
1. go to login page
2. input invalid username
3. input invalid password
4. click login button
5. click the x button in the input fields

*actual result*: the x-icon looks clickable
![alt text](https://raw.githubusercontent.com/myrondizon/test-planning-demo/main/bug-report-picture(1).jpg "bug-report-picture(1).jpg")

### *Title*: Error message text does not fit inside error container
*Description*: When user inputs username and clicks login button, then error message appears. Yet the error message seems to overflow its container

#### *Steps to replicate*:
1. go to login page
2. input invalid username
3. click login button
4. click the x button in the input fields

*actual result*: the error message overflows its container
![alt text](https://raw.githubusercontent.com/myrondizon/test-planning-demo/main/bug-report-picture(2).jpg "bug-report-picture(2).jpg")

### *Title*: Clicking navigation menu option does not redirect to correct page
*Description*: When user opens hamburger menu and clicks "About", then user is directed to swag labs page

#### *Steps to replicate*:
1. login as existing user
2. click hamburger icon, side menu should open
3. click About

*actual result*: the user is redirected outside of the app to Swag Lab's page

Video capture: [video_capture.mp4](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
