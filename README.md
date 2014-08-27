git-cheat-list
==============

##To clone a repo:

```text
git clone <repository-path> [destination directory]
```

## To create a branch:

### Create only:

git branch <branch-name>

### Create and checkout:
git checkout -b <branch-name>
To push new branch to repo:
git push -u origin <branch-name>
To delete a local branch:
git branch -d <branch-name>
To delete a remote branch:
git push origin :<branch-name>
To merge a branch:
With the "destination" branch checked out:
git merge <branch-to-merge-in>
To tag a branch:
To stage local changes:
git add -p
(opens up interactive tool for staging specific changes, follow directions within)
To commit staged local changes:
git commit -m <commit message>
To stash local changes:
git stash
To unstash local changes:
git stash pop
To view remote branches:
git branch -r
To view local branches:
git branch
To sync up the local and remote branches
git fetch
To switch to a branch:
git checkout <branch-name>
To track a remote branch:
git checkout -t origin/<branch-name>
To restore a previously deleted file:
git rev-list -n 1 HEAD -- <path_to_deleted_file>
git checkout <deleting_commit_from_above>^ -- <path_to_deleted_file>
To zip up a git project:
git archive -o my_project.zip HEAD
