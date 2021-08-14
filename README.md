# Git-Cheat-sheet


## Discard unstaged changes
- Discard unstaged changes in all tracked files in the current directory:
```
git restore .
```
If this is run in the root of the repository, it will discard unstaged changes in all tracked files in the project.

- Discard unstaged changes in one tracked file:
```
git restore <filename>
```

https://stackoverflow.com/questions/52704/how-do-i-discard-unstaged-changes-in-git


## Remove staged files
- Remove all files from the staging area:
```
git reset .
```

- Remove one file from the staging area:
```
git reset <filename>
```

https://stackoverflow.com/questions/19730565/how-to-remove-files-from-git-staging-area


## Quit git diff listing
Use ```q```.

https://stackoverflow.com/questions/7568811/git-diff-how-to-quit-the-diff-listing
