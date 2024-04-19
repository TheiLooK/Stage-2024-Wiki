As a user
I want to update an item in the list
So that I can modify its properties

Acceptance criteria 1:
**Given** the user select different quantity for archive and unarchived item
**When** the user updates the item
**Then** the system change the quantity 

Acceptance criteria 2 set quantity to 0:
**Given** the user select quantity 0
**When** the user update the item
**Then** the item is deleted
