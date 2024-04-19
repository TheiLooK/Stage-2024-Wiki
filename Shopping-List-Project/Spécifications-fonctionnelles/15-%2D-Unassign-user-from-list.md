As a user
I wan to unassign an user to my list
So that I can share the list with the user

Acceptance criteria 1: other user stay
Given that other user will stay in the list
When I unassign user from list
Then the user is unassigned and other user can continue to use the list

Acceptance criteria 2: last user to unassign
Given that is the last user to unassign to the list
When I unassign user from list
Then the user is unassigned and the list is delete because no one user will stay in