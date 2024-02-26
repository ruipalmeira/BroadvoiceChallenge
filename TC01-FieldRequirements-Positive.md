# Test case 01 - Verify when passing the correct number of characters for email, first name and last name fields.
## Description
This test cases verifies that the user inputs correct/expected data in all fields.

## Pre-requisites
* Email field, first name field and last name field, should have a minimum of six (6) characters and a maximum of thirty (30) characters each. 
* First name and last name fields cannot be empty.  
* The email, first name and last name fields should only accept alphanumeric characters.

## Steps
 * User enters a valid email address.
 * User enters a valid first name.
 * User enters a valid last name.
 * User clicks on "Save" button.

# Expected results
 * Fields are stored correctly in their respective database fields.
 * User is created in the system. 
 * User receives an email with temporary password.


