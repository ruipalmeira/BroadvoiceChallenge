# User Creation Window - Test Scenario

## Description
This document contains the framework for testing the "Add new user" feature present in the "User Creation Window".
This scenario is composed of 5 test cases.

## Features
- User should be able to create new account - "Add new user".
- After login, Home Page should display First Name, Last Name and Email address.

## Test Cases
1. Verify when passing the correct number of characters for email, first name and last name fields. | TC01-FieldRequirements-Positive.md
2. Verify when passing incorrect number of characters for email, first name and last name fields. | TC02-FieldRequirements-Negative.md
3. Verify when passing empty fields for first name or last name fields. | TC03-FieldRequirements-Empty.md
4. Testing home page. | TC04-HomePageRequirements.md
5. Database requirements | TC05-DataBaseRequirements.md 