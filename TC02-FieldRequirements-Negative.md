# Test case 02 - Verify when passing incorrect number of characters for email, first name and last name fields.
## Description
This test cases verifies that if the user inputs incorrect number of characters for some or all fields an error message is shown.

## Pre-requisites
* "Email" field, "First Name" field and "Last Name" field, with at least one of the required fields having the wrong number of characters.
* First Name and Last Name fields should not be empty.
* The "Email", "First Name" and "Last Name" fields should only accept alphanumeric characters.

## Steps
 * User enters a 4 character email address.
 * User enters a 3 character first name.
 * User enters a 20 character last name.
 * User clicks on "Save" button.

# Expected results
 * UI should display a warning, informing the user that "First Name" does not have expected number of characters.
 * User should not be created in the system.


