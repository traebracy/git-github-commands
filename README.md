# git-github-cmds

## git setup 

| command              | what it does                              |
| -------------------- | ----------------------------------------- |
| `git init`           | initializes a git repository              |
| `git status`         | shows the current state of the project    |
| `git branch`         | shows the branches in the repository      |
| `git branch -M main` | renames the current branch to `main`      |

---

## staging & committing 

| command                          | what it does                        |
| -------------------------------- | ----------------------------------- |
| `git add .`                      | stages all changed files            |
| `git add file-name`              | stages one specific file            |
| `git commit -m "commit message"` | saves staged changes with a message |

---

## github remote process

| command                                | what it does                                          |
| -------------------------------------- | ----------------------------------------------------- |
| `git remote add origin repository-url` | connects a local project to a github repository       |
| `git remote -v`                        | shows the connected github remote                     |
| `git push -u origin main`              | pushes the `main` branch to github for the first time |
| `git push`                             | pushes new commits to github                          |
| `git pull`                             | pulls the newest changes from github                  |

---

## cloning

| command                    | what it does                                 |
| -------------------------- | -------------------------------------------- |
| `git clone repository-url` | copies a github repository onto the computer |

---

## branching

| command                                      | what it does                                    |
| -------------------------------------------- | ----------------------------------------------- |
| `git checkout -b branch-name`                | creates a new branch and switches to it         |
| `git checkout branch-name`                   | switches to an existing branch                  |
| `git push --set-upstream origin branch-name` | pushes a new branch to github                   |
| `git branch -d branch-name`                  | deletes a local branch after it has been merged |
| `git branch -D branch-name`                  | force deletes a local branch                    |
