# Requirements Clarification 

## Description 
This file will hold questions I would ask to the project owner, manager or product owner, regarding conflicting specifications or why some requirements were made in the first place.

## 

#### 1. What is the reasoning behind limiting the first name and last name to a minimum of 6 characters?
    Some languages and cultures have full first and last names of different sizes. For example, my first name is Rui, and I would not be able to register with this hypothetic service because of this requirement.

#### 2. Why would you make "First Name" and "Last Name" required fields, but not the "Email" field? 
    Currently, the UI for the "Add new user" feature, does not show that "Email" is a required field, despite being critical for account activation/communication with end user.

#### 3. Since the "First Name" and "Last Name", by design, have up to 30 characters, why doesn't the respective database fields reflect that?
    As it is my understanding, the value inside the parenthesis on the VARCHAR field, is the maximum number of characters for that field. 
    If not checked, this would result in a bug, because of bad requirements or a bad database design. 

#### 4. In most countries in the world, human beings cannot be named freely and have to follow the legal terms and rules from their country of birth. Why allow alphanumeric - which for programming purposes encompasses all symbols that can be written and displayed on a screen - for this field? 
    Most countries have strict laws regarding the names their citizens can have. 
    For example, and for most countries this applies, a person cannot be named 123456, and that wouldn't be a problem regarding the requirements portrayed in this exercise.