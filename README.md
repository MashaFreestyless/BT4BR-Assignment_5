# BT4BR-Assignment_5
Maria Vystoropska
25.11.2026

25.11.2026

A repository for assignment #5 for BT4BR

## What knowledge on Git I consider important:

### Starting a project

```
git clone <url>        # copy a repository from GitHub to my computer
git init               # or: turn the current folder into a new repository
git status             # see which files changed and what is staged
git log --oneline      # short history of commits
```

### Branching, forking and committing

```
git branch new_branch       # creating a new branch

git checkout new_branch     # switching branches,
git switch -c new_branch    # or alternatively: create and switch in one step

git add file1.txt file2.txt # staging files before committing

git commit -m "Add README with Git summary"  # commit with a message saying what was changed

git commit --amend          # changing the last commit (only before pushing it)

git push                    # uploads commits so that others can see them

git pull                    # fetching changes from the repo and merging them
```

### Combining work

```
git switch main             # go back to the main branch
git merge new_branch        # bring the changes from the branch into main
```

On GitHub the same is usually done with a **pull request**: I propose my changes and the owner reviews and accepts them.

### Why these are the most important

All of the above are the most important commands that will serve me in the future. Others will also play a role, but they are secondary.

Branching fosters cooperation and the social side of programming: everyone can work on their own feature without breaking the main code. Forking (done on GitHub) takes it even further, by creating a brand new copy of the repository for each person, which is suited for open-source work. Commits systemise all changes, so the whole history can be tracked and restored.

There are other features that might be very useful, but those are the bare minimum that makes Git Git.
