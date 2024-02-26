# Test case 03 - Verify when passing empty fields for first name or last name fields.
## Description
This test cases verifies that the system warns the user when trying to submit empty required fields.

## Pre-requisites
"First Name" or "Last Name" fields are empty.

## Steps
 * User inputs an accepted "Email" string for the "Email" field.
 * User inputs an accepted "First Name" string for the "First Name" field.
 * User inputs an empty "Last Name" string for the "Last Name" field.
 * User clicks on "Save" button.

# Expected results
 * UI should display a warning, informing the user the required field are empty and cannot be empty.
 * User should not be created in the system.


