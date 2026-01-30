# Git Practical

**Name:** Hem Gajjar
**Mentor:** Nilesh Prajapati
**Git Repository Link:** *<add link here>*

---

## 1. Create a new repository with a template

* A new Git repository is created using a predefined template.
* Templates help maintain a consistent project structure, files (README, .gitignore), and initial configuration across projects.

---

## 2. Initialize git-flow

* `git-flow` is initialized to standardize the branching strategy.
* It creates branches like `main`, `develop`, `feature`, `release`, and `hotfix`.
* This ensures clean separation between development, features, and releases.

---

## 3. Create a feature branch for project setup with proper Zoho task ID

* A new feature branch is created from `develop`.
* The branch name follows the required Zoho task format (e.g., `TP2-T1299_Project_Setup`).
* This helps in tracking work against tasks and improves collaboration.

---

## 4. Add a commit message hook to the repository

* A Git hook is added to enforce commit message rules.
* The hook ensures every commit includes a valid Zoho task ID.
* This prevents improper or untraceable commits.

---

## 5. Perform multiple commits in the new branch

* Multiple commits are made while working on the feature branch.
* Each commit represents a small, meaningful change.
* This improves history readability and easier debugging.

---

## 6. Push branches to the remote repository

* The local feature branch is pushed to the remote repository.
* This allows other developers to view and review the changes.
* It also serves as a backup of local work.

---

## 7. Perform squash operation

* Multiple commits are squashed into a single commit.
* Squashing creates a clean and concise commit history before merging.
* It is commonly done during pull request preparation.

---

## 8. Create a Pull Request (PR) to develop branch

* A PR is created from the feature branch to `develop`.
* This enables code review and discussion before merging.
* Ensures code quality and team collaboration.

---

## 9. Create another branch from develop while previous PR is under review

* A new branch is created from `develop` without waiting for the first PR to merge.
* This allows parallel development and avoids blocking work.

---

## 10. Commit changes in the new branch and push

* New changes are committed to the current branch.
* The branch is pushed to the remote repository.
* Work continues independently of the earlier PR status.

---

## 11. Previous PR gets merged into develop

* The earlier PR is approved and merged into `develop`.
* `develop` now contains the latest approved changes.

---

## 12. Create a PR ensuring branch is up to date with develop

* The current branch is updated (merge/rebase) with the latest `develop`.
* A new PR is created targeting `develop`.
* This avoids conflicts and ensures smooth merging.

---

## 13. Add version tag for new build release

* A version tag is added to the release commit (e.g., `v1.0.0`).
* Tags help track builds and releases.
* Useful for rollback and release management.

---

## 14. Create 3rd and 4th branches from develop

* Two new branches are created from `develop`.
* Readme changes are committed and pushed in the 3rd branch.

---

## 15. Cherry-pick commit from 3rd branch to 4th branch

* The commit from the 3rd branch is cherry-picked into the 4th branch.
* This applies a specific change without merging entire branch history.

---

## 16. Change commit message in the 4th branch

* The commit message is modified using amend or interactive rebase.
* Helps correct or improve commit message clarity.

---

## 17. Add 3 commits in 4th branch and delete the last commit

* Three new commits are added sequentially.
* The last commit is removed using reset or rebase.
* Demonstrates history rewriting and cleanup techniques.

---

### Conclusion

This practical demonstrates hands-on experience with Git workflows including branching, hooks, pull requests, tagging, cherry-picking, and history management following industry standards.
