# git-github-cmds

this repository is a summary of **(CLI)** commands I practiced while learning how to use git & github.

---

## git setup commands

| command              | what it does                              |
| -------------------- | ----------------------------------------- |
| `git init`           | starts git tracking in the current folder |
| `git status`         | shows the current state of the project    |
| `git branch`         | shows the branches in the repository      |
| `git branch -M main` | renames the current branch to `main`      |

---

## staging and committing commands

| command                          | what it does                        |
| -------------------------------- | ----------------------------------- |
| `git add .`                      | stages all changed files            |
| `git add file-name`              | stages one specific file            |
| `git commit -m "commit message"` | saves staged changes with a message |

---

## github remote commands

| command                                | what it does                                          |
| -------------------------------------- | ----------------------------------------------------- |
| `git remote add origin repository-url` | connects a local project to a github repository       |
| `git remote -v`                        | shows the connected github remote                     |
| `git push -u origin main`              | pushes the `main` branch to github for the first time |
| `git push`                             | pushes new commits to github                          |
| `git pull`                             | pulls the newest changes from github                  |

---

## clone command

| command                    | what it does                                 |
| -------------------------- | -------------------------------------------- |
| `git clone repository-url` | copies a github repository onto the computer |

---

## branch commands

| command                                      | what it does                                    |
| -------------------------------------------- | ----------------------------------------------- |
| `git checkout -b branch-name`                | creates a new branch and switches to it         |
| `git checkout branch-name`                   | switches to an existing branch                  |
| `git push --set-upstream origin branch-name` | pushes a new branch to github                   |
| `git branch -d branch-name`                  | deletes a local branch after it has been merged |
| `git branch -D branch-name`                  | force deletes a local branch                    |

---

## practice commands

```bash
git init
git status
git branch
git branch -M main
git add .
git add file-name
git commit -m "commit message"
git remote add origin repository-url
git remote -v
git push -u origin main
git push
git pull
git clone repository-url
git checkout -b branch-name
git checkout branch-name
git push --set-upstream origin branch-name
git branch -d branch-name
git branch -D branch-name
```

---

## git workflow

```bash
git status
git add .
git commit -m "Describe the change"
git push
```

---

## project workflow

```bash
mkdir my-project
cd my-project
git init
touch README.md
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main
```

---

## pull request branch workflow

```bash
git checkout -b update-readme
git add .
git commit -m "Update README"
git push --set-upstream origin update-readme
```

---
