**As** a user
**I want** to add an item in the list
**So that** I see it my list

Acceptance criteria 1: default add new item (max 50 characters)
**Given** the user types an item that does not exist in the system
**When** the add the item to the list
**Then** the new item is created with the first letter in uppercase and added to the list and with no extra space caracter

Acceptance criteria 2: item exist in the system
**Given** the user types an item that already exists
**When** the user selects the item
**Then** the existing item is added to the list

Acceptance criteria 3: item exist in the list
**Given** the user types an item that item exist in the list
**When** the user selects the item
**Then** the systment alert th user. He can choose to cancel or increment the quantity

Acceptance criteria 4: autocomplete
**Given** the user starts typing a name of an item and user is connected
**When** the user has provided at least 3 letters
**Then** the system provide a list of all existing items containing these letters (not case sensitive) sorted alphabetical

Acceptance criteria 5: unarchive item
**Given** the item is in the list and unarchived
**When** the user click on the shopping cart
**Then** the item is unarchived and added to the list

Acceptance criteria 6: item exist in the system, is in the list but is archived
**Given** the user types an item that already exists in the list and is archived
**When** the user selects the item
**Then** the existing item is unarchived (so it's added to the list)
