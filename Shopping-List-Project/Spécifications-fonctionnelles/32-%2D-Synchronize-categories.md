**As** a system
**I want to** synchronize categories
**So that** The data is safely stored and available to other users in case of shared lists

**Acceptance criteria 1:** 
**Given** user download the app
**When** the data is synchronized
**Then** every default categories are put in the local storage

**Acceptance criteria 2:** 
**Given** category already exist in the DB no in local
**When** the data is synchronized
**Then** the category is added in the local storage

**Acceptance criteria 3:** 
**Given** category already exist in local no in DB
**When** the data is synchronized
**Then** the category is pu in the DB

**Acceptance criteria 4:** 
**Given** category already exist (same name) in local and DB
**When** the data is synchronized
**Then** the category from local storage are replaced by the DB category