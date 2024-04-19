**As** a user
**I want to** create a new list
**So that** I can add items

**Acceptance criteria 1:** the user already have a list with the same name
**Given** the user types a list name that already exists
**When** the user create a new list
**Then** an error is showed and the new list can't be create with this name

**Acceptance criteria 2:** the user doesn't have a list with the same name and he is connected
**Given** the user types a list name that isn't used (max 50 characters)
**When** the user create a new list
**Then** the new list is created and she's insert in the DB

**Acceptance criteria 3:** the user doesn't have a list with the same name and he isn't connected
**Given** the user types a list name that isn't used (max 50 characters)
**When** the user create a new list
**Then** the new list is created and she isn't insert in the DB