git-cheat-list
==============

##To clone a repo:

```text
git clone <repository-path> [destination directory]
```

## To create a branch:

### Create only:

```text
git branch <branch-name>
```text

### Create and checkout:

```text
git checkout -b <branch-name>
```

## To push new branch to repo:

```text
git push -u origin <branch-name>
```

## To delete a local branch:

```text
git branch -d <branch-name>
```

## To delete a remote branch:

```text
git push origin :<branch-name>
```

## To merge a branch:

With the "destination" branch checked out:
```text
git merge <branch-to-merge-in>
```

## To tag a branch:

## To stage local changes:

```text
git add -p
````
(opens up interactive tool for staging specific changes, follow directions within)

## To commit staged local changes:

```text
git commit -m <commit message>
````

## To stash local changes:

```text
git stash
```

## To unstash local changes:

```text
git stash pop
```

## To view remote branches:

```text
git branch -r
```

## To view local branches:

```text
git branch
```

## To sync up the local and remote branches

```text
git fetch
```

## To switch to a branch:

```text
git checkout <branch-name>
```

## To track a remote branch:

```text
git checkout -t origin/<branch-name>
```

## To restore a previously deleted file:

```text
git rev-list -n 1 HEAD -- <path_to_deleted_file>
git checkout <deleting_commit_from_above>^ -- <path_to_deleted_file>
```

## To zip up a git project:

```text
git archive -o my_project.zip HEAD
```
