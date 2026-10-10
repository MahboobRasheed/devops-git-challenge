PROOF_OF_WORK.md
# PROOF OF WORK — DevOps Git Challenge

## Git Commit History

35b93a2 (HEAD -> main, origin/main) Merge pull request #1 from MahboobRasheed/development
bece984 (origin/development, development) fix: resolved merge conflict
d0ba293 (origin/staging, staging) fix: staging label
17098d6 feat: customize development deployment
e2d644b feat: initial commit with deploy script

 Reflection Questions
Q1: Difference between Git and GitHub

Git is a distributed version control system that tracks changes in source code and manages local commit history. It allows developers to create branches, commit changes, and merge code without an internet connection. GitHub is a cloud-based platform that hosts Git repositories and supports team collaboration. It provides Pull Requests, code reviews, and remote repository management.

 Q2: Working Directory, Staging Area, and Local Repository

The Working Directory contains the project files that developers create or modify. The Staging Area, also called the Git index, stores the selected changes prepared for the next commit. The Local Repository stores committed versions of the project and its history inside the .git directory. Changes typically move from the Working Directory to the Staging Area using git add and then to the Local Repository using git commit.

Q3: Difference between git stash pop and git stash apply

Both git stash pop and git stash apply restore saved changes to the working directory. The git stash pop command normally removes the stash entry after the changes are successfully applied. The git stash apply command restores the changes but keeps the stash entry for future use. If conflicts occur during a pop operation, Git usually retains the stash so the changes are not lost.

 Q4: Difference between git fetch and git pull

The git fetch command downloads new commits and remote reference updates without automatically merging them into the current branch. It allows developers to inspect remote changes before integrating them. The git pull command first fetches remote updates and then integrates them into the current branch using merge or rebase, depending on the configuration. As a result, git pull can change local working files and may cause merge conflicts.