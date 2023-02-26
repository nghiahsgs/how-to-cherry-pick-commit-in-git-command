# how-to-cherry-pick-commit-in-git-command
how to cherry pick commit in git command


To cherry pick a commit in Git, you can use the git cherry-pick command followed by the hash of the commit you want to cherry pick. Here are the steps to do so:

## Start by navigating to the branch where you want to apply the cherry-pick.

```
git checkout <target-branch>
```

## Identify the hash of the commit you want to cherry-pick. You can find this by running the git log command.

```
git log
```
## Use the git cherry-pick command to apply the commit to your current branch.

```
git cherry-pick <commit-hash>
```
You can also specify a range of commits to cherry-pick using the <start-commit>..<end-commit> syntax.

Git will apply the commit to your current branch, creating a new commit with the same changes.

```
[target-branch 1234abc] Commit message
```
Note that if there are any conflicts between the cherry-picked commit and your current branch, Git will prompt you to resolve them.

## Finally, push your changes to the remote repository.
```
git push
```
