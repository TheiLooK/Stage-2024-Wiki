**As** a system
**I want to** synchronize items
**So that** The data is safely stored and available to other users in case of shared lists

**Acceptance criteria 1:** 
**Given** user download the app
**When** the data is synchronized
**Then** every default item are put in the local storage

**Acceptance criteria 2:** 
**Given** item already exist in the DB no in local
**When** the data is synchronized
**Then** the item is added in the local storage

**Acceptance criteria 3:** 
**Given** item already exist in local no in DB
**When** the data is synchronized
**Then** the item is pu in the DB

**Acceptance criteria 4:** 
**Given** item already exist (same name) in local and DB
**When** the data is synchronized
**Then** the item from local storage are replaced by the DB item

**Acceptance criteria 5:** 
**Given** user hasn't internet connection
**When** the data is synchronized
**Then** the user has an alert and items are save only in local storage