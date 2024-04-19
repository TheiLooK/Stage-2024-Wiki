**As** a system
**I want to** synchronize list items
**So that** The data is safely stored and available to other usrs in case of shared lists

**Acceptance criteria 1:** 
**Given** list already exist in the DB no in local
**When** the data is synchronized
**Then** the list is synchronized with items from the DB

**Acceptance criteria 3:** 
**Given** list already exist in local no in DB
**When** the data is synchronized
**Then** the list is synchronized with items from the local storage

**Acceptance criteria 4:** 
**Given** list already exist (same name) in local and DB
**When** the data is synchronized
**Then** the list items from DB are replaced by the local items

**Acceptance criteria 5:** 
**Given** user hasn't internet connection
**When** the data is synchronized
**Then** the user has an alert and list items are save only in local storage. When the internet access is back everything is synchronized.