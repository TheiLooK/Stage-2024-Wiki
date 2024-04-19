As a user
I want to assign a user to my list
So that I can share the list with the user

Acceptance criteria 1: user already exists and user are connected
Given that the user email already exists in the system
When I assign a the user to the list
Then the user is assigned and he can manage the items in the list

Acceptance criteria 2: user does not exists and user are connected
Given that the user email does not exist in the system
When I assign a the user to the list
Then the system can't share the list because the user don't exist

Acceptance criteria 3: user aren't connected
Given that the user email does not exist in the system
When I assign a the user to the list
Then the system can't share the list because the user aren't connect