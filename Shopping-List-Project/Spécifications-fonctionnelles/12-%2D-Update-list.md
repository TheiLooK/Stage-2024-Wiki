**As** a user
**I want to** update a list
**So that** I can change it's parameters

**Acceptance criteria 1:** I am the owner of the list and the new name isn't used and I'm connected
**Given** the user types a new list name that isn't used
**When** the user update the list
**Then** the list is update with the new name and she's updated in the DB

**Acceptance criteria 2:** I am the owner of the list and the new name already exists
**Given** the user types a new list name that already exists
**When** the user update the list
**Then** the list can't be update with this new name

**Acceptance criteria 1:** I am the owner of the list and the new name isn't used and I'm not connected
**Given** the user types a new list name that isn't used
**When** the user update the list
**Then** the list is update with the new name and she isn't updated in the DB