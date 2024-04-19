As a user
I want to remove an item from the list
So that I don't see it in the list anymore

Acceptance criteria 1 click on delete:
**Given** the item exists in the list user is connected
**When** the user click on the delete button and confirms
**Then** the item is deleted in the list and in the DB

Acceptance criteria 2 click on delete: 
**Given** the item exists in the list user isn't connected
**When** the user click on the delete button and confirms
**Then** the item is deleted only in the list