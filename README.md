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
- /login page
- /navigation

----

# Bug Report
*Title*: X icon in the login input field looks clickable
*Description*: When the validation prompts appear in the input fields, the user might think that the user can click the x buttons to close the red validation prompts. The only clickable x button is at the red banner below the password input field.

*Steps to replicate*:
1. go to login page
2. input invalid username
3. input invalid password
4. click login button
5. click the x button in the input fields

*actual result*: the x-icon looks clickable

