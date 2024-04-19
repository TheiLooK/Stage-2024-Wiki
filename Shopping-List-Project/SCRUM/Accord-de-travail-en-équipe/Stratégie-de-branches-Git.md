**- Préfixer les commentaires de commits par l'id de la tache Jira**

**- Keep a high quality, up-to-date main branch.**

**- Use feature or hotfix branches for all new features and hotfixes.**
Feature branch naming convention: feature/[jira_item_id]-[work_item_name]
Feature branches are deleted after merge

Hotfix branch naming convention: hotfix/[jira_item_id]-[work_item_name]

**- Push on feature branch at least once a day**
Feature branch does not need to be stable

**- Use release branches for every release.**
Release branch naming convention: release/ShoppingList-[major]_[minor]_[bugfix]

**- Merge branches into the main branch using pull requests.**
Code in the pull request must comply wit the definition of done

See https://learn.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance?view=azure-devops


<IMG  src="https://dholmes.co.uk/img/git-parent-feature-branch.png"  alt="The Benefits of Using a Feature-Based Branching Strategy | …"/>


