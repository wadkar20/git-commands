# git-commands

# basic git commands:

| Command      | Description                                       | Example                                      |
| ------------ | ------------------------------------------------- | -------------------------------------------- |
| `git init`   | Create a new Git repo                             | `git init`                                   |
| `git clone`  | Download (clone) a repo from remote (like GitHub) | `git clone https://github.com/user/repo.git` |
| `git status` | Show the current status (changes, staged files)   | `git status`                                 |
| `git add`    | Stage files to be committed                       | `git add .`                                  |
| `git commit` | Save changes to local repo                        | `git commit -m "Added feature X"`            |
| `git push`   | Upload local commits to remote repo               | `git push origin main`                       |
| `git pull`   | Download and merge changes from remote            | `git pull origin main`                       |
| `git fetch`  | Download changes (no merge)                       | `git fetch origin`                           |

# branching and merging :

| Command        | Description                                | Example                  |
| -------------- | ------------------------------------------ | ------------------------ |
| `git branch`   | List or create branches                    | `git branch new-feature` |
| `git checkout` | Switch branches                            | `git checkout main`      |
| `git switch`   | Modern way to switch branches              | `git switch main`        |
| `git merge`    | Merge changes from another branch          | `git merge dev`          |
| `git rebase`   | Reapply commits on top of another base tip | `git rebase main`        |

# remote repository :

| Command              | Description                | Example                                                  |
| -------------------- | -------------------------- | -------------------------------------------------------- |
| `git remote -v`      | Show connected remotes     | `git remote -v`                                          |
| `git remote add`     | Add a new remote repo      | `git remote add origin https://github.com/user/repo.git` |
| `git remote set-url` | Change the URL of a remote | `git remote set-url origin <new-url>`                    |


# clean-up & reset :

| Command         | Description               | Example                   |
| --------------- | ------------------------- | ------------------------- |
| `git reset`     | Unstage or revert changes | `git reset HEAD file.txt` |
| `git clean`     | Remove untracked files    | `git clean -fd`           |
| `git stash`     | Save changes temporarily  | `git stash`               |
| `git stash pop` | Restore stashed changes   | `git stash pop`           |

# logs & history :

| Command    | Description              | Example                  |
| ---------- | ------------------------ | ------------------------ |
| `git log`  | View commit history      | `git log`                |
| `git diff` | Show file changes        | `git diff`               |
| `git show` | Show details of a commit | `git show <commit-hash>` |

# devops specifics use cases :

| Use Case                                           | Command                                       |
| -------------------------------------------------- | --------------------------------------------- |
| CI/CD config versioning                            | `git push origin main` (to trigger pipelines) |
| Rollback to previous version                       | `git checkout <commit-id>`                    |
| Track infrastructure code (Terraform, Dockerfiles) | `git add`, `commit`, `push`                   |
| Manage multiple environments                       | `git branch dev`, `git branch prod`           |
| Automate with Git Hooks                            | `.git/hooks/pre-commit`, etc.                 |


# git init - initialize the repo
# git status - see trcked and untracked files
# git commit -m - 
# git remote -v -
# git remote add origin url
# git push -
# git revert - changes undo
# git rebase - files in sync
# branches - 
# git branch -
# git checkout - see which repose we are
# git merge -Merges changes from one branch into the current branch.




















