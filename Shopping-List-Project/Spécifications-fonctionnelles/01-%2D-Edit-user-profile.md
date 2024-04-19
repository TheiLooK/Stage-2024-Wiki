**As** a user
**I want to** edit my profile
**So that** the user can be edit his profil

**Acceptance criteria 1:** the new nickname isn't taken
**Given** the user types his new nickname
**When** he want to edit his profil
**Then** the user success to edit his nickname

**Acceptance criteria 2:** the new nickname is already taken
**Given** the user types his new nickname
**When** he want to edit his profil
**Then** the user can't edit his nickname

**Acceptance criteria 3:** the new password isn't the old one
**Given** the user types his new password
**When** he want to edit his profil
**Then** the user success to edit his password

**Acceptance criteria 4:** the new password is the old one
**Given** the user types his new password
**When** he want to edit his profil
**Then** the user can't edit his password and gets an error message

**Acceptance criteria 5:** 
**Given** the new passwword confirmation is different than the new password
**When** he want to edit his profil
**Then** the user can't edit his password and gets an error message

**Acceptance criteria 6:** 
**Given** the user isn't connected
**When** he want to edit his profil
**Then** the user can only connect or create an account