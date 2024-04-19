**As** a system
**I want to** get athentificated 
**So that** the application knows what user is connected

**Acceptance criteria 1:** 
**Given** the user is not authenticated
**When** he want to get authenticated to access the application
**Then** the application displays a login / password screen

**Acceptance criteria 2:** the account doesn't exist
**Given** the user types his email and his password
**When** he want to anthentificate
**Then** a new user is create and he ask the pseudo

**Acceptance criteria 3:** the account exist and information are right
**Given** the user types his email and his password
**When** he want to anthentificate
**Then** the user is connect and he see his lists

**Acceptance criteria 4:** the account exist and information are wrong
**Given** the user types his email and his password
**When** he want to anthentificate
**Then** the user isn't connect and he is still on the login page with error message