**As** a user
**I want** to delete a list
**So that** it's removed from my list of shoppping lists

**Acceptance criteria 1:** delete a list than you are the owner
**Given** the user select a list than he is owner
**When** the user delete the list
**Then** the list is delete in the database and if any other is accessing the list at the same time he gets an error message

**Acceptance criteria 2:** delete a list than you are assign
**Given** the user select the list that he is assign
**When** the user delete the list
**Then** the user is unassign in the list but she still exist for other users