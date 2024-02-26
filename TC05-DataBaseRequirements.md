# Test case 05 - Database requirements.
## Description
This test cases verifies that the database has correct field types and size

## Pre-requisites
* Database exists;
* User table has 3 fields: 
  * "Email" of type `VARCHAR(30)`.
  * "FirstName" of type `VARCHAR(10)`.
  * "LastName" of type `VARCHAR(12)`.

## Steps
* User inputs a string for "First Name" that has more characters than the database type.

# Expected results
* Should notify product owner or project manager of the conflict in requirements.   
In this case this is something that shouldn't pass the analysis phase in the SDLC. But anyway, the expected results should be: 
  * While the specifications tell us the "First Name" can be up to 30 characters long, the type chosen for the database field does not support that.
  * User creation should fail, because the entry for the new user cannot be created in the database.


